Securing a web page is a difficult task.  There must be a balance between access and security that allows users to access their data while ensuring that other people don't have access to that same data.  

## Passwords
The primary way of keeping web pages secure is through the use of passwords.  The primary problem with passwords is that people forget them and need the "forgot password" option on a website.  This option will e-mail you a reset key.

Imagine that your e-mail is compromised, could someone other than you access your other accounts through the "forgot password" link?  But if we take that option away, a person who legitimately forgot their password would be unable to access their account.  As much as we'd all like to think we're in a spy novel, it is much more likely that we would forget our own password than have a hacker trying to access our accounts.

## Authentication
Every additional step that we take to secure a web page means an additional step our users will have to take to log into their account.  The addition of a second step as in the case of two-factor authentication adds a step for users.  In two-factor authentication you take something you know, your password, and something you have, your phone, to create a more secure log in experience.  The third authentication technique is to take something you are, biometric scan of your fingerprint, etc. to use as a factor in authentication.

## Secure Protocols
Web pages using the HTTPS protocol transmit the contents of the page in a secure way.  This means that someone eavesdropping on the wire or on one of the servers that the data traveled through would not be able to read any of the data.  To provide a secure web page, a host needs an SSL certificate.  These are only provided by a few companies to further ensure security.

HTTPS was the focus of a recent exploit known as heartbleed.
[Heartbleed info](https://en.wikipedia.org/wiki/Heartbleed)