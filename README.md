# docker-vsftpd

```docker run -d -p 21:21 -e USER=ftpuser -e PASSWORD=yourpassword -e DIR=/ftp -v /your/path:/ftp --name vsftpd krustyhack/vsftpd```
