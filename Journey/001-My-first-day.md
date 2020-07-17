<!-- This is a template you can use for quick progress days. It removes a lot of the steps we encourage you to share in the longer template 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

# How to Create an IAM User, Enable MFA for Root Account and Add IAM Password Policy

# Create IAM User

* I am creating a IAM user today.
* I had to setup a new AWS root user because I closed my old one after doing my hands on learning for CCP.
* Once I got in, I typed in IAM user and it showed me my IAM user sign-in link and the 12 numbers I needed.
* Which I remember learning from ExamPro's CCP Course when I did the hands on.
* I copied the numbers.
* Then I signed out of my root user.
* I clicked on IAM Account and I pasted the 12 numbers in the login. 
* Then it brought me to sign-in to IAM user, so I pasted the 12 numbers in again and created a user name and password and it didn't work.
* I got annoyed 😡... now I am confused😫
* It was showing my old email in the IAM user with the account I closed.
* No clue what's going on. I must have mixed up what I have learned?
* I logged back into my root account to see what I could figure out and typed in IAM.
* I clicked on create individual IAM users thinking this sounds right.
* I clicked Manage Users.
* I clicked Add Users.
* I created a User Name 
* I see there is a option to click AWS Management Console Access!
* That is what I'm supposed to be doing! 😄
* I create a password, it asks me if I want to create a group
* I create a group called Admins and I gave it AdministratorAccess
* I create user.
* Yay I did it 👏

# Enable MFA for Root User

* Now I need to enable MFA for root user.
* I go to IAM Managament Console.
* I click on Activate MFA on your root account.
* I click manage MFA.
* I click on MFA.
* I click on Activate MFA.
* I select Virtual MFA device.
* I have to install a compatible app on my phone and I choose Google Authenticator
* (which i still had on my phone when I was doing my CPP course)
* I scan bar code to sync it.
* I enter in the codes and its saying invalid MFA? So I do it again and says the same thing..
* I remove what I scaned and just start over and scan the bar code and enter in the numbers and it works!
* So I successfully assigned virtual MFA 👊


# Apply IAM Password Policy that Follows Securitys Best Practices

* Now I need to apply an IAM password policy that follows security best practices.
* I go back to IAM Managment Console and click on Apply an IAM password policy and click manage password policy.
* I click set password policy
* Then it gives me a bunch of options and I select most of them.
* I save changes and I'm DONE!!


https://twitter.com/sammy5_j/status/1284110246194094083


