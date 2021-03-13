# Diário de aulas de Git Essencial

### Aula 1 
- 

### Aula 1 v2 (27/02/2021 09:00 ~ 10:30)

- Criação do repositório no GitHub
- Inicialização de um versionamento em um projeto (`git init`)
- Adição de um repositório remoto à um projeto local (`git remote add origin http://github.com/....`)
- Commmit de alteração de conteúdo (`git commit`)
- Subimos alterações (`git push origin branch`)
- Trouxemos alterações da branch no repositório remoto (`git pull origin`)
- Aprendemos a clonar um repositório (sem especificar nome, especificando nome e dentro de uma pasta vazia)

### Aula 2 (28/02/2021)

- Criar branches:
    - Criar e mudar para a branch criada (`git checkout -b nova-branch`)
    - Criar SEM mudar para a branch criada (`git branch nova-branch`)
    - Alternando entre branches (`git checkout nome-da-branch-que-quero`)
    - Fazendo merge de branches locais/trazendo alterações de outra branch para a branch atual (`git merge nome-da-branch-que-quero`)
    - Fazendo merge de branches remotas/trazendo alterações de outra branch remota para a branch atual (`git pull origin nome-da-branch-que-quero`)
    - Corrigindo conflitos de alterações
    - Entendendo que posso ter N branchs locais mas não preciso ter as mesmas remoto se não quiser

### Aula 3 (06/03/2021)

- Ferramentas GUI para GIT (Graphic User Interface)
    - Pros
        - Apresentação amigável
        - Botões que executam ações que normalmente vc terira que digitar
        - Mostra visualmente o que está acontecendo (às vezes)
    - Contras
        - Se vc só utilizar GUI pode serque não se acostume a utilizar CLI
        - Pode ficar refém de botões
        - Nem sempre resolve todas as necessidades pois às vezesé necessário algum 'macete' que só o CLI te traz
    - Algumas Ferramentas
        - https://git-scm.com/downloads/guis

- GIT CLI (Command Line Interface)
    - Recursos avançados
    - Mais flexibilidade no manejo das ações
    - Traz mais profissionalismo para si

### Aula 4 (13/03/2021)

- Usando ferramentas gráficas junto com o CLI
    - Commit, pull, fetch, push, stash
- Mostrando rollback progressivo
    - Voltando um arquivo à um ponto específico do hsotórico