run `npm install dotenv`

Add these into .env: 

```
ALFREDDBNAME=<dbname>
ALFREDDBUSERNAME=<username>
ALFREDDBPASSWORD=<password>
ALFREDDBHOST=<host>
ALFREDDBPORT=<port>
```

Database table structure: 

| service_name | instance_name | available | reserved_at | duration | booked_by | comments |
|--------------|---------------|-----------|-------------|----------|-----------|----------|

Database name should be same as provided on the `.env` for the script at https://github.com/pradiptasarma/alfred

Run ./bin/hubot

Enjoy bro
