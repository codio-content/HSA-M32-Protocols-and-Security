While the goal of Information Assurance is to guarantee that no data is lost or compromised, and that information is always available, there are some times that the goal is not met.  

## Challenges to Confidentiality
The goal is to ensure that only you or authorized users can see your data.  How does a computer determine who you are?  One way is with a username and password combo.  This system works well until the user's password is learned by a potential "bad actor".  There is no way for a computer to determine two people with valid passwords apart.  

Unfortunately, some users inadvertently give away their info through social engineering attacks.  An email requests you reset your password.  The email looks valid and warns of consequences for inaction.  After you "reset" your password by providing your current password, the attackers have gained access to your account.

Other practices such as re-using passwords from site-to-site allow hackers who have gained access to one, poorly defended site, to access your other sites through a common password.

While additional security measures can be taken such as two-factor authentication, biometric devices, or other advanced tools, these all require more time and effort on both the server-side and the user.

## Challenges to Integrity
How do we ensure that data you send is not modified in transit?  If you send data, is there a way to verify it is the same when it arrived as when it left?  Various methods such as file permissions, checksums, and access control are used to ensure Integrity.  Multiple copies of files are kept across servers so that if one server breaks, the other still contains the data.  The various copies of files are compared to each other at regular intervals to check that they contain the same data and if changes have been made, the authenticity of the change is determined.

## Challenges to Availability
Servers require maintenance, periods of time when they are not in operation to install new components or new software.  During this time, data may not be available.  To ensure constant availability, the data must be stored in several places such that if one server is temporarily turned off, the other server can deliver the data.  This is more difficult and subsequently more expensive.  Companies and users must decide what the value of "always available" is worth.

Cyber attacks such as a Denial of Service attack may also cause data to become unavailable.  Imagine you're trying to use an elevator to go up several floors.  As you arrive, several hundred other people get in line for the elevator.  These people don't actually need to go anywhere and are only riding the elevator up and down without getting off on any specific floor.  They have effectively denied you service of the elevator.  Since an elevator has no way of determining a genuine user from a bogus one, it has to treat all users as genuine.  A denial of service attack is similar but instead of requesting an elevator, bogus users request server data.  Without a way to determine genuine from false, the server tries to give all users the data they've requested and the genuine requests get bogged down in the middle of all of the false requests.