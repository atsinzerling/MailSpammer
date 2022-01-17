# MailSpammer
This application will send as many emails to a list of specified email addresses as you want (the only limitation is the number of emails that google services allow you to send, which is around 85 times).

This is an Apache NetBeans project. If you want to run the jar file without importing the project, you need to copy dist/lib and dist/MailSpammer_gh.jar to the same directory, and then just run the jar file.
You can list as many emails as you want in the field “Emails listed”, and every email must be in a separate line. To send emails, you have to use a Gmail address as a sender email; you also have to turn on Less secure app access in google settings for the account you intend to use for it (https://myaccount.google.com/lesssecureapps). The link to this setting is also provided under the “Sender email password” field. Also, this security setting doesn’t work when 2-Step Verification is enabled.

“Repeating String in the subject” and “Repeating String in the message” are fields to create a piece of a message, that would be added to the default message after sending every message. This feature was added to prevent all the emails from being put into the same folder; so, making all the messages differ by a few symbols makes the spam more annoying.

Important! The purpose of this application is just to prank a friend or joke, by no means not to do real spam or molest someone.

