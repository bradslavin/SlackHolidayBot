# Slack Holiday Bot

Post today's holiday to the specified channel in [Slack](http://slack.com).

![Example Message](example.png)

## Instructions
* Add a new [**Incoming WebHook**](http://my.slack.com/services/new/incoming-webhook) integration in Slack
 * Copy your unique webhook URL to your clipboard
 * Specify a channel where the message will be posted to
 * Press the **Add Integration** button
* Paste the unique webhook URL in the curl request *(line 41 of index.php)*
* Also set your timezone accordingly *(line 6 of index.php)*
* Set up a cron job somewhere to run index.php every day
* Celebrate when the message arrives

## Holiday List
The list of holidays came from a post on [StudentBeans.com](http://www.studentbeans.com/worldweirdweb/a/odd+facts/what-crazy-national-day-falls-on-your-birthday3119.html).