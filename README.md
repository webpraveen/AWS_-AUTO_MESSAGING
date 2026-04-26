# AWS_-AUTO_MESSAGING
- Developed an automated messaging system on AWS using SES, EventBridge Scheduler, S3, and Lambda. Configured EventBridge Scheduler to trigger every hour, invoking Lambda to send scheduled emails to recipients via SES. Email logs/data were stored in S3 for tracking and auditing.


# What this project does
- Sends emails automatically to recipients at a scheduled time (for example, every 1 hour).
- Amazon Web Services EventBridge Scheduler triggers the process on schedule.
- Amazon Web Services Lambda runs the code to prepare the email.
- Amazon Web Services SES sends the email to recipients.
- Amazon Web Services S3 stores sent email data/logs/reports.

# AWS Services Used
- AWS EventBridge Scheduler
- AWS S3
- AWS LAMBDA
- AWS SES
- AWS CLOUDWATCH
- AWS IAM

- # Steps I followed
- Created an Amazon Web Services S3 bucket to store email logs and related data.
- Verified sender email/domain in Amazon Web Services SES.
- Created an Amazon Web Services IAM role with permissions for Lambda to access SES, S3, and logs.
- Developed an Amazon Web Services Lambda function to generate and send emails.
- Added code in Lambda to store sent email details/logs in S3.
- Configured Amazon Web Services EventBridge Scheduler to trigger Lambda every 1 hour.
- Tested the workflow by running the scheduler manually and checking email delivery.
- Monitored logs and errors in Amazon Web Services CloudWatch.
- Optimized message content, timing, and permissions for smooth automation.
