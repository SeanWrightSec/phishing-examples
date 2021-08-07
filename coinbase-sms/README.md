# coinbase-sms

This was a sms/text message which attempts to get the victim to click on the link.

![Screenshot of sms/text](https://github.com/SeanWrightSec/phishing-examples/blob/main/coinbase-sms/1628283065920%20-%20original.jpg)

On the face of this there is not much which stands out to make this look suspicious. But if you look closely to the link you can see the letter 'a' in "coinbase" looks a bit off:

![Highlighted character](https://github.com/SeanWrightSec/phishing-examples/blob/main/coinbase-sms/1628283065920.jpg)

And in fact it is, instead of the actual letter 'a' it is in fact the character 'ạ'. This is a common trick which attackers use. The attacker relies on the fact that hyperlinks are underlined, so the dot beneth the letter "a" appears to be a part of the hyperlink formatting, when in fact it's a completely different character. This character then makes this a new domain (and not the legitimate domain), which the attacker has ownership over.
