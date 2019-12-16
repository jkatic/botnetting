# slacker Slackbot

This super-light weight bot responds to simple greetings (sorry for not making it interesting guys).

## Reproduce the bot yourself

Requirements:
  - Slack channel and SLACK_TOKEN env var
  - Golang v 1.11+
  - Docker v 19.03+

Reproduce the bot locally:
  - Download slacker.go and Dockerfile
  - Build it with `GOOS=linux GOARCH=amd64 go build`
  - Build the container with `docker build -t slacker .`
  - Run the container from anywhere `docker run -d -e SLACK_TOKEN=$SLACK_TOKEN slacker`
