# googleTest
If you want to run on your personal agent docker, use this command:
```
docker run -t -d --restart always --mount source=katalon-runtime-engines,target=/root/.katalon -e SERVER_URL=https://analytics.katalon.com -e KATALON_USERNAME={YOUR_EMAIL} -e AGENT_NAME=${YOUR_AGENT_NAME} -e TEAM_ID=${TEAM_ID} -e KATALON_API_KEY=${YOUR_KATALON_API_KEY} katalonstudio/agent:latest
```
