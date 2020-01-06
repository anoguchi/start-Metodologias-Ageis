## O que é o Scrum?

O Scrum é um framework ágil e sua principal característica é trabalhar com time-boxes: caixas de tempo cujo tamanho, uma vez definido, não muda durante a Sprint atual.

## O que é uma Sprint (ou iteração do Scrum)?

Sprint é a time-box básica do Scrum. Ela é o tempo que o time tem para agregar valor para o usuário do projeto.

O que perdemos ao escolher um mês de duração da Sprint, em vez de uma semana? Quanto maior o Sprint, menos chances de feedback temos e, portanto, maior o risco de errarmos o que precisa ser feito.

---

## Review Meeting

Mesmo com o feedback que o PO dá ao longo da Sprint, tudo o que foi produzido pode ainda não ser bem o que o usuário final quer. Pensando nisso e na construção de um relacionamento pessoal entre time e cliente ou usuário, temos um momento na Sprint em que ambas as partes participam: a Review Meeting.

Na reunião de Review, mostra-se para o cliente e, se possível, o usuário homologa tudo o que ficou **pronto** na Sprint. Além de cliente e usuários convidados, todos os membros do time participam dessa reunião: desenvolvedores, Scrum Master e Product Owner.

A mecânica é geralmente bem simples. O usuário final experimenta cada uma das funcionalidades que o time terminou na Sprint e dá feedback. Esse feedback é variado, afinal o cliente pode dar ok, encontrar bugs e até mesmo pensar em melhorias ou novas funcionalidades.

O PO nesse momento, toma notas desses itens e os adiciona ao Product Backlog na prioridade que lhes couber. Mesmo um bug pode não ser tão importante a ponto de entrar no topo das prioridades: pode ser que valha a pena adiar a correção de um bug não-impeditivo para colocar uma feature que agregue mais valor no lugar.

Ao fim da reunião, definimos se o Sprint foi bem-sucedido ou mal-sucedido, de acordo com a meta definida na Planning Meeting.

Definição de Pronto
Um detalhe importante do Scrum nesse momento é definir o que levar para o cliente validar. O time deve levar apenas os itens prontos para o usuário validar. Mas a questão que surge é: o que é "pronto"?

A Definição de Pronto é a sequência de passos que um item a ser desenvolvido tem que passar, desde o zero até estar Pronto para mostrar para o cliente. A Definição de Pronto varia de projeto para projeto, de time para time, de momento em momento do projeto. Exemplos de Definições de Pronto são:

Desenvolvido + Testado Manualmente
Análise + Desenvolvimento + Em homologação
Teste de aceitação + desenvolvimento + code review + aprovação
Quanto mais completa a Definição, mais trabalho existe para ter itens prontos na Review, mas também implica em menos chances de bugs e falhas de entendimento chegarem à Review Meeting. Quanto menos completa, mais itens serão levados à Review, mas maior a chance de queda na qualidade.

Apenas lembre-se: seja lá qual for a Definição de Pronto do seu time, ela precisa estar clara para todos os membros do time, a todo momento!

---

## Retrospectiva

O último timebox dentro de uma Sprint é o que chamamos de reunião de Retrospectiva. Em toda Sprint, problemas acontecem e sempre temos como crescer e melhorar. Para isso, contudo, é necessário parar e pensar em o que foi legal, para mantermos, e no que não foi bom, para mudarmos.

A ideia de uma Retrospectiva é pôr em prática o conceito de melhoria contínua. Nessa reunião, o time todo (PO, Scrum Master e Desenvolvedores) se foca em descobrir como melhorar ainda mais o time, o processo e o projeto já na próxima Sprint.

Há diversas mecânicas para essa reunião. Para saber mais sobre elas, você sempre pode olhar referências como o blog Fun Retrospectives ou a Retrospectives Wiki. Aqui, vamos mostrar um modelo básico e bastante utilizado.

Nesse modelo, levantaremos pontos positivos e negativos da Sprint anterior, para aprendermos com ela. Costumamos fazer isso em silêncio, para que cada um dê a própria opinião, sem enviesar os outros.

