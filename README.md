# docker-vsftpd

```docker build -t vsftpd .```
```docker run -d -p 21:21 -e USER=ftpuser -e PASSWORD=mypassword -e DIR=/ftp -v /home/krustyhack:/ftp --name vsftpd vsftpd```
