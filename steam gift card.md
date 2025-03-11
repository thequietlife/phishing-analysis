## 🎮 Steam gift card analysis

I did a search for scams during the week. I found the following:
- fake job interview meeting details
- tax department (US tax time)
- tolls
- gift cards (steam/discord and one tied in with a romance baiting scam)

Here is a closer look at the Steam gift card scam I found on x.com

<img
src="https://github.com/thequietlife/phishing-analysis/blob/65614cd1aafeb8d81cb2539d233e3cbf81899050/images/steam%20gift%20card.png"
alt="post found on x/twitter about free gift cards" width="300"/>

⚠️ A post about "free" gaming gift cards is enticing. 
Our first step is to search for the URL on [VirusTotal](https://www.virustotal.com/gui/home/upload).

We can try some other tools to dig for more information. Let's go with [DomainTools](https://whois.domaintools.com/)

<img
src="https://github.com/thequietlife/phishing-analysis/blob/a0fefdc829816250a0092d0d2f997074d9183dde/images/freegiftcard_VirusTotal.png"
alt="VirusTotal screenshot for freegiftcodegenerator[.]com URL search" width="300"/>

The search shows several security companies have marked the URL as malicious.
When we select Details we can find the IP address:

<img
src="https://github.com/thequietlife/phishing-analysis/blob/13eed7dfcb483a08862415642125b6169d36b05b/images/freegiftcard_IP.png"
alt="VirusTotal screenshot for freegiftcodegenerator[.]com IP address" width="300"/>

The IP address has been marked as malicious.
Next we can select Relations in VirusTotal:

<img
src="https://github.com/thequietlife/phishing-analysis/blob/dd0bf40b49b4c422ef6dc29897042e4bbc095b9c/images/freegiftcard_relations.png"
alt="VirusTotal screenshot for freegiftcodegenerator[.]com Relations" width="300"/>

Here we can see one URL that has been flagged and several results for malicious files.

We can dig a bit further by using some other tools. Using DomainTools we can have a look at the Whois Record.

<img
src="https://github.com/thequietlife/phishing-analysis/blob/d743f71b35bafb473f32320ade30afa81165a7b3/images/free%20gift_DomainTools.png"
alt="Whois record from DomainTools" width="300"/>

The Whois record gives us the date the site was created, the company it is registered with and the website host. 
- It was created on 2015-05-2. 🕰️ Ten years ago!
- It was registered with PDR - PublicDomainRegistry[.]com
- Hosted by Bluehost.

Here we find a screenshot of the freegiftcodegenerator[.]com website. 🚨 The website looks pretty basic and the logo branding does not look real.

<img
src="https://github.com/thequietlife/phishing-analysis/blob/944cd067d69ff146597bd2bfbe368b4bcd5b183a/images/free%20gift_screenshot.png"
alt="screenshot of the freegiftcodegenerator[.]com website" width="300"/>

Running the URL through urlscan gives us a bit more information:<br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/e9a6c5c7f0f6aba8562279bb32799dabe7c73c41/images/freegift_urlscan.png"
alt="screenshot of urlscan results" width="300"/>

<img
src="https://github.com/thequietlife/phishing-analysis/blob/a19501922746a337627351a03c386470ebda2a9d/images/freegift_urlscan%202.png"
alt="screenshot of urlscan results done again shows a different IP address" width="300"/>

Well that was an interesting one to start with. <br>
<img
src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMGdkMG4xcW9sZ2JpamJuNWVibDdocWcyeWVmcDFqZmRpcHE5cjM2dCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xUOxf0J6CO5hH2cZ7W/giphy.gif"
alt="hat tip to BushidoToken" width="300"/>

Big thank you to BushidoToken for sharing how he analyses SMS phishing text messages.

__________________
References: 
1. [Gone Phishing, BushidoToken](https://blog.bushidotoken.net/2020/05/gone-phishing.html)
2. [Investigating SMS phishing text messages from scratch](https://blog.bushidotoken.net/2023/07/investigating-sms-phishing-text.html)
   
