# Snap

O Snap é o gerenciador de pacote secundário do Ubuntu. Ele foi desenvolvido para que desenvolvedores possam distribuir pacotes (programas) para diferentes distribuições Linux com o mínimo de esforço.

## Página Web

Para encontrar e instalar pacotes snap basta acessar: https://snapcraft.io/store.

## Comandos

### Pesquisar pacote

Para pesquisar por um pacote, no terminal digite:

```
snap search '<pesquisa>'
```

Exemplo:

```
snap search vlc
```

### Instalar pacote

Para instalar um pacote, no terminal, digite o seguinte comando:

```
sudo snap install <nome-do-pacote>
```

Exemplo:

```
sudo snap install spotify
```

CUIDADO: AO INSTALAR PACOTES SNAP, VERIFIQUE SE O AUTOR DO PACOTE É VERIFICADO. PACOTES NÃO VERIFICADOS PODEM CONTER MALWARE.

### Atualizar pacote

Para atualizar um pacote, no terminal, digite o seguinte comando:

```
sudo snap refresh <nome-do-pacote>
```

Exemplo:

```
sudo snap refresh snapd
```

### Desinstalar pacote

Para desinstalar um pacote, no terminal, digite o seguinte comando:

```
sudo snap remove <nome-do-pacote>
```

Exemplo:

```
sudo snap remove spotify
```

## Exemplos de programas

Exemplos de programas que podem ser instalados por meio do Snap:

[Spotify](https://snapcraft.io/spotify)

[Visual Studio Code](https://snapcraft.io/code)

[IntelliJ IDEA Community Edition](https://snapcraft.io/intellij-idea-community)

[PyCharm Community Edition](https://snapcraft.io/pycharm-community)

[Skype](https://snapcraft.io/skype)