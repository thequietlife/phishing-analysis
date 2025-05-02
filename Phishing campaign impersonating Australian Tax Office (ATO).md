### Phishing campaign impersonating Australian Tax Office (ATO)

<img
src="https://github.com/thequietlife/phishing-analysis/blob/23e2993daaef59f2faf916f5d8df5e3fa31fb92b/images/ATO%20task%20SMS.png"
alt="SMS supposedly from ATO" width="400"/>


<img
src="https://github.com/thequietlife/phishing-analysis/blob/367b54e47efbbcd2071efabb137616d1afc4ab31/images/challenge%20platform.png"
alt="challenge platform" width="400"/>

### Notes:

* A SMS text I received a few days ago.
* I wasn't able to access the phishing page at first. When I looked in the dev tools I could see it is using Cloudflare's Bot Fight Mode. h/t to @BushidoUK for this tip.
* The aim of the site is to collect users personal information by pretending to set up their ATO user account.
* The phishing site opens to a sign in page and then moves to a enter a SMS verification code. I was able to step through the phishing kit by entering fake information. 
* The next page was to set up secret questions. There is a skip button to bypass this and progress further.






__________________
Sources: 
1. [Investigating SMS phishing text messages from scratch](https://blog.bushidotoken.net/2023/07/investigating-sms-phishing-text.html)
2. [Netflix themed survey phishing campaign](https://github.com/PaloAltoNetworks/Unit42-timely-threat-intel/blob/main/2025-02-03-IOCs-for-Netflix-themed-survey-phishing-campaign.txt)
