# apple-app-store

This was an email which attempts to get the victim to open the attached PDF. The email portrayed itself as an invoice for the purchase of a mobile app via the Apple App Store.

![VirusTotal screenshot](https://github.com/SeanWrightSec/phishing-examples/blob/main/apple-app-store/apple-screenshot.png)

Performing an analysis on the attached PDF (via VirusTotal) does indeed confirm that the attachment was not legitimate:

![VirusTotal screenshot](https://github.com/SeanWrightSec/phishing-examples/blob/main/apple-app-store/virus-total.png)

In addition there are several flags which stand out making the email look suspicious:

### Flag 1

The from address is certaintly not from Apple. Although by setting Apple's official email addresses in the To field and having the victim's email in the Bcc field attempts to make it to appear that it is in fact from Apple. Also by having the victim's email address in the Bcc field is a clever tactic to ensure that any automated responses are not sent to the victim.

![Flag 1](https://github.com/SeanWrightSec/phishing-examples/blob/main/apple-app-store/flag-1.png)

### Flag 2

The second flag is incorrect punctuation. In this case the word "Please" has an uppercas 'P' in mid-sentence. A company such as Apple would unlikely to have this error in their official emails.

![Flag 2](https://github.com/SeanWrightSec/phishing-examples/blob/main/apple-app-store/flag-2.png)
