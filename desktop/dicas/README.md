# Dicas

## Como utilizar diferentes versões de runtime em projetos diferentes

Um dos problemas comum a muitos desenvolvedores de software é o desenvolvimento em runtimes com versões diferentes em projetos diferentes. Por exemplo, um desenvolvedor pode em um projeto A estar desenvolvendo em Node.js versão v22.11.0 (LTS) em um projeto B em Node.js com a versão v20.18.1 (LTS).

Uma solução a esse problema é a ferramenta ASDF.

Mais informações em: https://asdf-vm.com/

### Instalando o ASDF

Para instalar o ASDF siga os seguintes passos:

#### STEP 1 - Instale os requisitos

No terminal do linux, digite:

```
sudo apt install curl git
```

#### STEP 2 - Baixe o ASDF

No terminal do linux, digite:

```
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.1
```

#### STEP 3 - Instale o ASDF

Abra em um editor de texto o arquivo ```~/.bashrc```.

Exemplo: Para utilizar o Editor de Texto do Gnome, no terminal, digite:

```
gnome-text-editor ~/.bashrc
```

Adicione estas linhas no final do arquivo ```.bashrc```:

```
. "$HOME/.asdf/asdf.sh"
. "$HOME/.asdf/completions/asdf.bash"
```

### Utilizando o ASDF

O ASDF utiliza plugins para poder rodar diferentes versões de runtime para cada projeto. Cada runtime possue o seu respectivo plugin.

#### Listando os plugins disponíveis

Para listar os plugins disponíveis, no terminal do linux, digite:

```
asdf plugin list all
```

#### Adicionando um plugin

Para adicionar um plugin, no terminal do linux, digite:

```
asdf plugin add <nome-do-plugin>
```

Exemplo:

```
asdf plugin add java
```

#### Removendo um plugin

Para remover um plugin, no terminal do linux, digite:

```
asdf plugin remove <nome-do-plugin>
```

Exemplo:

```
asdf plugin remove deno
```

### Atualizando um plugin

Para atualizar um plugin, no terminal do linux, digite:

```
asdf plugin update <nome-do-plugin>
```

Exemplo:

```
asdf plugin update nodejs
```

### Listando as versões runtimes para um plugin

Para listar as versões das runtimes para um plugin, no terminal, digite:

```
asdf list-all <nome-do-plugin>
```

Exemplo:

```
asdf list-all golang
```

E será mostrada todas as versões do plugin.

### Instalando uma runtime para um plugin

Para instalar uma runtime para um plugin, no terminal, digite:

```
asdf install <nome-do-plugin> <versão-da-runtime>
```

Exemplo:

```
asdf install ruby 3.3.6
```

### Removendo uma runtime para um plugin

Para desinstalar uma runtime para um plugin, no terminal, digite:

```
asdf uninstall <nome-do-plugin> <versão-da-runtime>
```

Exemplo:

```
asdf uninstall kotlin 2.1.0
```

### Configurando uma runtime para um projeto

Para configurar uma runtime para um projeto, no terminal, digite:

```
asdf local <nome-do-plugin> <versão-da-runtime>
```

Exemplo:

```
asdf local java openjdk-23.0.1
```

E um arquivo ```.tool-versions``` será criado na pasta do projeto. Nesse arquivo terá a versão da runtime escolhida para o projeto.

### Configurando uma runtime para o seu usuário (global)

Para configurar uma runtime para o seu usuário, no terminal, digite:

```
asdf global <nome-do-plugin> <versão-da-runtime>
```

Exemplo:

```
asdf global kotlin 2.1.0
```

E um arquivo ```.tool-versions``` será criado na pasta do seu usuário. Nesse arquivo terá a versão da runtime escolhida.