# Weird Anti-Cheat Ideas
## Objective:
- Minimize the impact of cheaters in FPS games by 2025

## Key Ideas:
- Some anti-cheat systems are robustly secure, immune to client-side security arms race
  - VACNET-like detection pipelines robustly model player perception of "cheaty-ness"
  - Occlusion culling systems prevent hard-to-detect wallhacks and are information-theoretically secure
  - Damage control (rollbacks/compensation) alleviate the damage of even the most blatant cheats
- Proctoring tournaments (camera recording mouse and monitor) increases competitive integrity
- Implement an unbiased player feedback collection, analysis, and reporting system
  - Gather diverse and great ideas
  - Hold the community accountable for its suggestions
- Tie efforts with anti-harassment work
  - Both problems have similar causes and solutions
  - Easy to find organizational support
  - Harassment can cause more damage than cheaters

### Detection:  
- Quantifying impact of cheaters
  - Reports / (players * playtime)? Stratify data by player skill, trust, spending?
  - Player retention
  - Quantifying perception across many games
- Quantifying distribution of types of cheaters and tools to prioritize targets
- Proctoring major online tournaments
- Implement efficient replay system for VACNET
- Improved labels provided to VACNET
  - Labels in time
  - Labels with type of hack and degree of certainty/severity
  - Record abusive text and voice (legality?)

- Kaggle competition for classifiers. Why crowdsource just the labels?
- Cool features:
  - Trust factor
  - Lack of non-aim skills (movement, decision making, pre aim, discipline)
  - Drastic changes in skill
  - Network access patterns
  - Knowledge of enemy positions, never looking in a direction without enemies
  - Burst DPS
 - Inspiring architectures:
   - Valve's GRU on raw mouse dynamics
   - Transformer and unsupervised pre-training to improve skill encoding
   - Stack or average predictions of per-engagement models?
   - https://d4mucfpksywv.cloudfront.net/emergent-tool-use/images/multi-agent-policy-architecture-20190904a.png
   - Graph neural networks for unsupervised clustering of social graphs
- Generating artificial aimbot data with a GAN. Will basic smoothing aimbots be classified as abnormal?
- Generating aimbot data from constrained self-play
  -  "Supervised deep learning systems can only be as good as their training datasets, but in self-play systems, the available data improves automatically as the agent gets better." https://openai.com/blog/more-on-dota-2/
  
### Prevention:  
- Occlusion culling/fog of war
- Increasing cheater cost of reentry--2FA, trust factor, time requirements
- Protecting high-profile streamers from playing against suspicious accounts
- Securing the client
  - Quantify effectivness to determine development focus
  - What can you do against adversaries with physical access?  
- Sandbox highly skilled new accounts, accounts with recently changed passwords or IP 
- Stricter identification requirements for top ~1% ranks  
- Messing with pixel bots by tweaking in-game colors
- Feasibility of hardware security, secure enclaves

### Deterence:  
- HWID and network bans--same issues as securing the client 
- False-positive quantification, defining and constraining error budget  
- Integrate with VAC
- Ban alternatives
  - Shadowban, use bots to supplement population
  - Make shadow pool engaging to cheaters with leaderboards and features. Unlikely to stop malicious types.
  - Spyro DRM strategy. Pester cheaters in subtle ways that make them blame the game or the hack.

### Behavioral:  
- Compensate players for running into cheaters, without making the system gameable  
  - Rollback competitive game changes if a cheater is detected
  - Thank them for reporting cheaters
- Incentivize players to help fight cheaters
- Again, incentivize cheaters to stay in isolated lobbies

### Anti-Harassment
- Harassment likely causes more damage than cheaters
- Really easy to get organizational support
- Best damage control and rehabilitation policies?
- Harassment and hatred aren't specific to gaming, but it's enhanced by it.
- How to cultivate a community that brings out the goodness in everyone?

