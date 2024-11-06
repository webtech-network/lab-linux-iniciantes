# Instalar distribuição

## Importante

## Roadmap

### STEP 1 - Download da imagem de instalação

Acesse a página de download da distribuição Ubuntu para Desktop em: https://ubuntu.com/download/desktop

<img src="../../imagens/pagina_download_ubuntu.png" alt="Captura de tela da página de Download do Ubuntu. Nela contém o título: 'Download Ubuntu Desktop', e a seção: 'Ubuntu 24.04.1 LTS'. Em 'Ubuntu 24.04.1 LTS' contém o botão verde:'Download 24.04.1 LTS'.">

Clique no ícone em verde 'Download 24.04.1 LTS'.

<img src="../../imagens/icone_download_24_04_1.png" alt="Captura do ícone verde 'Download 24.04.1 LTS'">

E o arquivo 'ubuntu-24.04.1-desktop-amd64.iso' será baixado. Aguarde o fim do download desse arquivo e siga para o
próximo passo.

### STEP 2 - Gravar a imagem de instalação

Após ter baixado a imagem de instalação do Ubuntu, será necessário gravá-la em uma mídia física. Para isso será
necessário um pendrive que possa ser formatado.

Para gravar a imagem do Ubuntu em um pendrive existem várias ferramentas que podem ser utilizadas. Segue o passo a passo
de cada ferramenta

**Cuidado: Ao gravar uma imagem de instalação em um pendrive, todos os dados desse pendrive serão apagados.**

#### Opção 1 - Ventoy

##### STEP 2.1 - Acesse a página de download do Ventoy em: https://www.ventoy.net/en/download.html

<img src="../../imagens/pagina_download_ventoy.png" alt="Captura de tela da página de download do Ventoy. Nela contém o título 'Ventoy', e a seção 'Binary'. Na seção 'Binary' contém os links 'ventoy-1.0.99-windows.zip','ventoy-1.0.99-linux.tar.gz', 'ventoy-1.0.99-livecd.iso'.">

##### Windows

##### STEP 2.2 - Caso o seu sistema operacional seja o Windows, clique no link 'ventoy-1.0.99-windows.zip'. E o arquivo 'ventoy-1.0.99-windows.zip' será baixado. Extraia o arquivo baixado.

##### STEP 2.3 - Após extraír os arquivos do Ventoy, na pasta 'ventoy-1.0.99', execute o arquivo executável 'Ventoy2Disk.exe'.

<img src="../../imagens/arquivos_ventoy_windows.png" alt="Captura de tela da janela do Windows Explorer exibindo os arquivos do Ventoy. Nessa janela contém uma barra superior, uma barra lateral e uma área principal. Na área principal contém as pastas: 'boot', 'plugin', 'ventoy', 'altexe', e os arquivos: 'FOR_X64_ARM.txt', 'Ventoy2Disk.exe', 'VentoyPlugson.exe', 'VentoyVlnk.exe'. Na barra superior contém o caminho 'Computador\Downloads\ventoy-1.0.99-windows\ventoy-1.0.99">

Legenda: Captura de tela da janela do Windows Explorer exibindo os arquivos do Ventoy.

##### STEP 2.4 - Ao executar o 'Ventoy2Disk.exe', uma janela se abrirá com as opções para instalar o Ventoy no pendrive.

<img src="../../imagens/ventoy_2_disk_windows.png" alt="Captura de tela do programa Ventoy2Disk. Nela contém uma janela com um programa com o título 'Ventoy2Disk X86'. Na barra de menus, contém os menus: 'Option' e 'Language'. Na parte principal contém as seções 'Device', 'Ventoy in Package', 'Ventoy In Device' e 'Status', e os botões 'Install' e 'Update'. Na seção 'Device' contém uma lista com os dispositivos que podem ser gravados, neste caso está selecinado o 'E: [16GB] Kingston DataTraveler 2.0'. E um botão com o icone de atualizar. Na seção 'Ventoy In Package contém a versão do Ventoy '1.0.99 exFAT MBR'. A seção 'Ventoy In Device' está vazia. E a seção 'Status' contém 'READY' e uma barra de progresso vazia. Em baixo do programa contém os links 'Donate' e 'www.ventoy.net'">

