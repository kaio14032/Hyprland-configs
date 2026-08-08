# Hyprland Configs

Minhas configurações pessoais do "Hyprland" (https://hyprland.org).

## Dependências

| Programa | Uso |
| --- | --- |
| "Hyprland" (https://hyprland.org) | Window manager |
| "Waybar" (https://github.com/Alexays/Waybar) | Barra de status |
| "Hyprlauncher" | Menu de aplicativos |
| "Kitty" (https://sw.kovidgoyal.net/kitty) | Terminal |
| "Hyprpaper" (https://github.com/hyprwm/hyprpaper) | Wallpaper |
| "Hyprlock" | Tela de bloqueio |
| "Grimblast" | Screenshots |

## Estrutura

```
├── hypr/        hyprland.conf, hyprpaper.conf
├── waybar/      config, style.css, mocha.css
├── kitty/       kitty.conf, current-theme.conf
└── fastfetch/   config.jsonc
```

## Atalhos

| Tecla | Ação |
| --- | --- |
| $mod + Q | Abrir terminal (kitty) |
| $mod + C | Fechar janela |
| $mod + E | Abrir ranger |
| $mod + R/T | Abrir menu (hyprlauncher) |
| $mod + V | Alternar floating |
| $mod + F | Tela cheia |
| $mod + W | Abrir navegador (qutebrowser) |
| $mod + L | Bloquear tela (hyprlock) |
| $mod + P | Screenshot da área |
| $mod + Print | Screenshot da tela |
| $mod + setas | Navegar entre janelas |
| $mod + 1-0 | Alternar workspace |
| $mod + Shift + 1-0 | Mover janela para workspace |

«$mod = SUPER (tecla Windows)»

## Instalação

```
git clone https://github.com/kaio14032/Hyprland-configs.git
cd Hyprland-configs
cp -r config/* ~/.config/
```

Ou copie apenas o que precisar.
