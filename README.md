# Weird Anti-Cheat Ideas
A place for collecting anti-cheat ideas that I find weird or compelling.  
Hopefully, I don't include anything that will come back to bite.

### Detection:  
- Quantifying impact of cheaters. Just player perception? If players don't notice, is there a problem?  
  - Reports / (players * playtime)? Stratify by skill, trust, spending?
  - Quantifying perception across games. What does the same person think about CS, Overwatch, and Valorant?
- Quantifying distribution of types of cheaters and tools, the amount of damage they do. 
- Is machine learning the end game? Or other automated systems? When do bans have to be manual?
- Generating artificial cheat vs legitimate data by simulating bots with cheats vs no cheats.
- Graph neural networks for unsupervised clustering of friend graphs.
- Kaggle competition for classifiers. Why crowdsource just the labels?
- Recording system optimizations:
  - Shadowplay past 30 seconds of enemy
- Reporting system optimizations:
  - Labels in time
  - Labels with type and degree
  - Record abusive text and voice (legal?)
- Weird features:  
  - Quantify aim skill relative to other skills (movement, inventory management)   
  - Drastic changes in some skill  
  - Weird networking, changing IP, changing latency
  - Knowledge of enemy positions
  - Burst DPS
  - Features that discourage blatant hacking
  
### Prevention:  
- Occlusion culling / fog of war  
- Give up fighting client-side code protection?  
  - What can you do against hardware access?  
  - How skilled are cheat developers?  
- Increasing cheater cost of reentry, higher level for comp, price tag, 2FA  
  - Sandbox highly skilled new accounts, or accounts with recently changed passwords or IP, or are behind a VPN 
  - Stricter identification requirements for top ~1% ranks  
- Foliage that matches pixel bot color.

### Deterence:  
- Give up on permabans? Isn't there always eventually a workaround?  
- False positive quantification, defining and constraining cost  
- Integrate with VAC 
- Shadowban. Populate servers with some bots. Give them their own leaderboards.

### Behavioral:  
- Compensate players for running into cheaters, without making the system gameable  
- Rollback competitive game changes if a cheater is later detected  
- Incentivize players to help with crowdsourced detection  
- Reward cheaters for staying in isolated lobbies
- Game modes that satisfy desires of cheaters

### Industry Goals:
- Anti-cheat developer community of scale similar to anti-malware community? Journals? Conferences?  
- How to incentivize people working at competing companies to contribute?
- Simple, open-source tools to help small developers protect themselves.  
- Incorporating ideas from many genres? FPS, MMO, RTS, MOBA.  
- Gaining knowledge from EAC and Battleye. Job opportunities?  
- Collaborating with former and current cheat creation researchers.
- Specific companies to reach out to:
  - Valve
  - Riot
  - EA
  - Tencent
  - Blizzard | Activision
  - Epic Games
  - Bungie
  - Ubisoft
  - Dice
  - Bohemia Interactive
  - New World Interactive
  - EAC, Battleye, Denuvo
  - ESA, Fair Play Alliance

### Economic:  
- Measure economic impact of cheaters on current and past games.  
- Convincing community, shareholders, and directors to support us.  
- Measuring elasticity of cheat demand.  
- Possible to undercut cheat providers? Or does supply just create more demand?  

### Developer Practices:  
- EAC dev recommends to not announce ban waves (small number looks lazy, big number normalizes cheating).  
  - Still give feedback through individual ban announcements like Battleye?  
- Don't interact with trolls on forums.  
- Communicate with community in clearly designated cheat forum. Get player feedback, ideas, desires.  
- Act like a duck.  
- How transparent should you be about features? Should you be totally transparent if you can?  
- Stay safe
  - Don't be a target. Would someone be incentivized to harm you or your friends?  
  - Use good personal security practices.  

### Community Interaction
- Bad behavior is purely about player experience and perception
- Survey community for perceptions and suggestions
  - In game?
  - Incentives to reply?
  - Stratify based on skill, playtime, spendnding?
  
### Project Management:  
- Ideal anti-cheat team composition. Size, skills?  
- Collaborating with security team?  
- How much labor to outsource to third parties. How deeply integrated should those systems be?  
- Beta deploy features? Slow partial rollout? Playtest with pros? 

### Career:
- Where to start working? Indie devs, studios, publishers, third-party solutions, cheaters?
- How to decide between offers?
  - Potential to learn
  - Potential to make an impact
  - Potential to make connections
  - Collaborative open-source spirit!
  - $? Not really.

### Misc:  
- Trust factor depending on linked accounts. Integrate with Valve's trust factor.  
- Grouping cheaters together in games instead of banning.  
- Custom game modes with wallhacks and easy aim, maybe speed. Modes with asymmetric player power.  
- Legally taking down cheat providers.  
- Mobile constraints?  
- Laying traps for cheat developers, bait or directed evolution.  
- Collaborating locally to secure different regions. Tencent for China.
- Speech to text to voice line?

### Favorite talks
https://www.gdcvault.com/play/1024994/Robocalypse-Now-Using-Deep-Learning
https://www.gdcvault.com/play/1025804/Reporting-Metasystem-Design-and-Penalization
https://www.gdcvault.com/play/1026757/What-Does-It-Take-to
