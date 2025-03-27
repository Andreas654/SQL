FROM mcr.microsoft.com/mssql/server:2019-latest

ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrong!Passw0rd

EXPOSE 1433

# Optional: Installieren Sie zusätzliche Tools oder Bibliotheken
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip

# Optional: Kopieren Sie Ihre SQL-Skripte oder andere Dateien
COPY . /workspace
WORKDIR /workspace
