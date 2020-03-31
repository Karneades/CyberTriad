# Cyber Triad

**or how to spot Antifragility in Cyber Security**

After re-reading Antifragility by Nassim Taleb, I went on mapping the
_Triad_ (fragility, robustness, antifragility) to different areas of cyber
security and their characteristics. I don't know where that's leading to and
whether it has a value at all. But it's fun as a thought experiment anyways.
Maybe it’s easier to discuss a future initiative with this _Triad_ in mind. So
let's detect fragility and the position of different topics in the _Triad_ and 
answer "What has more upside than downside?" and "How to get from the left to
the right?".

As in the words of Nassim Taleb:

> This is the key to the Triad - we can classify things by three simple
> distinctions: things, that in the long run, like disturbances (or errors),
> things that are neutral to them, and those that dislike them.

And

>The Triad gives us some indication of what should be done to live in a world
>that does not want us to understand it.

Cyber security is exposed to uncertainty in all the involved fields, from
prevention, to detection, to technology in general and at most to
unpredictable attackers, _Gegenspieler_ so to speak.

Let's see how we can change it and start appreciating randomness and
uncertainty to improve the (cyber) security for all of us. To my dear reader,
with just a click of pull request it’s possible to contribute to the Cyber
Triad!

**Afterthought** When looking at the table, there are multiple topics which
have low downside but bring a lot of upside, especially bug bounty programs,
red teaming, threat hunting and research time for analysts and engineers. In
this areas the most upside is given due to the nature of the activity: most
open to findings and new insights but in a controlled environment.

| Fragile | Robust | Antifragile |
| --------| ------ | ----------- |
| no bug bounty program at all | bug bounty program for specific applications, limited scope | bug bounty for whole infrastructure, the real deal! |
| bug bounty notification results in fixing only the exact location of the vulnerability | bug bounty notification results in fixing all similar issues on the same platform | bug bounty notification results in fixing all similar issues on all platforms, take all to the next level
| no information sharing | information sharing internally | information sharing globally |
| searching for IOC like hash or IP to infrastructure after incident detection | | searching for TTPs in infrastructure | 
| no threat hunting program | | threat hunting program |
| security architecture in theory | security architecture centrally managed, every team must be supervised | security architecture decentralized managed, teams get their information from a central place but do their work on their own |
| no lessons learned after incident | | lessons learned with prevention and detection improvement |
| | | threat intelligence and external information analysis
| block malware without identified root cause | block malware with identified root cause for specific platform | block malware with identified root cause for all platforms |
| no red teaming or penetration testing | penetration testing | red teaming |
| risk management with theory and probabilities about future attacks and without real value for prevention but with the side effect that too much risks are taken due to the illusion of knowledge | risk management with focus on reducing negative exposure and use it to improve prevention | | 
| closed source  | | free software and open source security tools | 
| detection rules are kept in-house | | sharing of detection rules in public or at least in trusted groups |
| closed source and self-made cryptography | time tested, free and open source cryptography | |
| only one layer of defense | second or more layer of defense, the failing of one is assumed | |
| no research and playground to develop tools, preventions and detections | | research and playground to develop tools, preventions and detections |
| untested detections with too narrow rules | detections with techniques using more generic patterns | |
| too narrow and easy to bypass preventions | preventions with enough buffer for bypasses | |
| all application are allowed to be executed | application whitelisting | baselining and user behavior for blocking unwanted software |
| no DDoS protection | DDoS protection for the single Internet access | distributed internet access and multiple access layers |
| theorised attack models |  attack models studied based on (unfortunately) experienced incidents | red team thinking "without a box" and without constraints |
| vendor lock-in for security products | | multiple different (self-made) and independent security products |
| asking questions about how probable it is that an attacker gets access to the super secure database, then feeling secure because it’s so improbable, leaving that topic on the side after talking big words | reduce exposure of database, restrict access, build multiple detections, make it impossible to get data out of the database | |
| anxiety of customer communication when security incident happens, fear of loss of reputation uncovers fragilities because it eventually gets public anyway | known and trained communication procedures, image of company is not affected by a security incident because of a one time issue and trust is still established | as with robust but customers and public will thanks for transparent communication and appreciate it with even more sales, "their communication is more transparent", conditional that the company is comparable in all other manners |
| paying a hacker a sum to keep the reporter silent about a vulnerability | reduce exposure for all involved groups and for companies assets, user / customer information as needed | |
| likewise paying ransom after ransomware attack | restore service according to procedures and bring clean environment back online | |
| no vulnerability scanning because it could crash systems | vulnerability
scanning knowing that the systems will be robust against scanning activities | |
| know-how sharing through dedicated learning sessions | know-how sharing
through self-learning and individual training programs | |
