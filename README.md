# Pi-Hole

This is meant as a way to aggregate multiple blocklists into one. In no way am I the original creator of these lists and nor do I claim to be, I have only combined ones I felt have been useful and/or ones that I personally use. All lists (or where they can be found) will be linked below. Please make sure to utilize the provided white-list regardless of if you use the Extended Primary Blocklist.

---

## Installation
1. Log on to the Pi-Hole WebUI
2. Navigate to Settings>Blocklist
3. Scroll down and copy the Lists from below that you would like to use:
```
List 1: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Primary%20Blocklist.txt?token=AG7JK7JXOUUEVO6FUNSNUZK5CAWHU
List 2: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Extended%20Primary%20Blocklist.txt?token=AG7JK7PSKLWXHQL24BFXOUS5CAWJS
List 3: https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Secondary%20Blocklist.txt
```
- [List 1:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Primary%20Blocklist.txt?token=AG7JK7JXOUUEVO6FUNSNUZK5CAWHU) Contains domains from WaLLy3K over at https://firebog.net. All of these Domains are considered least likely to interfere with browsing.
- [List 2:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Extended%20Primary%20Blocklist.txt?token=AG7JK7PSKLWXHQL24BFXOUS5CAWJS) Contains domains from WaLLy3K over at https://firebog.net. These domains are likely to block multiple useful sites (e.g: Pi-hole updates, Amazon, Netflix). Please note that this can interfere with many normal, non-ad related features on devices. (For advance users)
- [List 3:](https://raw.githubusercontent.com/nicholasb2101/PiHole/master/Blocklists/Secondary%20Blocklist.txt) Contains domains gathered from The Blocklist Project (includes lists from: ads, fraud, fakenews, malware, phishing, porn, ransomware, redirect, scam, spam, and tracking)

---

## To Do

- [x] Primary Blocklist (List 1)
- [x] Extended Primary Blocklist (List 2)
- [x] Primary Whitelist
- [x] Secondary Blocklist (List 3)
- [ ] User requested lists

---

##### Credits:
- *WaLLy3K* over at https://firebog.net for the first and second lists.
- All the good people at https://blocklist.site/app
