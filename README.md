
### 项目说明
- OpenWrt 常用插件包源码合集，适用于 [Lean](https://github.com/coolsnowwolf/lede) 源码

- 除lean源码、kenzok8额外的插件


- 所有插件都为 GITHUB 上收集的开源插件，感谢作者们的付出

### 使用方法（以下二选一）
1. 添加到 feeds.conf.default 文件
```yml
sed -i '1i src-git whiskyrye https://github.com/whiskyrye/zdpackages' feeds.conf.default
./scripts/feeds update -a
./scripts/feeds install -a
make menuconfig
```
2. 在源码目录内直接拉取
```yml
git clone https://github.com/whiskyrye/zdpackages package/zdpackages
make menuconfig
```
