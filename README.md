# Font Installation
```bash
mkdir -pv ~/.local/share/fonts/{Cantarell,Comfortaa,IcoMoon-Custom,Nerd-Patched,Unifont}
```

---

```bash
wget --no-hsts -cNP ~/.local/share/fonts/Comfortaa/ https://raw.githubusercontent.com/googlefonts/comfortaa/main/fonts/OTF/Comfortaa-{Bold,Regular}.otf
```

```bash
wget --no-hsts -cNP ~/.local/share/fonts/IcoMoon-Custom/ https://github.com/owl4ce/dotfiles/releases/download/ng/{Feather,Material}.ttf
```

```bash
wget --no-hsts -cNP ~/.local/share/fonts/Nerd-Patched/ https://github.com/owl4ce/dotfiles/releases/download/ng/M+.1mn.Nerd.Font.Complete.ttf
```

```bash
wget --no-hsts -cNP ~/.local/share/fonts/Nerd-Patched/ https://github.com/owl4ce/dotfiles/releases/download/ng/{M+.1mn,Iosevka}.Nerd.Font.Complete.Mono.ttf
```

```bash
wget --no-hsts -cNP ~/.local/share/fonts/Unifont/ https://unifoundry.com/pub/unifont/unifont-14.0.02/font-builds/unifont-14.0.02.ttf
```

```bash
wget --no-hsts -cN https://download-fallback.gnome.org/sources/cantarell-fonts/0.303/cantarell-fonts-0.303.1.tar.xz
```

---

```bash
tar -xvf cantarell*.tar.xz --strip-components 2 --wildcards -C ~/.local/share/fonts/Cantarell/ \*/\*/Cantarell-VF.otf
```
