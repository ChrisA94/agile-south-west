Agile South West Website
------------

A tiny web application to invite a user into your slack team.

Started life as 
[slack-invite-automation](https://github.com/outsideris/slack-invite-automation)

## Run ( with Docker )

It's easy to run this service if you have installed Docker on your system.

```shell
$ git clone git@github.com:outsideris/slack-invite-automation.git
$ cd agile-south-west
$ docker build -t agile-south-west .
$ docker run -it --rm -e COMMUNITY_NAME="YOUR-TEAM-NAME" -e SLACK_URL="YOUR-TEAM.slack.com" -e SLACK_TOKEN="YOUR-ACCESS-TOKEN" -p 3000:3000 agile-south-west
```