Para os pontos negativos, buscamos entender o que aconteceu para causá-los, claro, mas mais importante do que isso, definimos ações de melhoria para que tais problemas sejam evitados (ou reduzidos) no futuro.

Similarmente, analisamos os pontos positivos e, se o time sentir necessidade, definimos também lembretes para os pontos que ainda não viraram rotina.

É comum também que durante a retrospectiva, discutam-se também os itens da retrospectiva anterior, com o objetivo de validar se os problemas se repetiram e se as ações anteriores deram o efeito esperado.

Ao final da reunião, o time possui uma lista de ações a fazer na próxima Sprint. Essa lista deve ficar visível durante o andamento da próxima Sprint, para que o time se relembre delas.

### Ações

É importante também notar que a lista de itens a fazer que sai de uma retrospectiva contém apenas ações, isto é, atividades que membros do time vão efetivamente fazer para obter algum resultado.

Note que o time não pode decidir que o cliente vá mudar seu comportamento ou que outra área da empresa vá passar a ajudá-los. Essas não são ações, são desejos de que algo magicamente vá mudar. No mundo da agilidade, isso é frequentemente chamado de wishful thinking.

Ações, por outro lado, envolvem os membros do time. Se o problema em questão é que o cliente desaparece e não conseguimos tirar dúvidas com eles:

-  desejo: o cliente vai entender a importância de estar presente
-  uma ação: o Scrum Master vai explicar as perdas e ganhos de uma maior participação do cliente
-  outra ação: em toda história daqui para a frente, haverá também o contato de quem pode sanar dúvidas dos desenvolvedores desse item em particular.

O resultado de uma retrospectiva é uma lista, preferencialmente curta, de ações que serão tomadas durante o próximo Sprint para melhorar ainda mais o time e o andamento do projeto.

### Para que serve a reunião de retrospectiva?

A retrospectiva é a maior oportunidade, em cada Sprint, de promovermos melhorias no processo, no time e no andamento do projeto que está sendo desenvolvido.

### Esperamos obter ações de melhoria ao final de cada retrospectiva. Dê dois exemplos de ação para resolver ou reduzir o seguinte problema:

Existe uma área na empresa, externa ao time, responsável pelos deploys e o time precisa de mais rapidez nos deploys de homologação para conseguir passar a fase de "Aprovação em Homologação" de seu Critério de Pronto.

Ações possíveis seriam:

-  Automatizar o processo de deploy para homologação e conversar com o pessoal de deploy para que o script seja rodado automaticamente;
-  Remover a Aprovação em Homologação do critério de pronto do time.

A primeira ação precisa de convencimento de outra equipe. A segunda, potencialmente, causará mais problemas na Review. Ambas, no entanto, são ações válidas já que dependem da ação do time, não de outras pessoas. Devemos tomar cuidado para não cairmos em wishful thinking: desejos de que, por exemplo, o time de deploy vá magicamente começar a fazer deploys mais rápido.

---

## Daily Scrum

No capítulo de Retrospectiva você aprendeu sobre essa importante ferramenta para promover melhoria contínua, mas esperar o fim da Sprint para resolver probleminhas do dia-a-dia seria um grande desperdício de tempo.

Para resolver obstáculos do dia-a-dia e para todos saberem como está o andamento das tarefas e histórias nessa Sprint, o Scrum tem ainda mais uma cerimônia. Todos os dias, no mesmo horário e no mesmo local, a equipe se reúne para responder 3 perguntas simples:

-  O que fiz desde o último Daily Scrum?
-  O que pretendo fazer até o próximo?
-  Quais problemas me atrapalharam?

O timebox para essa reunião é de apenas 15 minutos por dia e, como qualquer outro timebox, deve ser respeitado. Para isso, é importante lembrar que essa é uma reunião expositiva: o objetivo aqui não é resolver o problema, mas sim apontá-lo. Se alguém souber como ajudar, apenas indica que sabe e após o fim do Daily os interessados se reunem para conversar.

