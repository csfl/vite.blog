# vite.blog

> Official blog for Vite Labs

## Start

clone project and clone submodule

```
git clone https://github.com/vitelabs/vite.blog.git --recursive
```

Install hexo

```
npm install hexo-cli -g
```

Add new draft 

```
hexo new draft hello-world --lang zh-CN
```

Publish a draft named "hello-word" (in Chinese)

```
hexo publish post hello-world --lang zh-CN
```

Publish a draft named "hello-word" (in English)

```
hexo publish post hello-world --lang en
```

Add new post

```
hexo new post hello-world --lang zh-CN
```

## FAQ

### How to upload image?

```
npm i
npm run dev
```

Visit `localhost:4000/admin`. In the admin page, you can paste your image to editor.

![](https://cdn.discordapp.com/attachments/425845491478298624/479212487728693248/unknown.png)

Please make sure the image filename is unique.
![](https://cdn.discordapp.com/attachments/425845491478298624/481333553032855562/unknown.png)

But you should only use `localhost:4000/admin` as a editor. If you want to create post, Please use cli. 
