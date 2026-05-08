GXICC国三年级羽毛球联赛网页

文件：
- index.html：主赛事控制台，比分输入、自动晋级、男单小组排名、设置当前比赛、Reset Draw
- draw.html：抽签页面，假随机动画、保存正式签表、Reset Draw
- viewer.html：观众页面，只显示logo、当前比赛、树状淘汰赛、小组排名、比赛结果和下一场
- assets/gxicc-logo.png：logo

推荐使用流程：
1. 打开 draw.html
2. 点击 Begin Draw / Reveal All
3. 点击 Save Official Draw
4. 回到 index.html
5. 点击 Refresh Draw
6. 在 index.html 里输入比分，每场点击 Save
7. 想投屏/给观众看时，打开 viewer.html
8. 在 index.html 的某场比赛中点击 Set Current，viewer.html 会自动显示当前比赛

Reset Draw：
- index.html 右上角 Reset Draw：会同时清除抽签、比分、当前比赛，避免旧比分和新签表冲突。
- draw.html 的 Reset Draw：只清除保存的抽签结果。

注意：
- index.html / draw.html / viewer.html 需要在同一个网址或同一个文件夹下打开，localStorage 才能共享。
- 用 GitHub Pages 发布会更稳定。
