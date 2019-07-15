# Pi-Hole

This is meant as a way to aggregate multiple blocklists into one. It contains approximately 2,016,000 Blacklisted domains (please note that I am not perfect and there are duplicates within each list and overlap between lists). In no way am I the original creator of these lists and nor do I claim to be, I have only combined ones I felt have been useful and/or ones that I personally use. All lists (or where they can be found) will be linked below. Please make sure to utilize the provided white-list regardless of if you use the Extended Primary Blocklist.

---

## Installation
1. Log on to the Pi-Hole WebUI
2. Navigate to Settings>Blocklist
3. Scroll down and copy the Lists from below that you would like to use:
4. Go to the [Primary Whitelist](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Whitelists/Primary%20Whitelist.txt) and simply copy all of the Domains and paste them in the Whitelist section of your Pi-hole.
```
List 1: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Primary%20Blocklist.txt
List 2: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Extended%20Primary%20Blocklist.txt
List 3: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Secondary%20Blocklist.txt
List 4: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Tertiary%20Blocklist.txt
List 5: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Supplemental%20Blocklist.txt
```
- [List 1:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Primary%20Blocklist.txt) (1,057,808 Individual domains blocked) Contains domains from WaLLy3K over at https://firebog.net. All of these Domains are considered least likely to interfere with browsing.
- [List 2:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Extended%20Primary%20Blocklist.txt) (406,371 Individual domains blocked) Contains domains from WaLLy3K over at https://firebog.net. These domains are likely to block multiple useful sites (e.g: Pi-hole updates, Amazon, Netflix). Please note that this can interfere with many normal, non-ad related features on devices. (For advance users)
- [List 3:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Secondary%20Blocklist.txt) (1,339,180 Individual domains blocked) Contains domains gathered from The Blocklist Project (includes lists from: ads, fraud, fakenews, malware, phishing, porn, ransomware, redirect, scam, spam, and tracking)
- [List 4:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Tertiary%20Blocklist.txt) (682,029 Individual domains blocked) Contains other domains gathered from various locations and through personal trial and error. These block things including Malware, Phishing, Tracking, and Ads.
- [List 5:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Supplemental%20Blocklist.txt) (TBD Individual domains blocked) This is a list of domains that I have found intrusive and/or of additional ad-serving domains that have been missed in the other lists found above. (Please note this is currently a short, slowly growing list so it is not vital and may or may not impact much of anything.)
---

## To Do

- [x] Primary Blocklist (List 1)
- [x] Extended Primary Blocklist (List 2)
- [x] Primary Whitelist
- [x] Secondary Blocklist (List 3)
- [x] Tertiary Blocklist (List 4)
- [ ] Supplemental Blocklist (List 5)
- [ ] User requested lists

---

### DISCLAIMER

**I AM NOT RESPONSIBLE FOR ANY NETWORK CONNECTIVITY ISSUES AS A RESULT OF USING THE ABOVE MENTIONED LISTS, USE AT YOUR OWN RISK**

Also, if I used your list and forgot to mention you, please contact me and I will correct this.

---

##### Credits:
- *WaLLy3K* over at https://firebog.net for the first and second lists.
- All the good people at https://blocklist.site/app
