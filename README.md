<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WELCOME%20TO -PREM BABU MEDIA DOWNLOADER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&font-weight=bold&size=20&color=FFFF00&background=FF0000&center=true&vCenter=true&width=400&height=60&lines=HELLO+FRIENDS+I'M+MR+PREM+BABU+🙂+🤞;PREM+PROJECT+BOT;PREM+FACEBOOK;PREM+INSTAGRAM;PREM+YOUTUBE;PREM+IMGUR;PREM+IMGBB;PREM+PINTEREST;PREM+TIKTOK;PREM+CAPCUT;PREM+ALL+MEDIA;THANKYOU+FOR+USING+PREM+PROJECT&border=20px+solid+000000&speed=100)](https://git.io/typing-svg)


<div style="display: flex; justify-content: center; gap: 50000px;">
  <a href="https://www.facebook.com/prembabu66" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" style="width: 60px; height: 60px;">
  </a>
  <a href="https://www.instagram.com/prem_.status" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" style="width: 60px; height: 60px;">
  </a>
  <a href="https://www.youtube.com/@premfilm" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube" style="width: 60px; height: 60px;">
  </a>
  <a href="https://github.com/prem-project3608" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub" style="width: 60px; height: 60px;">
  </a>
</div>

![Image](https://i.imgur.com/rZxmABp.png)


## NPM INSTALL 
```bash
npm install prem-babu-media
```
## LATEST UPDATE 
```
• PREM FACEBOOK 
• PREM INSTAGRAM 
• PREM YOUTUBE 
```

## EXAMPLE ( FB & INSTA )
```js
const { ndown } = require("prem-babu-media")
let URL = await ndown("https://www.facebook.com/")
console.log(URL)
```

## Instagram Usage 
```js
const {instagram} = require("nayan-media-downloader");

const link = "https://www.instagram.com/p/DAxzjkAyWOm/?igsh=MTZ5eThrMXpteTFpOA==" //past video link

  instagram(link).then(data => {

    console.log(data)

});
```
## Example (TikTok)
```js
const { tikdown } = require("nayan-media-downloader")
let URL = await tikdown("https://vt.tiktok.com/ZSNvs6h6o/")
console.log(URL)
```
## Output Example (tikTok)
```
{
    "developer": "MOHAMMAD NAYAN",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "data": {
        "author": {
            "id": "7021670496278447110",
            "unique_id": "rowdy__baby_212",
            "nickname": "Rasel_official_97⚡",
            "avatar": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-avt-0068/d673e8357d05f3599741c7c974ec3e9a~c5_300x300.jpeg?lk3s=45126217&x-expires=1704636000&x-signature=z2SNWwaql50uUONx2NIzt8Pn8GY%3D"
        },
        "view": 59711,
        "comment": 628,
        "play": 345065,
        "share": 1728,
        "download": 7666,
        "duration": 19,
        "title": "Kokhono asuk💐🥹 #rowdy__baby212 ",
        "video": "https://v16m-default.akamaized.net/ad3c167bb8792b3693ecf372632b1ea2/6599b519/video/tos/alisg/tos-alisg-pve-0037c001/okyBYBAQ4wiBNE9UEPALXHEjZCIvGYWwL1iUb/?a=0&ch=0&cr=0&dr=0&lr=all&cd=0%7C0%7C0%7C0&cv=1&br=936&bt=468&bti=OUBzOTg7QGo6OjZAL3AjLTAzYCMxNDNg&cs=0&ds=6&ft=XE5bCqT0m7jPD12-NFzR3wUTV3yKMeF~O5&mime_type=video_mp4&qs=4&rc=ZzQzaDU3NWQzN2hlNmlkaUBpMzYzb3c5cnFncDMzODczNEAuLTI0L2A0XjUxYjVjL2A2YSNwYTNhMmRrYC5gLS1kMS1zcw%3D%3D&l=202401061416056062C3D543FE05F58BCB&btag=e00088000",
        "audio": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7314645119033936642.mp3"
    }
}
```
## Example (YouTube)
```js
const { ytdown } = require("nayan-media-downloader")
let URL = await ytdown("https://youtu.be/aRSuyrZFu_Q?si=bsfzgeeGmRpsHqnF")
console.log(URL)
```
## Example (Twitter)
```js
const { twitterdown } = require("nayan-media-downloader")
let URL = await twitterdown("https://twitter.com/TeamAbhiSha/status/1743351410761019794?t=vms8wxcU0mQuhVxwGCHjFw&s=19")
console.log(URL)
```
## Output Example (Twitter)
```
{
    "developer": "MOHAMMAD NAYAN",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "data": {
        "HD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/810x720/gKWI2KEyLdRMQBFa.mp4?tag=12",
        "SD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/404x360/dtDrE8AqyxXhoRhO.mp4?tag=12"
    }
}
```
## Example Fbdown 
```js
const { fbdown } = require("nayan-media-downloader");
const request = require('request')

const key = "Nayan" //dont change key

const cookie = "cookie" //past your fb cookie here

const link = "url" //past video link

fbdown(link, cookie, key).then(data => {
  console.log(data)
});
```
## Output Example (fbdown)
```
{
    "developer": "MOHAMMAD NAYAN",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "url": "https://www.facebook.com/saroj.dwivedi.7121/videos/691539259851175/?idorvanity=213813760197847",
    "thumbnail": "https://scontent.fkul8-4.fna.fbcdn.net/v/t15.5256-10/427275886_286050634275782_6523162309266122490_n.jpg?stp=dst-jpg_p960x960&_nc_cat=104&ccb=1-7&_nc_sid=dd673f&_nc_ohc=8gfhuR00MokAX9K7Xoa&_nc_ht=scontent.fkul8-4.fna&oh=00_AfA0TUr_aw2q146jhqW3Fs-Yd5z0C3O75Hthf7qdLbXKmg&oe=65DB995F",
    "status": true,
    "media": {
        "title": "The real master.\\ud83d\\ude06\\ud83d\\ude06",
        "hd": "https://video.fkul8-2.fna.fbcdn.net/o1/v/t2/f1/m69/GAflixlLP9JH0IMCAFfy-_verBcfbmdjAAAF.mp4?efg=eyJ2ZW5jb2RlX3RhZyI6Im9lcF9oZCJ9&_nc_ht=video.fkul8-2.fna.fbcdn.net&_nc_cat=108&strext=1&vs=2b8b34f9bdb1e75e&_nc_vs=HBksFQIYOnBhc3N0aHJvdWdoX2V2ZXJzdG9yZS9HQWZsaXhsTFA5SkgwSU1DQUZmeS1fdmVyQmNmYm1kakFBQUYVAALIAQAVAhg6cGFzc3Rocm91Z2hfZXZlcnN0b3JlL0dHWGZneG1QTTZMaXltTUJBSFh5aVVpaEdyRkxidjRHQUFBRhUCAsgBAEsHiBJwcm9ncmVzc2l2ZV9yZWNpcGUBMQ1zdWJzYW1wbGVfZnBzABB2bWFmX2VuYWJsZV9uc3ViACBtZWFzdXJlX29yaWdpbmFsX3Jlc29sdXRpb25fc3NpbQAoY29tcHV0ZV9zc2ltX29ubHlfYXRfb3JpZ2luYWxfcmVzb2x1dGlvbgAddXNlX2xhbmN6b3NfZm9yX3ZxbV91cHNjYWxpbmcAEWRpc2FibGVfcG9zdF9wdnFzABUAJQAcjBdAAAAAAAAAABERAAAAJoTxuc7t1sYBFQIoAkMzGAt2dHNfcHJldmlldxwXQDONDlYEGJMYIWRhc2hfZ2VuMmh3YmFzaWNfaHEyX2ZyYWdfMl92aWRlbxIAGBh2aWRlb3MudnRzLmNhbGxiYWNrLnByb2Q4ElZJREVPX1ZJRVdfUkVRVUVTVBsKiBVvZW1fdGFyZ2V0X2VuY29kZV90YWcGb2VwX2hkE29lbV9yZXF1ZXN0X3RpbWVfbXMBMAxvZW1fY2ZnX3J1bGUHdW5tdXRlZBNvZW1fcm9pX3JlYWNoX2NvdW50BzE4MDYyOTQRb2VtX2lzX2V4cGVyaW1lbnQADG9lbV92aWRlb19pZA82OTE1MzkyNTk4NTExNzUSb2VtX3ZpZGVvX2Fzc2V0X2lkDzI1MjE4MzU2NDU5ODgzNhVvZW1fdmlkZW9fcmVzb3VyY2VfaWQPNDM2ODk4Nzg1MzQ0NTc4HG9lbV9zb3VyY2VfdmlkZW9fZW5jb2RpbmdfaWQQMTg3MjY2MTQyNjUwNjYyNQ52dHNfcmVxdWVzdF9pZAAlAhwAJb4BGweIAXMEMzU4NQJjZAoyMDI0LTAyLTE3A3JjYgcxODA2MjAwA2FwcBRGYWNlYm9vayBmb3IgQW5kcm9pZAJjdApHUk9VUF9QT1NUE29yaWdpbmFsX2R1cmF0aW9uX3MGMTkuNTc1AnRzFXByb2dyZXNzaXZlX2VuY29kaW5ncwA%3D&ccb=9-4&oh=00_AfDc2eioFzHbbvrcmY0F65aiNa-wOEJkjs1zDxMJlvCgSw&oe=65D866B1&_nc_sid=1d576d&_nc_rid=485391820915246&_nc_store_type=1",
        "sd": "https://video.fkul8-1.fna.fbcdn.net/v/t42.1790-2/428523452_7328222917198762_1280577179298892870_n.mp4?_nc_cat=101&ccb=1-7&_nc_sid=55d0d3&efg=eyJybHIiOjQ1MywicmxhIjo1MTIsInZlbmNvZGVfdGFnIjoic3ZlX3NkIn0%3D&_nc_ohc=9ONnrxW_k8gAX-iSMM2&rl=453&vabr=252&_nc_ht=video.fkul8-1.fna&oh=00_AfBkjxUy6GrISzoJfBZEu2RwLa-CLwv5q2tc2Iyc2SjBPw&oe=65DC3B6C"
    },
    "audio": "https://video.fkul8-2.fna.fbcdn.net/v/t39.25447-2/428621206_935765774852656_1505609703629717781_n.mp4?_nc_cat=110&ccb=1-7&_nc_sid=9a5d50&efg=eyJ2ZW5jb2RlX3RhZyI6ImRhc2hfYXVkaW9fYWFjcF80OF9mbm9ybTE0X2ZyYWdfMl9hdWRpbyJ9&_nc_ohc=ZoKNtZHq6VUAX_r1QSE&_nc_ht=video.fkul8-2.fna&oh=00_AfAQ7FB2SUPfXGO-2yfIYWhQme4WTkD--g2mZ2anaVmS3A&oe=65DC7873"
}
 ```
## Example Fbdown2
```js
const { fbdown2 } = require("nayan-media-downloader");
const request = require('request')

const key = "Nayan" //dont change key

const link = "url" //past video link

fbdown2(link, key).then(data => {
  console.log(data)
});
```
## Output Example (fbdown2)
```
{
    "developer": "MOHAMMAD NAYAN",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "media": {
               title: video title,
                hd: Hd video link,
                sd: normal video link
              }
}
```

## Usage GDLink 
```js
const {GDLink} = require("nayan-media-downloader");

const url = 'url' // Public Google Drive Url

GDLink(url).then(data => {
  console.log(data)

});
```
## Usage Pintarest 
```js
const {pintarest} = require("nayan-media-downloader");

const url = 'url' // pintarest post url

  pintarest(url).then(data => {
  console.log(data)
    });
```
## Usage CapCut 
```js
const { capcut } = require("nayan-media-downloader");

const url = "link" // capcut link

capcut(url).then(data => {
  console.log(data)
});
```
## Usage Likee 
```js
const { likee} = require("nayan-media-downloader");

 const url = "link" // past url
likee(url).then(data => { 
  console.log(data) 
});
```
## Usage Threads
```js
const { threads } = require("nayan-media-downloader");

 const url = "link" // past url
threads(url).then(data => { 
  console.log(data) 
});
```
## Usage All Media Down
```bash
support url: facebook, tiktok, twitter, instagram, youtube, pinterest, gdrive, capcut, likee, threads
note: Let me know if any of the platforms you use are missing
```
```js
const {alldown} = require("nayan-media-downloader");
const url = 'url' // past url

  alldown(url).then(data => {
  console.log(data)
    });
```
## Output Example (alldown)
```
{
    "developer": "MOHAMMAD NAYAN",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "media": {
        "title": "video title",
        "low": "normal video link",
        "high": "hd video link"
    }
}
```

[![WhatsApp](https://img.shields.io/badge/WhatsApp-green?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801615298449)
[![Facebook](https://img.shields.io/badge/Facebook-green?style=for-the-badge&logo=facebook)](https://www.facebook.com/www.xnxx.com169)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/100000959749712)
[![Github](https://img.shields.io/badge/Github-MrDarkYTgreen?style=for-the-badge&logo=github)](https://github.com/MOHAMMAD-NAYAN)
