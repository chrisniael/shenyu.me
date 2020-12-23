# shenyu.me

[https://shenyu.me](https://shenyu.me)

我的博客，使用 [Jekyll](https://github.com/jekyll/jekyll) 生成，基于 [minima](https://github.com/jekyll/minima) 主题。

## 预览网站

确保已经安装 docker。

```bash
docker pull jekyll/jekyll:3.8.6
docker run \
  --volume="$PWD:/srv/jekyll" \
  -it -p 4000:4000 jekyll/jekyll:3.8.6 \
  jekyll serve --watch
```

然后浏览器打开 <http://127.0.0.1:4000>

## 生成静态网站

```bash
docker pull jekyll/jekyll:3.8.6
docker run \
  --volume="$PWD:/srv/jekyll" \
  -it -p 4000:4000 jekyll/jekyll:3.8.6 \
  jekyll build

```
