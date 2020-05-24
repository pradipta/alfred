run `npm i`

Add these (replace actual values) into .env: 

```
ALFREDDBNAME=dbname
ALFREDDBUSERNAME=username
ALFREDDBPASSWORD=password
ALFREDDBHOST=host
ALFREDDBPORT=port
```

Database table structure: 

| service_name | instance_name | available | reserved_at | duration | booked_by | comments |
|--------------|---------------|-----------|-------------|----------|-----------|----------|

Database name: `alfred`

Run on local: `./bin/hubot`
Run on Slack: HUBOT_SLACK_TOKEN=<SLACK TOKEN HERE> ./bin/hubot --adapter slack

Enjoy bro
