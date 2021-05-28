# Day 3 - DOTNET WEBAPI REVIEW

## Daily Journal

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
