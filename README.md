Newest Note: The script works for some users and now also retries downloading the RSS feed. Won't work 
for some users (including myself), this might be connected to the export not finishing on time server-side.
<s>Newer Note: The script is still working. If it isn't it might just be that soup had another outage again.</s>
<s>NOTICE: Won't work since ... hmm,  2012 as the soup export RSS isn't working anymore.</s>

This script saves your soup including enclosures and might kill your cat
(laughing or not.) A little .sh by neingeist (http://nein.gei.st.)

Usage: 

~~~
./soup-backup http://www.soup.io/export/dead23cafe42babe17n0n00b.rss
~~~

Call the script with your soup export RSS URL as the single argument. To
determine the export URL: Go to your soup, login, and open the options panel.
You'll find the export URL under 'Privacy'.

The export RSS file and the enclosures will be saved in your current working
directory. This script requires `wget` and `xsltproc`.
