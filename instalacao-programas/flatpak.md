# Flatpak

Outro gerenciador de pacote disponível para o Ubuntu é o Flatpak. O Flatpak, da mesma forma que o Snap, foi desenvolvido para que desenvolvedores possam distribuir pacotes (programas) para diferentes distribuições Linux com o mínimo de esforço.

Diferente do Snap, o Flatpak não vem instalado por padrão no Ubuntu.

## Instalação do Flatpak

Para instalar o Flatpak, no terminal, digite o seguinte comando:

```
sudo apt install -y flatpak
```

### Integração do Flatpak à loja de aplicativos

O Flatpak pode ser integrado com a loja de aplicativos do Ubuntu, permitindo instalar pacotes sem ter que digitar comandos. Para isso, no terminal, digite o seguinte comando:

```
sudo apt install -y gnome-software-plugin-flatpak
```

### Instalação do repositório do FlatHub

O FlatHub é um repositório comunitário onde vários pacotes são distribuídos. Por padrão o FlatPak não vem com o FlatHub instalado. 

Para adicionar este repositório, no terminal, digite o seguinte comando:

```
sudo flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```

## Página Web

Para encontrar e instalar pacotes Flatpak basta acessar: https://flathub.org

## Comandos

### Pesquisando por um pacote Flatpak

Para pesquisar por um pacote Flatpak, no terminal, digite o seguinte comando:

```
flatpak search '<pesquisa>'
```

### Instalar um pacote Flatpak

Para instalar um pacote Flatpak, no terminal, digite o seguinte comando:

```
sudo flatpak install <nome-do-pacote>
```

**Cuidado: Alguns pacotes do flatpak não são oficiais (são mantidos pela comunidade). Eles podem ser infectados por malware (vírus). Use por sua conta e risco.**

### Desinstalar um pacote Flatpak

Para desinstalar um pacote Flatpak, no terminal, digite o seguinte comando:

```
sudo flatpak uninstall <nome-do-pacote>
```

### Atualizar um pacote Flatpak

Para atualizar um pacote Flatpak, no terminal, digite o seguinte comando:

```
sudo flatpak update <nome-do-pacote>
```

Ou para atualizar tudo, no terminal, digite o seguinte comando:

```
sudo flatpak update
```

## Exemplos de programas

Exemplos de programas que podem ser instalados por meio do Flatpak.

[Discord](https://flathub.org/apps/com.discordapp.Discord)

[RetroArch](https://flathub.org/apps/org.libretro.RetroArch)

[Gimp](https://flathub.org/apps/org.gimp.GIMP)

[OBS Studio](https://flathub.org/apps/com.obsproject.Studio)

[Stremio](https://flathub.org/apps/com.stremio.Stremio)

[Firefox](https://flathub.org/apps/org.mozilla.firefox)

[Audacity (não oficial)](https://flathub.org/apps/org.audacityteam.Audacity)

[Android Studio (não oficial)](https://flathub.org/apps/com.google.AndroidStudio)

[Free File Sync (não oficial)](https://flathub.org/apps/org.freefilesync.FreeFileSync)

[Signal Desktop (não oficial)](https://flathub.org/apps/org.signal.Signal)