# docker-wp-lamp-ssl

Docker build for creating a local WordPress website running on a LAMP stack with SSL from Lets Encrypt. Includes a PHPMyAdmin container so you have a GUI for the database. Includes MailHog, a testing SMTP server, so you can test site messaging locally.

### Getting Started
``` docker-compose up -d ```

### Access Site
``` https://localhost ```
(or at the custom URL that you create using the instructions in the comments near the https-portal container :wink:)

### Access PHPMyAdmin
``` http://localhost:8081 ```

### Preset PHPMyAdmin creds
<p><b>User:</b> root</p>
<p><b>Pass:</b> wordpressrootpw</p>

### Access the testing mail server inbox
``` http://localhost:8025 ```
