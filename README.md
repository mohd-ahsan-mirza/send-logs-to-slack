# Description
I run `slack.sh` every minute on a server to send logs on a slack channel
# Setup
[Webhooks for slack](https://api.slack.com/incoming-webhooks)

Once you have the invocation url, replace `{Web Hook}` with that URL

Also replace `{ABSOLUTE PATH TO LOGS}` with absolute to your logs

Add the aboslute path to `slack.sh` in your cron scheduler using `crontab -e`. Ideally for every minute.

Please note that the script only capture logs that have a timestamp.

