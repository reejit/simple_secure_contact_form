***Kontact PHP Mail Contact Form Mailer***

I am trying to build a simple, secure php mail contact form to integrate into existing HTML page.

This is a work in progress with many features I am planning on implementing.

Right now, you can specify a webiste URL and a logo image location to send a nice formatted email (Screenshot below) with URL link goodness to your webiste wrapped right in. This can be configured easily in main kontact_mail.php file. 

I did include within this script to try and determine the senders "TRUE" IP address It is sent to the recipient you chooe during configuration along with original Contact email so a webmaster could easily copy/paste that IP address and add it to blacklist with minimal effort and no need to look through logs to find that IP Address.

I did include within this script to try and determine the senders "TRUE" IP address and email that to the recipient you choose during configuration within the message to easily copy/paste that IP address so one could add it to blacklist with minimal effort or looking through logs if they are spammers to stop that unwanted behavior.

Check it out, give feedback and help out if you would like.


***Wanted Features (ATPIT):***

Addition of config.inc.php file for easier customization.

Multiple Choices for Captcha Options

Custom Themed emails

Ability to echo output messages to existing HTML pages for ease and confort.

More ideas to come

Thank you and enjoy ... 


***Installation***:
Installation is quite simple. Upload included files with file structure preserved. Included .html pages should go to your webroot and edit those files accordingly to match your existing site look and feel. The files located in /kontact/ folder should upload into a folder named /kontact/ (I spelled it wrong on purpose) and edit kontact_mail.php file within the Configuration Section to suite your needs. You then need to add code, depending on your choice of Captcha, to your existing HTML page where the contact form is located. These code examples are more detailed within the kontact_mail.php file itself.


***Screenshot of Email***

![Alt text](/images/screenshot_dar_blue.png?raw=true "Dark Blue Theme")