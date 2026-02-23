# 🌑 Stealth Gray - Hyprland Dotfiles

Este repositório contém os meus arquivos de configuração para um setup focado em produtividade e estética minimalista ("Stealth Gray"). 

## 🛠️ Componentes do Sistema
* **Compositor:** [Hyprland](https://hyprland.org/)
* **Barra:** [Waybar](https://github.com/Alexays/Waybar)
* **Launcher:** [Wofi](https://hg.sr.ht/~scoopta/wofi)
* **Widgets:** [Eww](https://github.com/elkowar/eww) (Control Center)

## ⌨️ Atalhos Principais (Configuração Padrão)
`Super + Q` -> Abrir Terminal (Kitty)

`Super + R` -> Abrir Launcher (Wofi)

`Super + C` -> Fechar Janela

`Super + M` -> Sair do Hyprland

## 📦 Instalação

Se estiver no Arch Linux, pode instalar todas as dependências principais com o comando abaixo:

```bash
sudo pacman -S hyprland waybar wofi kitty network-manager-applet pavucontrol pamixer ttf-jetbrains-mono-nerd
```

Nota: Para o Eww e a fonte Lexend, recomenda-se o uso de um auxiliar do AUR (como o yay):
```bash
yay -S eww-wayland ttf-lexend
```

[!NOTE]
Este projeto foi desenvolvido com uma forte colaboração de IA e refinado através de modificações humanas para garantir precisão técnica e o melhor ajuste visual.
