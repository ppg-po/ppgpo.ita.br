# Instalação de programas para Windows

## Segue os passos para rodar o Linux no seu computador.

### **Para instalar o Ubuntu no Windons**

Antes de fazer a instação é necessario fazer o procedimento abaixo que autoriza a instalação no Linux no computador.

Para autorizar o Windows instalar o Ubuntu siga esses passos antes de tentar instalar o programa.

Na barra de pesquisa do computador pesquisar por: ativar ou desativar recursos do Windows 
    
        1.	Selecionar a caixa de Subsistema do Windows para Linux
        2.	Reinicia o computador
        3.	Instalar o UBUNTU
        4.	Colocar um nome de usuários e senha

Caso prefira basta assistir o video abaixo com as explicações de como fazer a instalação.

* Vídeo: https://www.youtube.com/watch?v=kKglzOgMhzw 

### **Visual Studio Code**

Baixar o programa no site (https://code.visualstudio.com/)

**Não equeça de baixar o VSC para Linux**
Para instalação basta seguir o passo a passo recomendado no video abaixo:

* Vídeo : https://www.youtube.com/watch?v=49K-Zxc8A7A

Após isso instalar as extensões que vai precisar:
No VSC (visual studio code) - Selecione o 5º botão do lado esquerdo (Extensions).

 Digite na barra de pesquisa e instale as seguintes extenssões: 

    1.	WSL
    2.	GitLab
    3.	Markdown All in one
    4.	GitLens
    5.	Markdown lint

### **Para instalar o Hugo versão Extended**

No próprio WSL digitar os seguintes comandos:

`wget https://github.com/gohugoio/hugo/releases/download/v0.103.1/hugo_extended_0.103.1_linux-amd64.deb`

Com esse comnado ele vai baixar automaticamente o programa. Para instalar o programa digite o seguinte comando:

`sudo apt install ./hugo_extended_0.103.1_linux-amd64.deb` 

Quando se usa o comando `sudo` é solicitado o uso da senha (aquela salva no momento da instalação)

### **Para instalar o Git no Ubunto**

No próprio WSL digitar os seguintes comandos:

`sudo apt install git`

### **Instalar o golang**

Go - é uma linguagem de programação criada pela Google e lançada em código livre.

Ainda no WSl digitar o comando: 

`sudo apt install golang`

Vai demorar um pouco até fazer a instação.

### **Comandos importantes**
Usados no **WSL**

`sudo apt update`  - Verifica se tem alguma atualização disponivel

`sudo apt upgrade` - Instala as atualizações 



