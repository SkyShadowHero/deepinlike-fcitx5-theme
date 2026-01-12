# 自用fcitx5输入法皮肤
风格模仿deepin，半透明背景加浅蓝色候选背景  
Fork from[Ori-fcitx5](https://github.com/Reverier-Xu/Ori-fcitx5)
## 预览
![预览](views/image.png)

## 快速安装
```bash
sudo mkdir -p /usr/share/fcitx5/themes/SkyShadow/
git clone https://github.com/SkyShadowHero/skyshadow-fcitx5-theme.git
cd skyshadow-fcitx5-theme
sudo cp -r $(ls -A | grep -Ev '^(\.git|views|README\.md)$') /usr/share/fcitx5/themes/SkyShadow/ 2>/dev/null && echo "Done"
```

# 声明
本项目基于遵循 Mozilla Public License 2.0 的 [Ori-fcitx5](https://github.com/Reverier-Xu/Ori-fcitx5) 修改，并同样依此协议发布。