# Use the official PostgreSQL image as the base
FROM postgres:latest


# Set environment variables
ENV POSTGRES_USER=deemah
ENV POSTGRES_PASSWORD=dm1234
ENV POSTGRES_DB=deemah_db

# Mount a volume for persistent data storage
VOLUME /var/lib/postgresql/data
# Expose the PostgreSQL port
EXPOSE 5432