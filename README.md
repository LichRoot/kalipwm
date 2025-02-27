# KaliPWM

Implante um ambiente de hacking profissional para Kali Linux executando apenas um script.

![kalipwm-1](https://github.com/user-attachments/assets/0e11571f-7c71-416f-9bb8-32ab9c47d015)
![kalipwm-2](https://github.com/user-attachments/assets/b67853d2-922d-4303-90a8-4fbc2564555a)

## Instalação e Uso

- Recomenda-se o uso de uma instalação nova/limpa do Kali Linux.
- Testado no Kali Linux 2024.4 com VMware, VirtualBox e Bare Metal.

```
git clone https://github.com/afsh4ck/kalipwm.git
cd kalipwm
bash kalipwm.sh
sudo reboot
```
- Após reiniciar, selecione bspwm na tela de login.
- O papel de parede é carregado de ~/Wallpapers/wallpaper.*
- Vídeo completo do ambiente: https://youtu.be/3clLjO8W7Q4?si=GupOi6Bqwuu2O9Wk

## Comandos

> [!NOTA]
> No MacOS, substitua Windows por Command e Alt por Option.

| Comando                     | Descrição                                                   |
|-----------------------------|-------------------------------------------------------------|
| Clique direito na Polybar   | Altera o tema da Polybar usando o menu do clique direito   |
| Windows + 1,2,3,4           | Navega entre os desktops                                   |
| Windows + Enter             | Abre um novo terminal                                      |
| Windows + Enter             | Divide o terminal atual                                   |
| Windows + Setas             | Navega entre janelas abertas                              |
| Windows + Tab               | Alterna entre os dois desktops mais recentes              |
| Windows + Shift + W         | Fecha o terminal atual                                   |
| Windows + Alt + R           | Recarrega o ambiente de desktop                          |
| Windows + Alt + Q           | Reinicia o BSPWM                                         |
| Windows + Alt + Setas       | Redimensiona a janela atual                              |
| Windows + Shift + F         | Abre o Firefox                                          |
| Windows + Shift + B         | Abre o Burp Suite                                       |
| Windows + Shift + A         | Abre o gerenciador de arquivos Thunar                   |
| Windows + Shift + 1,2,3,4   | Move a janela atual para outro desktop                   |
| Windows + Shift + Setas     | Move a janela atual                                     |
| Ctrl + Shift + -+           | Ajusta o tamanho do texto no terminal                   |
| Ctrl + T                    | Abre um buscador avançado no terminal                    |
| .config/sxhkd/sxhkdrc       | Arquivo de configuração de atalhos (sxhkd)               |
| .config/bspwm/bspwmrc       | Arquivo de configuração do BSPWM                         |
| .config/polybar             | Pasta com temas da Polybar                              |
| .config/kitty/kitty.conf    | Arquivo de configuração padrão do terminal Kitty         |
| ~/Wallpapers                | Pasta de papéis de parede. Apenas um arquivo chamado wallpaper.jpg é permitido |
| target 10.0.0.1             | Define um IP de destino que é exibido na Polybar         |
| target reset                | Remove o alvo definido                                   |
| tmux                        | Alterna o terminal para tmux                            |
| tmux —help                  | Exibe a ajuda do tmux                                   |
| p10k configure              | Configura o tema do terminal Powerlevel10K              |
| .zshrc                      | Arquivo de configuração do ZSH e aliases de comandos    |
| bpython                     | Python interativo no terminal                           |

## Pacotes incluídos:

```
Bspwm
Polybar
Oh my zsh + Plugins
Powerlevel10k
Hack Nerd Fonts
JetBrains Font
Python + pip + bpython
Tmux + Oh my tmux
Kitty
lsd
Batcat
Fastfetch
Scrot
feh
Rofi
Sxhkd
Picom
Neovim
```

## Créditos
- Autor:       afsh4ck 
- Instagram:   <a href="https://www.instagram.com/afsh4ck">afsh4ck</a>
- Youtube:     <a href="https://youtube.com/@afsh4ck">afsh4ck</a>
- Tdc PT/BR :  lichroot

## Suporte

<a href="https://www.buymeacoffee.com/afsh4ck" rel="nofollow"><img width="250" align="left">
![buy-me-a-coffee](https://github.com/user-attachments/assets/8c8f9e81-334e-469e-b25e-29888cfc9fcc)
</a>
