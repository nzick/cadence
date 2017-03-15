# Cadence

Music player based on koel

## Install

- All requirements by Laravel – PHP, OpenSSL, composer and such. Consider setting PHP's memory_limit to a good value (512M or better) if you have a big library.
- MySQL or MariaDB. Actually, any DBMS supported by Laravel should work.
- NodeJS latest stable with yarn

Set .env Vars:
```
DB_CONNECTION= mysql | pgsql | sqlsrv
DB_HOST=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
ADMIN_EMAIL=
ADMIN_NAME=
ADMIN_PASSWORD=
```

## Run


```
# Initialise
composer install 
npm init

# Start
npm start

# Sync
npm sync
```
