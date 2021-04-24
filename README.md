Slightly changed this [Telegram bot](https://www.youtube.com/watch?v=Kh16iosOTIQ), that can help you calculate your expenses.

Replaced polling with webhooks
Added settings that allow you deploy bot to Heroku

All you need to do is:
clone bot
create new heroku project (heroku create your-project-name)
login to Heroku, choose project, that you just create and set environment variables
`API_TOKEN` your bot token
`HEROKU_APP_NAME` your project name
then push your project to heroku (git push heroku master)

if something doesn't work check logs - heroku logs --tail

