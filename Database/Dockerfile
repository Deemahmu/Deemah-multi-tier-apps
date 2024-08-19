# Use the official PostgreSQL image as the base
FROM postgres:latest

   environment:
      POSTGRES_USER: deemah
      POSTGRES_PASSWORD: dm1234
      POSTGRES_DB: deemah_db
# Mount a volume for persistent data storage
VOLUME /var/lib/postgresql/data
# Expose the PostgreSQL port
EXPOSE 5432
