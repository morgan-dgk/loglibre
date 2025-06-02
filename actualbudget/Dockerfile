FROM ghcr.io/actualbudget/actual:latest

# Add additional folder for server state and change ownership to non-root user
RUN mkdir /server && chown actual:actual /app /data /server

# Avoid using root user
USER actual
