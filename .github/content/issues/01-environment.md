# Configuração de ambiente

Para começar o guia de programação será necessário verificar o seu ambiente. Você irá precisar:

---

## Ambiente de Desenvolvimento

Para iniciar a desenvolver em Python será necessário escolher o seu ambiente de desenvolvimento ou seu editor de texto para simplificar o desenvolvimento de software.

Segue algumas opções interessantes, caso não possua:

1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Pycharm](https://www.jetbrains.com/pycharm/)

- [ ] Ambiente de desenvolvimento está configurado

*Nota:* Recomendamos instalar o Visual Studio Code, por ser uma IDE versatil e possuir suporte para outras linguagens de programação alem do Python. Segue link para auxiliar [instalação](https://neps.academy/br/blog/como-instalar-e-configurar-python-e-vscode)

## Docker 

Para facilitar o setup e agilizar a parte inicial do curso, criamos uma imagem docker que possui ambiente configurado que pode ser usado para o curso:

Siga as orientações do guia caso possua interesse:

1. [Guia de Instalação: Docker e WSL2](https://tin-technician-e2e.notion.site/Guia-de-Instala-o-Docker-e-WSL2-2c75ab52dc4642e18bf573b515696d4d)

## Verificar se Python está instalado

Você precisará instalar o Python não esteja instalado na sua máquina. Para verificar se o Python está instalado, vá no seu terminal e digite :

`python -V`

Se a versão do Python for exibida, está tudo pronto. Caso contrário, você precisará [baixar o Python](https://www.python.org/downloads/) para seu computador. Instale a versão mais recente para seu ambiente.

- [ ] O Python já está instalado

## Verificar se Git está instalado

Na sua linha de comentário, digite:

`git --version`

Se a versão do Git for exibida, você está pronto para prosseguir. Caso contrário, você precisará [baixar o Git](https://git-scm.com/downloads) para seu computador.

- [ ] O Git já está instalado

## Extensões do Visual Studio Code

Caso você tenha optado por utilizar o visual studio code como IDE, será necessário baixar algumas extensões para facilitar o desenvolvimento:

Para isso, selecione Extensions no menu do canto superior esquerdo do VS Code. Procure e instale as seguintes extensões:

1. Python
2. Pylance
3. Python Indent
4. **Caso esteja utilizando o docker:** Dev Containers

### Dicas para uso da extensão Dev Containers:

Para acessar o container pelo visual studio, faça o seguinte procedimento:

1. Com o container rodando na sua maquina, digite Ctrl+Shift+P, este comando ira carregar uma janela na parte superior da IDE 
2. Digite/Selecione a opção : Dev Containers: Attach to running container..
3. Selecione o container que voce subiu para realizar o curso



## Clonar o repositório

Para finalizar a etapa de configuração de ambiente, clone o repositório para seu ambiente local, onde será realizado o guia:

`git clone https://github.com/{{ InserirSeuNomeDoUsuarioGithub }}/guia-introducao-python.git`

Você também pode baixar ou clonar o repo via SSH na pagina inicial do repositório.

- [ ] O repositório já está na minha máquina

---

## Vamos começar!

<img src="https://i.giphy.com/media/xT39Db8zIOODTppk08/giphy.webp" width="350" height="350" />

Com seu ambiente de programação configurado, vamos começar.
Para continuarmos, execute no terminal, dentro do repositório do projeto, os seguintes comandos:

1. Commitar as mudanças:

   `git commit --allow-empty -m "#001 - Configuração do ambiente"`

**Nota** : Não modifique a mensagem do commit em nenhuma parte deste guia, pois poderá inteferir em sua execução automática .

2. Enviar para o repositório do github:

   `git push`

Após o push, será gerado um nova issue automaticamente pelo github com sua proxima tarefa. Aguarde aqui. 
