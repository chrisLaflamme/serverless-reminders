# Serverless-Reminders

Two small Node functions that send email reminders to (currently) hard coded AWS SES verified emails based on simple cron jobs setup as AWS CloudWatch events.  This project was created and is managed via the [Serverless Framework](https://serverless.com/) npm package.

Initially created to follow the Pluralsight demo [Using the Serverless Framework with Node.js on AWS](https://app.pluralsight.com/library/courses/aws-nodejs-serverless-framework-using/table-of-contents).

### Functions:
- sendReminderDaily
- sendReminderWeekend