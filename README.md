<div align="center">
  <img alt="Logo" src="https://raw.github.com/JIEJOE-Visual/MAA/main/img/screenshots/1.png" width="100" />
</div>
<h1 align="center">
  SNAKEBALL
</h1>
<p align="center">
  ⌨Tech stack: <b>HTML, CSS, JS, SVG, Vue, Pinia, GSAP, Howler, Matter</b>
</p>

![screenshot](https://snakeball.jiejoe.com/meta/screenshot.jpg)

<br>

## 📜 About this project
SNAKEBALL是一个休闲网页小游戏，在游戏中，玩家可以操控一条由球体组成的小蛇、在屏幕范围内随意移动，<br>
小蛇的身体每隔随机的时间会进行重置：小蛇的移动速度、以及身体的延迟都会发生改变，<br>
在关卡时间里，屏幕内会出现各种各样的子弹球，玩家需要根据情况来“吃”或者“碰撞”它们，并获得一定的分数，以计入排行榜。<br>

<br>

## ✊️ Support me
如果不懂这个网站怎么交互、或者想了解更多内容的小伙伴可以查看演示视频👇

<a href="https://www.bilibili.com/video/BV1gqZ4Y1ETA/">
<img src="https://i2.hdslb.com/bfs/archive/c6c949165f5b927c70ebd240267f177f887305ea.jpg" width="40%">
</a>

如果你觉得这个项目还不错的话，欢迎你的**Fork**或**Star**，非常感谢🙇‍

<br>

## 🛠 Set up
1. 初始化node_modules，构建项目

   ```sh
   npm install
   ```

2. 启动Vue开发服务器

   ```sh
   npm run serve
   ```

3. 将项目打包成静态网页

   ```sh
   npm run build
   ```
   
4. 所有代码的中文注释已全部添加，因为JIEJOE是第一次做WEB游戏，所以有的地方难免存在不合理的代码和BUG，还请见谅。
5. 该项目会涉及到后端服务和数据库，但是因为涉及隐私包括其他部分原因，上传的项目里面、不包含后端服务和数据库代码，项目里对应的数据请求链接被JIEJOE替换成了占位字符串，但总体不影响游戏的游玩体验（只有排名部分无法正常进行），有后端服务和数据库需求的小伙伴还请自己配置相应内容。
6. JIEJOE已经尽量将交互内容和游戏逻辑内容给独立分开，项目的主交互界面在src/components/sections里面，游戏的主逻辑代码在src/components/game/stage里面，感兴趣的小伙伴可以自己研究。
<br>

## 🎨 Color reference
| Color         | Hex      | Block
| --------      | ---------| -------------
| black         | #080808  | ![#080808](https://placehold.co/15/080808/080808)
| white         | #f8f8f8  | ![#f8f8f8](https://placehold.co/15/f8f8f8/f8f8f8)
| gray          | #8b8b8b  | ![#8b8b8b](https://placehold.co/15/8b8b8b/8b8b8b)
| yellow        | #e3d80f  | ![#e3d80f](https://placehold.co/15/e3d80f/e3d80f)
| fireball      | #dc1130  | ![#dc1130](https://placehold.co/15/dc1130/dc1130)
| medicineball  | #0ee515  | ![#0ee515](https://placehold.co/15/0ee515/0ee515)
| frozenball    | #16b7df  | ![#16b7df](https://placehold.co/15/16b7df/16b7df)
| scaleball     | #a37e22  | ![#a37e22](https://placehold.co/15/a37e22/a37e22)
| splitball     | #ef7706  | ![#ef7706](https://placehold.co/15/ef7706/ef7706)
| magneticball  | #113ede  | ![#113ede](https://placehold.co/15/113ede/113ede)
| shadowball    | #9f4df0  | ![#9f4df0](https://placehold.co/15/9f4df0/9f4df0)
| invisibleball | #808080  | ![#808080](https://placehold.co/15/808080/808080)
| signalball    | #ea4fc0  | ![#ea4fc0](https://placehold.co/15/ea4fc0/ea4fc0)
| hball         | #046312  | ![#046312](https://placehold.co/15/046312/046312)

