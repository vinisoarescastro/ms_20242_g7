
## Sistema de Provas - ms_2024_g7

Este repositório contém o desenvolvimento de um **Sistema de Provas**, parte da disciplina **Modelagem de Software**, ministrada pelo professor **Gilmar** na **Universidade Federal de Goiás (UFG)**.

### Objetivo
O sistema tem como objetivo automatizar e gerenciar o processo de aplicação, correção e análise de provas. Ele visa fornecer uma interface intuitiva para professores e alunos, além de ferramentas para criação de provas, submissão de respostas e avaliação de desempenho.

### Estrutura do Projeto

- **Branch `main`**: Contém o código estável do projeto.
- **Branches de colaboradores**: Cada colaborador possui uma branch dedicada para desenvolvimento e integração de novas funcionalidades.

### Colaboradores

Esse projeto será desenvolvido pelos integrantes do Grupo 7:

| Matrícula  | Nome                                 | GitHub                                                |
|------------|--------------------------------------|-------------------------------------------------------|
| 202403066  | Davi Augusto Ferreira de Carvalho    | [Clique aqui](https://github.com/DaviAugusto778)      |
| 202400696  | Eduardo Divido Miranda Pereira       | [Clique aqui](https://github.com/sedivino)            |
| 202403080  | Kezer dos Santos Souza               | [Clique aqui](https://github.com/KezerSouza)          |
| 202206163  | Vinicius Soares Castro               | [Clique aqui](https://github.com/vinisoarescastro)    |

### Backlog do produto


| Código   | Descrição                                                                                                                      |
|----------|--------------------------------------------------------------------------------------------------------------------------------|
| RF001.0  | Cadastro de professores e autenticação                                                                                         |
| RF001.1  | Funcionalidade de criação de contas para professores, com login e autenticação segura.                                         |
| RF002.0  | Banco de questões                                                                                                              |
| RF002.1  | Acesso a um banco de questões estilo ENEM e vestibulares, permitindo busca por assunto, nível de dificuldade e tipo de questão.|
| RF002.2  | Funcionalidade para que os professores possam adicionar suas próprias questões ao banco.                                       |
| RF003.0  | Sistema de criação de uma prova (a prova em si, e não apenas o registro de suas notas).                                        |
| RF003.1  | Implementar interface para criação da prova, com edição de texto simples e possibilidade de inserção de imagens.               |
| RF003.2  | Permitir ao usuário importar um pdf de prova ao sistema, caso ele tenha feito a prova externamente ao sistema.                 |
| RF003.3  | Possibilitar impressão em pdf da prova feita.                                                                                  |
| RF004.0  | Geração do QR Code e arquivo PDF.                                                                                              |
| RF004.1  | Criar um QRCode que identifica o gabarito cadastrado.                                                                          |
| RF004.2  | Gerar de provas em formato PDF, com a opção de criar múltiplas versões embaralhadas das mesmas questões.                       |
| RF005.0  | Correção automatizada via Aplicativo Mobile.                                                                                   |
| RF005.1  | Criação de um template de folha de respostas própria do sistema, padronizada, para reconhecimento pelo sistema, que será colocado nas provas criadas. |
| RF005.2  | Implementar o “scan” dessa folha com a câmera.                                                                                 |
| RF005.3  | Implementar reconhecimento da folha e processamento das respostas.                                                             |
| RF005.4  | Permitir que o usuário veja e confira se o sistema reconheceu as respostas corretamente, e altere caso necessário; E então validar as respostas. |
| RF006.0  | Correção de uma prova de múltipla escolha.                                                                                     |
| RF006.1  | Criar uma interface para lançamento do gabarito.                                                                               |
| RF006.2  | Criar interface para lançamento manual das respostas de um aluno.                                                              |
| RF006.3  | Implementar lógica para calcular número de acertos e nota de acordo com o gabarito lançado no início.                          |
| RF007.0  | Registro de provas e notas já calculadas.                                                                                      |
| RF007.1  | Criar uma interface que mostra uma lista de alunos com seus respectivos acertos e notas em determinada prova.                  |
| RF007.2  | Adicionar no lançamento das respostas de um aluno um campo para colocar seu nome.                                              |
| RF007.3  | Após a correção, aluno ficará registrado com sua nota e número de acertos naquela prova.                                       |
| RF007.4  | Permitir o registro e alternância de diferentes provas.                                                                        |
| RF008.0  | Filtros e informações das notas.                                                                                               |
| RF008.1  | Permitir que o usuário filtre a ordem em que os alunos devem aparecer na lista (ordem alfabética, maior para menor nota).      |
| RF008.2  | Implementar o destaque de informações estatísticas da prova, como média de nota.                                               |

### Requisitos Não Funcionais

| Código   | Descrição                                                                                                                      |
|----------|--------------------------------------------------------------------------------------------------------------------------------|
| RNF001   | Descrição do Requisito Não Funcional                                                                                           |

### Atividades

|ID | Tarefa                                    | Data Início   | Data Fim      | Responsável   | Situação      |
|---|-------------------------------------------|---------------|---------------|---------------|---------------|
|001| Definição do Grupo                        | Indisponível  | Indisponível  | Grupo         | Concluído     |
|002| Definição do Tema                         | Indisponível  | Indisponível  | Grupo         | Concluído     |
|003| Definição do Backlog do Sistema           | Indisponível  | Indisponível  | Grupo         | Em andamento  |

### HIstórias de Usuário

| Código HU                       |Descrição                                                                                                                                                              |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.1 - Cadastro de Usuário       | COMO UM professor EU QUERO me cadastrar no sistema PARA QUE eu possa criar e gerenciar minhas provas.                                                                 |
| 1.2 - Login                     | COMO UM professor EU QUERO fazer login no sistema usando meu e-mail e senha PARA QUE eu possa acessar minhas provas e resultados.                                     |
| 1.3 - Criação de Prova          | COMO UM coordenador EU QUERO criar uma nova prova, incluindo questões de diferentes níveis de dificuldade PARA QUE meus alunos possam ser avaliados de forma justa.   |
| 1.4 - Edição de Prova           | COMO UM professor EU QUERO editar uma prova existente PARA QUE eu possa corrigir erros ou adicionar novas questões.                                                   |
| 1.5 - Geração de QR Code        | COMO UM professor EU QUERO que um QR code único seja gerado para cada aluno em suas provas PARA QUE eu possa facilitar a identificação na hora da correção.           |
| 1.6 - Design de Garabito        | COMO UM coordenador EU QUERO que o gabarito seja gerado automaticamente na prova PARA QUE os alunos possam marcar suas respostas de forma clara e organizada.         |
| 1.7 - Visualização de Provas    | COMO UM professor EU QUERO visualizar uma lista de todas as provas que criei PARA QUE eu possa rapidamente acessar e gerenciar cada uma delas.                        |
| 1.8 - Inscrição dos Alunos      | COMO UM coordenador EU QUERO inscrever meus alunos nas provas de forma rápida PARA QUE todos estejam prontos para participar das avaliações.                          |
| 1.9 - Correção Automática       | COMO UM professor EU QUERO usar o aplicativo para escanear o QR code e o garabito dos alunos PARA QUE eu possa corrigir as provas automaticamente e economizar tempo. |
| 2.0 - Geração de Relatórios     | COMO UM coordenador EU QUERO gerar relatórios com o desempenho dos alunos em cada prova PARA QUE eu possa identificar áreas que precisam de melhorias.                |
| 2.1 - Notificação de Resultados | COMO UM professor EU QUERO que os alunos recebam notificações sobre seus resultados PARA QUE eles possam acompanhar seu desempenho.                                   |
| 2.2 - Suporte ao Aluno          | COMO UM aluno EU QUERO acessar um suporte dentro do sistema PARA QUE eu possa esclarecer dúvidas sobre a prova ou sobre o processo de correção.                       |
| 2.3 - Redefinição de Senha:     | COMO UM professor EU QUERO poder redefinir minha senha caso a esqueça PARA QUE eu sempre tenha acesso à minha conta.                                                  |
| 2.4 - Feedback sobre a Prova    | COMO UM aluno EU QUERO fornecer feedback sobre a prova após a correção PARA QUE os professores possam melhorar as avaliações futuras.                                 |
| 2.5 - Acesso Móvel              | COMO UM professor EU QUERO que o sistema seja acessível em dispositivos móveis PARA QUE eu possa corrigir provas e gerenciar atividades mesmo fora da sala de aula.   |
Teste teste