Legenda: Captura de tela do programa Ventoy2Disk.

##### STEP 2.5 - Em 'device', selecione o pendrive que deseja instalar o Ventoy. E depois clique em 'Install'.

Após instalar o Ventoy no pendrive, duas partições serão montadas no Windows Explorer: 'Ventoy' e 'VTOYEFI'.

<img src="../../imagens/particao_ventoy_windows.png"/>

##### STEP 2.6 - Copie o arquivo 'ubuntu-24.04.1-desktop-amd64.iso' para dentro da partição 'Ventoy'.

Legenda: Captura de tela do Windows Explorer mostrando a partição 'Ventoy'. Note no canto esquerdo a partição 'VTOYEFI'.

##### Linux

##### STEP 2.2 - Caso esteja em uma máquina com Linux, clique no link 'ventoy-1.0.99-linux.tar.gz'. E o arquivo
'ventoy-1.0.99-linux.tar.gz' será baixado.

##### STEP 2.3 - Após extraír o arquivo 'ventoy-1.0.99-linux.tar.gz', abra o arquivo executável 'VentoyGUI.x86_64'.

<img src="../../imagens/arquivos_ventoy_linux.png" alt="Captura de tela da janela do Gnome Files no Linux exibindo os arquivos do Ventoy. Nessa janela contém uma barra superior, uma barra lateral e uma área principal. Na área principal contém as pastas: 'boot', 'plugin', 'tool', 'ventoy', 'WebUI', e os arquivos: 'CreatePersistentImg.sh', 'ExtendPersistentImg.sh', 'README, 'Ventoy2Disk.sh', 'VentoyGUI.aarch64', 'VentoyGUI.i386', 'VentoyGUI.mips64el', 'VentoyGUI.x86_64', 'VentoyPlugson.sh', 'VentoyVlnk.sh', 'VentoyWeb.sh'. Na barra superior contém o caminho 'Pasta Pessoal/Downloads/ventoy-1.0.99-linux/ventoy-1.0.99'. Na barra lateral contém os acessos rápidos para 'Recentes', 'Favorito', 'Pasta Pessoal', 'Documentos', 'Imagens', 'Musica', 'Videos', 'Lixeira'.">

Legenda: Captura de tela da janela do Gnome Files no Linux exibindo os arquivos do Ventoy.

##### STEP 2.4 - Ao executar o 'VentoyGUI.x86_64', uma janela se abrirá com as opções para instalar o Ventoy no pendrive.

<img src="../../imagens/ventoy_2_disk_linux.png" alt="Captura de tela do programa Ventoy2Disk. Nela contém uma janela com um programa com o título 'Ventoy2Disk'. Na barra de menus, contém os menus: 'Option' e 'Language'. Na parte principal contém as seções 'Device', 'Ventoy in Package', 'Ventoy In Device' e 'Status', e os botões 'Install' e 'Update'. Na seção 'Device' contém uma lista com os dispositivos que podem ser gravados, neste caso está selecinado o 'sdb [16GB] Kingston DataTraveler 2.0 (USB)'. E um botão com o icone de atualizar. Na seção 'Ventoy In Package contém a versão do Ventoy '1.0.99 MBR'. A seção 'Ventoy In Device' está vazia. E a seção 'Status' contém 'READY' e uma barra de progresso vazia. Em baixo do programa contém os links 'Donate' e 'www.ventoy.net'">

Legenda: Captura de tela do programa Ventoy2Disk.

##### STEP 2.5 - Em 'device', selecione o pendrive que deseja instalar o Ventoy. E depois clique em 'Install'.

