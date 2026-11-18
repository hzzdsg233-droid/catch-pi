Four Ways to Catch π（捕捉 π 的四种方法）· 离线网站文件包
====================================================

文件夹里有什么
--------------
index.html                网站本体（所有样式、实验和测验都在这一个文件里）
videos/                   8 个视频（英文版 4 个、中文版 4 个）和 4 张封面图
  archimedes.mp4 / archimedes_zh.mp4     割圆术          2:34
  monte_carlo.mp4 / monte_carlo_zh.mp4   蒙特卡洛        2:18
  buffon.mp4 / buffon_zh.mp4             布丰投针        2:22
  leibniz.mp4 / leibniz_zh.mp4           莱布尼茨级数    3:27
.nojekyll                 上传到 GitHub Pages 时用的空文件，不要删
README.txt                就是这个使用说明

注意：index.html 和 videos 文件夹必须放在一起，不能拆开，否则视频无法播放。


一、在自己电脑上打开（展示当天的备用方案）
------------------------------------------
1. 先把压缩包解压（不要在压缩包里直接双击打开）。
2. 双击 index.html，用 Chrome 或 Edge 打开。
3. 视频、互动实验、测验、中英切换全部可以离线使用。

小提示：
- 没有网络时，网页会改用电脑自带的字体，样式略有不同，但所有功能都正常。
- 展示前建议先在教室电脑上打开一次，确认视频能播放。


二、上传到 GitHub Pages（得到一个任何人都能打开的网址）
------------------------------------------------------
1. 注册并登录 https://github.com 。
2. 右上角 “+” → New repository，名字比如 catch-pi，选 Public，点 Create repository。
3. 在新仓库页面点 “uploading an existing file”，
   把 catch-pi 文件夹里的所有内容（index.html、videos 文件夹、.nojekyll）拖进去，
   点 Commit changes。
   （.nojekyll 是隐藏文件，如果拖不进去也没关系，网站照样能用。）
4. 进入仓库的 Settings → Pages，
   Source 选 “Deploy from a branch”，Branch 选 main、文件夹选 /(root)，点 Save。
5. 等 1～2 分钟，页面上会出现网址，格式是：
   https://你的用户名.github.io/catch-pi/
   这个网址可以发给老师、同学，也可以做成二维码放进 PPT。

说明：GitHub 网页上传单个文件的上限是 25 MB，这里最大的视频约 10 MB，可以直接上传。


三、交给老师 / 放进课程网站
--------------------------
直接把整个 catch-pi 文件夹（或压缩包）交给老师即可。
放进课程网站时，只要保持 index.html 和 videos 文件夹的相对位置不变，就能正常运行。
如果老师只需要视频，videos 文件夹里的 mp4 可以单独使用。


四、以后要修改网站
------------------
- 文字、题目、颜色都在 index.html 里，用任何文本编辑器（比如 VS Code）打开就能改。
- 换视频：用同名文件替换 videos 文件夹里对应的 mp4 即可。
