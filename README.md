Hunt for breached credentials
- Dehashed 
- Haveibeenpwnd

Search for valid usernames and email addresses - data leaks, google lists for emails at the company domain
put all accounts into a txt file for password spraying.

Find login panels for the company, try reset PW pages and logins to see valid accounts. Google dork will help find login panels

<h2> Attacking office 365 </h2>
tool called trevorspray can be used to spray external emails, ensure to know lockout account policy.

<h2> Attacking OWA </h2>
Msfconsole has a owa module for spraying, use generated email wordlist.
Also tool called mailsniper

<h2> bypassing MFA </h2>
Tool called MFAsweep, pass valid email and password and it will check where it can login with 2FA.

Use vulnerability scanning on the permimiter to look into services and any associated CVEs
