
# 提交 PR 的极简流程（基于 dev 分支）

> 已开启分支保护：不能直接合并到上游 `dev`，请按以下步骤提 PR，由维护者合并。


## 1) Fork 后，从自己的 Fork Clone 并切换到 dev
```bash
# 先在 GitHub 页面点击 Fork 到你自己的账号

# 然后从“你的 Fork仓库”克隆（将 <your-name> 替换为你的 GitHub 用户名）
git clone https://github.com/<your-name>/Awesome-RL-for-Diffusion-Models.git
cd Awesome-RL-for-Diffusion-Models
git checkout dev

# 添加上游仓库（只需执行一次）
git remote add upstream https://github.com/lyongo/Awesome-RL-for-Diffusion-Models/
```

---

## 2) 修改并提交
```bash
git add -A
git commit -m "feat: <your change>"
```

---

## 3) 提交前同步最新代码
```bash
git fetch upstream
git merge upstream/dev   # 或者 git rebase upstream/dev

# 若有冲突，按提示解决：
# 1. 编辑冲突文件
# 2. git add <resolved-files>
# 3. git commit
```

---

## 4) 推送并发起 PR
```bash
git push -u origin dev
```

到 GitHub 打开 PR：

* base：上游仓库 `dev`
* compare：你的 Fork `dev`

即可等待维护者审核与合并。