### Industry Goals:
- Encourage collaboration, publications, and conferences
  - Individual developers often like to share ideas
  - Large-scale efforts hampered by organizational pursuit of competitive advantage
- Simple, open-source tools to help small developers protect themselves.  
- Incorporating ideas from many genres? FPS, MMO, RTS, MOBA, table-top.
- Consulting with former and current cheat creators
- Specific companies to reach out to (in loose order):
  - Valve
  - Riot
  - Tencent
  - EA / EAP
  - Denuvo, EAC, BattleEye
  - Epic Games
  - PUBGC
  - Blizzard / Activision
  - Jagex
  - Chess.com
  - Bungie
  - Ubisoft
  - Bohemia Interactive
  - New World Interactive
  - Other indies
  - ESA, Fair Play Alliance

### Economic:  
- Measure economic impact of cheaters on current and past games
- Consider studies on economics of drug industry
- Measuring elasticity of cheat demand
- Possible to undercut cheat providers? Or does supply just create more demand?

### Developer Practices:  
- EAC dev recommends to not announce ban waves (small number looks lazy, big number normalizes cheating)
- Don't get involved with trolls, only interact with polite users
- Be transparent with community, hold both parties accountable
- Act like a duck--always calm above water
- Stay safe
  - Don't be a target. Would someone be incentivized to harm you or your friends?  
  - Use good personal security practices. Passwords, 2FA.
  - Separate hardware network and VM for dangerous work.

### Community Interaction
- Success is primarily about player experience and perception
- Survey community for perceptions and suggestions
  - Controlled in-game form, Google form, forum analytics?
  - Gather additional data on player trust, skill, playtime, etc.
  
### Project Management:
- How to prioritize anti-cheat strategies?
  - Impact (short/long term)
  - Cost (to develop and distribute)
  - Strategies of competitors
  - Community feedback
- Ideal anti-cheat team composition. Size, skills?  
- Collaborating with infosec/security team?  
- Getting organizational resources, using analytics to determine areas of focus
- How to integrate and delegate tasks to third parties like EAC?
- Testing framework. Playtest with pros? Roll out in one map/mode? Random rollout with RCT?

### Career:
- How to ramp up quickly and sustainably
- How to decide between offers?
  - Potential to learn and network
  - Potential to make an impact (freedom, development resources, open-sourcing, company vision)
- Turn down a good offer for a chance of a better offer? Uncertainty of appraisal, expected utility
- Conisder contracting:
  - https://www.youtube.com/watch?v=R1aznQvqMQw
  - Find a good attorney

### Thoughts on Hack vs. Hack
- Could be a mode with competitive integrity, save for problems with balance.
- Hard to get into because it requires investment in VPN and VM/separate machine.
- Rewards decision making over mechanical aim in fights.
- Rewards strategy and teamplay over positional game sense and information control.
- Rewards usage, tuning, and creation of tools.
- Hopefully reduce casual cheating a little bit. Ineffective at deterring people who hack to win.

### Misc:  
- Examine MOBA market's response to Riot's anti-cheat
- Trust factor, possibly integrate with Valve's.  
  - Does trust factor increase cheat contagion?
- Custom game modes with wallhacks and easy aim, maybe speed. Modes with asymmetric player power.  
- Legally taking down cheat providers. Studies on effectiveness? 
- Laying traps for cheat developers, bait, or directed evolution.  
- Determine special considerations for Asian markets

### News
- (April 2020) https://www.pubg.com/en-us/2020/04/21/dev-letter-anti-cheat-performance-plans-for-2020/

### Favorite talks
- https://www.gdcvault.com/play/1024994/Robocalypse-Now-Using-Deep-Learning
- https://www.gdcvault.com/play/1025804/Reporting-Metasystem-Design-and-Penalization
- https://www.gdcvault.com/play/1026757/What-Does-It-Take-to
- https://www.youtube.com/watch?v=knvySXCNfd8
- https://www.youtube.com/watch?v=C5qfKaVe89c
