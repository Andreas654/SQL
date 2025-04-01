FROM mysql:latest

# Setze Root-Passwort und erstelle eine Beispiel-Datenbank
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=testdb
ENV MYSQL_USER=testuser
ENV MYSQL_PASSWORD=testpass

# Kopiere ein SQL-Skript zum Erstellen von Tabellen
COPY init.sql /docker-entrypoint-initdb.d/

# Exponiere den Standard-MySQL-Port
EXPOSE 3306
