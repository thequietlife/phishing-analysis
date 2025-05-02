### Phishing campaign impersonating Australian Tax Office (ATO)

1️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/23e2993daaef59f2faf916f5d8df5e3fa31fb92b/images/ATO%20task%20SMS.png"
alt="SMS supposedly from ATO" width="400"/>

2️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/367b54e47efbbcd2071efabb137616d1afc4ab31/images/challenge%20platform.png"
alt="challenge platform" width="400"/>

3️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/my%20ato%20tasks%20phishing%20site.png"
alt="login" width="400"/>

4️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/sms%20code.png"
alt="SMS code verification page" width="400"/>

5️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/secret%20qus.png"
alt="Set up secret questions page" width="400"/>

6️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/personal%20info.png"
alt="Bypass secret questions and get Name, DOB page" width="400"/>

7️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/DL.png"
alt="Upload drivers licence" width="400"/>

8️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/21%20days.png"
alt="Please wait 21 days" width="400"/>

9️⃣ <br>
<img
src="https://github.com/thequietlife/phishing-analysis/blob/218841fd87c446a0f19b9705d5b43c0f73acd9a7/images/ATO.png"
alt="Pivots to real ATO website" width="400"/>


### Notes:

* A SMS text I received a few days ago.
* I wasn't able to access the phishing page at first. When I looked in the dev tools I could see it is using Cloudflare's Bot Fight Mode. h/t to @BushidoUK for this tip.
* The aim of the site is to collect users personal information by pretending to set up their ATO user account.
* The phishing site opens to a sign in page and then moves to a enter a SMS verification code. I was able to step through the phishing kit by entering fake information. 
* The next page was to set up secret questions. The target user can either set up secret questions which provide more personal data.
* There is a skip button to bypass this and progress further.
* The next page asks for Name and Date of Birth.
* The message says a medicare card and drivers licence is needed but only the drivers licence needs to be uploaded before it finishes up.
* The next page is clumsily worded with a typo but also mentioning income statement. The browser then pivots to the actual ATO website.





__________________
Sources: 
1. [Investigating SMS phishing text messages from scratch](https://blog.bushidotoken.net/2023/07/investigating-sms-phishing-text.html)
2. [Netflix themed survey phishing campaign](https://github.com/PaloAltoNetworks/Unit42-timely-threat-intel/blob/main/2025-02-03-IOCs-for-Netflix-themed-survey-phishing-campaign.txt)
