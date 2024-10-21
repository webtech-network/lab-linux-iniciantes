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

##### [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/)

<img src="https://extensions.gnome.org/extension-data/screenshots/screenshot_307_90H8hVD.jpg" width="800px" alt="Captura de tela do Gnome Shell com a extensão Dash to Dock. No canto superior contém uma barra com os botões 'Atividades' no canto esquerdo, 'Data e Hora (24 Oct 21:37)' no meio e 'Conexões de Rede, Som e Energia' no canto direito. E no canto superior contém um Dock com os seguintes programas: 'Firefox', 'Calendário', 'Terminal', 'Arquivos', 'Loja de aplicativos' e 'Todos os programas'. 'Todos os programas' está exibindo um menu de contexto com 'Dash to Dock Settings'.">

Legenda: Captura de tela do Gnome Shell com a extensão Dash to Dock.

##### [Bing Wallpaper](https://extensions.gnome.org/extension/1262/bing-wallpaper-changer/)

<img src="https://extensions.gnome.org/extension-data/screenshots/screenshot_1262_0my2B7h.jpg" width="800px" alt="Captura de tela do Gnome Shell com a extensão Bing Wallpaper. No canto superior contém uma barra com os botões 'Atividades' no canto esquerdo, 'Data e Hora (Sep 29 4:54PM)' no meio, 'Bing Wallpaper' (separado), 'Conexões de Rede, Som e Energia' no canto direito. O 'Bing Wallpaper' foi pressionado, e está mostrando um menu com os seguinte botões: 'Simbolo coração', seguido por 'Simbolo lixeira', seguido por 'Seta de voltar', seguido por 'Seta de avançar', seguido por 'Seta de avançar', seguido por 'Símbolo de um dado'. Em baixo contém um botão com as informações da imagem. Em baixo contém um submenu 'Quick settings', com os seguintes toggle switches: 'Always show new images' (ativado), 'Images shuffle mode' (ativado), 'Image shuffle only favourites' (desativado), 'Image shuffle only UHD resolutions' (desativado). Em baixo contém o botão 'Settings'.">

Legenda: Captura de tela do Gnome Shell com a extensão Bing Wallpaper.

##### [Hibernate Status Button](https://extensions.gnome.org/extension/755/hibernate-status-button/)

<img src="https://extensions.gnome.org/extension-data/screenshots/screenshot_755_AJd7yZx.png" width="800px" alt="Captura de tela do Gnome Shell com a extensão Hibernate Status Button. No canto superior contém uma barra com os botões 'Atividades' no canto esquerdo, 'Data e Hora (Sep 29 4:54PM)' no meio, 'Conexões de Rede, Som e Energia' no canto direito. O botão 'Conexões de Rede, Som e Energia' foi pressionado, e está mostrando um menu com o sub-menu 'Power Off' (desligar). Nesse submenu contém os seguintes botões: 'Suspend' (Suspender), 'Hibernate' (Hibernar), 'Hybrid Sleep' (Suspensão Híbrida), 'Restart' (Reiniciar), 'Power Off' (Desligar) e 'Log Out' (Deslogar).">

Legenda: Captura de tela do Gnome Shell com a extensão Hibernate Status Button. 

## Ativar atualizações automáticas em 2º plano

É possível ativar atualizações automáticas software em 2º plano, de modo que quem estiver utilizando o computador não vai perceber que o sistema e os programas estão sendo atualizados.

Para isso, basta instalar o pacote ```unattended-upgrades```, por meio do gerenciador de pacotes APT:

```
sudo apt install unattended-upgrades
```