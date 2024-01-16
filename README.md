# Solana experiencias Page

A simple landing page for solana experiencias

## Tools
- TailwindCSS v3.3
- AstroJs v4

## Deploy

Se utiliza el servidor de premiunhosting y se sube por FTP

```bash
ncftpput -R -v -u [FTP_USER] -p [FTP_PASSWORD] ftp.solanaexperiencias.cl /public_html ./dist/*
```

con la opción `-p` es posible añadir el password inmediatamente.

Nota: instalar la app ftp para terminal `sudo apt-get install ncftp`.