# Weird Anti-Cheat Ideas
A place for collecting anti-cheat ideas that I find weird or compelling.  
Hopefully, I don't include anything that will come back to bite.

### Detection:  
- Quantifying impact of cheaters. Just player perception? If players don't notice, is there a problem?  
  - Reports / (players * playtime)? Stratify by skill, trust, spending?
  - Quantifying perception across games. What does the same person think about CS, Overwatch, and Valorant?
- Quantifying distribution of types of cheaters and tools, the amount of damage they do
- Is machine learning the end game? Or other automated systems? When do bans have to be manual?
- Generating artificial aimbot data with a GAN. Will basic smoothing aimbots be classified as abnormal?
- Generating aimbot data from constrained self-play
  -  "Supervised deep learning systems can only be as good as their training datasets, but in self-play systems, the available data improves automatically as the agent gets better." https://openai.com/blog/more-on-dota-2/
- Graph neural networks for unsupervised clustering of friend graphs
- Kaggle competition for classifiers. Why crowdsource just the labels?
- Proctoring major online tournaments. Feasibility, player support?
- Recording system optimizations:
  - Hotkey to shadowplay past 30 seconds of enemy
- Reporting system optimizations:
  - Labels in time
  - Labels with type of hack and degree of certainty/severity
  - Record abusive text and voice (legality?)
- Weird features:  
  - Quantify aim skill relative to other skills (movement, inventory management)   
  - Drastic changes in some skill  
  - Weird networking, changing IP, changing latency
  - Knowledge of enemy positions, never clearing empty corners
  - Burst DPS
 - Inspiring architectures:
   - Valve's GRU on raw mouse dynamics
   - Transformer on unlabeled data to improve encoding
   - Stack or average predictions of per-engagement models? Incorporate trust factor?
   - https://d4mucfpksywv.cloudfront.net/emergent-tool-use/images/multi-agent-policy-architecture-20190904a.png
  
### Prevention:  
- Occlusion culling / fog of war
- Increasing cheater cost of reentry, higher level for comp, price tag, 2FA
- Preventing streamers from playing against suspicious accounts
- Can you fight for client-side security?
  - What can you do against hardware access?  
  - How skilled are cheat developers?  
- Sandbox highly skilled new accounts, accounts with recently changed passwords or IP 
- Stricter identification requirements for top ~1% ranks  
- Messing with pixel bots by changing in-game colors.
- Feasibility of hardware security, secure enclaves

### Deterence:  
- Give up on permabans? Isn't there always eventually a workaround?  
- False-positive quantification, defining and constraining cost  
- Integrate with VAC 
- Ban alternatives
  - Shadowban, use bots to supplement population
  - Hacker league. Ranked hack vs hack only. Exclusive cosmetics. Incentivize AI bots.

### Behavioral:  
- Compensate players for running into cheaters, without making the system gameable  
- Rollback competitive game changes if a cheater is later detected  
- Incentivize players to help with crowdsourced detection  
- Reward cheaters for staying in isolated lobbies
- Game modes that satisfy the desires of cheaters

### Note on Hack vs. Hack
- HvH can be a great mode with competitive integrity, save for problems with balance.
- Hard to get into because it requires investment in VPN and VM/separate machine.
- Rewards decision making over mechanical aim in fights.
- Rewards strategy and teamplay over positional game sense and information control.
- Rewards usage, tuning, and creation of tools.
- Hopefully reduce casual cheating a little bit. Ineffective at deterring people who hack to win.

### Industry Goals:
- Anti-cheat developer community of scale similar to security community. Journals? Conferences?  
- How to incentivize people working at competing companies to contribute?
- Simple, open-source tools to help small developers protect themselves.  
- Incorporating ideas from many genres? FPS, MMO, RTS, MOBA.  
- Collaborating with former and current cheat creators.
- Specific companies to reach out to:
  - Valve
  - Riot
  - Tencent
  - EA
  - DICE
  - Epic Games
  - PUBGC
  - Jagex
  - Chess.com
  - Blizzard
  - Activision
  - Bungie
  - Ubisoft
  - Bohemia Interactive
  - New World Interactive
  - Other indies
  - EAC, Battleye, Denuvo
  - ESA, Fair Play Alliance

### Economic:  
- Measure economic impact of cheaters on current and past games
- Consider studies on economics of drug industry
- Convincing community, shareholders, and directors to support us
- Measuring elasticity of cheat demand
- Possible to undercut cheat providers? Or does supply just create more demand?

### Developer Practices:  
- EAC dev recommends to not announce ban waves (small number looks lazy, big number normalizes cheating)
  - Still give feedback through individual ban announcements like Battleye?
- Don't get baited by trolls. Only interact with polite users
- Communicate with community in clearly designated cheat forum. Get player feedback, ideas, desires.
- Act like a duck--calm above water.
- How transparent should you be about features? Should you be totally transparent if you can? Does corporate want to maintain an advantage?
- Stay safe
  - Don't be a target. Would someone be incentivized to harm you or your friends?  
  - Use good personal security practices. 2FA, VM for dangerous work

### Community Interaction
- Success is mainly about player experience and perception
- Survey community for perceptions and suggestions
  - Controlled in-game form, Google form, our forums, or Reddit?
  - Incentives to reply?
  - Stratify based on skill, playtime, spending?
  
### Project Management:
- How to prioritize anti-cheat strategies?
  - Impact (short/long term)
  - Cost
  - Community feedback
- Ideal anti-cheat team composition. Size, skills?  
- Collaborating with infosec/security team?  
- How much labor to outsource to third parties. How deeply integrated should those systems be?  
- Beta deploy features? Playtest with pros? Rollout in one game-mode? Random rollout with RCT?

### Career:
- How to ramp up quickly and sustainably
- How to decide between offers?
  - Potential to learn and network
  - Potential to make an impact (freedom, development resources, open-sourcing)
- Turn down a good offer for a chance of a better offer? Uncertainty of appraisal, expected utility

### Misc:  
- Trust factor depending on linked accounts. Integrate with Valve's trust factor.  
- Grouping cheaters together in games instead of banning.  
- Custom game modes with wallhacks and easy aim, maybe speed. Modes with asymmetric player power.  
- Legally taking down cheat providers. Studies on effectiveness? 
- Mobile constraints?  
- Laying traps for cheat developers, bait, or directed evolution.  
- Collaborating locally to secure different regions. Tencent for China.
- Speech to text to voice line?

### News
(April 2020) https://www.pubg.com/en-us/2020/04/21/dev-letter-anti-cheat-performance-plans-for-2020/

### Favorite talks
https://www.gdcvault.com/play/1024994/Robocalypse-Now-Using-Deep-Learning
https://www.gdcvault.com/play/1025804/Reporting-Metasystem-Design-and-Penalization
https://www.gdcvault.com/play/1026757/What-Does-It-Take-to
https://www.youtube.com/watch?v=knvySXCNfd8
