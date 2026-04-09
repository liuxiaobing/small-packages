#### 使用
一键命令
```yaml
sed -i '1i src-git lenzo https://github.com/liuxiaobing/small-packages.git' feeds.conf.default
git pull
./scripts/feeds update -a
./scripts/feeds install -a
make menuconfig
```
