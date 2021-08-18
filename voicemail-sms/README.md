# voicemail-sms

This was a sms/text message which attempted to potray that it was from the victim's mobile phone provider informing the victim that they had a missed call attempting to get the victim to navitage to the link in the sms/text.

![Screenshot of sms/text](https://github.com/SeanWrightSec/phishing-examples/blob/main/voicemail-sms/IMG_2088.jpeg)

Numerous characteristics of them sms/text raise suspicions over it:

### Flag 0

Perhaps the biggest flag of them all, the fact if you look at your call logs and identify that you in fact have no missed calls!

### Flag 1

![Flag 1](https://github.com/SeanWrightSec/phishing-examples/blob/main/voicemail-sms/flag-1.png)

The first flag within the actual sms/text is the name. Typically this won't actually be your name. Perhaps often want to have access to things which they shouldn't have access to, and attackers use this to their advantage. Having a voicemail which isn't yours does make that urge to "just give it a quick listen to".

### Flag 2

![Flag 2](https://github.com/SeanWrightSec/phishing-examples/blob/main/voicemail-sms/flag-2.png)

Spelling mistakes are often a very good indication of a potential phishing email.

### Flag 3

![Flag 3](https://github.com/SeanWrightSec/phishing-examples/blob/main/voicemail-sms/flag-3.png)

This is again another flag. Typically if had a voicemail, you would use your mobile provider's voicemail inbox on your account which is accessed by dialing the voicemail number or with more modern phones this ties directly with the mobile OS and you can listen to the voicemail directly. I've in all my years, never have once needed to access a voicemail via a link to a site. Also this being a HTTP site (as opposed to HTTPS) also raises suspicions. Most providers would typically use HTTPS (it is worth noting that just because HTTPS is used, doesn't necessarily make it legitimate still).
