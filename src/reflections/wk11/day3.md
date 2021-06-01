# Day 3 - DOTNET WEBAPI REVIEW

## Daily Journal

Welp, here we are.

I've decided to be proactive with this particular assignment, and today's project will ultimately be a template Workspace document that I will be able to use as a base for my final project. The goal with this is to set up a working Workspace, create a dedicated Auth and SQL server, and by end of day ensure that it's all hooked up without any errors crashing the thing.

Once that's handled, I should be able to just copy that template down from GitHub, rename it whatever name is ultimately appropriate for the Final, and rename a few key variables across the Application and BAM. Fully functional working template with no headaches!

... TWO HOURS LATER ...

Well that was surprisingly easy!

All things considered, that should shave off two hours from my first day on the thing, and thus the goal for Friday is to do my best to get all my Postman tests passing by end of day. Maybe a tall order, but I feel like I've set myself up as good as I can so I may as well go for it.

## Daily Challenges

Morning:

Afternoon: https://github.com/SamLimpic/cs-auth

### Read "Dotnet WebAPI's > SQL Injection"

1. What is SQL injection?
   An online attack where a user can insert malicious data into your SQL table

2. What are 3 methods SQL injection can be done by?
   User input, cookie modification, and forged HTTP headers

3. How can we detect and sanitize SQL injection attacks?
   Sanitize your input validation with prepared statements and parameterized queries. Identify the specific properties you want your users to have access to, and sanitize any data they send through to only permit those specific properties. This prevents the user from modifying variables you don't want them to access.
