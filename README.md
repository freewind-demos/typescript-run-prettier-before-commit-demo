# TypeScript Run Prettier Before Commit Demo

使用<https://prettier.io/>推荐的 husky 来在 package.json 中设置`pre-commit`命令。

我们可以利用该功能自动运行 prettier 修正代码样式。

```
npm install
```

修改`hello.ts`内容，故意把样式弄乱，然后正常`git commit`，可看到效果。
