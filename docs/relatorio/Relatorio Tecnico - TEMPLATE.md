# Informações do Projeto
`TÍTULO DO PROJETO`  

Security Virtual Classes

`CURSO` 

Ciência da Computação - PUC-MG

## Participantes

| Augusto Guerra de Lima
| Eduardo Soares Castilho
| Gabriel Méro de Omena
| Samuel Correia Pedrosa
| Vinícius Vasconcelos Vargas
| Wanderson Teixeira dos Reis Junior

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

A facilidade que a web trouxe para todas as pessoas gera uma forte oposição com a realidade da segurança de seus dados pessoais, atualmente fazer compras pela internet, manter contato online com seu círculo social, curtir posts de assuntos que gostamos, anda de modo intrínseco com a divulgação de dados bancários, exposição de assuntos íntimos e o processo de arquitetar um perfil de usuário, representando metódicamente cada um dos membros conectados. Observando isso, pode-se concluir que os dados de pessoas nunca estiveram circulando por todos os cantos, e nunca estiveram tão inseguros, nunca foi tão fácil que eles caissem na mão de mentes desocupadas. Conclusão essa que foi potencializada, pela pesquisa realizada pelo grupo, que concluiu que a maioria das pessoas pensam estar mais seguras do que realmente estão.

## Objetivos
Inicialmente, o objetivo geral é arquitetar um software com caráter informativo, para deixar os usuários mais equipados, com conhecimentos mais robustos, permitindo que eles mesmos façam um policiamento de como usam a rede e mantenham suas informações preservadas.
Os objetivos específicos são trazer todas essas informações em módulos, organizados em níveis, para que os usuários tenham uma base sólida em segurança e possam evoluir constantemente. Ademais, outro objetivo específico está em criar uma rede de usuários, para discutir entre si e potencializar o caráter informativo. Outrossim, um objetivo futuro está na implementação de mecanismos de segurança no software.

## Justificativa
Acreditamos que o tema segurança digital é de grande importância na modernidade, visto que as pessoas confiam cada vez mais informações à intenet, mas não se protegem devidamente, deixando esse conteúdo exposto e criando uma falsa sensação de segurança. Há ainda uma grande gama de pessoas que não se preocupam tanto com a segurança na Internet e que não sabem o valor da informação que oferecem. Além disso, alguns membros do projeto pretendem seguir com a área de segurança cada vez mais.

## Público-Alvo
O público-alvo do projeto, inicialmente era bastante abrangente, no entanto ele foi filtrado para chegarmos à um público-alvo seleto: As pessoas fundamentais para o SecurityVC são as que já têm um contato frequente com a internet, e constantemente utilizam seus dados online, essas pessoas no geral prezam por sua segurança e sabem que seus dados muitas vezes podem não estar tão seguros.
Em segundo lugar, as pessoas importantes para o projeto, são as que de fato, não têm noção sobre como utilizar as redes a seu favor, não entendem nada de segurança, acreditamos que os módulos do software darão à elas uma base solida para começarem a entender segurança, nesse ponto estão pessoas mais velhas que não estão muito familiarizadas com a tecnologia, ou pais de crianças que por muitas vezes deixam seus aparelhos nas mãos dos pequenos, tornando o dispositivo um alvo fácil sob qualquer clique descuidado.
Por fim, as pessoas influentes são as que usam assiduamente o mundo online e querem entender mais de segurança, acreditamos que o forum será um local ideal para esses usuários.
 
# Especificações do Projeto
Para identificar as Personas do projeto foram realizadas entrevistas, presenciais para ter um maior contato com o público e online para fazer estatísticas melhores e traçar o perfil dos usuários com maior facilidade.

## Personas e Mapas de Empatia
As Três personas projetadas foram baseadas nos públicos alvos, fundamentais, importantes e influenciadores. Dessa forma traçamos os seguintes perfis, personas e mapas de empatia:

