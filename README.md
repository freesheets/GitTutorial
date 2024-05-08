# Como usar o Git e Github na prática

Pra você que é Dev ou iniciante e não conhece o Git, é fundamental que em seus codigos esteja configurado um repositorio, aqui está o passo a passo do que é e como utilizar!

# Instalando o GIT
Link com os downloads
https://git-scm.com/downloads

# Vamos começar falando o que é o Git?
Primeira resposta o que Git e a mesma coisa que o Github? não são ferramentas distintas, mas colaboram de maneira integrada para tornar o desenvolvimento de software mais eficiente.

O Github é uma “rede social dev” em que é possível armazenar e compartilhar projetos de desenvolvimento de software.
O Git é um sistema de controle de versão de arquivos; em outras palavras, é responsável por guardar o histórico de alterações sempre que alguém modificar algum arquivo que está sendo monitorado por ele.

Desta maneira, o Git e o GitHub são pilares fundamentais que auxiliam as equipes de desenvolvimento a controlar o versionamento de código, rastrear mudanças, colaborar de forma eficiente e garantir que o trabalho em equipe flua sem problemas

segue imagem ilustrativa
![comparativo-git-github](https://github.com/freesheets/GitTutorial/assets/169274014/387c7a2c-f0ce-4d14-888a-9bfd62a69d19)

# Para que serve o Git?
Em outras palavras em uma empresa você provavelmente vai trabalhar em equipe, e apenas poder acessar o código de outras pessoas colaboradoras não é suficiente, mais do que isso, precisamos manter o histórico dos nossos arquivos e das nossas modificações.
Muitas vezes mudamos arquivos em grupo, num movimento único onde, no contexto do Git, é um commit. O que, em tradução literal para português, significa “compromisso” ou “comprometer-se” às alterações em um repositório, mas basicamente é um save point do seu codigo.

Dessa forma, podemos voltar atrás e recuperar o estado do sistema: como ele era ontem, ou no ano passado, comparar as mudanças para encontrar bugs e estudar otimizações.

Segue exemplo abaixo
![commits](https://github.com/freesheets/GitTutorial/assets/169274014/380ad775-79a3-4264-9291-36a608d53004)

OBS: Os commits são os Save Points do seu "jogo", você pode voltar e manipula-los da forma que quiser, podendo voltar, alterar ou excluir commits anteriores etc...

# Como faço para executar o Git?

Primeiramente senhoras e senhores vcs precisaram configurar o git com o github!

1 - Após a intalação do Git, em seu desktop clique com o botão direito do mouse em -> "Open Git Bash Here"
![image](https://github.com/freesheets/GitTutorial/assets/169274014/7e695477-f962-447f-9d6f-220c04c723b3)

2 - Configure seu nome de usuário e e-mail:
O Git registra quem fez cada alteração no código. Portanto, é importante configurar seu nome de usuário e e-mail. Use os comandos, no terminal:

![image](https://github.com/freesheets/GitTutorial/assets/169274014/0838d95c-15f8-4f47-93f7-060e26909590)

OBS: Utilize o seu e-mail do Github

3 - Cole o texto abaixo, substituindo o email usado no exemplo pelo seu endereço de email do GitHub, para gerar a key de conexão!

![image](https://github.com/freesheets/GitTutorial/assets/169274014/254bb807-a018-4b92-bd05-8f97d079b853)

Isso cria uma nova chave SSH, usando o e-mail fornecido como rótulo.

![image](https://github.com/freesheets/GitTutorial/assets/169274014/690c8e73-9009-4502-8849-3a733926bf57)

 Quando for solicitado a "Inserir um arquivo no qual salvar a chave", você pode pressionar Enter para aceitar o local padrão do arquivo

 ![image](https://github.com/freesheets/GitTutorial/assets/169274014/85c203c3-ecca-405b-8b40-cc220c48cb38)

 No prompt você pode digitar uma senha ou apenas pressionar Enter

4 - Com a Key gerada de maneira rapida pelo windows entre no Disco local C: => Usuarios => Seu Usuario => .ssh => id_rsa.pub (Abra com o bloco de notas e copie a chave).

![image](https://github.com/freesheets/GitTutorial/assets/169274014/9dfb6f5f-9151-4524-b24b-cee57bd5f988)

5 - Abra sua conta no Github, clique no icone do seu perfil e vá em -> Settings

![image](https://github.com/freesheets/GitTutorial/assets/169274014/0330d636-a8dd-47c8-9e31-7440ef7d69bc)

6 - Depois entrem na opção de SSH and GPG Keys

![image](https://github.com/freesheets/GitTutorial/assets/169274014/80c9a149-367a-4b02-8867-6b476e92287e)

7 Clique em New SSH Key, coleque um titulo e cole a chave dentro de Key!

![image](https://github.com/freesheets/GitTutorial/assets/169274014/84c4831e-15c1-4f97-8a42-1acd022a092e)

# Como iniciar um repositorio e subir para o Github?

1 - Abra o git bash na pasta no qual deseje subir para o Github!

![image](https://github.com/freesheets/GitTutorial/assets/169274014/1981bc8e-7904-4f61-ad5a-f3cd039cab45)

2 -  Crie um Repositório Git:

Para começar a rastrear seu código, crie um repositório Git em seu projeto. Navegue até a pasta do seu projeto e execute:

![image](https://github.com/freesheets/GitTutorial/assets/169274014/8cde18c3-5821-41d6-9214-dad0c9079cc4)

3 -  Adicione Arquivos ao Controle de Versão:

Use o comando git add para adicionar arquivos ao "staging area", que é onde você prepara os arquivos para serem “commitados” ou salvos.

![image](https://github.com/freesheets/GitTutorial/assets/169274014/2bc52399-7e4e-442b-8014-863375bb8c51)

ou digit git add . para adicionar todos os arquivos

![image](https://github.com/freesheets/GitTutorial/assets/169274014/09f98765-5e5f-483b-bffc-5e062c3f1a6e)

4 - Faça um Commit:

Um commit é seu save point. Use o comando git commit -u "" para criar um commit com uma mensagem descritiva do que foi alterado no projeto.

![image](https://github.com/freesheets/GitTutorial/assets/169274014/5cd0ad0f-4d15-48ae-bb5c-1ab9d2630049)

5 - Comando para visualizar o Histórico de Commits:

Use git log para ver o histórico de commits no repositório.

![image](https://github.com/freesheets/GitTutorial/assets/169274014/e320bb2d-eb83-49f7-bdcd-bbd0a422ceec)

6 - Crie seu repositorio no Github

![image](https://github.com/freesheets/GitTutorial/assets/169274014/c1408dbc-127f-4393-9d74-600b73178c29)

Não adicione o README file para que apareça as opção de ajuda para subir seu repositorio

![image](https://github.com/freesheets/GitTutorial/assets/169274014/0f2a63f9-1a64-4cb6-88fd-1144085677e8)

7 - Feito isso, apenas siga os comandos após o commit para finalizar o processo

![image](https://github.com/freesheets/GitTutorial/assets/169274014/c72cadc0-4381-4ef1-8e96-2d3be1cc85d6)

# Comandos Git












