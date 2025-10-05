# Use the official n8n image
FROM n8nio/n8n:latest

# Expose default n8n port
EXPOSE 5678

# Optional: Default environment variables (can override in Render dashboard)
# ENV N8N_BASIC_AUTH_ACTIVE=true
# ENV N8N_BASIC_AUTH_USER=admin
# ENV N8N_BASIC_AUTH_PASSWORD=supersecret
# ENV DB_TYPE=postgresdb
# ENV DB_POSTGRESDB_HOST=your-db-host
# ENV DB_POSTGRESDB_PORT=5432
# ENV DB_POSTGRESDB_DATABASE=your-db-name
# ENV DB_POSTGRESDB_USER=your-db-username
# ENV DB_POSTGRESDB_PASSWORD=your-db-password
# ENV DB_SSL_MODE=require
# ENV WEBHOOK_URL=https://your-render-domain.onrender.com/
