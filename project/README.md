# YOUR PROJECT TITLE
#### Video Demo:  <https://youtu.be/G7UXVD46FWw>
#### Description:

    My PROJECT is a MAIL that gives E-mail service to the public. that i'm the front end and the back end of the serivice.
my project consist of different programing code. like python, html, css, templates, sql so that using flask run to give a service to public.

    This MAIL service called KALID@MAIL use python. to creat applcation calld app.py that use different kind  of router for
example /index /email /sent /register /login /logout.

    And the TEMPLATES which consist of a differnt type of html file. like for example apology.html, compose.html, index.html
layout.html, register.html, email.html, login.html, reply.html

    And i use different types style from styles.css. file which is good for disply of the app. and allso the SQL data base.
which store emails, text, password, id... and creat tabe which we can access to insert data to store data so that we can
access any time we wanted.
     Send Mail: When a user submits the email composition form, python code to actually send the email.
You’ll likely want to make a POST request to /emails, passing in values for recipients, subject, and body.
Once the email has been sent, load the user’s sent mailbox.

  Mailbox: When a user visits their Inbox, Sent mailbox, or Archive, load the appropriate mailbox.
You’ll likely want to make a GET request to /emails/<mailbox> to request the emails for a particular mailbox.
When a mailbox is visited, the name of the mailbox should appear at the top of the page (this part is done for you).
Each email should then be rendered in its own box (e.g. as a <div> with a border) that displays who the email is from, what the subject line is, and the timestamp of the email.

   View Email: When a user clicks on an email, the user should be taken to a view where they see the content of that email.
You’ll likely want to make a GET request to /emails/<email_id> to request the email.
Your application should show the email’s sender, recipients, subject, timestamp, and body.
Archive and Unarchive: Allow users to archive and unarchive emails that they have received.
When viewing an Inbox email, the user should be presented with a button that lets them archive the email. When viewing an Archive email, the user should be presented with a button that lets them unarchive the email. This requirement does not apply to emails in the Sent mailbox.Once an email has been archived or unarchived, load the user’s inbox.
     Reply: Allow users to reply to an email.When viewing an email, the user should be presented with a “Reply” button that lets
 them reply to the email.When the user clicks the “Reply” button, they should be taken to the email composition form.
Pre-fill the composition form with the recipient field set to whoever sent the original email.
Pre-fill the subject line.
