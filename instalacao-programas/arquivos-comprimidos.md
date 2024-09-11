# Arquivos Comprimidos

Em alguns casos específicos, a única forma de instalar um determinado programa em distribuições Linux é por meio do download e extração de arquivos comprimidos ('.zip', '.tar.gz', '.tar.xz', '.tar.bz').

## Download do arquivo comprimido

O download de arquivos comprimidos deve ser feito no site do desenvolvedor.

**CUIDADO: Arquivos comprimidos, podem conter malware (vírus). Baixe arquivos comprimidos somente de fontes confiáveis.**

## Extração do arquivo comprimido

### Interface gráfica

### Linha de comando

#### Arquivos '.zip'

Para extraír um arquivo '.zip' no Linux, no terminal, na pasta onde ele foi baixado, digite o seguinte comando:

```
unzip <nome-do-arquivo.zip>
```

Para executar o comando 'unzip' é necessário ter o pacote 'unzip' instalado no sistema. Para instalá-lo, basta digitar o seguinte comando no terminal:

```
sudo apt install unzip
```

#### Arquivos '.tar.xz', '.tar.gz' e 'tar.bz'

Para extrair um aquivo '.tar.xz' no Linux, no terminal, na pasta onde ele foi baixado, digite o seguinte comando:

```
tar -xf <nome-do-arquivo>
```

## Criação de links simbólicos

Às vezes, é desejável a criação de links simbólicos para facilitar a execução do programa pelo terminal do linux.

### Linha de Comando

Para criar links simbólicos no Linux, no terminal, digite o seguinte comando:

```
ln --symbolic <caminho-arquivo-origem> <caminho-do-link-a-ser-criado>
```

Ou, se precisar de permissão de administrador:

```
sudo ln --symbolic <caminho-arquivo-origem> <caminho-do-link-a-ser-criado>
```

Exemplo: Criação do link simbólico 'javac8' para o programa javac (compilador de java) versão 8:

```
sudo ln --symbolic "/usr/lib/jvm/java-1.8.0/bin/javac" "/bin/javac8"
```

## Criação de atalhos (Desktop Entry)

Às vezes, em programas com interface gráfica, é desejável que eles possam ser abertos por meio de atalhos no ambiente de trabalho.

Para criar atalhos para o ambiente de trabalho, é necessário criar um arquivo '.desktop' e colocá-lo na pasta '~/.local/share/applications' (somente para o usuário) ou na pasta '/usr/share/applications' (para todos os usuários).

O arquivo '.desktop' deve ser criado em um editor de texto. Seu formato é esse:

```
[Desktop Entry]
Type=Application
Name=<nome-do-programa>
GenericName=<nome-genérico-do-programa>
Icon=<nome-ou-caminho-do-icone-do-programa>
Exec=<nome-ou-caminho-do-executável-com-ou-sem-argumentos>
Terminal=<se-o-programa-deve-ser-executado-no-terminal-true-ou-false>
Keywords=<palavras-chave-para-busca-separadas-por-ponto-e-virgula>
StartupNotify=<notificação-de-que-o-programa-abriu-true-ou-false>
```

Exemplo: Um arquivo '.desktop' para o Java Runtime Environment 8:

```
[Desktop Entry]
Type=Application
Name=Java Runtime Environment 8
GenericName=Java 8
Icon=java-1.8.0-openjdk
Exec=java8 -jar %f
Terminal=false
MimeType=application/x-java-archive
Keywords=java; runtime; environment; 8; jre
StartupNotify=true
```

Mais informações da especificação de arquivos '.desktop' em: https://specifications.freedesktop.org/desktop-entry-spec/latest/

## Exemplos de programas

Exemplos de programas que podem ser instalados por meio do download e extração de arquivos comprimidos.

[Oracle Java JDK](https://www.oracle.com/java/technologies/downloads/)

[Visual Studio Code](https://code.visualstudio.com/Download)

[Mozilla Firefox](https://www.mozilla.org/pt-BR/firefox/all/)

[WinRAR](https://www.win-rar.com/download.html)

Alguns dos programas listados também podem ser instalados por outros métodos de instalação.