Após instalar o Ventoy no pendrive, a partição 'Ventoy' será montada no Files:

<img src="../../imagens/particao_ventoy_linux.png">

Legenda: Captura de tela do Files do Linux mostrando a partição 'Ventoy'.

##### STEP 2.6 - Copie o arquivo 'ubuntu-24.04.1-desktop-amd64.iso' para dentro da partição 'Ventoy'.

#### Opção 2 - Rufus (somente Windows)

##### STEP 2.1 - Acesse a página de download do Rufus em: https://rufus.ie/pt_BR/

<img src="../../imagens/pagina_download_rufus.png" alt="Captura de tela da página de download do Rufus. Nela contém o título: 'Rufus'; o logo, que é o símbolo de um pendrive; o subtítulo: 'Crie drives USB inicializáveis de forma fácil'; e a captura de tela do programa Rufus. A captura de tela do programa rufus é uma janela cujo título é 'Rufus 3.20.1929'. Essa janela contém três áreas: 'Propriedades do Drive', 'Opções de formatação' e 'Status'. Na área 'Propriedades do Drive', contém o 'Dispositivo' e em baixo deste, uma barra de seleção 'Windows 11 22H2 (F:) [8 GB].' Em baixo da barra de seleção 'Windows 11 22H2 (F:) [8 GB]', contém o texto: 'Seleção de Boot' e em baixo deste, a barra de seleção 'Windows 11 22H2.iso'; a barra de seleção 'Windows 11 22H2.iso' é seguida do botão 'Selecionar'. Em baixo da barra de seleção 'Windows 11 22H2.iso', contém contém o texto 'Opções de Imagem', e em baixo deste, a barra de seleção 'Instalação padrão do Windows'. Em baixo da barra de seleção 'Instalação padrão do Windows', contém os textos: Esquema de partição, e embaixo deste a barra de seleção 'GPT'; a barra de seleção 'Instalação padrão do Windows' é seguida de 'Sistema de Destino', e embaixo deste 'UEFI (não CSM). E embaixo da barra de seleção 'GPT', contém o um botão no formato de seta para baixo com o texto à direita 'Exibir propriedades avançadas do drive'. Na área 'Opções de formatação', contém o texto 'Nome do volume', e embaixo deste a entrada de texto escrita 'Windows 11 22H2'. Embaixo da entrada de texto escrita 'Windows 11 22H2', contém o texto 'Sistema de arquivos', e embaixo deste a entrada de texto 'NTFS', 'Sistema de arquivos' é seguido do texto 'Tamanho do cluster', e embaixo deste a entrada de texto escrita '4096 bytes (Padrão)'. E embaixo da entrada de texto 'NTFS' contém um botão no formato de seta para cima com o texto 'Esconder opções avançadas de formação'. Em baixo deste botão no formato de seta, contém uma caixa de seleção (marcada) cuja descrição é 'Formatação rápida', em baixo disso, a caixa de seleção (marcada) cuja descrição é 'Criar arquivos de nome estendido e ícone'. E em baixo disso, contém a caixa de seleção (não marcada) cuja descrição é 'Procurar blocos defeituosos'. Á direita desta caixa de seleção, contém a barra de seleção '1 passada'. Na área de 'Status' contém uma barra de progresso verde escrito 'Pronto'. No canto inferior contém os botões: Símbolo de internet, Símbolo de exclamação, Símbolo de configuração, outro símbolo de status, 'Iniciar' e 'Fechar'">

##### STEP 2.2 - Em 'Download', clique no link 'rufus-4.6.exe'. E o arquivo 'rufus-4.6.exe' será baixado.

<img src="../../imagens/download_pagina_download_rufus.png"/>

##### STEP 2.3 - Execute o arquivo baixado. E uma janela se abrirá.

<img src="../../imagens/rufus_windows.png"/>

##### STEP 2.4 - Em 'Dispositivo', selecione o dispositivo USB que deseja gravar a imagem.

