## 🎮 Steam gift card analysis

I did a search of scam texts during the week. I found the following scam texts:
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
