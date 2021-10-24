

## git subtree 步骤
* 在父仓库中操作
* git subtree add --prefix=sub/slave https://github.com/wenling-lichao/gitTreeSlave.git --squash

(--squash参数表示不拉取历史信息，而只生成一条commit信息。)