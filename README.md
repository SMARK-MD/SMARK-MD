<h1 align="center" style="font-weight: bold;">ꪶSMARK ＭＤꫂ</h1>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<p align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=65&pause=500&color=25D30E&center=true&width=1150&height=100&lines=SMARK+BOT;MULTI+DEVICE+WHATSAPP+BOT;CREATED+BY+SILVA+ANGEL;RELEASED+BY+@SMARK-MD" alt="Typing SVG" />
    </a>
</p>

<div align="center">
    <img src="https://github.com/SilvatechB.png" width="500" height="400" />
</div>
<br>
<p align="center">
<a href="#"><img title="Dev" src="https://img.shields.io/badge/Dev-SMARK-MD-red.svg?style=for-the-badge&logo=github"></a>
</p>

<div class = "repo" align = "center">
<p align="center">
<a href="https://github.com/SilvaTechB?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/SilvaTechB?color=green&style=flat-square"></a>
<a href="https://github.com/SMARK-MD/SMARK-MD/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/SMARK-MD/SMARK-MD?color=white&style=flat-square"></a>
<a href="https://github.com/SMARK-MD/SMARK-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/SMARK-MD/SMARK-MD?color=yellow&style=flat-square"></a>
<a href="https://github.com/SMARK-MD/SMARK-MD/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/SMARK-MD/SMARK-MD?label=Watchers&color=red&style=flat-square"></a>
<a href="https://github.com/SMARK-MD/SMARK-MD"><img title="Size" src="https://img.shields.io/github/repo-size/SMARK-MD/SMARK-MD?style=flat-square&color=darkred"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/SMARK-MD/SMARK-MD/hit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2304FF00&title=hits&edge_flat=false"/></a>
<a href="https://github.com/CrazyPrince/CRAZY-MD-v2/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained-Yes-red.svg"></a>&nbsp;&nbsp;
</p>
</a>
</div>



<p align="center"><img src="https://profile-counter.glitch.me/{SMARK-MD}/count.svg" alt="SMARK-MD :: Visitor's Count" /></p>

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

#### First You Must...
1. Put star⭐️ on my repo 🥺
    <br>
2. Fork the repo
    <br>
<a href="https://github.com/SMARK-MD/SMARK-MD/fork"><img title="SMARK-MD" src="https://img.shields.io/badge/FORK_SMARK-MD-h?color=blue&style=for-the-badge&logo=stackshare&logoColor=green&labelColor=purple&color=blue"></a>

3. Scan or pair to get session ID (only Qr code give good session now)
    <br>
<a href='COMING SOON' target="_blank"><img alt='Get SESSION_ID' src='https://img.shields.io/badge/Get-Session_ID-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=green&color=purple'/></a>

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
#### DEPLOY STEPS

1. Fork This Repository 
2. Update [`config.js`] if you want more functions or skip (bot require update global.owner)
```js
{
  "SESSION_ID": "your session id here",
  "OWNER_NUMBER": "254700xxxxxx",
  "OWNER_NAME": "SMARK",
  "AUTO_READ_STATUS": "true",
  "AUTO_STATUS_SAVER": "false",
  "PACK_INFO": "👑;smark",
  "PREFIX": "."
   
}
```

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<details close>
<summary>DEPLOY TO GITHUB WORKFLOWS</summary>

**Create new file [`.github/workflows/deploye.yml`] After created, copy this and paste it there.**
```yml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start

```
</details>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

#### DEPLOY TO RENDER

1. If You don't have a account in Render. Create a account.
    <br>
<a href='https://dashboard.render.com/register' target="_blank"><img alt='Render' src='https://img.shields.io/badge/REGISTER-h?color=black&style=for-the-badge&logo=render' width="96.35" height="28"/></a></p>

2. Now Deploy
    <br>

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://dashboard.render.com/select-repo?type=web)

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

#### DEPLOY TO RAILWAY

1. If You don't have a account in Railway. Create a account.
    <br>
<a href='https://railway.app/login' target="_blank"><img alt='Railway' src='https://img.shields.io/badge/LOGIN-h?color=black&style=for-the-badge&logo=railway' width="96.35" height="28"/></a></p>

2. Now Deploy
    <br>

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/2gWw63?referralCode=Mo3xZD)

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

#### DEPLOY TO KOYEB 

1. If You don't have a account in koyeb. Create a account.
    <br>
<a href='https://app.koyeb.com/auth/signup' target="_blank"><img alt='koyeb' src='https://img.shields.io/badge/-Login-black?style=for-the-badge&logo=koyeb&logoColor=white'/></a>

3. Get [DATABASE_URL](https://github.com/A-d-i-t-h-y-a-n/hermit-md/wiki/DATABASE_URL) and copy it

4. Get [Koyeb api key](https://app.koyeb.com/account/api)

2. Now Deploy without ban
    <br>

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?...)

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

## 🔗 Follow Me
[![smark](https://img.shields.io/badge/SUBSCRIBE%20ME-red?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@silvaedits254/)</br>
[![smark](https://img.shields.io/badge/FOLLOW%20CRAZY%20ON%20WHATSAPP-green?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel)</br>
[![silva](https://img.shields.io/badge/FOLLOW%20SUPPORT%20ON%20WHATSAPP-green?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/I404Kcfw1JnIwi7n6aRvLe)</br>
[![tg](https://img.shields.io/badge/CrazyMdChat-0A66C2?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/)
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
</br>

This project is submitted to the [LICENCE CC BY-NC-SA 4.0](https://github.com/SMARK-MD/SMARK-MD/blob/main/LICENSE) And it stipulates that anyone who partially or totally using the code of this project without the authorization of the Author should mention the Author in the Credits as a thank you otherwise it is taken as plagiarism and may be subject to legal proceedings... A good greeting
## 👨🏽‍💻 Dev
 <br>
[SMARK](https://github.com/SMARK-MD/SMARK-MD) •All rigths reserved 2024•
