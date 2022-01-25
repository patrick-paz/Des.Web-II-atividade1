# Des.Web-II-atividade1

**Atividade: Configuração do ambiente de desenvolvimento
para as aulas de Web II.**

### Ferramentas para Instalação
- Python e Pip
- Pycharm
- Git
- SQLite
- SQLite Browser

---

### Descrição

**Python:** é uma linguagem Open-Source de propósito geral usado bastante em data science, machine learning, desenvolvimento de web, desenvolvimento de aplicativos, automação de scripts, fintechs e mais. O Python roda no servidor, e é responsável por processar a lógica dos Inputs dos usuários, interagindo com bases de dados e outros servidores, etc.

**Pip:** O PIP é uma ferramenta para gerenciamento de pacotes de software escrito em Python. E serve para instalar, remover, atualizar ou listar os pacotes instalados em um determinado projeto.

**Git:** Git é um sistema de controle de versão open-source, ou seja, gratuito. Ele é utilizado para a criação de um histórico de alterações em código-fonte de projetos de desenvolvimento de software. Por meio de sua utilização, podemos saber quais foram as alterações realizadas, quem fez cada uma das alterações e baixar essas mudanças em nossa máquina. Se necessário, revertê-las para uma versão anterior.

**SQLite:** O SQLite é uma base de dados relacional de código aberto e que dispensa o uso de um servidor na sua atuação. Armazenando seus arquivos dentro de sua própria estrutura, ele é capaz de funcionar muito bem em aplicações diversas, principalmente, websites de tráfego médio e sistemas mobile.

**SQLite Browser:** O SQLite Browser é uma ferramenta visual usada para criar, projetar e editar arquivos de banco de dados compatíveis com SQLite. Sua interface é baseada em QT e deve ser usada por usuários e desenvolvedores que desejam criar bancos de dados, editar e pesquisar dados usando uma interface familiar semelhante a uma planilha, sem a necessidade de aprender comandos SQL complicados.

---
### Instalação

**Python:**
1. Abrir o terminal
2. Digitar: sudo apt-get install python3
3. Aguardar a instalação finalizar

**Versão:** python3 20.3.1



**Pip:**
1. Abrir o terminal
2. Digitar: sudo apt-get install python3-pip
3. Aguardar a instalação finalizar

**Versão:** python3-pip 20.3.1



**Git:**
1. Abrir o terminal
2. Digitar: sudo apt-get install git-all
3. Aguardar a instalação finalizar

**Versão:** 2.25.1



**SQLite:**
1. A primeira coisa que devemos fazer é preparar o sistema operacional com os pacotes necessários para a compilação e construção dos pacotes a partir do código fonte. Ciente disso, abra um terminal (use as teclas CTRL + ALT + T);
2. Primeiramente, instale os softwares necessários à instalação;
sudo apt-get install build-essential tar wget
3. Em sequida baixe o código fonte do programa nesse endereço e salve-o como sqlite.tar.gz, ou use o comando abaixo;
wget -c https://www.sqlite.org/2021/sqlite-autoconf-3360000.tar.gz -O sqlite.tar.gz
4. Crie uma pasta para SQLite e acesse-a;
mkdir sqlite3 && cd sqlite3
5. Em seguida, descompacte o arquivo nesta pasta;
tar xvfz ../sqlite.tar.gz
6. Acesse a pasta gerada pela descompactação;
cd sqlite-autoconf-*/
7. E configure o código para iniciar a compilação;
./configure
8. Compile o SQLite com o comando make;
make
9. E, finalmente, instale-o;
sudo make install

**Versão:** 3.36.0



**SQLite browser:**
1. Abrir terminal;
2. Digitar o comando: sudo add-apt-repository universe (para ativar o repositório universal);
3. Após ativar o repositório universal, usar o comando: sudo apt update (para atualizar as fontes de software do ubuntu);
4. Depois de configurar e atualizar o repositório, agora use o comando: sudo apt install sqlitebrowser (para instalar o SQLite browser);

**Versão:** ???



---

### Versão do Sistema Operacional:

**Ubuntu 20.0.4**



