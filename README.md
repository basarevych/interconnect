# Work in progress

### Tracker

1. Install Node 6+, Postgres 9.4+, Redis 3+

2. **apt-get install build-essential ca-certificates**

3. **npm install -g bhit --unsafe-perm**

4. **bhit install my.host.name**

5. Edit /etc/bhit/config.js, create the database, then

  **bhit create-db**

6. **systemctl daemon-reload**

  **systemctl enable bhit**

  **systemctl start bhit**

### Daemon

1. Install Node 6+

curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs

2. **apt-get install build-essential ca-certificates**

3. **npm install -g bhid --unsafe-perm**

4. **bhid install**

5. systemd-way:

  **systemctl daemon-reload**

  **systemctl enable bhid**

  **systemctl start bhid**

  or just:
  
  **bhid run**
