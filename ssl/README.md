
##**//cerbot repo link for creating ssl certiicate//**
`sudo git clone https://github.com/certbot/certbot`

##**//run certbot//**
`cd certbot`
`./certbot-auto -h`

###**//create certificate//**
`cd /opt/certbot`

`sudo ./certbot-auto certonly --webroot -w /var/www/html \
    -d baymax.com \
    --non-interactive --agree-tos --email baymax1298@gmail.com`
