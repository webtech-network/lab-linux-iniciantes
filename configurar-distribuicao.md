# Configurar distribuição

## Personalizar o Gnome Shell

O ambiente de trabalho Gnome Shell pode ser customizado.

### Alterar ícones e estilos visuais

É possível alterar os ícones de programas e estilos de janelas no Gnome Shell. Para isso, é necessário instalar o GNOME Tweak Tool.

Para instalar o Gnome Tweak Tool, no terminal, digite o seguinte comando:

```
sudo apt install gnome-tweak-tool
```

Após ter instalado o Gnome Tweak Tool, na barra de pesquisa do Gnome (aberta pela tecla 'Super' ('Símbolo do Windows') no teclado), busque por 'Ajustes' (se a sua distro estiver em português) ou 'Tweaks' (se a sua distro estiver em inglês).

**Cuidado: Um [bug conhecido](https://askubuntu.com/questions/1513701/gnome-tweak-tool-crashes-ubuntu-24-04lts-with-gnome-v46) do Gnome Tweak Tool é que ele pode crashar o sistema. Use-o por sua conta e risco.**

### Instalação de extensões

É possível instalar extensões no Gnome Shell. As extensões permitem mudar o comportamento padrão do Gnome Shell.

Para instalar extensões, acesse: https://extensions.gnome.org

**Cuidado: As extensões do Gnome Shell são mantidas e desenvolvidas pela comunidade. Elas podem ser infectadas ou conterem malware (vírus). Use por sua conta e risco.**

#### Exemplos de extensões

[Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/)

[Bing Wallpaper](https://extensions.gnome.org/extension/1262/bing-wallpaper-changer/)

## Ativar atualizações automáticas em 2º plano

É possível ativar atualizações automáticas software em 2º plano, de modo que quem estiver utilizando o computador não vai perceber que o sistema e os programas estão sendo atualizados.

Para isso, basta instalar o pacote ```unattended-upgrades```, por meio do gerenciador de pacotes APT:

```
sudo apt install unattended-upgrades
```