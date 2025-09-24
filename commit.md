# 提交 PR 的极简流程（基于 dev 分支）

> 已开启分支保护：不能直接合并到上游 `dev`，请按以下步骤提 PR，由维护者合并。

---

## 1) Clone 并切换到 dev
```bash
git clone https://github.com/lyongo/Awesome-RL-for-Diffusion-Models  # 你的 Fork
cd Awesome-RL-for-Diffusion-Models
git checkout dev
```

## 2) 修改并提交
```bash
git add -A
git commit -m "feat: <your change>"
```

## 3) 提交前同步最新代码
```bash
git pull   # 与远端 dev 同步，若有冲突按提示解决
# 解决冲突后：
git add <resolved-files>
git commit
```

## 4) 推送并发起 PR
```bash
git push -u origin dev
```
即可等待维护者审核与合并。
