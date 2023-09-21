# 1.Visão Geral do Produto
Durante a formação acadêmica em cursos de engenharia, particularmente na FGA, os estudantes são colocados em uma trilha de aprendizado intensiva com atividades e disciplinas que requerem a execução de projetos práticos. Nestes cenários, as metodologias ágeis surgem como uma opção viável para o gerenciamento desses projetos. No entanto, equipes ágeis compostas por estudantes enfrentam desafios distintos que vão além das complexidades técnicas. Muitas dessas equipes operam com um orçamento bastante limitado, o que torna difícil adquirir licenças para ferramentas de gestão de projetos robustas, como IBM Jazz, Trello ou Github Projects.

Além disso, a necessidade de utilizar várias ferramentas diferentes — muitas vezes versões gratuitas com funcionalidades limitadas — pode resultar em um ambiente de trabalho fragmentado. Isso pode acarretar em duplicação de esforços e dificuldade de manter todos os membros da equipe alinhados e informados sobre o status do projeto.

Esse cenário é agravado pelo fato de que essas equipes estão em um processo de aprendizado, implicando em maior dificuldade ao usar ferramentas cujo público alvo são equipes profissionais.


Dentro do contexto apresentado, foram analisadas as versões gratuitas das ferramentas de gestão de projetos mais utilizadas por equipes ágeis com base em um conjunto de funcionalidades julgadas pela equipe como importantes para o bom andamento de um projeto ágil. Os resultados são descritos na tabela a seguir:

| Ferramenta        | Overview/Docs | Estrutura de Requisitos | Backlog do Produto | Rastreabilidade | Métricas | Quadro Kanban | Gerência de Sprints | Cargos e Permissões | Assistência Guiada | Integração de Artefatos no Git | Calendário/Timeline | Orientado a Times Ágeis |
|-------------------|--------------|-------------------------|--------------------|-----------------|----------|--------------|---------------------|---------------------|-------------------|-----------------------------|-------------------|------------------------|
| Jira              | ✅           | ✅                      | ✅                 | ✅              | ✅       | ✅           | ✅                  | ❌                  | ❌                | 🟧                          | ✅                | ❌                     |
| Trello            | ❌           | ❌                      | ❌                 | 🟧              | ❌       | ✅           | ❌                  | ❌                  | ❌                | ❌                          | ❌                | ❌                     |
| Github Projects   | ✅           | 🟧                      | 🟧                 | 🟧              | ❌       | ✅           | ❌                  | 🟧                  | ❌                | ✅                          | 🟧                | ❌                     |
| Asana             | ✅           | 🟧                      | ❌                 | ✅              | ❌       | ✅           | ❌                  | ❌                  | 🟧                | ❌                          | 🟧                | ❌                     |
| ClickUp           | ✅           | 🟧                      | ❌                 | ❌              | ❌       | ✅           | ✅                  | ❌                  | ❌                | ❌                          | 🟧                | 🟧                     |
| Monday            | ✅           | ❌                      | ❌                 | ❌              | ✅       | ✅           | ❌                  | ❌                  | ❌                | ❌                          | ❌                | ❌                     |
| Wrike             | ✅           | ❌                      | ✅                 | ❌              | ❌       | ✅           | ❌                  | ❌                  | ❌                | ❌                          | ❌                | ❌                     |

### 1.1 Oportunidade Identificada
Diante do contexto apresentado, foi identificada a oportunidade de preencher as lacunas existentes no que diz respeito às funcionalidades oferecidas pelas versões gratuitas dos produtos acima citados. Além disso, com o enfoque na público acadêmico, há a possibilidade de integrar um aspecto educativo ao produto.

![Diagrama de Ishikawa](https://raw.githubusercontent.com/mdsreq-fga-unb/2023.2-FrameIT/docs/img/ishikawa.png "Diagrama de Ishikawa para a Oportunidade").

### 1.2 Declaração de Posição
Para estudantes que desejam utilizar metodologias ágeis e que não possuem orçamento para licenciar ferramentas pagas de gestão de projeto, o FrameIT é uma plataforma acessível para gestão de projetos ágeis. Ao contrário de soluções comerciais que possuem uma versão gratuita limitada, nosso produto disponibiliza funcionalidades essenciais de maneira mais completa e voltada para equipes que estão em processo de aprendizado, que permitem concentrar a gestão de projetos ágeis em um só lugar.

* **Qual é o produto que você se propõe a desenvolver?**
Uma aplicação projetada para auxiliar estudantes na gestão de projetos ágeis no âmbito acadêmico.
* **O que torna este produto diferente dos seus concorrentes?**
O diferencial do nosso produto está em funcionalidades educativas tais como assistência guiada, modelos pré-definidos, métricas detalhadas e personalização, oferecendo uma experiência única aos usuários.

* **Quem são os usuários-alvo e clientes do produto?**
Os usuários-alvo do produto são estudantes universitários que desejam gerenciar projetos acadêmicos utilizando metodologias àgeis, especialmente os que estão no processo de aprendizado. Os clientes podem incluir instituições de ensino superior que desejam fornecer uma ferramenta de organização e aprendizado aos seus alunos, bem como equipes individuais que buscam uma solução para suas necessidades acadêmicas.

* **Por que os clientes deveriam utilizar / comprar este produto?**
Os clientes devem utilizar o "FrameIT" porque ele oferece uma solução abrangente, com assitência guiada, eficaz e gratuita para o gerenciamento de projetos ágeis no contexto acadêmico, promovendo a aprendizagem, a colaboração e o sucesso dos estudantes.

| Pergunta                     | Resposta                                           |
|--------------------------|----------------------------------------------------------|
| Para  | Equipes ágeis compostas por estudantes |
| Quem                    | Necessita de uma ferramenta de gestão de projetos ágeis gratuita e completa|
| O FrameIT | É uma ferramenta                                 |
| Que                  | Oferece funcionalidades de gestão de um projeto ágil essenciais e voltada para estudantes |
| Ao contrário de          | Jira, Trello, Azure Boards, IBM Jazz, Asana, Monday.com, ClickUp e afins                      |
| Nosso produto       | É financeiramente acessível e disponibiliza em uma mesma ferramenta funcionalidades que não são oferecidas ou estão dispersas entre as versões gratuitas das ferramentas citadas, tais como: quadro kanban, assistência guiada, métricas detalhadas, permissões de usuário, timeline e afins|

### 1.3 Objetivos

#### Objetivo Geral
O objetivo geral do "FrameIT" é oferecer uma ferramenta de gerenciamento de projetos ágeis acessível para estudantes universitários, focada na organização de projetos acadêmicos e na promoção da aprendizagem colaborativa.

#### Objetivos Específicos
* **Assistência Guiada:** Proporcionar assistência guiada e modelos predefinidos para facilitar a criação de projetos.
* **Integração de Metodologias Ágeis:** Integrar conceitos ágeis, com foco em SCRUM e XP, no contexto dos projetos acadêmicos.
* **Colaboração:** Facilitar a colaboração entre alunos e professor, permitindo feedback  do trabalho realizado.
* **Gestão de Tempo:** Oferecer integração com o calendário acadêmico para auxiliar na gestão do tempo.
* **Personalização:** Permitir a personalização da interface por meio de temas e estilos visuais.

### 1.4 Tecnologias Utilizadas
- **Plataforma:** Aplicação Web  
- **Linguagens de Programação:** Python, Javascript/VueJs
