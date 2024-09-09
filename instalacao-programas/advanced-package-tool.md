# Advanced Packaging Tool (APT)

O Advanced Packaging Tool (APT) é o principal gerenciador de pacotes do Ubuntu.

## Comandos

### Atualizar lista de pacotes

Para que o Advanced Packaging Tool possa instalar e pesquisar por pacotes, é necessário que a sua lista de pacotes esteja atualizada.

Para atualizar a lista de pacotes, no terminal digite:

```
sudo apt update
```

### Pesquisar pacote

Para pesquisar por um pacote, no terminal, digite:

```
apt search '<busca>'
```

E uma lista de pacotes aparecerá com o nome de cada pacote (programa) e a sua respectiva descrição.

Ou se preferir pode utilizar o site [pkgs.org](https://pkgs.org/) para pesquisar por pacotes.

### Instalar pacote

Para instalar um pacote, no terminal, digite:

```
sudo apt install <nome-do-pacote-a-ser-instalado>
```

Uma mensagem será exibida perguntando se confirma a instalação do pacote escolhido e suas dependências. Basta digitar 's' ou 'y' para confirmar.

E o pacote será instalado.

### Instalar um arquivo .deb

No Ubuntu quando um pacote não estiver disponível para ser instalado pelos repositórios do Advanced Packaging Tool, é possível baixar através do navegador web um arquivo '.deb'.

Para instalar um arquivo '.deb', no terminal, dentro da pasta onde este arquivo '.deb' está localizado, digite:

```
sudo apt install ./<nome-do-arquivo.deb>
```

CUIDADO: ARQUIVOS '.DEB' PODEM CONTER SOFTWARE MALICIOSOS (VÍRUS). BAIXE ARQUIVOS '.DEB' SOMENTE DE FONTES CONFIÁVEIS.

### Desinstalar pacote

Para desinstalar um pacote, no terminal, digite:

```
sudo apt remove <nome-do-pacote-a-ser-removido>
```

Caso o pacote a ser desinstalado esteja instalado na sua máquina, uma mensagem será exibida perguntando se confirma a desinstalação do pacote escolhido. Basta digitar 's' ou 'y' para confirmar.

E o pacote ser desinstalado.

CUIDADO: DESINSTALAR PACOTES QUE FAZEM PARTE DA BASE DO SISTEMA PODE DESTRUIR O SISTEMA OPERACIONAL.

### Atualizar pacote

Para atualizar a versão instalada de um pacote, no terminal, digite:

```
sudo apt upgrade <nome-do-pacote-a-ser-atualizado>
```

Caso a versão instalada desse pacote esteja desatualizada, uma mensagem será exibida perguntando se confirma a atualização do pacote escolhido. Basta digitar 's' ou 'y' para confirmar.

Ou para atualizar tudo, no terminal, digite:

```
sudo apt upgrade
```

Caso a versão instalada de algum pacote instalado esteja desatualizada, uma mensagem será exibida perguntando se confirma a atualização. Basta digitar 's' ou 'y' para confirmar.

## Exemplos de programas

Exemplos de programas que podem ser instalados por meio do APT.

### Ferramentas de Desenvolvimento

#### Python:

```
sudo apt install python3
```

#### Open JDK 17 JDK:

```
sudo apt install openjdk-17-jdk
```

#### Open JDK 17 JRE:

```
sudo apt install openjdk-17-jre
```

#### Linguagem Go

```
sudo apt install golang
```

#### GNU C Compiler

```
sudo apt install gcc
```

#### GNU C++ Compiler

```
sudo apt install gcc-c++
```

#### Git

```
sudo apt install git
```

### Utilitários

#### VLC Media Player

```
sudo apt install vlc
```

#### qBittorrent

```
sudo apt install qbittorrent
```

#### Gimp

```
sudo apt install gimp
```

#### Brasero

```
sudo apt install brasero
```

#### Calibre

```
sudo apt install calibre
```

#### Okular

```
sudo apt install okular
```

#### Steam:

```
sudo apt install steam
```