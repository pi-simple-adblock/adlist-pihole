# adlist-pihole

# List iklan untuk pihole dengan filtering

# Penggunaan 

INSTALL PI HOLE
===============
apt update
apt upgrade
curl -sSL https://install.pi-hole.net | bash
 
 
BLOCKLIST:
==========
https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts_without_controversies.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
https://v.firebog.net/hosts/static/w3kbl.txt
https://v.firebog.net/hosts/BillStearns.txt
https://www.dshield.org/feeds/suspiciousdomains_Low.txt
https://www.dshield.org/feeds/suspiciousdomains_Medium.txt
https://www.dshield.org/feeds/suspiciousdomains_High.txt
https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
https://someonewhocares.org/hosts/zero/hosts
https://raw.githubusercontent.com/vokins/yhosts/master/hosts
https://winhelp2002.mvps.org/hosts.txt
https://hosts.nfz.moe/basic/hosts
https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt
https://ssl.bblck.me/blacklists/hosts-file.txt
https://adaway.org/hosts.txt
https://v.firebog.net/hosts/AdguardDNS.txt
https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
https://v.firebog.net/hosts/Easylist.txt
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts
https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts
https://v.firebog.net/hosts/Easyprivacy.txt
https://v.firebog.net/hosts/Prigent-Ads.txt
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts
https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt
https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt
https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt
https://v.firebog.net/hosts/Prigent-Crypto.txt
https://v.firebog.net/hosts/Prigent-Malware.txt
https://mirror.cedia.org.ec/malwaredomains/immortal_domains.txt
https://www.malwaredomainlist.com/hostslist/hosts.txt
https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt
https://phishing.army/download/phishing_army_blocklist_extended.txt
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt
https://v.firebog.net/hosts/Shalla-mal.txt
https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
https://urlhaus.abuse.ch/downloads/hostfile/
https://raw.githubusercontent.com/HorusTeknoloji/TR-PhishingList/master/url-lists.txt
https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_all.list
https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_top1m.list
https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser
 
 
WHITELIST:
==========
s3.amazonaws.com
clients2.google.com
clients3.google.com
clients4.google.com
clients5.google.com
www.bit.ly
bit.ly
ow.ly
j.mp
goo.gl
tinyurl.com
msftncsi.com
www.msftncsi.com
ea.com
cdn.optimizely.com
gravatar.com
rover.ebay.com
imgs.xkcd.com
netflix.com
alluremedia.com.au
tomshardware.com
ocsp.apple.com
s.shopify.com
keystone.mwbsys.com
dl.dropbox.com
api.ipify.org
