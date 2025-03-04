<p align="center">
  <img width="200" height="200" src="https://telegra.ph/file/e77b79d6b544603222cfa.jpg">
</p>

## Installation

```bash
$ npm install canvas-fatih
```

<p align="center">
    <a href="https://github.com/FatihArridho">
        <img
            src="https://readme-typing-svg.herokuapp.com?size=15&width=280&lines=thank+you+for+using+this+module"
            alt="FatihArridho"
        />
    </a>
</p>

## How To Use?
<details><summary><b>Example Welcome V1</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Welcome()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setGuildName("CpdXSeven")
    .setGuildIcon("https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setMemberCount("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/welcome-v1.png', data)
 
```
### Result Welcome V1
<img src="https://api.fatiharridho.my.id/api/canvas/welcome/v1?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&namagc=CpdXSeven&ppgc=https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&member=404" height="145"></img>

</details>

<details><summary><b>Example Welcome V2</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Welcome2()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setBg("https://img.freepik.com/free-vector/perspective-japanese-street-neon-lights_52683-44988.jpg")
    .setGroupname("CpdXSeven")
    .setMember("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/welcome-v2.png', data)
 
```
### Result Welcome V2
<img src="https://api.fatiharridho.my.id/api/canvas/welcome/v2?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&bg=https://img.freepik.com/free-vector/perspective-japanese-street-neon-lights_52683-44988.jpg&namagc=CpdXSeven&member=404" height="145"></img>
</details>

<details><summary><b>Example Welcome V3</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Welcome3()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/welcome-v3.png', data)
 
```
### Result Welcome V3
<img src="https://api.fatiharridho.my.id/api/canvas/welcome/v3?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho" height="145"></img>
</details>

<details><summary><b>Example Goodbye V1</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Goodbye()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setGuildName("CpdXSeven")
    .setGuildIcon("https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setMemberCount("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/goodbye-v1.png', data)
 
```
### Result Goodbye V1
<img src="https://api.fatiharridho.my.id/api/canvas/goodbye/v1?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&namagc=CpdXSeven&ppgc=https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&member=404" height="145"></img>
</details>

<details><summary><b>Example Goodbye V2</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Goodbye2()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setBg("https://img.freepik.com/free-vector/perspective-japanese-street-neon-lights_52683-44988.jpg")
    .setGroupname("CpdXSeven")
    .setMember("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/goodbye-v2.png', data)
 
```
### Result Goodbye V2
<img src="https://api.fatiharridho.my.id/api/canvas/goodbye/v2?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&bg=https://img.freepik.com/free-vector/perspective-japanese-street-neon-lights_52683-44988.jpg&namagc=CpdXSeven&member=404" height="145"></img>
</details>

<details><summary><b>Example Goodbye V3</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Goodbye3()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/goodbye-v3.png', data)
 
```
### Result Goodbye V3
<img src="https://api.fatiharridho.my.id/api/canvas/goodbye/v3?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho" height="145"></img>
</details>

<details><summary><b>Example Promote</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Promote()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setGuildName("CpdXSeven")
    .setGuildIcon("https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setMemberCount("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/promote.png', data)
 
```
### Result Promote
<img src="https://api.fatiharridho.my.id/api/canvas/promote?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&namagc=CpdXSeven&ppgc=https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&member=404" height="145"></img>
</details>

<details><summary><b>Example Demote</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Demote()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setGuildName("CpdXSeven")
    .setGuildIcon("https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setMemberCount("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/demote.png', data)
 
```
### Result Demote
<img src="https://api.fatiharridho.my.id/api/canvas/demote?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&namagc=CpdXSeven&ppgc=https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&member=404" height="145"></img>
</details>

<details><summary><b>Example Verification</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Verification()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setGuildName("CpdXSeven")
    .setGuildIcon("https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setMemberCount("404")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/verification.png', data)
 
```
### Result Verification
<img src="https://api.fatiharridho.my.id/api/canvas/verification?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&namagc=CpdXSeven&ppgc=https://cdn.dribbble.com/users/1051393/screenshots/7011829/media/f19892ea228d4dfafd5a0abf273f6b3c.png&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&member=404" height="145"></img>
</details>

<details><summary><b>Example Signup</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Signup()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setName("Fatih Arridho")
    .setBackground("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setEmail("admin@fth.my.id")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/signup.png', data)
 
```
### Result Signup
<img src="https://api.fatiharridho.my.id/api/canvas/signup?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&email=admin@fth.my.id" height="145"></img>
</details>

<details><summary><b>Example Hacker V1</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Hacker1()
    .setName("Fatih Arridho")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/hacker-v1.png', data)
 
```
### Result Hacker V1
<img src="https://api.fatiharridho.my.id/api/canvas/hacker/v1?nama=Fatih%20Arridho" height="145"></img>
</details>

<details><summary><b>Example Hacker V2</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Hacker2()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/hacker-v2.png', data)
 
```
### Result Hacker V2
<img src="https://api.fatiharridho.my.id/api/canvas/hacker/v2?bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Hacker V3</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Hacker3()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/hacker-v3.png', data)
 
```
### Result Hacker V3
<img src="https://api.fatiharridho.my.id/api/canvas/hacker/v3?bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Rank</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Rank()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setBg("https://telegra.ph/file/3f4993d39b9994c54da94.jpg")
    .setNeedexp("5000")
    .setCurrxp("6000")
    .setLevel("9")
    .setRank("https://i.pinimg.com/originals/b2/fc/1d/b2fc1da4a7c50bcc2f48fc75b54c1fee.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/rank.png', data)
 
```
### Result Rank
<img src="https://api.fatiharridho.my.id/api/canvas/rank?pp=https://api.fatiharridho.my.id/images/logo.png&nama=Fatih%20Arridho&bg=https://telegra.ph/file/3f4993d39b9994c54da94.jpg&needxp=5000&currxp=6000&level=9&logorank=https://i.pinimg.com/originals/b2/fc/1d/b2fc1da4a7c50bcc2f48fc75b54c1fee.png" height="145"></img>
</details>

<details><summary><b>Example Level Up</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Up()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/up.png', data)
 
```
### Result Level Up
<img src="https://api.fatiharridho.my.id/api/canvas/levelup?pp=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Gfx V1</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Gfx1()
    .setName("Fatih")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/gfx-v1png', data)
 
```
### Result Gfx V1
<img src="https://api.fatiharridho.my.id/api/canvas/gfx1?text=Fatih" height="145"></img>
</details>

<details><summary><b>Example Gfx V2</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Gfx1()
    .setName("Fatih")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/gfx-v2.png', data)
 
```
### Result Gfx V2
<img src="https://api.fatiharridho.my.id/api/canvas/gfx2?text=Fatih" height="145"></img>
</details>

<details><summary><b>Example Gfx V3</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Gfx3()
    .setText1("Fatih")
    .setText2("Idhoo")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/gfx-v3.png', data)
 
```
### Result Gfx V3
<img src="https://api.fatiharridho.my.id/api/canvas/gfx3?text1=Fatih&text2=Idhoo" height="145"></img>
</details>

<details><summary><b>Example Gfx V4</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Gfx4()
    .setText1("Fatih")
    .setText2("Idhoo")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/gfx-v4.png', data)
 
```
### Result Gfx V4
<img src="https://api.fatiharridho.my.id/api/canvas/gfx4?text1=Fatih&text2=Idhoo" height="145"></img>
</details>

<details><summary><b>Example Gfx V5</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Gfx5()
    .setName("Fatih")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/gfx-v5.png', data)
 
```
### Result Gfx V5
<img src="https://api.fatiharridho.my.id/api/canvas/gfx5?text=Fatih" height="145"></img>
</details>

<details><summary><b>Example Custom Gfx V1</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.customGfx()
    .setText("Fatih")
    .setBg("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/customGfx-v1.png', data)
 
```
### Result Custom Gfx V1
<img src="https://api.fatiharridho.my.id/api/canvas/customgfx1?text=Fatih&bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Custom Gfx V2</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.customGfx2()
    .setText1("Fatih")
    .setText2("Idhoo")
    .setBg("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/customGfx-v2.png', data)
 
```
### Result Custom Gfx V2
<img src="https://api.fatiharridho.my.id/api/canvas/customgfx2?text1=Fatih&text2=Idhoo&bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Gura</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.customGfx2()
    .setName("Fatih")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/customGfx-v2.png', data)
 
```
### Result Gura
<img src="https://api.fatiharridho.my.id/api/canvas/gura?text=Fatih" height="145"></img>
</details>

<details><summary><b>Example Spongebob Burn</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Burn()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/burn.png', data)
 
```
### Result Spongebob Burn
<img src="https://api.fatiharridho.my.id/api/canvas/spongebob?bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Patrick</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Patrick()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/patrick.png', data)
 
```
### Result Patrick
<img src="https://api.fatiharridho.my.id/api/canvas/patrick?bg=https://api.fatiharridho.my.id/images/logo.png" height="145"></img>
</details>

<details><summary><b>Example Instagram Profile</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Ig()
    .setAvatar("https://api.fatiharridho.my.id/images/logo.png")
    .setUsername("Fatih Arridho")
    .setPost("19")
    .setFollowers("10000")
    .setFollowing("230")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/instagram-profile.png', data)
 
```
### Result Instagram Profile
<img src="https://api.fatiharridho.my.id/api/canvas/instagram?pp=https://api.fatiharridho.my.id/images/logo.png&username=Fatih%20Arridho&post=19&followers=10000&following=230" height="145"></img>
</details>

<details><summary><b>Example Xnxx</b></summary><br>

```js
const cf = require("canvas-fatih");
const fs = require('fs');

const image = await new cf.Xnxx()
    .setImage("https://api.fatiharridho.my.id/images/logo.png")
    .setTitle("Fatih Arridho")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/xnxx.png', data)
 
```
### Result Xnxx
<img src="https://api.fatiharridho.my.id/api/canvas/xnxx?pp=https://api.fatiharridho.my.id/images/logo.png&username=Fatih%20Arridho" height="145"></img>
</details>

---

<div align="center">
  <h2>⭐ Thanks To</h2>

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/squad-404"><img src="https://github.com/squad-404.png" width="100px;" alt="Squad 404"/><br /><sub><b>Squad 404</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/hardianto-cpu"><img src="https://github.com/hardianto-cpu.png" width="100px;" alt="Hardianto"/><br /><sub><b>Hardianto CPU</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/FatihArridho"><img src="https://github.com/FatihArridho.png" width="100px;" alt="Fatih Arridho"/><br /><sub><b>Fatih Arridho</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>
</div>