Há uma divergência de opiniões sobre quem deve estar presente nessa reunião. O Scrum Guide aponta que os desenvolvedores respondem as perguntas e o Scrum Master apenas assiste a reunião, eximindo a participação do P.O.

Na prática, vemos uma real vantagem em ter o P.O. presente nessa reunião, já que ele precisa saber do andamento da Sprint, entender os problemas que estão desacelerando desenvolvedores e ainda ajudar a alterar o plano de ação, se o time estiver atrasado. Assim, recomendamos fortemente que o P.O. esteja, sim, presente nessa reunião.

Com o Daily Scrum, o time evita com que problemas durem muitos dias e que desenvolvedores façam trabalhos repetidos - tanto trabalhando sobre uma mesma feature, quanto sofrendo para resolver um problema que outro sabe solucionar.

---

## Planning Meeting

No Scrum, toda Sprint começa com uma reunião para entendermos os itens a serem feitos, planejarmos o que cabe no tempo disponível e definirmos a meta para o time nessa Sprint. O time todo (todos os desenvolvedores, Product Owner e Scrum Master) participa dessa reunião.

O timebox dessa reunião é de 5% do tempo total da Sprint, isto é, temos 4 horas para planejar o que será feito em uma Sprint de duas semanas. E, como qualquer outro timebox, ele deve ser estritamente respeitado.

Em preparação para essa reunião, o P.O. já deve ter olhado as histórias mais prioritárias do projeto, confirmando o entendimento delas com o cliente, melhorando sua clareza, quebrando grandes funcionalidades em partes menores que já agreguem valor para o cliente, etc. Esse processo é conhecido como grooming, ou refinamento, do topo do Product Backlog.

É importante que o P.O. já tenha feito esse processo antes do Planning começar, para que o timebox seja suficiente para essa reunião!

### Mecânica da reunião

Existe uma certa divergência dentro da comunidade ágil sobre como essa reunião deve acontecer, mas isso é menos importante já que o Scrum é um framework, isto é, foca em o que fazer em vez de como fazê-lo. A forma mostrada aqui é uma das várias utilizadas mundialmente.

A reunião começa com o P.O. explicando o item de maior prioridade da visão de negócios, isto é, da perspectiva do usuário/cliente da aplicação. Então, os desenvolvedores tiram dúvidas de entendimento com o P.O., quebram a funcionalidade em sub-itens técnicos e discutem em alto nível sobre as dificuldades de implementação desse item, apenas o bastante para conseguirem atribuir a ele uma estimativa de esforço.

Esse processo se repete com o próximo item mais prioritário ainda não estimado, o próximo, o próximo, etc... mas só até passar um pouco do que o time historicamente consegue fazer em uma Sprint!

Então, os desenvolvedores e o P.O. negociam quais desses itens mais prioritários realmente serão feitos na próxima Sprint e, assim, definem o Sprint Backlog: a lista priorizada das histórias (itens de negócio) e tarefas (sub-itens técnicos) que o time planeja fazer nessa Sprint.

Uma vez que o Sprint Backlog foi decidido, o time olha para as histórias selecionadas e cria uma meta: uma frase que exprime o maior valor que esse Sprint vai trazer para o usuário! Vale qualquer frase que mostre para os desenvolvedores o que está em jogo e como um Sprint bem sucedido vai impactar positivamente na vida dos usuários da aplicação.

Resumindo, como o nome já indica, na Planning Meeting o time faz o planejamento do que será feito na iteração. Antes de começar a reunião, o PO traz o Product Backlog já priorizado e com histórias mais prioritárias já refinadas e, ao final do Planning, o time tem em mãos a lista de histórias a serem feitas, as tarefas para cada uma delas e uma meta motivante.

### Para que serve o planning meeting e qual a duração dessa reunião, assumindo um Sprint de uma semana?

No Scrum, toda Sprint começa com uma reunião para entendermos os itens a serem feitos, planejarmos o que cabe no tempo disponível e definirmos a meta para o time nessa Sprint. A reunião consome 5% do tempo da Sprint então, para Sprint de uma semana, a reunião dura no máximo 2 horas.

