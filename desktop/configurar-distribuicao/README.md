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

## Personalizar o shell do Linux

O terminal do Linux pode ser customizado.

<img src="../../imagens/ubuntu_terminal.png"/>

Legenda: Terminal padrão do Ubuntu.

### Alterar as cores

Para alterar as cores do terminal, no canto superior, clique no botão Opções, e um menu de contexto abrirá.

<img src="../../imagens/ubuntu_terminal_opcoes_selecionado.png"/>

Legenda: Opções do Terminal do Ubuntu.

E depois clique no botão 'Preferências'. E uma nova janela se abrirá com as preferências do terminal.

<img src="../../imagens/ubuntu_terminal_opcoes_preferencias_selecionado.png"/>

Legenda: Menu de contexto de Opções do Terminal do Ubuntu, com 'Preferências' selecionado.

Em baixo de 'Perfis', clique em 'Sem nome'.

<img src="../../imagens/ubuntu_terminal_preferencias_geral_perfil_sem_nome_selecionado.png"/>

Legenda: Preferências do Terminal, com 'Sem nome' de 'Perfils' selecionado.

Clique na aba 'Cores'.

<img src="../../imagens/ubuntu_terminal_preferencias_perfil_sem_nome_cores_selecionado.png"/>

Legenda: Preferências do Terminal, no perfil 'Sem nome', com a aba 'Cores' selecionada.

Neste menu é possível alterar as cores do terminal do Ubuntu. Nele é possível alterar a cor do plano de fundo. Além da palheta de cores do texto.

<img src="../../imagens/ubuntu_terminal_preferencias_perfil_sem_nome_cores.png"/>

Legenda: Opções de cores no Terminal do Ubuntu para o perfil 'Sem nome'

Ao desmarcar a opção 'Usar cores do tema do sistema', e em 'Esquemas embutidos' selecionar 'GNOME Claro' obtém-se o seguinte tema:

<img src="../../imagens/ubuntu_terminal_branco.png"/>

Legenda: Terminal do Ubuntu com o tema 'GNOME claro'.

### Alterar mensagem do terminal

Para alterar a mensagem mostrada no terminal, abra em um editor de texto o arquivo ```~/.bashrc```.

Exemplo: Para utilizar o Editor de Texto do Gnome, no terminal, digite:

```
gnome-text-editor ~/.bashrc
```

<img src="../../imagens/ubuntu_gnome_text_editor.png"/>

Legenda: Arquivo .bashrc aberto no Gnome Text Editor.

Ao abrir o arquivo .bashrc, altere a variável ```PS1``` para a mensagem que deseja exibir.

#### Exemplo: Exibindo "olá mundo" no terminal

Adicione esta linha no final do arquivo ```.bashrc```:

```
PS1="olá mundo";
```

O resultado será:

<img src="../../imagens/ubuntu_terminal_ola_mundo.png"/>

Legenda: Resultado da alteração do valor da variável PS1 para "olá mundo".

#### Exemplo: Exibindo o caminho atual, com o usuário atual e o nome do computador

Adicione esta linha no final do arquivo ```.bashrc```:

```
PS1="[$(whoami)@$(hostname) $(pwd)]$ ";
```

O resultado será:

<img src="../../imagens/ubuntu_terminal_usuario_nome_computador_pasta_atual.png"/>

Legenda: Resultado da alteração do valor da variável PS1 para "[$(whoami)@$(hostname) $(pwd)]$ ".