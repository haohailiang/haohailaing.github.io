# 用到的精命令
1. 添加SUMMARY.md文件
2. 安装gitbook

```
npm i gitbook-cli -g
```
3. 初始化gitbook生成文件[会自动生成文件]
```
gitbook init
gitbook build
```
4. 打Tag提交文件
```
git tag -a 'v0.0.1' -m 'first commit'
git push origin v0.0.1
```