### Com base no que estudamos nestas últimas video-aulas, você conseguiria descrever em linhas gerais como é usualmente, o processo da reunião de planejamento (sprint planning)?

-  Enquanto não passar um pouco do que o time consegue fazer na Sprint:
   -  P.O. explicando o item de maior prioridade da visão de negócios;
   -  Desenvolvedores tiram dúvidas de entendimento e o discutem tecnicamente;
   -  Desenvolvedores atribuem uma estimativa de esforço à história.
-  Desenvolvedores e P.O. negociam o Sprint Backlog
-  Time todo monta uma meta para a Sprint

---

## Product Backlog, Sprint Backlog e suas partes

### Product e Sprint Backlogs

No capítulo passado comentamos que o P.O. deve chegar à reunião de Planning com o topo do Product Backlog devidamente atualizado, isto é, com os itens mais relevantes para o negócio, já granulares o bastante para caber no Sprint. Falamos também que sairemos de cada Planning Meeting com um Sprint Backlog. Faltou, no entanto, estudarmos mais a fundo o que é o Product e os Sprint Backlogs e quais regras do Scrum se aplicam a eles.

### Product Backlog

Assim que imaginamos um projeto, já temos uma lista de funcionalidades que gostaríamos de ter nele! Essa lista é frequentemente usada para decidir se o projeto realmente será desenvolvido e, quando vamos começar a transformar esses desejos em realidade é importante fazê-lo de forma consciente, para maximizar o valor produzido a cada interação.

O Product Backlog, a lista ordenada de itens a serem feitos no projeto, é o artefato que ajuda o P.O. a manter todos esses pedidos organizados. O P.O. é responsável por mantê-lo atualizado e priorizado de modo a agregarmos o máximo de valor possível para o cliente a cada iteração.

Embora clientes, usuários e o próprio time tenham a liberdade de influenciar mudanças no Product Backlog, a única pessoa que de fato o altera é o Product Owner -- inclusive, o papel é chamado dessa forma porque o P.O. é dono do Product Backlog! Os itens do Product Backlog são sempre mutáveis: o P.O. pode adicionar itens, removê-los e re-priorizá-los sempre que achar que consegue agregar mais valor ao projeto dessa forma.

A proposta do Product Backlog é, também, que evitemos colocar trabalho em itens pouco importantes ou que sequer sabemos se serão feitos: os itens mais prioritários de um backlog têm que ter sua importância de negócio estudada e ser pequenos o bastante para que o time estime e os aloque em Sprints, mas os mais distantes e menos prioritários podem permanecer em blocos maiores e mais grosseiros, que serão refinados conforme sua prioridade cresce.

### Sprint Backlog

Uma vez que itens cheguem ao topo do Product Backlog, eles serão discutidos em uma Planning Meeting, quebrados em alguns sub-itens técnicos e, se escolhidos para serem executados, esses itens e sub-itens comporão o chamado Sprint Backlog: a lista ordenada de itens funcionais e seus sub-itens técnicos que serão feitos durante essa Sprint.

Diferente do Product Backlog, apenas o time pode influenciar e alterar o Sprint Backlog. Existe uma razão para isso: o Sprint Backlog é formado dos itens mais prioritários do Product Backlog e é uma indicação séria de problemas sistêmicos se os itens mais prioritários precisarem sofrer grandes modificações. Se os itens mais prioritários não fizerem sentido nas, digamos, 2 semanas de Sprint, isso indica que o P.O. não fez um bom trabalho de refinamento e de descobrir com usuários o que eles realmente precisam.

### Histórias e tarefas

Cada item que compõe um Product Backlog representa uma funcionalidade, algo que agrega valor para o usuário final -- note, portanto, que "documentação técnica" não é um item válido, já que o usuário não se beneficia disso.

