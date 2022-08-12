# Webp Converter API
##### Converting image to webp format, inspired by statically.io image api by Frans Allen

- Build on the top of [Sharp(js)](https://github.com/lovell/sharp) for the image proccessing
- *this codebase is intended to be hosted on netlify*

### Endpoint
#### *Only Converting Image*
> yourdomain.com/api/imageconv/:outputname?url=:url

#### *Resizing and Converting Image*
> yourdomain.com/api/imageconv/:outputname?width=:width&heigth=:height&url=:url
#### Height
> yourdomain.com/api/imageconv/:outputname?heigth=:height&url=:url
#### Width
> yourdomain.com/api/imageconv/:outputname?width=:width&url=:url

#### *Example* : [Click this](https://webp.projectxi.my.id/api/imageconv/pepe?width=123&height=123&url=https://raw.githubusercontent.com/aryarkusuma/aryarkusuma/main/png-clipart-pepe-the-frog-smiling-illustration-pepe-the-frog-video-game-warframe-meme-pepe-the-frog-sticker-game-food-thumbnail-removebg-preview%20(1).png)

### Future milestones
- Adding input image metadata API 

***soon gonna push the code***
