# Principais Ferramentas de Desenvolvimento

Instalação das principais ferramentas de desenvolvimento.

## Editores de Código

### Visual Studio Code

Acesse o site: https://code.visualstudio.com/Download

Baixe o arquivo ```.deb``` e instale-o através do comando ```sudo apt install ./<nome-do-arquivo.deb>```

Ou instale-o através da Snap Store.

```
sudo snap install code --classic
```

## Ambientes de desenvolvimento integrado

### JetBrains (IntelliJ, PyCharm, Clion, WebStorm, etc.)

Acesse o site: https://www.jetbrains.com/toolbox-app/, e baixe o arquivo ```.tar.gz``` e extraia esse arquivo no diretório desejado.

Ou acesse o perfil oficial da JetBrains na Snap Store em: https://snapcraft.io/publisher/jetbrains e baixe o IDE desejado.

### Eclipse

Acesse o site: https://www.eclipse.org/downloads/packages/installer, baixe o arquivo ```.tar.gz``` e extraia esse arquivo no diretório desejado.

### NetBeans

Acesse o site: https://netbeans.apache.org/front/main/download/nb23/, baixe o arquivo ```.deb``` e instale-o através do comando ```sudo apt install ./<nome-do-arquivo.deb>```

## Compiladores e Interpretadores

### GNU C Compiler

```
sudo apt install gcc
```

### GNU C++ Compiler

```
sudo apt install gcc-c++
```

### Oracle Java JDK

#### Compilador

```
sudo apt install openjdk-17-jdk
```

#### Ambiente de execução

```
sudo apt install openjdk-17-jre
```

### Python

```
sudo apt install python3
```

### Node.js

```
sudo apt install nodejs
```

### Deno

```
curl -fsSL https://deno.land/install.sh | sh
```

## Utilitários

### Postman

```
sudo snap install postman
```