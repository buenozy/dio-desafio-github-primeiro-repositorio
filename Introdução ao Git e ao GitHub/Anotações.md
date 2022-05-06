# Anotações e Comandos Git

##### :arrow_right:[Link para download do Git](https://git-scm.com/downloads):arrow_left:

**Git Bash** é um terminal estendido para otimizar o uso do **Git**.

**Branch** é uma ramificação, são utilizados para desenvolver funcionalidades isoladas.

**Merge** mesclar, juntar as alterações.

**Commits** são basicamente um conjunto de mudanças.

**Git** é o sistema de versionamento em si, é onde você cria _“commits”_ e pode registrar o histórico de modificações.

**GitHub** é apenas uma das muitas centrais de repositórios remotos existentes.

##### :arrow_right:[Link com comandos do Git](https://comandosgit.github.io/):arrow_left:

##### :arrow_right:[Link guia prático Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html):arrow_left:

:arrow_down:Comandos _Básicos_:arrow_down:

- Obter ajuda: [git --help]()

- Mostra a versão do Git instalada: [git --version]()

- Lista as configurações gerais do Git: [git config --list]()

- Configura seu nome de usuário padrão no Git: [git config --global user.name "Seu Nome"]()

- Configura seu e-mail de usuário padrão no Git: [git config --global user.email "seuemail@example.com"]()

- Escolher VsCode como editor padrão: [git config --global core.editor 'code --wait']()

- Inicia um subdiretório .git para monitorar o projeto: [git init]()

- Adiciona todo o conteúdo da pasta para o monitoramento *** não altera o repositório e as alterações não são salvas até usarmos o "git commit" **: [git add . ou git add *]()

- Guarda um conjunto de alterações no histórico junto de uma mensagem: [git commit -m "comentário das alterações"]()

- **"Se você não clonou"** Esse comando faz um vinculo entre o repositório online e o local: [git remote add origin https://linkdorepositorio]()

- Empurra para o servidor as alterações realizadas: [git push origin master]() **"altere master para qualquer branch"**

- Atualiza seu repositório local: [git pull]()

- Faz uma copia do repositório remoto na sua maquina local: [git clone https://linkdorepositorio]()

  
