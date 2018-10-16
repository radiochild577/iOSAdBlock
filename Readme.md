# iOS AdBlock list

My personal hosts file that I began creating back when I was jailbroken on iOS 11.3.1. I’m no longer jailbroken as I upgraded to an iPhone XS (and there is no iOS 12 jailbreak yet), so I took the jailbroken hosts file and converted it into a format that can be used on stock iOS to block ads in apps, on the web, prevent cert revokes, etc. 

I tried a few different host file tweaks and still saw ads in a few places, so I decided to take a few of the better jailbreak/tweak host files and combine them into one. This list is a combination of the hosts files listed below, with duplicates between the different lists removed, and I also added a few custom rules myself. The rules that I added prevent iOS cert revokes (for signing service/sideloaded apps), block ads in the Yahoo Fantasy app, and allow YouTube and Facebook to function properly (since some of the blocked URLs of these host files killed some functionality on these sites for me). 

To use this hosts file on iOS, install AdGuard/AdGuard Pro from the App Store, and add a Privacy subscription setting to the raw version of this list (https://raw.githubusercontent.com/radiochild577/iOSAdBlock/master/Hosts.txt).  


The host files below were used in generating this custom list:

  • Minimal Hosts Blocker (https://www.ios-repo-updates.com/pack/92278/)
  
  • AdMissile (http://pwn20wnd.science/repo)
  
  • Thireus Untrusted Hosts Blocker (https://www.ios-repo-updates.com/pack/95899/)
