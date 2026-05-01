**第一步：**在进行更新操作后，打开该文件夹的终端

**第二步：**更新GitHub

1. `git status`
   - 查看更新内容
2. `git add .`
   - 加入更新内容
3. `git commit -m "输入更新批注"`
4. `git pull origin main`
   - 如果需要进行线上同步

5. `git push origin main`
   - 上传更新内容

**第三步：**同步Vercel

https://vercel.com/lou-uos-projects

点击 `Deployments` → 选择更新项目 → 找到最新更新的右边的 `…` → 再点击 `Promote`



**更新时注意：**

打开终端，输入

```cmd
pnpm install astro
pnpm dev
```

实现热更新