Esses itens podem ter o formato que você quiser -- por exemplo, um conjuntinho de casos de uso do sistema pode ser um item válido. Há uma forte preferência entre agilistas, no entanto, de usar um formato especial para representar esses itens: uma história de usuário (user story).

Uma história é um formato criado em eXtreme Programming (XP) para representar um item que agrega valor a usuários e agrega, de uma forma bastante simples, três informações importantíssimas para a priorização e posterior desenvolvimento da funcionalidade: por que é importante, para quem é importante e, só então, o que a pessoa quer, em si. O modelo que costumamos preencher é o seguinte:

```
[TÍTULO]
**Para...** [por que o pedido é importante]
**No papel de...** [para quem é importante]
**Quero...** [o pedido em si]
```

Em um sistema de vagas online como o OndeTrabalhar.com, por exemplo, poderíamos ter a história:

```
VAGAS POR LOCALIDADE
**Para...** não perder tempo olhando cada vaga para descobrir se é na minha cidade
**No papel de...** pessoa procurando trabalho
**Quero...** ter a opção de filtrar as vagas de trabalho por cidade
```

Durante o Planning é comum verificarmos o entendimento da história quebrando ela em itens menores, técnicos, que não necessariamente agregam valor ao usuário individualmente. Esses sub-itens técnicos de histórias são chamados tarefas. A história acima poderia ser quebrada nas seguintes tarefas:

-  Cadastro de cidades no banco de dados;
-  Mudança no formulário de postagem de vaga para limitar à lista de cidades;
-  Filtro de busca de vagas no menu principal.

Muito comumente também, embora não seja regra, é vermos histórias em cartões (fichas pautadas) e tarefas em post-its.

Como o Scrum não se limita a projetos de software, vamos exercitar esse pensamento fora da caixa: nosso projeto aqui é a sua casa dos sonhos!

### Escreva uma história

Escreva uma história que descreva sua Sala de Estar, sem esquecer de seguir o formato da história que vimos em aula: comece pelo porquê, siga se identificando e termine, aí sim, com o que você quer na sua sala. Para isso, complete o template abaixo:

**Sala de Estar**

**Para...** receber meus amigos para degustar queijos e vinhos com conforto

**Eu, como...** morador

**Quero...** uma sala de estar de 20m², com carpete de madeira, grandes almofadas soltas pelo chão, uma mesinha central retrátil, uma mini adega para 6 vinhos e sistema de som ambiente.

### Quebrando histórias em tarefas

Considere a seguinte história:

**Mesinha retrátil**

**Para...** ter onde colocar petiscos sem medo de que alguém vá pisar neles

**Eu, como...** morador que gosta de receber visitas

**Quero...** uma mesinha central que fica escondida na maior parte do tempo, mas emerge do chão quando necessário.

Lembrando que tarefas são subitens técnicos de uma história, quebre essa história em tarefas que poderiam ser desenvolvidas preferencialmente paralelamente por membros do time.

Tarefas poderiam ser:

1. mesa em si;
2. mecanismo de esconder a mesa;
3. ligação do botão para expor a mesa.

---

## Scrum Master

### Papéis: Scrum Master

Assim como o Product Owner, há outro papel que é executado por uma pessoa: o de Scrum Master. Enquanto o P.O. foca no produto a ser desenvolvido e em atender as necessidades do cliente, a função principal do Scrum Master é focar no processo e se assegurar que o time esteja tirando o maior proveito possível dele.

Como o próprio nome diz, a pessoa que tem o papel de Scrum Master tem que entender muito bem o Scrum e ser capaz de passar isso para todos os envolvidos no projeto: desenvolvedores, Product Owner, clientes e a própria organização na qual o time está inserido.

O Scrum Master não é, contudo, chefe do time e não deve agir como tal. Um bom Scrum Master é um facilitador e coach excelente, que atua como Líder Servidor, isto é, livrando o time dos problemas que o impede de ter uma melhor performance.

O dia-a-dia de um Scrum Master
Durante o andamento do projeto que usa Scrum, o Scrum Master deve:

