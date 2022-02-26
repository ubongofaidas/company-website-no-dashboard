# company-website-no-dashboard
Created company website with php and swift mailer

This website allow subscrition, contact and membership registration.

The website for startup made with php, mysql and swiftmailer here you go, create a database with any name but remember to change the name in connection file
found in root_folder/process/cnnect/connect.php and import database sql tables found in root_folder to your server.

Then navigate to process/filenaeme_mailing.php set your email and pass in the following methods

    ->setUsername("putmail")
    ->setPassword("putpass");
    
Then go here https://symfony.com/doc/current/email.html to read the swiftmailer documentation
If you're previewing the project via localhost then go to gmail app where you can set your google mailing system
to authorize email from other less secure app,
Finally;
Run your website while turned on internet and test for subscrition, contact and membership registration

Any modification are allowed,

Dangerous:
Do not host the project until you do the modification in all files which require passwords such as database conection file and swift mailer connection to any mail server

