## Add a new agent

```bash
curl --request POST \
  --url http://spoutbreeze.test/agents \
  --header 'Authorization: Basic YXBpQHNwb3V0YnJlZXplLnRlc3Q6YXBpQHNwb3V0YnJlZXplLnRlc3Q=' \
  --header 'Content-Type: application/json' \
  --cookie PHPSESSID=hcea2bmi35dn3q9tud3c0v33nl \
  --data '{"name":"local_youtube","ip_address":"127.0.0.1","port":"20031","status":"enabled"}'
```