-  Facilitar as reuniões, quando necessário;
-  Atentar para o cumprimento dos time-boxes e explicar o porquê deles;
-  Educar desenvolvedores, product owner e clientes sobre o processo;
-  Remover ou reduzir impedimentos (não problemas!);
-  Buscar continuamente ferramentas para ajudar o time a evoluir.
-  E no que pode estar impedindo o time de melhorar sua performance.

### Evolução do papel

Note que performance é um termo muito mais abrangente que produtividade. Produzir vários incrementos é interessante, claro, mas a performance do time está, também, em decidir quais funcionalidades agregam mais valor, em evitar reuniões desnecessárias, em melhorar a qualidade da comunicação, etc.

### Problemas e Impedimentos

Há uma enorme confusão em implantações do Scrum pelo mundo sobre o que é um problema e o que é um impedimento. O mau entendimento da diferença entre eles faz com que diversos Scrum Masters se comportem mais como babás de times do que deveriam - e isso também prejudica a evolução do time.

Como Scrum Master, portanto, é importante que você deixe claro para o time a diferença entre um problema e um impedimento.

Tudo o que atrapalha o time, interno ou externo, é considerado um problema do time e, como tal, é responsabilidade do próprio time (qualquer membro, não apenas o Scrum Master!) resolvê-lo.

Se o time tentou resolver o problema e não conseguiu, isso pode ser considerado um Impedimento.

Assim, lembre-se que Scrum Master não é a pessoa que vai resolver problemas técnicos (ele nem precisa ser técnico!) ou cotidianos ("Acabou o café!"). O time deve trabalhar junto para resolver esses problemas.

```
Você, Scrum Master, evite acostumar mal o time: isso pode tirar o senso de responsabilidade das pessoas e você pode acabar se tornando uma muleta.
```

### Como é a atuação do Scrum Master nas reuniões do time?

O Scrum Master age para manter a reunião produtiva e dentro do timebox combinado. Ele não coordena reuniões como faria um chefe tradicional, apenas ajuda o time a manter o foco!

### Qual a diferença entre problemas e impedimentos? Dê um exemplo de cada!

Enquanto problemas são feitos de qualquer coisa que atrapalhe o time, eles só se tornam impedimentos quando o time tentou resolvê-lo e não conseguiu.

**Exemplos**
**Problema:** estamos há 3 sprints sem bater a meta por bugs que aparecem no meio do caminho.

**Impedimento:** o setor de infra não responde nossos pedidos (tentamos e-mail e conversa cara-a-cara) e precisamos de acesso ao serviço xpto pra prosseguir.

### Resolvendo impedimentos

De que forma você, como Scrum Master, poderia transformar o seguinte impedimento em um problema?

**Impedimento:** o setor de infra não responde nossos pedidos (tentamos e-mail e conversa cara-a-cara) e precisamos de acesso ao serviço xpto pra prosseguir.

Talvez um Scrum Master possa fazer um acordo de como serão as comunicações entre projeto e infra para que, na próxima ocasião, fique claro para ambos os times como fazer o pedido, com qual antecedência e o que esperar uns dos outros.

---

## Product Owner

### Papéis: Product Owner (P.O)

Agora que já vimos os timeboxes e artefatos do Scrum, também já falamos um bocado da atuação de cada um dos três papéis que pessoas desenvolvem no Scrum. Nessa e nas próximas sessões, faremos uma grande revisão e consolidação do conhecimento já visto até agora, focando nos papéis do Scrum.

Certamente, o papel mais comentado nas sessões anteriores é o do Product Owner. Essa terminologia é bastante expressiva e, até por isso, acabou sendo utilizada informalmente mesmo em equipes que não trabalham com Scrum, mas cuidado para não entendê-la errado: quando trabalhamos com métodos ágeis o time todo se sente responsável pelo produto que está sendo produzido e o cliente se interessa por ele, portanto a palavra Owner do nome do papel não exime o resto do time dessa responsabilidade. O P.O. é, no entanto, o dono do Product Backlog.

### O dia-a-dia de um Product Owner

