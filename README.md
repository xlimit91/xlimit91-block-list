# xlimit91-block-list for Pi-Hole
Handpicked custom block list annoying ads, trackers, scam sites etc. for Pi-Hole.

![](https://raw.githubusercontent.com/xlimit91/xlimit91-block-list/master/img/xlimit91-pihole-blocklist-github-banner.jpg)

You can add the list to your adblock or Pi-Hole if you want. I will try to keep it up2date regularly.
- Added blacklist and regex.list seperately.
- List.txt » This list will probably not receive any new updates, or at least at longer intervals. List remains online, as some still use it.

(RAW)
- (rarely updated) List.txt: https://raw.githubusercontent.com/xlimit91/xlimit91-block-list/master/List.txt
- blacklist.txt: https://raw.githubusercontent.com/xlimit91/xlimit91-block-list/master/blacklist.txt
- regex.list (for Pi-Hole): https://raw.githubusercontent.com/xlimit91/xlimit91-block-list/master/regex.list

(HOW TO)
- Add List.txt or blacklist.txt to your Pi-Hole
  - Go to your Pi-Hole Admin Console » Settings » Blocklists » Add link/url » Click 'Save and Update' button
  - ![](https://raw.githubusercontent.com/xlimit91/xlimit91-block-list/master/img/pi-hole-admin-console-blacklist.png)
- Add regex.list to your Pi-Hole
  - Open your console and go to the folder where regex.list is located: cd /etc/pihole/
  - Copy my regex.list entries and paste it into yours. Save your regex.list file
