# egg_u_webant



## QuickStart

<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

```bash
$ git checkout -b dev master
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Merge

```bash
$ git checkout master
$ git merge --no-ff dev
```

### Release

在本地项目
```
$ npm run rel
# 等同于 git branch -d rel && git checkout -b rel master && npm run build
```

先在服务器上创建好对应的文件夹

```bash
$ mkdir /home/egg/egg_u_webant && cd /home/egg/egg_u_webant
```

在本地项目

```bash
$ git checkout -b rel master
$ npm run tt
```

### Deploy

在服务器

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org

