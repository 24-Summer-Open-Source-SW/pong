# 🌞 HUFS Summer - OPEN SOURCE SW
### team2

> **과제** :pong

#### 👥 팀원
- **유지희** : Leader
- **김정주** : Member 2
- **김예지** : Member 3 
- **홍수지** : Member 1

### Today’s Lab: Centralized Workflow
Integration-manager workflow:<br />
#### Preparation<br />
**Maintainer:**<br />
• Create a Public Github repository<br />
• Remember to add a Readme file<br />
• Applie branch protection<br />
• Settings > Branches > Add a classic protection rule<br />
• Branch name pattern: main<br />
• Check “Lock Branch”<br />
• Add collaborators<br />

**All members:**<br />
• Clone the repository; $cd to the created folder<br />

Task assignment<br />
### 3 tasks<br />
**Paddle movement**<br />
• PaddleGUI.move_up() and move_down()<br />
• PaddleGUI.__init__(): keys assignment for left and right<br />

**Ball movement when hits the wall or paddle**<br />
• GameLogic.ball_hits_wall()<br />
• GameLogic.update(): process ball-hits situations<br />
**Score update when ball falls**<br />
• GameLogic.ball_falls_left() and ball_falls_right()<br />
• GameLogic.update(): process ball-falls situation<br />
**Note:**<br />
• In the code files, the TODOs are annotated by “# TODO:<br />

#### Workflow<br />
• Each member (except manager)<br />
• is assigned one task from the following and does the<br />
**following:**<br />
• Creates a feature branch for his task<br />
• Commits his tasks on that branch<br />
• Push that branch and requests manager to merge<br />
**Manager:**<br />
• Creates a topic branch (i.e., temp) based on master<br />
• Merges the pushed feature branch to the topic branch• After testing it, final merges the topic branch to the
master.<br />
• Deletes the topic branch
