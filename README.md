# :checkered_flag: EduPlay – Plataforma Educacional de Jogos


O EduPlay é uma plataforma web educacional criada para a Asa Branca Indie Game Dev. A aplicação reunirá jogos e quizzes educativos em um catálogo acessível ao público geral, permitindo que visitantes conheçam e joguem atividades públicas. Usuários cadastrados poderão acompanhar seu progresso, pontuação, tempo jogado e conquistas. A plataforma também terá recursos específicos para alunos, professores e administradores, como participação em quizzes, organização de turmas, acompanhamento de resultados e gerenciamento de jogos e conteúdos.

---

## Membros da Equipe

* Maria Luiza Albuquerque Quinto - Redes de Computadores.


* Marcos Paulo de Sousa dos Santos - Redes de Computadores.



---

## Objetivo Geral

> Desenvolver uma plataforma web educacional responsiva para disponibilizar jogos e quizzes da Asa Branca Indie Game Dev, ampliando o acesso da comunidade a experiências de aprendizagem interativas e permitindo o acompanhamento do progresso dos usuários.
> 
> 

O EduPlay deverá possuir uma área pública para visitantes e uma área restrita para usuários autenticados. A aplicação também deverá oferecer diferentes permissões para jogadores, professores e administradores, de acordo com suas responsabilidades.

---

## Público-Alvo

A plataforma será destinada a:

* Crianças e adolescentes interessados em jogos e aprendizagem.


* Alunos que participam de atividades educacionais ou turmas.


* Professores que desejam utilizar jogos e quizzes como apoio pedagógico.


* Escolas, diretores e instituições interessadas em recursos educacionais digitais.


* Pais e responsáveis.


* Pesquisadores e pessoas interessadas em educação, tecnologia e cultura nordestina.


* Público geral que queira conhecer e jogar atividades educativas.


* Integrantes e gestores da Asa Branca Indie Game Dev.



O acesso não será limitado a pessoas vinculadas a uma escola. Visitantes poderão consultar a plataforma e jogar atividades públicas, enquanto usuários cadastrados poderão salvar seu progresso e consultar suas estatísticas.

---

## Impacto Esperado

Espera-se que o EduPlay amplie o acesso a jogos educativos e aproxime a Asa Branca Indie Game Dev da comunidade. A plataforma poderá apoiar professores e escolas em atividades de aprendizagem, além de oferecer ao público geral uma forma interativa de conhecer conteúdos educacionais e aspectos da cultura nordestina.

Também se espera aumentar a visibilidade dos jogos e projetos da Asa Branca, centralizar suas informações e criar uma base tecnológica que possa evoluir após a entrega acadêmica. Para os usuários, o registro de pontuação, tempo jogado, progresso e conquistas poderá estimular a participação e o acompanhamento da própria aprendizagem.

---

## Papéis de Usuário

### Visitante (Usuário não autenticado)

* Acessar a página inicial e informações sobre a Asa Branca.


* Consultar o catálogo público de jogos e visualizar detalhes e categorias.


* Jogar atividades disponibilizadas publicamente.


* Consultar notícias e eventos.


* Criar uma conta ou realizar login.


* O visitante não poderá salvar progresso, acessar estatísticas pessoais ou utilizar recursos restritos.



### Jogador ou Aluno (Usuário autenticado)

* Acessar o dashboard pessoal e jogar atividades disponíveis.


* Salvar pontuação, progresso e tempo jogado.


* Consultar histórico, estatísticas próprias e visualizar conquistas.


* Participar de quizzes, rankings autorizados e de uma turma quando vinculado a ela.



### Professor

* Criar ou iniciar salas de quiz e gerar códigos de acesso.


* Acompanhar participantes, consultar resultados e desempenho das turmas.


* Utilizar jogos e quizzes em atividades pedagógicas.



### Administrador

* Criar, consultar, atualizar e remover jogos, categorias, notícias e eventos.


* Gerenciar usuários, papéis e administrar informações da plataforma.


* Publicar ou desativar conteúdos.



---

## Principais Funcionalidades

### Funcionalidades Gerais e Públicas

* Visualização da página inicial, apresentação da organização e acesso a notícias/eventos.


* Consulta ao catálogo de jogos organizados por categorias com detalhes (título, descrição, gênero, imagens, etc.).


* Execução de jogos liberados para visitantes.


* Cadastro de conta e acesso à página de login.



### Funcionalidades Restritas

* **Usuários Autenticados:** Login/logout, dashboard pessoal, histórico de jogos, registro de pontuação/tempo, progresso/conquistas e participação em quizzes por código.


* **Professores:** Gerenciamento de salas de quiz, geração de códigos, e acompanhamento de resultados e turmas.


* **Administradores:** CRUD de jogos, categorias, notícias/eventos, gerenciamento de usuários e controle de publicações.


* **Sistema de Quizzes:** Entrada por código, sala de espera, perguntas (verdadeiro/falso ou múltipla escolha) com temporizador, feedback, pontuação e ranking.



---

## Entidades do Sistema

* **Usuário:** Representa as pessoas cadastradas (Nome, E-mail, Senha, Papel, Data de cadastro).


* **Jogo:** Jogos educativos disponíveis (Título, Descrição, Categoria, Gênero, Imagem, Link, Disciplina, Dificuldade, Status).


* **Categoria:** Classificação dos jogos (Nome, Descrição, Imagem/Ícone).


* **Progresso:** Registra a interação do usuário com o jogo (Usuário, Jogo, Pontuação, Tempo jogado, Percentual, Último acesso).


* **Quiz:** Atividade com perguntas e pontuação (Título, Descrição, Tempo, Status, Autor).


* **Pergunta:** Questões do quiz (Enunciado, Tipo, Alternativas, Resposta correta, Valor, Imagem, Quiz relacionado).


* **Sala:** Sessão de participação em quiz (Código, Quiz relacionado, Status, Data, Usuários).


* **Resultado:** Desempenho do usuário no quiz/sala (Usuário, Sala, Pontuação, Tempo, Colocação, Data).


* **Notícia ou Evento:** Informações institucionais (Título, Resumo, Conteúdo, Imagem, Data, Autor, Status).


> A proposta do projeto está em [`PROPOSTA.md`](PROPOSTA.md) e a documentação de entrega final em [`ENTREGA.md`](ENTREGA.md).