![PMGCC-T - G3 - Falta de segurança com dados pessoais](https://user-images.githubusercontent.com/103451503/163690906-a3ab9ebd-5fad-497c-876f-043a9024d101.jpg)
![PMGCC-T - G3 - Falta de segurança com dados pessoais (1)](https://user-images.githubusercontent.com/103451503/163690927-19fffbc3-711e-4aa3-b672-16c3399b1d51.jpg)
![PMGCC-T - G3 - Falta de segurança com dados pessoais (2)](https://user-images.githubusercontent.com/103451503/163690948-304dd653-e7d1-4e99-aee5-4128ea4d7aa6.jpg)



## Histórias de Usuários
Aqui estão as histórias de usuário, ou seja, quem, o que e porquê:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                       |
|--------------------|------------------------------------|----------------------------------------------|
|Maria               | Aprender de forma gradual          | Fazer compras e navegar com mais segurança                 |
|Maria               | Aprender sobre segurança em vendas online      | Poder comprar em sites e indicar sites de vendas online                 |
|Rogério             | Tirar as suas duvidas sobre segurança | Rogério irá melhorar seu conhecimento em segurança |
|Rogério             | Aprender segurança em sites | Deixar seus sites mais seguros |
|Anderson            | Conseguir uma base sólida em segurança    | Anderson vai sair do zero e poder navegar com consciência|
|Anderson            | Suporte técnico                 | Ajuda o Anderson a não cometer erros|
|Administradores     | Monitoramento de fórum             | Poder avaliar a veracidade das informações   |
## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Módulos iniciais com base sólida | ALTA | 
|RF-002| Módulos diversos sobre segurança | ALTA |
|RF-002| Discussões no fórum | MEDIA |
|RF-002| Suporte técnico nos fóruns | MEDIA |
|RF-005| Módulos específicos sobre assuntos específicos  | BAIXO |
|RF-006| Mecanismo de segurança  | BAIXO |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Sistema voltado ao mobile principalmente | ALTO |
|RNF-002| Redirecionamento de dicas para sites seguros | ALTO |
|RNF-003| Usuário deve conseguir baixar os arquivos anexados |  MÉDIA | 
|RNF-004| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir:

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| Ainda não pode ser implementado um mecanismo de seguranças próprio|

# Projeto de Interface
No primeiro sprint foram criadas as primeira wireframes, tanto mobile quanto desktop, utilizamos o conceito de mobile first e além disso foi desenvolvido o user flow que será apresentado nessa parte:

## User Flow
![userflow](https://user-images.githubusercontent.com/103451503/163727344-e1c850b3-d46e-4aac-a310-8bb403617a6e.png)

## Wireframes
Wireframes Mobile:
![pngs](https://user-images.githubusercontent.com/103451503/163727050-68d6ed76-f1e2-4876-b328-dc0c5d52a3fe.png)
![Cadastro_Mobile](https://user-images.githubusercontent.com/103451503/163727065-83c6e7bc-a269-4103-a6c2-1e4159ba692e.png)
![Fórum_Mobile](https://user-images.githubusercontent.com/103451503/163727067-f6c43713-3262-433f-ba62-4aa38c5eca0f.png)
![Login_Mobile](https://user-images.githubusercontent.com/103451503/163727080-54e1c3be-da1e-4e95-8fb8-40a040574f3e.png)
![Módulos_Mobile](https://user-images.githubusercontent.com/103451503/163727085-c9d9479a-154a-4059-91fa-82234255acff.png)
![Módulos-2_Mobile](https://user-images.githubusercontent.com/103451503/163727090-f48359c2-59d6-4142-9e45-7f239e87d1ca.png)
![Perfil_Mobile](https://user-images.githubusercontent.com/103451503/163727094-bbd46d09-9a97-4ba7-80c5-a234b26c9a97.png)
![Perfil-alt_Mobile](https://user-images.githubusercontent.com/103451503/163727095-42e3f425-37bc-44f6-b506-4855f17be300.png)

Wireframes Desktop:
![Cadastro_Desktop](https://user-images.githubusercontent.com/103451503/163727108-c922e3cd-139b-4338-9d16-c02b380e7631.png)
![Fórum_Desktop](https://user-images.githubusercontent.com/103451503/163727112-3e33d8a2-92f5-4486-bf8b-087b8ace1465.png)
![Home_Desktop](https://user-images.githubusercontent.com/103451503/163727114-b884e376-48a3-48b5-bbcc-8d725ad954af.png)
![Módulos_Desktop](https://user-images.githubusercontent.com/103451503/163727115-7596d25b-5243-45f7-aa8a-d46c7379a507.png)
![Módulos-2_Desktop](https://user-images.githubusercontent.com/103451503/163727118-3437fec0-814d-4667-81df-edb0ae6a2509.png)
![Perfil_Desktop](https://user-images.githubusercontent.com/103451503/163727124-98662b24-a37a-4ea5-931f-f642f6096a26.png)
![Perfil-alt_Desktop](https://user-images.githubusercontent.com/103451503/163727125-f259b8a7-1397-41d7-96d7-66f19ef7450a.png)


# Metodologia
Durante o desenvolvimento do projeto, algumas metodologias foram aplicadas para otimizar o processo, sendo a primeira de todas, para idealizar o projeto, o brainwriting, onde todos colocaram ideias que eram cada vez mais melhoradas pelos membros do grupo. A segunda foi um processo de metodologia ágil, o scrum, onde o grupo dividiu em pequenas etapas o que seria feito, cada membro do grupo selecionou uma parte para ser responsável. Além disso, foram feitas reuniões diárias onde todos apresentavam o que foi feito e também para melhorar as criações.
Portanto, a metodologia ágil foi muito importante para finalizar o primeiro sprint, onde foram feitos o design thinking (outra metodologia) e os wireframes do projeto.

## Divisão de Papéis
A divisão de papéis no primeiro sprint não foi absolutamente rigorosa, já que houve atuação mutua dos membros em todas as etapas como o design thinking, as entrevistas, a construção dos primeiros wireframes e a estilização. No geral a divisão do grupo seguiu dessa forma:
Todos os membros - Entrevistas presenciais e estilização de wireframes
> - Augusto - Criação do formulário online, estatísticas, criação da logo, documentação parcial do projeto, desing thinking e estilização dos wireframes;
> - Eduardo - Entrevistas, desing thinking;
> - Gabriel - Entrevistas presenciais, desing thinking, estruração dos wireframes via Figma, concepção do estilo do software, estilização mobile e desktop;
> - Samuel - Concepção inicial do projeto, entrevistas, rascunho de wireframes, documentação parcial do projeto, desing thinking e estilização dos wireframes;
> - Vinícius - Entrevistas, rascunho de wireframes, estruturação dos wireframes via Figma, estilização dos wireframes;
> - Wanderson - Entrevistas presenciais, criação do nome do projeto, design thinking, rascunho e estilização dos wireframes, slides para apresentação do pitch.



## Ferramentas
| Ambiente  | Plataforma | Link de Acesso |
|-----------------------------|------|---------------------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVOB3aP5E=/                       | 
|Wireframe                    | Figma| https://www.figma.com/team_invite/redeem/P4MapzLJTu09rqinnRcIOS | 
|Apresentação                 | Canva| https://www.canva.com/design/DAE94m1Gfco/31HtabSIQlP8AOHyAjtbqQ/edit | 


## Controle de Versão

As versões serão atualizadas da seguinte maneira:
Alpha - Versão Inicial, atualização de bugs e recursos visuais simples
1.2 - Atualização com novas features e mais otimizadas
2.0 - Atualização parcialmente estável e mais otimizada
3.0 - Versão Final, atualização final, testada e estável (master)

> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
>As tags utilizadas para as atualizações seguem essa convenção:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> O projeto adotará as seguintes tags para atividades:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
> - `root`: uma modificação na base do sistema

# Projeto da Solução
O projeto de solução foi desenvolver um site de ensino capaz de ensinar usuários a se protegerem durante a navegação na web. Concordantemente, o software contempla uma página de módulos capaz de fornecer informações de forma gradual e uma página de fórum capaz de estabelecer a comunicação entre os usuários.

## Tecnologias Utilizadas
> - HTML - Para estruturação das páginas
> - CSS -  Para a personalização das páginas
> - Java-Script - Para a dinâmica das páginas 
> - Bootstrapt - Para facilitar a estruturação das páginas
> - Visual Studio Code - Para desenvolver o projeto com as linguagens
> - Github - Para repositório de códigos e versões do projeto final
> - Heroku - Para a hospedagem do projeto
> - Discord - Para reuniões remotas


## Arquitetura da solução
![arq](https://user-images.githubusercontent.com/103451503/177059018-78c74c48-a7f4-467e-b66b-477f390fac2a.jpg)

# Avaliação da Aplicação
|Cenário|Aplicação|
|---------|-----|
|Usuário acessa por dispositivo mobile|Aplicação totalmente responsiva|
|Usuário entra na aplicação para aprender| Módulos com conteúdos sobre segurança|
|Usuário entra na aplicação para comunicação no fórum| Atentido parcialmente|
|Usuário deseja ver seu perfil| Página de perfil do usuário|

## Plano de Testes
|Cenário|Grupo testado|Detalhes|Sucesso|
|-------|-------------|--------|-------|
|Mobile|Usuários com mais atividade em dispositivos mobile|Aplicação totalmente responsiva|SIM|
|Aprendizado por módulos|Usuários iniciantes em segurança|Módulos com conteúdos sobre segurança|SIM|
|Comunicação por fórum|Usuários intermediários e avançados|Fórum de discussões e dúvidas sobre segurança|NÃO|
|Visualização de Perfil|Todos|Usuário pode visualizar seus dados|SIM|
|Suporte técnico|Todos|Página de suporte técnico para dúvidas|NÃO|

## Registros de Testes
A principal parte da solução estava no conteúdos dos módulos, que foi adicionado e está funcional, além disso é possível adicionar mais conteúdos no JSON criado, portanto essa é uma das metas da próxima iteração. O processo de cadastro, login e visualização de perfil foram completados, para tornar melhor esses eventos é desejado inserir mais opções de personalização do perfil. A página de fórum da aplicação atendeu parcialmente os requisitos, devido ao fato de apresentar uma estruração fiel a dos wireframes e até conter uma alocação de dados, mas o desenvolvimento de um métodos responsável por inserir novas discussões ainda está pendente.
Por fim, na iteração que se segue, é necessário otimizar a relação e dinamica entre as páginas, objetivando uma experiência mais orgânica aos usuários.

# Referências

> - BOOTSTRAP. Bootstrap.The most popular HTML,CSS and JS library in the world.Disponível em: https://getbootstrap.com/. Acesso em: 16 de abril de 2022;
> - FLANAGAM, David, JavaScript: The Definitive Guide .Edição 2. O'Reilly & Associates. 1997; 
> - KALLE HALLDEN, How To Become Invisible Online.Disponível em: https://www.youtube.com/watch?v=S4E4yAktjug, Acesso em: 23 de junho de 2022.
