# WatchPeopleCode
Helper app for /r/WatchPeopleCode subreddit

Currently available at: http://watchpeoplecode.com

To run, create .env file with these contents

```
SECRET_KEY=secret
DATABASE_URL=<your_url>
MAILGUN_API_URL=
MAILGUN_API_KEY=
MAILGUN_TEST_OPTION=true
MAILGUN_SMTP_LOGIN=
WPC_REDDIT_PASSWORD=
WPC_REDDIT_USERNAME=
WPC_YOUTUBE_KEY=
GA_TRACKING_CODE=
```

Then try `foreman run python app.py run`
