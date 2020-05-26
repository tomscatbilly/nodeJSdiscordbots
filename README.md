# nodeJSdiscordbots
Run NodeJS-based discord bots in Docker
<h2> Docker Image</h2>
<strong>NOTE:</strong> Replace index.js with values that suit your needs.


```
docker create \
  --name=NodeJSBot \
  -e BOTFileName=index.js \
  -v /path/to/bot:/mnt/bot \
  --restart unless-stopped \
  tomscatbilly/nodejs-discord-bots
```
