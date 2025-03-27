### Phishing campaign impersonating Commonwealth Bank (Aus)

<img
src="https://github.com/thequietlife/phishing-analysis/blob/2ba00078bd2b363dcc3b8cb022dceb4977be6d5e/images/cba%20scam.png"
alt="SMS supposedly from Commonwealth Bank" width="400"/>

<img
src="https://github.com/thequietlife/phishing-analysis/blob/93d25bc8c9854e55622be2e8c53c4aaeb4a2a518/images/cba%20domaintools.png"
alt="domaintools record for cbahome[.]info" width="500"/>

<img
src="https://github.com/thequietlife/phishing-analysis/blob/ee8ac56d03a6457beece9621f49afcdc29db94cf/images/cba%20whois_2.png"
alt="more domaintools record for cbahome[.]info" width="500"/>

<img
src="https://github.com/thequietlife/phishing-analysis/blob/2a242a711eb286edf04ec1279b41843f84b6a2be/images/cba_screenshot.png"
alt="screenshot for cbahome[.]info" width="500"/>

<img
src="https://github.com/thequietlife/phishing-analysis/blob/32394521c0746d0ff1192b5e5456085512c5e5cd/images/cba%20actual.png"
alt="screenshot legit CBA website" width="500"/>


### Notes:

* Uses call spoofing/caller id spoofing
* The whois record gives us a bit of intel.
  - Date created: a few days ago
  - Registrar details: NameSilo
  - Host: Cloudlflare
  - IP address
* One line is of interest in the Whois Record "Domain Status: pendingDelete".
* Screenshot of the phishing site before it was taken down
* Screenshot of the actual Commbank website for comparison. 