Durante o andamento do projeto que usa Scrum, o Product Owner (P.O.) deve:

-  participar das reuniões;
-  responder dúvidas dos desenvolvedores sobre histórias ou indicar quem poderia respondê-las melhor;
-  deixar claro para o time qual o valor de negócios de cada Sprint;
-  obter feedback e expectativas dos diversos clientes e extrair delas as necessidades;
   manter o Product Backlog atualizado, isto é:
   -  adicionar itens novos;
      -  remover itens desatualizados;
      -  revisar a priorização do backlog constantemente;
      -  refinar histórias mais importantes em preparação para o próximo Planning.

### Refinamento do backlog

Uma dúvida frequente é o que o P.O. faz durante a maior parte da Sprint, quando os desenvolvedores estão trabalhando em incrementos de software. Há várias atividades listadas acima que tornam a disponibilidade diária do P.O. como para tirar dúvidas, repriorizar o Sprint backlog conforme necessidade, etc. Conforme o time amadurece e aprende a lidar consigo mesmo e com a organização, no entanto, é comum que esses trabalhos diminuam consideravelmente.

Algo que não diminui tanto, contudo, é o refinamento do topo do Product Backlog.

Vimos que, para que o planejamento de uma Sprint caiba nos 5% da duração da Sprint, é preciso que o P.O. saiba explicar histórias e que elas estejam em uma granularidade (tamanho) adequado para desenvolvedores conseguirem estimá-las. Portanto, para o próximo Planning correr bem, o P.O. já começa a se preparar para a reunião refinando os itens mais prioritários do Product Backlog, isto é, quebrando eles nas menores histórias possíveis e fazendo perguntas relevantes aos clientes.

Pense que a segunda história mais importante de nosso Backlog é a seguinte:

```
Opção de boleto

**Para...** atender aos pedidos de 15 pessoas que foram na conferência ano passado
**No papel de...** organização da Agile Brazil
**Quero...** oferecer a opção de pagamento em boleto no site e controlar as inscrições feitas com essa forma de pagamento no sistema.
```

Essa simples história já poderia ser quebrada em pelo menos duas menores, que individualmente já agregam valor para papéis diferentes e nem mesmo precisam ser feitos no mesmo Sprint!

```
Inscrição em boleto

**Para...** conseguir pagar minha inscrição no caixa eletrônico do meu banco
**No papel de...** participante da Agile Brazil
**Quero...** escolher pagar minha inscrição em boleto e emití-lo direto da próxima página
```

E, também:

```
Pagamentos de boleto

**Para...** não vender mais ingressos do que devia, nem menos do que podia
**No papel de...** organizador da Agile Brazil
**Quero...** reservar vagas na conferência quando alguém gerar um boleto e, ou criar a inscrição quando receber a confirmação do pagamento do gateway, ou abrir a vaga para vendas novamente, quando o boleto vencer sem ser pago.
```

Note que, graças ao refinamento, foi preciso perguntar melhor os porquês daquela história original e o que exatamente está sendo pedido. Assim, será mais fácil gerenciar essas histórias no Planning Meeting que está por vir.

### Uma pessoa só!

Outra informação importante sobre o P.O. é que ele é uma pessoa, não um comitê. A razão para isso é bastante simples: o time precisa saber quem está no comando do que será feito e, se tivéssemos diversos P.O.s correríamos um maior risco de informações conflitantes atrapalharem o time.

Assim, consideramos essas várias pessoas como clientes e tanto elas quanto o time podem influenciar o P.O., mas a palavra final e o plano de como maximizar o valor entregue pelo time é do Product Owner.

---

## Desenvolvedores

### Papéis: Desenvolvedor

Enquanto em ambientes mais tradicionais os executores das tarefas apenas fazem o trabalho que lhes é atribuido, tentando respeitar os prazos já decididos por eles e da forma como alguém definiu... essa não é nossa realidade em times ágeis.

Como vimos nos capítulos anteriores, desenvolvedores discutem histórias tecnicamente, estimam o esforço para fazê-las e negociam o que cabe na Sprint durante o planning. Daí, nos daily scrums, eles decidem qual tarefa vão pegar para si, considerando o resultado esperado da Sprint.

