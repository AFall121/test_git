1.master分支：代码是稳定的，平时是不能在上面干活的，仅仅是用来发布新版本用
2.dev分支：是不稳定的，bug、feature可以创建新的分支进行开发，最后再合并到master即可


git tag vx.x 历史版本xxxxx //创建
git tag // 查看
git push origin --tags // 一次推送所有标签