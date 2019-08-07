TypeScript Run Prettier Before Commit Demo
==========================================

可以使用 git-commit 这个npm包，在`package.json`中的`pre-commit`处设置命令，它将在运行git commit时，自动执行。

我们可以利用该功能自动运行prettier修正代码样式。

```
npm install
```

修改`hello.ts`内容，故意把样式弄乱，然后正常`git commit`，可看到效果。
