+++
date = "2017-01-18T11:44:56+02:00"
title = "FinMacAdmin 20.1.2017"
categories = ["blog", "FinMacAdmin"]
draft = false
+++
After a short hiatus, FinMacAdmin is back again - bigger and better than ever!
<br/><br/>
This year, the organizers will bring you our first ever guests from outside Finnish borders as [Henry Stamerjohann](https://github.com/headmin) ([Slack](macadmins.org):@henry) from [Apfelwerk](https://www.apfelwerk.de) and Viktor Glemme ([Slack](macadmins.org):@glemme) from [JAMF](https://www.jamf.com) will be presenting at the event.

Henry and Viktor will be joined on stage by the household names, such as [Hannes Juutilainen](https://github.com/hjuutilainen) (@hjuutilainen) and [Janne Lehikoinen](https://github.com/jlehikoinen) (@fatmrcrab).

## Attending:

We are sold out for this event.


## Venue:

The event will be held in the former Tieto Headquarter offices in Helsinki.  
The address is: Aku Korhosen tie 2, Helsinki.

Location on Google Maps: https://goo.gl/maps/9sttfNYPgsq


## Program
The event will start at 11.00(AM), speakers are adviced to arrive at 10.00(AM).

*Hands-on sessions have prerequisites, please familiarize yourself with them beforehand.*

### Schedule:
- 11.00 - 11.15: Registration and Welcome
- **11.15 - 12.00:** Janne Lehikoinen (Tieto Oyj): iOS & SysAdmin Tools
- 12.00 - 12.30: Lunch break
- 12.30 - 13.30: Lightning talks:
  - Hannes Juutilainen (University of Jyväskylä): *AutoPkg 1.0 features*
  - Antti Pettinen (Tampere University of Technology): *Caddy and Santa came to town*
- 13.30 - 14.15 Viktor Glemme (JAMF): *JAMF Pro*
- 14.30 - 18.00: Henry Stamerjohann (Apfelwerk): *Hands on Zentral*
  - read prerequisites from [FinMacAdmin2017/hands_on_zentral](https://github.com/macadminfi/finmacadmin2017/blob/master/hands_on_zentral/Prerequisites.md)
  - ssh-keys can be generated as follows:
      1. Open terminal
      2. ```ssh-keygen -t rsa -b 4096 -C "your.email@example.com"```
      3. When prompted, fill in the location where to save the key:  
          - for example: ```/Users/YourUserName/.ssh/id_rsa_zentraldemo```
      4. To secure your key, type in a passphrase
      5. Add key to your ssh-agent:
          1. Start the ssh-agent if not already running: ```eval "$(ssh-agent -s)"```
          2. Add the key to your ssh-agent: ```ssh-add ~/.ssh/id_rsa_zentraldemo``` (replace the name of the key if necessary)
- 18.00 -> : Discussion and Sauna (of course)



## Material

Material will be available in the MacAdminFi GitHub repository: https://github.com/macadminfi/finmacadmin2017


## Sponsors:

We thank these companies for support:

- [Tieto Oyj](https://www.tieto.com/)
- [JAMF](https://www.jamf.com/)

Special thanks to our employers for allowing us to work on the event not just on our free time.
