# Instalação da distribuição

## Importante

Antes de executar a instalação da distribuição Ubuntu, faça backup de todos os dados do seu computador para uma mídia externa.

TODOS OS DADOS DO COMPUTADOR ONDE SERÁ REALIZADA A INSTALAÇÃO SERÃO APAGADOS.

## STEP 1 - Baixar o Ubuntu

Acesse a página de download da distribuição Ubuntu para Desktop em: https://ubuntu.com/download/desktop

Na seção 'Ubuntu x.y LTS', clique no botão 'Download x.y LTS' (x.y representa a última versão de suporte estendido. No dia que desenvolvi este laboratório era a versão 24.04)

<img src="Imagens/Screenshot%202024-08-26%20at%2013-59-21%20Download%20Ubuntu%20Desktop%20Ubuntu.png" alt="Captura de tela da página de Download do Ubuntu. Nela contém o título: 'Download Ubuntu Desktop', e a seção: 'Ubuntu 24.04 LTS'. Em 'Ubuntu 24.04 LTS' contém o botão verde: 'Download 24.04 LTS'.">

Legenda: Captura de tela da página de Download do Ubuntu.

Na próxima página aparecerá a mensagem: 'Thank you for downloading Ubuntu Desktop x.y LTS', e um arquivo 'ubuntu-x.y-desktop-amd64.iso' com a imagem de instalação do Ubuntu será baixado.

<img src="Imagens/Screenshot%202024-08-26%20at%2014-05-24%20Thank%20you%20for%20downloading%20Ubuntu%20Desktop%20Ubuntu.png" alt="Captura de tela da página de agradecimento pelo download. Nela contém o título: 'Thank you for downloading Ubuntu Desktop 24.04 LTS'">

Legenda: Captura de tela da página de Download do Ubuntu.

## STEP 2 - Gravar o Ubuntu em um pendrive (não é necessário se for instalar em máquina virtual)

Após ter baixado a imagem de instalação do Ubuntu, será necessário gravá-la em um pendrive. Para isso será necessário um pendrive que possa ser apagado. TODOS OS DADOS ARMAZENADOS NELE SERÃO PERDIDOS.

Para isso precisaremos de uma ferramenta chamada Ventoy. O Ventoy permite a criação de pendrives _bootáveis_ (que possam ser inicializados pela BIOS ou UEFI do computador).

Para baixar o Ventoy, acesse a página de download em: https://www.ventoy.net/en/download.html

<img src="Imagens/Screenshot%202024-08-26%20at%2014-13-06%20Ventoy.png" alt="Captura de tela da página de download do Ventoy. Nela contém o título 'Ventoy', e a seção 'Binary'. Na seção 'Binary' contém os links 'ventoy-1.0.99-windows.zip', 'ventoy-1.0.99-linux.tar.gz', 'ventoy-1.0.99-livecd.iso'.">

Legenda: Captura de tela da página de download do Ventoy.

Baixe o arquivo correspondente ao sistema operacional e a arquitetura de sua máquina.

Extraia o arquivo .zip, e na pasta em que ele tiver sido extraído, execute o arquivo 'Ventoy2Disk'.

<img src="Imagens/Captura%20de%20tela%202024-08-26%20142122.png" alt="Captura de tela do programa que grava o Ventoy no disco. Nela contém uma janela com um programa com o título 'Ventoy2Disk X86'. Na barra de menus, contém os menus: 'Option' e 'Language'. Na parte principal contém as seções 'Device', 'Ventoy in Packege', 'Ventoy In Device' e 'Status', e os botões 'Install' e 'Update'. Na seção 'Device' contém uma lista com os dispositivos que podem ser gravados, neste caso está selecinado o 'E: [16GB] Kingston DataTraveler 2.0'. E um botão com o icone de atualizar. Na seção 'Ventoy In Package contém a versão do Ventoy '1.0.99 exFAT MBR'. A seção 'Ventoy In Device' está vazia. E a seção 'Status' contém 'READY' e uma barra de progresso vazia. Em baixo do programa contém os links 'Donate' e 'www.ventoy.net'">

Legenda: Captura de tela do programa que grava o Ventoy no disco.

Selecione o disco (pendrive) que deseja gravar. E clique em Install.

TODOS OS DADOS DESSE DISCO SERÃO APAGADOS.

Uma janela com uma mensagem de confirmação será aberta. Clique em 'Sim'.

Após o Ventoy tiver sido instalado no pendrive, aparecerão duas partições uma com o nome '' e outra com o nome ''. A primeira partição será onde será armazenado as imagens de instalação (arquivos .iso).

Copie o arquivo 'ubuntu-x.y-desktop-amd64.iso' que foi baixado (no [passo 1](#step-1---baixar-o-ubuntu)) para essa partição.

Ejete o pendrive do computador.

## STEP 3 - Realizar boot no Ubuntu

Este passo deverá ser realizado no computador em que se deseja instalar o Ubuntu.

Desligue o computador

Insira o pendrive em uma porta USB.

Ligue o computador.

Pressione a tecla que exibe os dispositivos para boot (Esta tecla é específica para cada modelo de computador. Geralmente é F12 ou F8. Caso não saiba, pesquise na Internet).

Na tela de boot selecione o pendrive, e pressione ENTER.

Uma tela escrita 'Ventoy' enorme aparecerá, e mostrará a opção 'ubuntu-x.y-desktop-amd64.iso'. Selecione 'ubuntu-x.y-desktop-amd64.iso' e pressione ENTER.

<img src="Imagens/screen_uefi.png" alt="Captura de tela da tela do Ventoy. Fonte: Site do Ventoy. Nela contém várias imagens de instalação: CentOS, ArchLinux, Windows 11, Deeping, FreeBSD, Ubuntu, VMWare, WinPE, etc. Em baixo contém a versão '1.0.64 UEFI', o site 'www.ventoy.net', e os atalhos no teclado: 'h:Help', 'F1:Memdisk', 'F2:Power', 'F3:TreeView', 'F4:Localboot', 'F5:Tools' e 'F6:ExMenu'.">

Legenda: Captura de tela da tela do Ventoy. Fonte: Site do Ventoy.

E a imagem de instalação do Ubuntu será inicializada.

<img src="Imagens/Captura%20de%20tela%202024-08-26%20150053.png" alt="Tela de carregamento do Ubuntu no VirtualBox. Seu fundo é preto. No centro está a logo do VirtualBox. E embaixo está a logo do Ubuntu.">

Legenda: Tela de carregamento do Ubuntu no VirtualBox. A logo do fabricante do computador (neste caso, VirtualBox) pode variar.

<img src="Imagens/Captura%20de%20tela%202024-08-26%20150749.png" alt="Tela inicial de instalação do Ubuntu. Nela contém uma janela com o título 'Welcome to Ubuntu', no canto esquedo a logo do Ubuntu, e aparece um título 'Choose you language' com um menu com as línguas disponíveis. E um botão 'Next'.">

Legenda: Tela inicial de instalação do Ubuntu.

Em 'Choose your language' (Escolha o seu idioma), escolha "Português (Brasil)"

Caso deseja instalar o Ubuntu junto ao Windows, basta ao particionar o disco marcar a opção

OS DADOS DO COMPUTADOR SERÃO APAGADOS.

Após ter instalado a distribuição Linux Ubuntu, desligue o computador e ejete o pendrive.

Ligue o computador novamente, e o Ubuntu será iniciado.