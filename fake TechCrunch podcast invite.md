### Phishing Campaign Impersonating TechCrunch Journalist

### About: 
A recent phishing campaign has used a fake request to appear on a TechCrunch podcast as its lure. Posing as a TechCrunch journalist they approached AI startup founders and ask them to appear on a podcast. 

<img
src="https://github.com/thequietlife/phishing-analysis/blob/e827054fb9eef2d7832f756706501c8b094e5b06/images/%22TechCrunch%22%20invite.png"
alt="DM from fake journalist" width="400"/>


### Where: 
X.com via a DM

### How: 
The calendar invite appears to be a Google calendar invite. But the URL actually is a malicious Calendly link. The URL is shortened thereby hiding it's true address. Once the invite had been accepted the threat actor has access to edit the victim's X account. 

### Why: 
The threat actor posts as the victim and posts a crypto token promotion (cryptocurrency Signa). They get people to buy tokens and then they sell them to make a profit. But the people who have bought into it do not make any money. Referred to as "pump and dump". 

### Timeline Analysis:

**2025** <br>

**Thur 13 Feb** <br>
7:24AM. Victim receives DM on X from a threat actor posing as a TechCrunch journalist inviting them to be on a podcast. <br>
<br>
**Fri 14 Feb** <br>
7:10PM. Victim accepts the invitation and asks the "TechCrunch journalist" to email their Head of Partnerships. <br>
<br>
**Sat 15 Feb** <br>
1:34AM. Threat actor continues to communicate via DM. Asks victim for their availability. <br>
12:12PM. Victim provides three timeslots. <br>
12:50PM. Threat actor sends invite to podcast. It appears as Google calendar. <br>

* Victim accepts invitation which opens a "Authorize Google Calendar to access your account?"
* This leads to a Calendly scheduling link
* Calendar event name appears as "Confirmed: Pre Discussion with Pre Discussion - 30 Minutes on Wednesday, February 19, 2025"

**Wed 19 Feb** <br>
Victim notices their X profile has updated and realises the account has been compromised.

**Thur 20 Feb** <br>
Victim gets ready for call:
1. The calendar event has no meeting link
2. Sees the name and email address of the sender - a unique private duck address, and realises how the X bio was changed.



**End Notes:**

h/t [Alex Banks for sharing what happened](https://x.com/thealexbanks/status/1892278711267053641) <br>
h/t [Jake | JCyberSec_ for their analysis](https://x.com/JCyberSec_/status/1892475501274358054) <br>
[X hacking spree fuels "$HACKED" crypto token pump-and-dump](https://www.bleepingcomputer.com/news/security/x-hacking-spree-fuels-hacked-crypto-token-pump-and-dump/)







