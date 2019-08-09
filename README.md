<h1 align="center"><a href="https://github.com/fancyapps/fancybox">fancyBox 3</a> for <a href="https://github.com/theme-next">NexT</a></h1>

<h2 align="center">If you want fancybox v2, please go to <a href="https://github.com/theme-next/theme-next-fancybox">theme-next-fancybox</a></h2>

<h1 align="center">Installation</h1>

<h2 align="center">Step 0 &rarr; Delete fancybox 2 (if you want to upgrade from v2)</h2>

```bash
$ rm -rf themes/next/source/lib/fancybox
```

<h2>If you want to use the CDN instead of clone this repo, please jump to the Step 3.</h2>

<h2 align="center">Step 1 &rarr; Go to NexT dir</h2>

Change dir to **NexT** directory. There must be `layout`, `source`, `languages` and other directories:

```sh
$ cd themes/next
$ ls
bower.json  _config.yml  docs  gulpfile.coffee  languages  layout  LICENSE.md  package.json  README.md  scripts  source  test
```

<h2 align="center">Step 2 &rarr; Get module</h2>

Install module to `source/lib` directory:

```sh
$ git clone https://github.com/theme-next/theme-next-fancybox3 source/lib/fancybox
```

<h2 align="center">Step 3 &rarr; Set it up</h2>

Enable module in **NexT** `_config.yml` file:

```yml
fancybox: true
```

**And, if you wants to use the CDN, then need to set:**

```yml
vendors:
  ...
  fancybox: //cdn.jsdelivr.net/gh/fancyapps/fancybox@3/dist/jquery.fancybox.min.js
  fancybox_css: //cdn.jsdelivr.net/gh/fancyapps/fancybox@3/dist/jquery.fancybox.min.css
```

<h1 align="center">Update</h1>

```sh
$ cd themes/next/source/lib/fancybox
$ git pull
```
