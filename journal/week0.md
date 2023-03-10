# Week 0 — Billing and Architecture

## Required Assignments
- [x] Set a Billing alarm: I set the billing alarm via the console while watching Chirag's video. <img src="/journal/images/week0-billing-alarm.png"  width=50% height=50%>
- [x] Set a AWS Budget: I set the AWS budget via the console while watching Chirag's video. <img src="/journal/images/week0-aws-budget.png"  width=50% height=50%>
- [x] Generate AWS Credentials: I already had AWS creds on my local machine, but spent some time getting them loaded propertly into the Gitpod environment as well and was able to recreate all of the commands and results Andrew demonstrated. <img src="/journal/images/week0-aws-cli-gitpod.png"  width=50% height=50%> 
- [x] <img src="/journal/images/week0-get-caller.png"  width=50% height=50%>
- [x] Use CloudShell: I used CloudShell to create an S3 bucket. I verified I was successful by confirming the result in the AWS UI. <img src="/journal/images/week0-cli-mb.png"  width=50% height=50%>
- [x] <img src="/journal/images/week0-cli-mb-confirm.png"  width=50% height=50%>
- [x] [Conceptual Architecture Diagram](https://lucid.app/lucidchart/invitations/accept/inv_7b027d05-0ead-4be9-a081-48b264785e83) ![Conceptual Architecture Diagram](/journal/images/week0-conceptual-diagram.png)
- [x] [Logical Architecture Diagram](https://lucid.app/lucidchart/da9380c1-991d-4bb5-9b13-3469c1f3cfd8/edit?viewport_loc=-773%2C32%2C2252%2C1022%2C0_0&invitationId=inv_195fbd1f-0613-4a41-8a52-3c1665dd29f4) ![Conceptual Architecture Diagram](/journal/images/week0-logical-diagram.png)

## Homework Challenges 
- [x] Destroy your root account credentials, Set MFA, IAM role
- [x] Use EventBridge to ~~hookup Health Dashboard to SNS and send notification when there is a service health issue.~~ I set up a notification system through EventBridge to notify me via email every time a file is uploaded to an s3 bucket. I will definitely start using this in my work because my company currently sends files to some of our customers' buckets and the customers are always complaining that they can't find the files and did we send them?. Now I can show them how to monitor this themselves! <img src="/journal/images/week0-eventbridge.png"  width=50% height=50%>
- [x] Review all the questions of each pillars in the Well Architected Tool (No specialized lens)
- [x] Open a support ticket and request a service limit: I actually opened a support ticket to purchase my domain through Route53. I was originally blocked from doing so, but the support agent resolved the issue in about 24 hrs.
- [x] Read chapter 1 of the official [AWS Solution Architect Study Guide](https://www.amazon.com/Certified-Solutions-Architect-Study-Guide/dp/1119713080/ref=asc_df_1119713080/?tag=hyprod-20&linkCode=df0&hvadid=459538011055&hvpos=&hvnetw=g&hvrand=1442647167613858578&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032112&hvtargid=pla-917135384856&psc=1) to cement my understanding of certain concepts. 
- [x] Ordered this book, [Building Secure and Reliable Systems: Best Practices for Designing, Implementing, and Maintaining Systems](https://www.amazon.com/dp/1492083127?psc=1&ref=ppx_yo2ov_dt_b_product_details) and [Site Reliability Engineering: How Google Runs Production Systems](https://www.amazon.com/gp/product/149192912X/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1). I work as a customer-facing engineer and we've had some reliability issues lately, so I'm hoping to weave together learnings from this course and book.