##### STEP 2.5 - Depois, clique em selecionar, e selecione o arquivo 'ubuntu-24.04.1-desktop-amd64.iso' baixado.

##### STEP 2.6 - E no final, clique em 'Iniciar', e a imagem de instalação será gravada no pendrive.

#### Opção 3 - Balena Etcher

##### STEP 2.1 - Acesse a página de download do Balena Etcher em: https://etcher.balena.io/#download-etcher

<img src="../../imagens/pagina_download_balena_etcher.png"/>

##### STEP 2.2 - Clique no link 'Download' correspondente ao seu sistema operacional.

##### STEP 2.3 - Execute o arquivo baixado.

<img src="../../imagens/balena_etcher_windows.png"/>

Legenda: Captura de tela do Balena Etcher.

##### STEP 2.4 - Clique em 'Flash from file' e selecione o arquivo 'ubuntu-24.04.1-desktop-amd64.iso'. 

##### STEP 2.5 - Depois, clique em 'Select target', e selecione o dispositivo USB que deseja gravar a imagem.

##### STEP 2.6 - E no final, clique em 'Flash!'.

### STEP 3 - Inicializar imagem de instalação

No computador onde deseja instalar o Ubuntu, siga os seguintes passos:

##### STEP 3.1 - Desligue o computador.

##### STEP 3.2 - Insira o pendrive em uma porta USB.

##### STEP 3.3 - Ligue o computador.

##### STEP 3.4 - Pressione a tecla que exibe os dispositivos para boot (Esta tecla é específica para cada modelo de computador. Geralmente é F12 ou F8. Caso não saiba, pesquise na Internet).

##### STEP 3.5 - Na tela de boot selecione o pendrive, e pressione ENTER.

##### STEP 3.6 - Caso tenha gravado o Ventoy no pendrive, selecione 'ubuntu-24.04.1-desktop-amd64.iso'.

E a imagem de instalação do Ubuntu será inicializada.

### STEP 4 - Instalar a distribuição

##### STEP 4.1 - Caso a tela do GRUB apareça, selecione 'Try or Install Ubuntu', e pressione ENTER.

<img src="../../imagens/ubuntu_inicializacao_grub.png"/>

Legenda: Tela do GRUB.

E a tela de inicialização do Ubuntu aparecerá.

<img src="../../imagens/ubuntu_inicializacao.png"/>

Legenda: Tela de inicialização do Ubuntu.

O Ubuntu inicializará e uma janela escrito 'Welcome to Ubuntu' abrirá.

<img src="../../imagens/ubuntu_instalador_idioma.png"/>

Legenda: Ubuntu com o programa de instalação com o título 'Welcome to Ubuntu'.

##### STEP 4.2 - Selecione o idioma 'Português do Brasil', e clique em 'Próximo'.

<img src="../../imagens/ubuntu_instalador_idioma_portugues.png"/>

Legenda: Ubuntu com o programa de instalação com o título 'Boas-Vindas ao Ubuntu' em Português do Brasil.

##### STEP 4.3 - Em opções de acessibilidade, caso não possua nenhuma necessidade de acessibilidade, clique em 'Próximo'.

<img src="../../imagens/ubuntu_instalador_acessibilidade.png"/>

Legenda: Ubuntu com o programa de instalação com o título 'Acessibilidade'.

##### STEP 4.4 - Em layout do teclado, selecione o layout do seu teclado.

Caso o seu computador tenha sido comprado no Brasil, selecione o layout 'Português (Brasil)'. Caso o teclado de seu computador tenha outro layout selecione esse layout ou clique em 'Detectar'.

E no final na caixa de texto 'Digite aqui para testar o seu teclado', digite as teclas do seu teclado, e verifique se elas estão aparecendo corretamente.

<img src="../../imagens/ubuntu_instalador_layout_teclado.png"/>

Legenda: Ubuntu com o programa de instalação com o título 'Layout do Teclado'.