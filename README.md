Lately, I've noticed discussions in the outbound community about Google and Outlook marking cold emails as spam. A popular workaround is using a Gmail inbox for Gmail users and Outlook for Outlook users, as these are the most common email services.

This got me thinking about how to identify the email service a domain uses. I recalled my earlier LinkedIn post about the dig command on Ubuntu (Linux), which can return the MX record for any domain with an email service.

For example, in the terminal, type: dig MX exampledomain.tld

This returns a text that reveals the email service used by that domain.

To make this process scalable, I used AI and Python to create a program that you can run in Jupyter Notebook. You'll need a CSV file with one column called “Domain.”
