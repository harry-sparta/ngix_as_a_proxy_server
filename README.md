#

## Shell commands
**App.** node seeds/seeds.js - populates the posts page of mongodb

node app.js to launch app

## Web servers
Apache - approximately 75% of the webservers

ISS - microsoft webservers approximately 20%

Nginx -

by default listens to port 80 (http)

Nginx as a protection server in front of the actual webservers

## Vim
sudo vim <file>
i to switch to insert mode
esc to switch mode
:wq (save and quit)

Shell commands
/etc/nginx/sites-enabled
change server name, location {
  proxy_pass http://localhost.3000 ;
}

sudo systemctl stop nginx
sudo systemctl start nginx
sudo nginx -t (to test if nginx runs successfully)
