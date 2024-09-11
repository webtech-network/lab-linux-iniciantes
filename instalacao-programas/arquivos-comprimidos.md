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

TODO

## Criação de atalhos

TODO