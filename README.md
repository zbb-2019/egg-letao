
# egg-letao

乐淘项目

## QuickStart

<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Deploy

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org

#### egg-letao
### 首次推送github步骤
- 添加远程仓库
- 强制合并拉去远程代码
- 推送本地代码
- git remote add letao(you project) https://github.com/zbb-2019/egg-letao.git
- git pull letao master --allow-unrelated-histories
- git push letao master
