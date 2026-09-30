# watchmy.cloud

A smoke detector for your AWS bill.

We check your AWS spend every hour. When an hour or a day jumps, we ping you in Slack, email, SMS, Jira, GitHub Issues or a webhook. You find out within hours, not at the end of the month.

We connect through one read-only role. It can read only your costs. It cannot read anything else, change anything or run anything.

- [aws-connector](https://github.com/watchmy-cloud/aws-connector): the role you deploy, and exactly what it can do.
- [examples](https://github.com/watchmy-cloud/examples): code for our webhooks and API.

See it on synthetic but real-looking data: [app.watchmy.cloud/demo](https://app.watchmy.cloud/demo).