A vida dos desenvolvedores dentro de um ambiente ágil é mais complexa do que em um ambiente tradicional, onde eles podem apenas seguir ordens e já fazem seu trabalho. Ao mesmo tempo, as possibilidades de crescimento pessoal aqui são muitas e a autonomia dada a esse grupo é muito interessante, especialmente dado que tratamos aqui com trabalhadores do conhecimento. Em um time ágil, há espaço para criatividade no desenvolvimento.

Em resumo, no dia-a-dia dos desenvolvedores em times ágeis...

### Desenvolvedores devem:

-  Decidir a abordagem técnica para os problemas apresentados;
-  Trocar informações e ajudar os companheiros de time;
-  Estimar as histórias durante o planning;
-  Escolher sua próxima tarefa a ser feita, considerando as prioridades da Sprint;
-  Buscar a qualidade do projeto e a redução de erros.

### E desenvolvedores não devem:

-  Considerar dúvidas técnicas como impedimentos - elas são apenas problemas;
-  Esperar que alguém decida as atividades a serem feitas por eles;
-  Se recusar a aprender um pouco sobre outras áreas de desenvolvimento.

---

## O time todo

### Papéis: time todo

Vimos anteriormente que há atividades e responsabilidades que são específicas para P.O., Scrum Master ou desenvolvedores. Há também as que são responsabilidade do time como um todo.

Poderíamos citar aqui diversos itens: participar das reuniões, definir e executar ações das retrospectivas, criar e manter uma definição de pronto clara para todos, definir a duração da Sprint, manter o ambiente do time organizado e informativo, identificar necessidades de estudo, contratação, etc.

Poderíamos também dar dois passos para trás e olhar para essas ações de uma forma mais sistêmica e simplificar essa enorme lista em apenas um termo: o time é responsável por sua própria Melhoria contínua. E é por conta disso que lemos nos princípios ágeis que "As melhores arquiteturas, requisitos e design emergem de times auto-organizados."

### Uma única restrição

Os papéis de Scrum Master e Product Owner têm funções complementares em um time de Scrum e provêm uma dualidade saudável, que incentiva melhorias no processo e no produto em desenvolvimento. Quando uma pessoa acumula as duas funções, a tendência é que uma delas seja deixada de lado e que o Scrum se desbalanceie.

Isso não quer dizer que eles devem batalhar um contra o outro no dia-a-dia, mas sim que devem manter em mente o que favorece cada parte e achar, junto aos desenvolvedores, um estado que agrada ao time todo e favorece a entrega de valor para o cliente sem perder qualidade de vida para o time.

Muitas vezes ouvimos sobre o confronto ::Scrum Master x Product Owner::, mas é importante que não se leve essa palavra ao pé da letra. É meramente uma questão de acúmulo de funções e, se há mais o que fazer do que uma pessoa consegue, ela tende a abandonar um dos lados, ou a sacrificar sua própria qualidade de vida no processo.

Tanto P.O. quanto Scrum Master, contudo, podem ser também desenvolvedores, já que desenvolvedores são um grupo. Assim, ele pode se dedicar ao desenvolvimento após terminar suas tarefas do papel específico que ocupa. Nesse caso, é recomendado que as pessoas que ocupam outros papéis além de desenvolvedores não se comprometam em fazer tarefas grandes ou que não possam ser facilmente transferidas para outra pessoa, caso surja alguma atividade do seu papel principal.

### Melhoria contínua

Qualquer ponto que causa dor ao time no momento é uma oportunidade de melhoria para o futuro -- e é um treino contínuo enxergar problemas como oportunidades.

Melhoria contínua é também, na minha opinião, uma forma de pensar que nos torna mais responsáveis pelo estado em que nos encontramos no momento. É uma responsabilização que ajuda a sair do hábito de reclamar e procurar culpados. E é algo que pode ser levado para outros aspectos da vida facilmente.
