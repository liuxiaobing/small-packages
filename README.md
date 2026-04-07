#### 使用
一键命令
```yaml
sed -i '1i src-git smallpackages https://github.com/liuxiaobing/small-packages' feeds.conf.default
git pull
./scripts/feeds update -a
./scripts/feeds install -a
make menuconfig
```
