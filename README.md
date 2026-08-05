Hyprland Configs

Minhas configurações pessoais do "Hyprland" (https://hyprland.org).

Dependências

Programa| Uso
"Hyprland" (https://hyprland.org)| Window manager
"Waybar" (https://github.com/Alexays/Waybar)| Barra de status
"Wofi" (https://hg.sr.ht/~scoopta/wofi)| Menu de aplicativos
"Kitty" (https://sw.kovidgoyal.net/kitty)| Terminal
"Hyprpaper" (https://github.com/hyprwm/hyprpaper)| Wallpaper

Estrutura

├── hypr/        hyprland.conf, hyprpaper.conf
├── waybar/      config, style.css
├── wofi/        config, style.css
└── kitty/       kitty.conf

Atalhos

Tecla| Ação
$mod + Q| Abrir terminal (kitty)
$mod + C| Fechar janela
$mod + E| Abrir gerenciador de arquivos (dolphin)
$mod + R/T| Abrir menu (wofi)
$mod + V| Alternar floating
$mod + F| Tela cheia
$mod + setas| Navegar entre janelas
$mod + 1-0| Alternar workspace
$mod + Shift + 1-0| Mover janela para workspace

«$mod = SUPER (tecla Windows)»

Instalação

git clone https://github.com/kaio14032/Hyprland-configs.git
cd Hyprland-configs
cp -r * ~/.config/

Ou copie apenas o que precisar.