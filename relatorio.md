# Relatório Diário #

**9/10/2024: Tudo sempre se resolve melhor com HashMaps, então vou começar a ir direto para uma solução com HashMaps visando melhorar a complexidade do algoritmo.**
*Meu problema atual é mais na parte do código do que na parte do problema em si, coisa que ja sei que melhora com o tempo pois a algum tempo atrás nem na resolução eu conseguia pensar.*

**10/10/2024: Tentei um desafio médio sobre linked list, ja sabia como funcionava uma então foi mais simples de pensar na resolução, porém ainda assim tive problemas com conceitos de matemática. 
Por enquanto alguns padrões estão sendo percebidos: 1º HashMaps, 2º Conceitos matemáticos para reverter números (x % 10 && x / 10)**

**11/10/24: Fiz mais um exercicio sobre linked list, por falta de atenção acabei não vendo que o exercicio pedia para remover a partir do FINAL da lista. Resultado: acabei criando o algoritmo de remoção de acordo com o número dado pelo usuário,
tenho esse algoritmo em outro repo sobre DSA então aqui mantive apenas o da solução, preciso estudar ambos os algoritmos escritos até aqui. Talvez eu use o final de semana para revisar ou até fazer mais.**
**Ainda no dia 11: Decidi por curiosidade inverter uma árvore binária sozinho e milagrosamente eu consegui completar o primeiro leetcode 100% solo. É bobeira, porém eu fiquei relativamente feliz.**

**12/10/24: Dia Ocioso de LeetCode, Apenas vi novamente a série de video do Akita falando sobre DSA**
**13/10/24: Mais um dia organizando os estudos e fazendo estudo de mercado.**

**14/10/24: Tentei entregar mais um exercício, mas ao submeter minha solução só passou em 28 casos, aparentemente o problema ocorre quando tem mais de 2 repetições do mesmo valor, sinto que consigo resolver porém não hoje.
Amanhã farei 2 para compensar.**

**15/10/24: Mais padrões percebidos em exercicios envolvendo linkedLists.**

**16/10/24: Mais uma vez eu consigo resolver o problema, porém na hora de traduzir em código eu falho :/**

**17/10/24: Parei para refletir sobre os exercicios de linkedLists e quase todos seguem o mesmo padrão de two pointers.
(Mais tarde) Voltei para fazer mais um exercicio, e acabei me deparando com uma solução que ja havia utilizado no exercicio two sum, 
consegui fazer tranquilamente (Tirando os problemas da descrição desse exercicio que me fizeram submeter errado algumas vezes), aparentemente a prática esta dando resultado.**
*(A partir de hoje irei alocar 2 horas por dia para praticar, afinal eu ainda preciso desenvolver projetos para portfólio)***

**18/10/24: Refatorei alguns códigos anteriores e fiz mais um exercicio. Mais uma vez, traduzir a solução em código foi um problema enorme,
mas absorvi mais um padrão de solução bem interessante, amanhã revisarei todos os algoritmos que fiz até aqui para refrescar a memória.**

**19/10/24: Descanso**

**20/10/24: Decidi criar um projeto de automação simples em shell script para utilizar enquanto versiono este repo. Vai ser bem simples na verdade apenas irei implementar um .sh com comandos como git add, git commit -m "" e git push, onde irei personalizar apenas a mensagem do commit, o resto vai ser padrão.**

**21/10/24: Criei o programa em shell simples para executar toda vez que eu quiser dar um push ou pull no repo (Não fiz leetcode hoje).**
  
**22/10/24: Conheci um site chamado neetcode.io onde contém um roadmap que achei viável para utilizar enquanto treino DSA em leetcode. Também adicionei mais 2 exercicios de arrays.**

**23/10/24: Conheci um novo padrão two pointer, que basicamente é ter um ponteiro no inicio e um no final de determinada lista, o ponteiro do inicio você incrementa fazendo determinado processo e do ponteiro final você decrementa. Não imaginava que esse era o famoso two pointer, achei que fosse o mesmo padrão do faster e lower de linked lists mas aparentemente são 2 coisas diferentes.**

**24/10/24: Cada dia que passa sinto que sei menos, mas isso é bom. A solução do desafio de hoje foi absurda e eu não passei nem perto da resolução.
com certeza vou revisar essa aqui milhões de vezes.**

**25/10/24: Eu acabei testando uma nova forma para fazer leetcode de ontem pra hoje, onde eu tento resolver um novo desafio, caso não consiga depois de algum tempo busco a solução,entendo o algoritmo utilizado e commito ele no *Repo*. No outro dia me forço a implementar este algoritmo diretamente no leetcode, sem consultar em lugar algum (A não ser que eu não consiga novamente).
E aparentemente eu consegui tanto pensar na explicação do algoritmo, quanto o exercício foi resolvido em menos de 10 minutos aproximadamente. Eu vou tentar sempre fazer isso a partir de hoje. (Bucket Sort é maluquice!)**

**26/10/24: Descanso.** 

**27/10/24: Acabei tendo uma ideia de projeto onde usarei RabbitMQ ou Kafka para conectar uma aplicação SpringBoot com outra em python, a cada registro novo no BD da aplicação principal é enviado uma mensagem para o "cluster", o programa python le desse cluster e busca a informação que mudou dentro do BD principal e grava em um arquivo txt (Poderia ser em qualquer outro lugar ou extensão) simples porém eu estava mesmo precisando fazer algo parecido com microserviços e utilizando mensageria.**

**28/10/24: Estudei sobre RabbitMQ e aprendi algumas coisas básicas que vão ser o suficiente para por o projeto em prática, como o funcionamento de exchanges, alguns tipos diferentes delas. A funcionalidade e o propósito de mensageria eu ja conhecia, porém agora sinto que solidifiquei mais o conhecimento, provavelmente amanhã eu começo o projeto.**

**29/10/24: Falhei**

**30/10/24: Iniciei a prática de "Micro serviços" e mensageria com o objetivo de fazer o projeto citado no dia 27/10, adicionei 2 repos com um projeto de base que criei apenas utilizando o get started do RabbitMQ (bem simples), a ideia agora é ir dando forma ao projeto aos poucos diariamente. Não consegui fazer LeetCode nos ultimos 3 dias, mas foi por um bom motivo.**

# Perdi o medo da doc #
**31/10/24: Preciso confessar... Hoje talvez tenha sido um dos melhores dias em relação a estudo, pois ao invés de ir atrás de tutoriais em video ou algum curso, recorri 100% a documentação, descobri (pelo menos o básico) de como se declara exchanges, filas, como enviar uma classe simples por mensagem (Oque abre um leque ENORME de possibilidades), eu me senti de fato como se estivesse dissecando os métodos da doc e descobrindo o que cada uma faz. Pretendo estudar mais assim daqui pra frente e menos com tutoriais.
Antes tarde do que nunca. (Será que o ato de ter começado a fazer leetcode, melhorou de alguma forma a minha "Vontade" (Essa não é a melhor palavra) de experimentar coisas mais complexas?)**

**01/11/24: Fiz o mesmo de ontem porém com spring boot, foi um sucesso. Ja tenho uma ideia de projeto para fazer, agora só irei implementar.(leetcode ficou de lado por enquanto)**

**02/11/24: Prátiquei um pouco de shellscript e senti um certo controle a mais em relação ao terminal e ao PC em geral, já havia praticado antes mas resolvi fixar mais um pouco por que acho uma linguagem muito importante para se aprender. (devo fazer mais alguma coisa hoje)**

**03/11/24: O plano da semana é implementar o rabbitMQ em um projeto um pouco mais "Robusto". Planejo também rever assuntos mais voltados a código como por exemplo arquitetura hexagonal e arquitetura limpa, não posso passar desse ano sem melhorar um pouco mais meu código em si.**

**04/11/24: Iniciei mais um conteúdo com o professor Isidro sobre Web Development com java, é uma sequência de aulas antigas de 5 anos atrás, porém que acredito que vá adicionar muito ao fundamento que identifiquei que estava faltando em java.**

**05/11/24: Aprofundei sobre servlet com o isidro.**

**06/11/24: Aprendi como configurar um webapp com servlet + jsp no intellij, subir um tomcat e expor rotas. Aparentemente é oque o springboot abstrai pra gente na hora de criar apis. (Obviamente em uma escala muito maior que isso)
Vou continuar a série de aulas com o isidro para me aprofundar mais.**

**07/11/24: falhei.**

**08/11/24: Preciso me organizar melhor, essa semana foi uma bagunça, hoje assisti uns videos do akita que me fizeram refletir bastante como sempre, mas acabei não colocando muito a mão no código.**

**09/11/24: Estudei um pouco sobre redes no canal hardwaredesbrasil que é uma branch do curso em video e me deu um fundamento legal sobre algumas coisas importantes.
Me dei conta que hoje faz exatamente um mês que eu comecei a fazer este relatório e é muito interessante reparar o quanto as coisas mudaram. Os dias anotados com descanso, significam que em algum dos dias do final de semana eu acabei não fazendo muito código e não tinha oque commitar (apesar de ainda assim ter consumido algum tipo de conteúdo de Tech)
Já os anotados com falhei significa basicamente a mesma coisa só que em um dia da semana, que é realmente considerado uma falha pois é quando eu deveria estar me esforçando mais então a boa noticia: em um mês foram apenas 2 falhas e 2 descansos. A má notícia: Apesar de poucos "erros" eu ainda preciso melhorar, foi um mês instável, isso aqui era pra ser uma repo de leetcode e virou um diário. Então para o próximo mês eu deveria focar mais ao invés de tentar abraçar muita coisa ao mesmo tempo.
Ao mesmo tempo que tenho que melhorar, fico feliz pois estou fazendo algo diferente, algo que nunca havia tentado antes que é documentar o meu dia a dia, ainda que apenas o necessário.**

**10/11/24: Fiz a compra do livro de sistemas operacionais do tanenmbaun chega amanhã, pretendo evoluir minha capacidade de leitura e entendimento de livros mais técnicamente complexos e consequentemente melhorar os meus fundamentos como profissional de TI.
Preciso voltar a fazer o curso de spring security é o ultimo módulo que falta para conseguir projetar completamente um sistema em spring, essa semana vai ser pesada...
*Inglês, CI/CD (Facul), Spring Security , leetcode + prática e Sistemas Operacionais***

**11/11/24: Decidi terminar de assistir a playlist do isidro sobre web para poder minimamente entender como um projeto 0 frameworks funciona em java, hoje (dia 12) eu termino.**

**12/11/24: Terminei a playlist do isidro e deu para entender bastante como as coisas funcionam por debaixo dos panos com servlets e também um pouco de jsp, apesar de achar uma bagunça, não sei se irei fazer um projeto relevante com essas tecnologias, mas vai me servir muito bem a partir de agora nas aplicações em springboot que eu fizer, além disso a aula de upload de arquivos foi sensacional, ler um arquivo multipart que vem direto de um formulário foi algo novo pra mim e me deu bastante vontade de me aprofundar nesta parte, hoje (dia 13) ja fiz alguns códigos utilizando FileInputStream, InputStream, preciso aprender mais sobre o OutPutStream, da pra fazer muita coisa legal com isso e é algo q eu sempre me esquivei por ignorância talvez, enfim, antes tarde do que nunca, é mais uma ferramenta importante que estou aprendendo a utilizar.**

**13/11/24: Estou maratonando uma série de videos do canal do Isidro novamente e to aprendendo muita coisa sobre serialização e desserialização, encaixou perfeitamente com o aprendizado de ontem sobre InputStream, eu fiz uns testes com JSON e consegui transformar em classe java e vice-versa com GSON e Jackson e de repente eu me vi em uma das aulas do Isidro falando sobre reflection que é oque essas bibliotecas justamente usam por dentro delas e foi um mindblowing total.**

**14/11/24: Maratonei o canal do isidro e estou dando uma repassada no DevDojo para relembrar alguns utilitários de java e outras coisas mais.**

**15/11/24: Estou aprofundando um pouco mais no pacote IO e NIO do java, e é talvez uma das coisas mais legais que eu ja vi, a sensação de você ler dados, escrever dados, depois você transferir estes dados para outro lugar, fisicamente (em disco), é quase a mesma sensação de quando eu estudei front-end pela primeira vez, da pra sentir que você ta criando algo de verdade, você de fato ve a coisa acontecendo, é um pouco diferente de quando estamos criando uma API, apesar de não ser TÃO DIFERENTE assim, eu não sei explicar.**

**16/11/24: Estudei um pouco sobre comunicação entre sistemas via socket em java, dei uma revisitada no conceito de threads e pensando seriamente em fazer um chatbot com IA utilizando esses 2 conceitos utilizando LangChain4j.**

**17/11/24: Quase todo domingo eu tiro um momento do dia para pensar no que eu vou fazer com a minha carreira e eu não consigo parar de pensar em fazer meu próprio software e tentar vender, eu estudo quase todo santo dia pra isso, ser bom o suficiente para que eu viva criando software e resolvendo o problema das pessoas através deles, mesmo que sozinho, mas confesso que é assustador as vezes.**

**18/11/24: Tirei o dia para matar as aulas da faculdade de uma vez, felizmente esse trimestre teve spring, docker e ci/cd, que tirando ci/cd eu ja to até trabalhando tranquilo com o resto e teve react também mas sinceramente... o commit do dia 19 vai ser autoexplicativo.**

**19/11/24: Comecei a estudar Angular para integrar com minhas APIS e vou repassar o assunto de ci/cd visto na faculdade pois achei importante demais, além disso provavelmente irei assinar um plano de vps para poder brincar de fazer deploy das aplicações, para poder chegar mais perto de uma aplicação em produção real.**

**20-21-22/11/24: Configurar websockets ta levando mais tempo do que eu esperava, amanhã irei tentar novamente.** 

**23-24/11/24: Consegui configurar o front-end e o back-end para se conectarem via websockets, esta semana irei fazer o esqueleto do projeto, o objetivo é fazer um chat igual um GPT da vida, vai ter um prompt do client e o servidor imediatamente responde com oque foi respondido pela IA, bem simples apenas para aprender mesmo.**

**25/11/24: Acabei dando por conta que inevitávelmente vou ter que usar concorrência no projeto, adicionei um concurrentHashMap para adicionar as sessões e consequentemente ter acesso mais tarde a 2 sessões possivelmente abertas, dando inicio assim a uma sessão compartilhada entre 2 usuários diferentes.**

**26/11/24: Encontrei algumas dificuldades na regra de negócio do projeto, ainda decidindo se terá algum tipo de persistência, inevitavelmente terá mas, para oque eu quero ainda não necessariamente precisaria ter, amanhã irei implementar mais alguma coisa, talvez eu foque mais na parte de envio da mensagem logo já que é o core da aplicação e depois eu organizo melhor os detalhes de implementação.**

**27/11/24: Faltam alguns detalhes mas ja consegui achar uma lógica para resolver a questão do chat, por um lado ja é possível enviar a mensagem e a mesma ser renderizada em uma sessão diferente para outro usuário, agora o código precisa passar por uma refatoração não tão complicada e algumas alterações na própria regra de negócio.**

**28/11/24: Tirei o dia pra fazer algumas alterações no currículo, ainda irei fazer alterações no github e no linkedin. Ainda assim enviei o curriculo para uma vaga de estágio de javinha, sei que tem muita coisa pra melhorar mas quem sabe.**

**29/11/24: Conheci um pouco de uma biblioteca chamada PDFBox que é utilizada para leitura e escrita de pdfs entre outras coisas, achei interessante, acabei fazendo um projeto protótipo onde eu leio o pdf do meu curriculo, passo para uma string e envio para o GPT pedindo uma opinião sobre o currículo. To pensando em implementar o modelo OLLAMA localmente para usar nos projetos, mas eu n sei se meu hardware vai tankar.**

**30/11/24 to 03/12/24: (percebi q as datas do mês passado estavam anotadas com 10 e não com 11... já foi corrigido.) Sobre o final de semana: de repente eu me peguei assistindo aulas de typescript na origamid e uma aula sobre angular de um canal novo chamado angularizando, percebi que eu precisava dar uma afinada no front-end apenas para poder dar alguma interface para minhas apis, acredito que seja um conhecimento importante de se ter, minha bagagem básica em js e o meu nível atual que tenho em programação em geral me deu certo conforto ao ir para o ts que é muito parecido com javinha. Sobre segunda e hoje terca-feira: Continuei assistindo as aulas e tentando implementar algumas coisas no projeto full-stack, acabei descobrindo exatamente oque eu precisava para continuar o projeto em angular e é possível que o projeto saia do lugar agora. (Criei mais um script em shell para automatizar meus relatórios neste repo, agora eu tenho 2 scripts, o que eu fiz nos primeiros dias desse repo e agora este que se integra a ele, mas só utilizo ele se for pra mexer no readMe).**

**04 - 05/12/24: Encontrei um bug no chat onde o client (Angular) não consegue enviar mais de uma mensagem, apenas receber, aparentemente o programa trava após o envio da mensagem, ainda não encontrei o bug mais tarde tentarei novamente.**

**06/12/24: Ainda ontem encontrei o bug citado, era um problema no angular, não estava fazendo o uso do binding, portanto o sistema acabava não funcionando a partir da segunda iteração, hoje adicionei algumas verificações com try catch e arrumei um pouco a estrutura de pastas do projeto, eu ainda estou patinando na estrutura do angular, mas eu vou melhorando com o tempo. Até agora muito satisfeito com a stack que eu escolhi, Spring e Angular são sensacionais.**


**07/12/24: Não fiz muita coisa hoje, por curiosidade dei uma revisada em interfaces funcionais, o objetivo era refletir sobre a melhor maneira de declara-las e se valia a pena criar algum tipo de classe que segura diversos predicates por exemplo, e na hora de utilizar dentro de streams nós só acessariamos o predicate ja declarado na classe através de alguma função, visando talvez uma legibilidade melhor de código ou algo assim, também revisei as classes BufferedReader e BufferedWriter que são utilizadas para ler e escrever em arquivos, sem muito objetivo, só que eu acho muito interessante esse tipo de funcionalidade, acabei descobrindo uma função chamada transferTo que recebe o writer como parâmetro, ela leva o conteúdo do reader diretamente para a file do writer, achei interessante.**

**08/12/24: Comecei a usar o GitHub Copilot no vsCode, vou usar para me ajudar no front-end, refatorei um pouco do projeto já fazendo uso do mesmo e até agora achei útil, acredito que seja uma boa pelo menos nas partes mais simples do projeto. Preciso ficar atento nas funções que são indicadas pelo copilot pois preciso entender oque ele está sugerindo, obviamente.**

**09/12/24: Consegui formatar a entrada e a saída dos dados, agora preciso adicionar algumas features no back-end e organizar melhor, adicionei o jackson para parsear a mensagem ao invés do GSON.**

**10/12/24: Mexi em algumas coisas no github e comecei mais um projeto em spring não inicializei o repo remoto ainda.**

**11/12/24: dia 09 fez 2 meses em que eu iniciei este relatório, a evolução de la até aqui foi evidente, estou praticando mais, tendo muito mais ideias de projetos para criar, por mais pequenos que sejam são muito importantes para a minha evolução. Preciso voltar a fazer leetcode também.**

**12/12/24: Terminei a introdução do livro de Sistemas Operacionais do Tannembaum, um livro muito dificil de ler, pesado, mas esta sendo uma experiência muito boa, não fiz modificações nos projetos hoje, amanhã sem dúvidas irei desenvolver algo, essa semana eu me encontro muito desorganizado novamente, acho que muito do pesado que tinha para estudar no começo eu ja peguei, pelo menos o básico, agora eu preciso refinar e praticar até que tudo se consolide mais ainda. Assuntos como AWS, IA, Kubernetes, microserviços e segurança, são assuntos que eu explorei muito pouco até hoje então acho que meus estudos vão nessa direção daqui pra frente, todo o resto estudado será revisado através de projetos e leitura diariamente, encontrando alguma dificuldade relacionado aos assuntos ja estudados sem dúvidas voltarei a estudar tal assunto para consolidar melhor o conceito seja ele qual for.**

**13/12/24: Estou começando a mudar a estrutura do projeto, antes de haver a conexão agora o nickname será enviado via HTTP imediatamente após a solicitação de conexão, havendo algum tipo de autenticação basica só para aumentar a robustez do projeto, ainda há muitas melhorias para se fazer, principalmente na nomeação das classes e na estrutura do projeto.**

**14/12/24: Iniciei um curso novo na devDojo sobre spring-boot para reciclar algumas coisas e aprender novas features ja que é um curso recente, hoje a aula foi mais uma explicação sobre virtual threads e suas vantagens acompanhado de um teste de performance que eu nem sabia que dava para fazer com postman e o uso de um sistema chamado visualVM para acompanhar o funcionamento da JVM, vi apenas essa aula por hoje.**

**15 - 16 - 17/12/24: Quarto dia estudando o novo curso da DevDojo, já aprendi alguns detalhes importantes que havia deixado passar durante o ano, principalmente sobre headers de requisição e como personaliza-las, faltam 150 aulas ainda, pretendo terminar antes do ano que vem.**

**18/12/24: Mais um dia, revisei alguns conceitos sobre Optional, ResponseEntitys, lambdas e streams. Além disso a partir de agora usarei mapStruct como mapper padrão nos meus projetos, antigamente eu fazia na mão e ficava horrível, depois vou estudar com mais detalhes a documentação, mas oque foi passado no curso é o suficiente para utilizar em projetos.**

**19/12/24: Cheguei na aula 29, por enquanto revisando o padrão MVC do spring, tranquilo até aqui.**

**20/12/24: Revisei alguns conceitos sobre @Bean e @Configuration no springboot,amanhã ou hoje mesmo ja começo as aulas sobre testes, preciso revisar alguns conceitos também.**

**21/12/24: Hoje configurei o LLM llama3 no meu pc, em breve farei um projeto utilizando ele, quem sabe eu não coloque ele lá no projeto do chat, tirando isso não fiz mais tanta coisa, hj eu peguei leve.**

**22/12/24: Dia de organizar a semana, vou tentar terminar o curso essa semana mesmo.**

**23/12/24: Aprendi e relembrei algumas coisas sobre testes unitários com Junit e mockito.**

**24 - 25/12/24: Ta dificil assistir as aulas neste final de ano, mas implementei os testes e fiz os exercicios propostos, vou assistir as aulas apenas para correção de algumas coisas. Feliz natal.**

**26/12/24: Refatorei alguns testes, e adicionei algumas utilidades, aproveitei para revisar generics, criando uma interface que recebe um tipo genérico e que possui um método que retorna uma Lista do tipo genérico também, diminuindo assim a repetição de código nos meus testes ja que a função é apenas retornar uma lista.**

**27-28/12/24: Iniciei o dia criando um script em shell para facilitar meu trabalho no dia a dia, bem simples apenas inicia o intellij automaticamente dentro de um projeto que eu defini, após isso executa outro script que serve para commitar neste repositório, se encaminha para o caminho do projeto definido e roda os testes com mvn test, se passar tudo corretamente, se inicia o git-automate, que serve para commitar o projeto no repositório remoto. Além disso dei inicio ao teste "unitário" do controlador, foi muito importante pois revisei a configuração para poder utilizar o mockmvc, que após tentar configurar sozinho acabei não conseguindo executar.**

**29/12/24: Refatorei alguns testes e implementei alguns outros no controller.**

**30/12/24: Terminando as aulas e os testes unitários hoje, ainda devo assistir mais algumas outras aulas para compensar 2 dias que eu fiz corpo mole semana passada, infelizmente não vou conseguir finalizar antes do ano novo provavelmente.Acabei de perceber que eu retirei o script de automação que utilizava para commitar neste repositório no dia 25, ou seja eu estava apenas commitando para o repositório local e não para o remoto, que tristeza.**

**31/12/24: Iniciei o exercicio proposto na aula 54 do curso, terminei o projeto, agora preciso criar os testes, ainda tentarei fazer hoje mesmo.**

**01/01/25: Iniciando o ano com algumas aulas do curso, corrigindo alguns testes e modificando o script de automação para algo mais dinâmico.**

**02/01/25: Passei o arquivo .md do relatório para um repositório novo, não tava mais fazendo sentido deixar o relatório em um repo de leetcode, até por que irei voltar a utilizar aquele repositório para os exercícios em si. Acabei de finalizar algumas aulas do curso sobre: variáveis de ambiente, @ConfigurationProperties e uma ótima aula de profiles, a cabeça ta explodindo mas jaja passa.**

**03/01/25: Comecei um desafio de vaga da UOL, que a professora giuliana bezerra postou a algumas semanas atrás e eu ja tava de olho a algum tempo, ainda não criei o repositório remoto, mas em breve comitarei, o repositório do desafio está aqui [repositório](https://github.com/uolhost/test-backEnd-Java "repositório desafio uol").**

**04/01/25: Hoje foi meu aniversário, acabei me presenteando um dia de descanso, amanhã voltarei ao desafio e a assistir o curso.**

**05/01/25: Hoje as aulas foram de bean validation e testes parametrizados, o assunto validação eu ja conhecia a algum tempo, mas foi bom para reciclar e fixar, e os testes parametrizados eu ja tinha visto mas ainda não implementado, amanhã mesmo farei a refatoração dos testes.**

**06/01/25: Hoje utilizei a ajuda do gpt para criar uma anotação de validação, onde o campo apenas é válido se pelo menos um atributo estiver preenchido corretamente, sendo assim continuei os testes parametrizados corretamente de acordo comesta validação.**

**07/01/25: Refatorei o projeto do curso com bean validation implementado, refatorei os testes também, amanhã continuarei o projeto de vaga da UOL, hoje farei mais algumas aulas do curso.**

**08/01/25: É nitido a evolução que eu obtive do ano passado pra cá, o springboot ja não é mais um desafio, um startup de aplicação ja não demora tanto, é bem legal ver o nível que eu cheguei, mas ainda tem muito trabalho a fazer.**

**09/01/25: Começando os trabalhos hoje refatorando o user service e adicionando testes para as novas funcionalidades, adicionei funcionalidades + JPA no anime service e refatorei todos os testes com as novas funcionalidades.**

**10/01/25: Adicionei testes de repositório com @DataJpaTests, ainda com algumas dúvidas sobre tal, porém deixei tudo passando certinho, vou ter que pesquisar mais sobre esse tipo de teste, inclusive vou olhar no outro repositório onde também fiz esse tipo de teste e tentar comparar.**

**11/01/25: Domain profile adicionado no projeto e alguns testes, faltam apenas os endpoints de leitura para testar, amanhã mesmo eu termino, ou hoje ainda, vamos ver.**

**12/01/25: Testes do profile finalizados e refatorados com sucesso, não assisti mais aulas hoje, amanhã eu vou tentar avançar pelo menos umas 20 aulas para compensar.**

**13/01/25: 20 aulas não foram, mas cheguei na aula 101, faltam apenas 65, hoje aprendi coisas bastante importantes sobre a performance das aplicações, o plano é terminar o curso esta semana.**

**14/01/25: Hoje aprendi um pouco sobre performance melhorando as querys ao BD com a utilização de jpql e @EntityGraphs.**

**15/01/25: Hoje começamos no tema teste de integração com testRestTemplate e Testcontainers, 2 tecnologias bastante conhecidas, confesso que vou ter que revisar mais essas aulas pois foram muitas anotações e bastante detalhes pequenos mas super importantes que eu não poderei deixar passar. Para lembrar disso tudo vai ser uma dor de cabeça.**

**16/01/25: Hoje Aprendi a utilizar o RestAssured, que é mais uma tecnologia utilizada para testes de integração, o hibernate me deu uma dor de cabeça com o ID sendo auto incrementado de maneira errada, acabei tendo que me virar para resolver alguns testes, mas foi tranquilo, mais uma tecnologia aprendida.**

**17/01/25: Hoje foi dia de revisar sobre o springDoc openApi, ou melhor, swagger, já havia feito um projeto com ele antes, mas rever assuntos é sempre bom para solidificar conhecimentos, também assisti algumas aulas sobre o manuseio de dependências no pom, com projetos parent, que basicamente são utilizados para servir como um "projeto principal" de onde serão herdadas as dependências para os outros serviços.**

**18/01/25: Hoje foi dia de revisar maven profiles, com o plugin failsafe e comecei a estudar novamente o módulo spring security, falamos sobre, roles, proteção de endpoints, algumas anotações muito poderosas como @PreAuthorize entre outras.**

**19/01/25: Ontem eu esqueci de por no relatório que eu voltei a mexer no projeto do desafio de vaga da uol, fiz bastante coisa até, porém ainda tem muito trabalho a fazer, hoje eu revi as aulas de ontem só para não passar em branco, peguei mais leve.**

**20/01/25: Hoje foi um dia bastante extenso, tivemos que refatorar todos os testes por causa da autenticação do spring security, ainda não terminamos, terei que refatorar um método PUT que eu acabei tendo que refazer. Essa semana se Deus quiser eu termino o curso.**

**21/01/25: Hoje terminei o módulo de segurança, obviamente que tem muito mais conteúdo sobre para complementar, eu ja possuo outro curso que irei fazer que é um pouco mais completo apenas sobre spring security, e também comecei as aulas sobre openApi contract first, que é basicamente sobre criar a especificação da api antes mesmo do código a partir de um arquivo yaml, achei bem interessante e é uma possível abordagem para próximos projetos.**

**22/01/25: Hoje aprendi sobre observabilidade com spring actuator, prometheus e grafana, além de como montar uma imagem do meu projeto com google jib.**

**23/01/25: Hoje foi dia de aprender sobre testes unitários com o restClient e wiremock para testes de integração, infelizmente acabei encontrando um bug em um dos testes do wiremock onde a resposta da requisição era incrementada a cada teste que eu rodava, além de ter ums valores nulos muito estranhos, com certeza é uma tecnologia que eu irei me aprofundar mais, aparentemente é uma das ferramentas mais atuais para fazer testes de integração então vale a pena ir atrás.**

**24/01/25: WireMock ta dando mais trabalho do que eu esperava, nada mais.**

**25/01/25: Iniciei os testes Unitários no desafio vaga uol, pretendo terminar antes do mês acabar, para já começar outro desafio, este foi até que tranquilo.**

**26/01/25: Hoje refatorei alguns testes unitários, eu vi que um método acabou ficando grande demais e resolvi separar o arrange e os asserts em 2 funções, mas ainda estou meio preocupado se essa foi a melhor escolha, eu acabei recriando muitas variáveis para deixar os asserts o máximo legível possível, mas eu ainda não consegui pensar em nada para substituir essas variaveis, talvez coloca-las na pasta utils, mas no fim não mudaria muita coisa, enfim amanhã voltarei novamente a este mesmo módulo por que não to satisfeito, além disso utilizei novas funções que não havia utilizado ainda e que vão adicionar muito a robustez do teste.**

**27/01/25: Hoje tomei a decisão de separar tudo em classes e implementar uma interface entre oque pode ser utilizado em um teste parametrizado, também mantive as constantes, para que seja possível o uso nas funções que não cabem o teste parametrizado, acho que é melhor desta maneira, apesar de ter dado um trabalho para arrumar tudo, na minha opinião está tudo onde deveria estar, em outros projetos eu analiso se vou mudar a maneira de preparar os dados para os testes ou se utilizarei este padrão.**

**28/01/25: Hoje eu acabei ficando preso em um teste no desafio uol, onde eu tenho uma função que faz uso de outras funções com modificadores de acesso private, a pergunta era, "como eu posso testar esta função se eu não posso mockar as outras?", a questão aqui é que eu simplesmente achei que ao usar @InjectMocks no serviço ele não funcionaria se eu não mockasse o resto das funções, só que não é assim que funciona e de certa forma eu sabia porém eu travei simplesmente, sem explicação, no final, eu acabei só mockando as dependências e suas funções (como sempre) e mudei apenas os parâmetros de entrada da própria função do service e deu tudo certo. Eu ainda não peguei feedback sobre meus testes, então não sei se estou fazendo o correto desta forma, mas é o jeito que aprendi e estou apenas fazendo oque eu acho certo.**

Vou deixar esta mensagem aqui, sem pretenção nenhuma, porém se alguém além de mim chegou até aqui e esta lendo meu relatório diário por algum motivo, por favor me deixe saber, fique a vontade para entrar em contato comigo, eu ainda sou aquele dev que fica infurnado no quarto só estudando e fazendo meus projetos sozinho, então é importante demais o contato com outras pessoas e eu tenho certeza de que se você não é um recrutador e ta aqui lendo este relatório, você tem um pouco ou muito da característica que eu citei anteriormente, mais uma vez, fique a vontade para entrar em contato. A luta continua.

**29/01/25: Faltando apenas os sliced tests do controller para terminar o projeto, não sei se irei fazer testes de integração, já que não foi pedido no desafio, também não acho que o projeto necessite tanto já que é só um desafio, hoje ja testei as constraints do banco, amanhã vai ser do controlador, e os unitários ja foram terminados, amanhã mesmo devo terminar e ja começar o desafio do itaú, que é um pouco mais dificil.**

**30/01/25: Testes sunny day ja terminados, falta agora testar toda a validação do bean validation e também o caso do email enviado ja existir.**

**31/01/25: Terminei os testes ontem mesmo e documentei o projeto no swagger, hoje criei um readme descrevendo o projeto e como executa-lo em outra máquina.**

**01/02/25: Acabei tendo um problema com o SSD do meu pc e vou ter que trocar, tenho um de backup graças a Deus, o trabalho continua.**

**02/02/25: Estou tendo que refazer meus scripts já que nenhum eu tinha subido no repositório remoto, este relatório está sendo feito através do novo script, vamos ver se funciona, hoje ainda vou começar a planejar o novo desafio de código, dessa vez vai ser o do picpay simplificado que utiliza bastante tecnologia e vai ser um ótimo teste para mim. O script funcionou,
Acabei de criar o repositório, vou tentar uma abordagem um pouco diferente, utilizarei o excalidraw ou o draw.io para desenhar a solução e colocarei no repositório amanhã mesmo, irei começar por ai, ja tenho uma idéia minima do que fazer, também irei implementar tecnologias diferentes (p.ex Ao invés do JPA irei utilizar a nova api jdbc do springboot visando aprendizado), neste projeto teremos teste de integração e containers, é uma ótima oportunidade para usar o testContainers e o wireMock, ambas tecnologias ensinadas na devDojo. Eu queria também postar o encaminhamento do projeto no linkedin que é uma vontade enorme minha, mas que infelizmente ainda não consegui implementar por falta de vergonha na cara.**

**03/02/25: Dei inicio ao projeto criando alguns fluxogramas e adicionando as dependências que eu sei que vou utilizar, ainda faltam algumas outras coisas, amanhã eu vou tentar desenhar a arquitetura do projeto também e colocar no repositório.**

**04/02/25: Tenho escrito pouco código nesses últimos 2 dias pois quero evoluir o meu processo de desenvolvimento, adicionando diagramas, fluxos, desenhos, arquitetura, enfim, coisas além do código que também importam e que foram de certa forma ignorados no começo dos meus estudos. Terminei a configuração do postgres no docker, ja tá tudo funcionando, preciso apenas criar as tabelas e as constraints, aliás o diagrama de classes também ta pronto, apenas preciso passar isso pro db.**

**05/02/25: Hoje foi o dia de começar a codificar, e ficou tudo diferente do que eu tinha desenhado xD, vou ter que desenhar tudo novamente depois, as idéias foram surgindo durante a codificação, fiz um bom progresso nos serviços, porém ainda não testei nada, provavelmente não vai dar certo, mas estamos aqui pra resolver bugs não é mesmo? Aliás eu fiz um post no linkedin hoje que ficou bastante legal na minha opinião, eu tentei o meu melhor, ainda nem olhei se teve qualquer reação, também o objetivo não é esse, então não importa muito.**

**06/02/25: Hoje eu dei praticamente o penúltimo passo do projeto, a regra de negócio está praticamente feita, o fluxo da transação está completo, falta agora fazer a integração com os 2 serviços externos propostos pelo desafio, tratar os erros e testar.**

**07/02/25: Primeira integração com o serviço de authorização está completo, criei algumas queries extras, agora faltam o serviço de notificação com rabbitmq, os testes e preparar pro "deploy", além do code review no final visando melhorias.**

**08/02/25: Hoje foi dia de adicionar a dependência e a imagem do rabbitMQ no projeto, configurá-lo para executar retries quando o consumidor lançar uma exceçãoquando o serviço externo estiver indisponível.**

**09/02/25: Implementei o famoso lock otimista no projeto, foi desgastante, nunca tinha feito antes, mas provavelmente eu compliquei meu trabalho ao tentar fazer update em 2 colunas ao mesmo tempo, acabou que eu resolvi fazer 2 querys mesmoque isso afete a performance do projeto, eu preferi manter as coisas funcionandocorretamente. O trabalho ainda não acabou, talvez eu volte nessa query novamente, mas ainda preciso implementar o serviço de notificação.**

**10/02/25: Implementei o serviço de notificação com rabbitmq, aparentemente ta tudo funcionando, amanhã começo os testes, ótima oportunidade para por em prática os conhecimentos do curso novamente.**

**11/02/25: Hoje foi dia de quebrar a cabeça com bean validation e com um problema na view do swagger, infelizmente demorei demais para perceber que as anotações do bean validation só funcionam corretamente em tipos primitivos, por isso tive que trocar alguns campos de long para Long. Amanhã vou revisar todo o código e toda a documentação para começar os testes.**

**12/02/25: Dei inicio aos testes, os unitários do walletService e da transaction ja estão prontos, posso sempre melhora-los depois, irei tentar terminar amanhã de uma vez.**

**13/02/25: Hoje foi dia de configurar o testContainers e iniciar os testes de integração.**

**14/02/25: Comecei os testes com wireMock, fiz apenas um cenário por enquanto, talvez faça mais alguns hoje, mas é garantido que terminarei amanhã de manhã.**

**15/02/25: Finalizei praticamente quase todos os testes, preciso automatizar um último que vai testar o lock otimista, os de integração já foram, da api ja foi, e os unitários também.**

**16/02/25: Hoje foi dia de começar a preparar o projeto para "produção", criei a imagem e coloquei no docker hub, ja puxei para o docker compose e ta tudo funcionando, porém ainda tem muita configuração que eu preciso remover, mas já serviu pra entender como vou fazer.**

**17/02/25: Hoje fiz o teste do lock otimista, sinceramente espero ter testado corretamente, fiquei satisfeito, o teste se comportou como eu queria, devem ter maneiras melhores para testar, quem sabe em algum momento eu receba um feedback desse teste.**

**18/02/25: Comecei a documentação do projeto no repositório.**

**19/02/25: Melhorei a documentação do projeto no repositório, esta quase na hora de ir para o pŕoximo desafio.**

**20/02/25: Sinceramente, tirei o dia para melhorar algumas coisas no meu linkedin/currículo e amanhã talvez faça o mesmo, ainda não peguei em código hoje, porém ainda devo codar algo.**

**21/02/25: Tive a ideia de implementar um teste automatizado no desafiopicpaysimplificado com selenium, ainda não sei como vou fazer pois nunca utilizei, amanhã mesmo irei implementar.**

**22-23/02/25: Não implementei o teste xD, mas vou deixar na lista das tecnologias para estudar, preciso revisar o projeto para ver se esta tudo ok realmente e irei ir para o próximo que talvez seja um projeto de verdade não mais um desafio técnico, um projeto para ajudar um amigo nutricionista a gerenciar e atender seus clientes. Hoje e ontem eu apenas fiz alguns exercicios no beecrowd de sql, eu senti que precisava reforçar mais a base e vou fazer isso não só com sql, mas também com algoritimos, quem sabe voltar pro leetcode, ou fazer os exercicios no beecrowd mesmo. Eu me sinto muito bem quando acordo e a primeira coisa q faço são esses pequenos exercicios, parece que o cérebro passa a funcionar um pouco melhor, claro que não pode ser um exercicio muito dificil pq se não se torna algo desafiador até demais, a proposta é exercitar e "ligar" o cérebro para começar o dia bem.**

**24/02/25: Hoje fiz mais alguns daqueles exercicios de sql para praticar, não fiz muito mais nada além disso.**

**25/02/25: Hoje foi um daqueles dias em que eu só pensei em desistir de continuar fazendo oque eu tenho q fazer, mas estamos ai**

**26/02/25: Dei inicio ao projeto do sistema de gestão do meu amigo por enquanto apenas fiz um endpoint para registrar as informações manualmente pelo próprio admin, oque não é efetivo, porém era o mais simples a se fazer, agora eu preciso tomar uma decisão, fazer esses dados virem de um forms feito por mim com Typescript ou Javascript, ou linkar um microsoft form ao sistema e fazer as informações virem diretamente de la, já que ele ja faz uso do forms da microsoft na empresa dele, preciso pensar nisto para continuar o projeto.**

**27/02/25: Dei inicio a um novo desafio de vaga do itau, ja fiz os controllers, algumas configurações e setupei os testes de integração, amanhã implemento a regra de negócio.**

**28/02/25: A primeira implementação que testei foi com uma estrutura concorrente para aceitar que diferentes threads adicionem transações ao mesmo DoubleSummaryStatistics, eu não sei exatamente se foi pedido isso no desafio, mas irei implementar dessa forma, irei refatorar toda regra para o service amanhã e decidirei oque vou fazer, ainda tenho que mexer em algumas constraints como não poder receber transações no passado(??).**

**01/03/25: Comecei a implementar a regra de negócio do projeto, já descobri como filtrar as últimas transações, amanhã mesmo passo a configuração do timing (60 seg) para um time configuravel no próprio application.yml, que é uma feature não obrigatória mas sugerida. Ainda preciso revisar as estruturas de dados e a biblioteca Duration, tem muita coisa pra ser refatorada ainda.**

**02/03/25: Hoje foi dia de estudar sobre IA com langchain4j no canal da kipper, estou pensando seriamente em fazer uma integração com llm em um projeto próximo.**

**03/03/25: Hoje organizei o código do desafio Itaú, deixei bem conciso, ainda tem bastante coisa para implementar além dos testes então tem muito trabalho a ser feito amanhã.**

**04/03/25: Finalizei os testes de integração do projeto Itaú, adicionei as validações necessárias para o endpoint que recebe as transações, faltam os testes unitários, o teste de concorrência e algumas outras coisas.**

**05/03/25: No dia 04 eu falei que havia finalizado os testes de integração, menti, no dia 05 ainda fiz varias modificações e novos testes, ainda tive que tomar uma decisão final sobre utilizar BigDecimal ou um double nas entidades de domínio.**

**06/03/25: Aparentemente dessa vez eu finalizei os testes de integração e unitários, agora faltam alguns testes específicos para confirmar que a concorrência no projeto esta bem implementada, faltam também a documentação com springdoc e a documentação visual.**

**07/03/25: Adicionei a documentação do swagger aos devidos endpoints, sinto que ainda da para melhorar, porém acho que é o suficiente para bater o olho e conseguirem testar a aplicação corretamente, agora eu vou passar a aplicação para um container docker, ainda preciso testar a performance do código entre outras coisas.**

**08/03/25: Tomei uma decisão fixa para meu cronograma a partir de hoje, todo final de semana eu vou estudar alguma matéria de ciência da computação em um dos repositórios que eu tenho como favorito aqui no github, mas antes de ir para a grade sugerida, irei estudar redes e sistemas operacionais, já havia estudado um pouco antes não estou zerado no assunto, mas a partir de hoje todo final de semana irei estudar pelo menos 2 horas de conceitos e ai durante a semana eu sigo normalmente praticando e estudando matérias mais práticas em si.**

**09/03/25: Hoje foi dia de organizar a semana e iniciar um novo projeto, não codei.**

**10/03/25: Adicionei os extras do desafio, ficou faltando apenas a documentação, hoje (dia 11), ja estou completando este passo também.**

**11/03/25: Finalizei a documentação e agora creio eu que não falte mais nada para o desafio estar completo, vou revisar e anotar como completo até amanhã, também vou dar um tempo dos desafios, preciso criar meus projetos para por no portfolio e curriculo, além do projeto atual que ja esta em andamento.**

**12/03/25: Documentação testada e completa, pronto para o próximo projeto.**

**13/03/25: Tenho 3 projetos para fazer, pretendo terminar os 3 este mês, não sei se vou conseguir mas vou tentar.**

**14/03/25: Dei inicio ao desafio do devMagro do ytb, ainda não subi para um repo remoto, mas vou amanhã, o desafio é pra ser feito em uma semana então já deixo aqui que comecei no dia 14, então eu preciso entregar até o dia 21.**

**15/03/25: O desafio é muito bom, pensei que iria travar mais, mas na verdade até que ta fluindo bem, acho que o mais complicado vão ser as constraints do projeto, tratamento de exceções e etc...**

**16/03/25: O repositório esta criado, o projeto ainda ta bem bagunçado precisa de mais organização e ainda tem muita feature para adicionar, amanhã terei muito trabalho.**

**17/03/25: Hoje fiz um baita progresso no projeto, a função de cadastro está quase completa, faltam as constraints das opções além da primeira que foi a única que eu terminei hoje.**

**18/03/25: Acho que eu terminei o menu, pelos meus testes ta tudo correto, na verdade falta só uma feature que é deixar o valor NÃO INFORMADO como padrão de alguns campos, ta sendo um mistério pra mim fazer isto já que oque eu costumo receber é o proprio tipo da propriedade, eu devo estar deixando passar alguma informação, mas vou dar continuidade no projeto mesmo assim, próxima feature é a feature de criar uma pasta e um arquivo com nome formatado para salvar a informação dos pets.**

**19/03/25: Fiz a função de salvar o pet no arquivo e comecei o desenvolvimento da feature de busca.**

**20/03/25: Rapaz, o desafio é muito mais trabalhoso do que pensei, mas as features estão implementadas e faltando apenas a de alterar os dados, queria deixar o desafio mais bonitinho, n vai dar n, agora eu entendi oque é codar sobre pressão, bem, tenho até amanhã a meia noite para concluir então tem tempo de arrumar algumas bagunças (tem uma função com +50 linhas) e eu não to pensando nem em performance. Amanhã meia noite eu vou adicionar uma tag no git para salvar a versão do desafio, mas depois eu irei continuar implementando, gostei muito de fazer o projeto.(Acabei de me ligar que na verdade eu comecei o projeto no domingo passado, então eu tenho pelo menos mais 3 dias e eu nunca me senti tão bem na vida ASUHDASUDH)**

**21/03/25: Funções implementadas com sucesso. Agora é revisar e refatorar, tem muito código ruim e principalmente nomeação de variaveis e funções horriveis, mas eu foquei em desenvolver as features antes de priorizar arrumação. amanhã o trabalho é só organizar classes e funções.**

**22/03/25: Renomeei e refatorei muitas funções e muitas variáveis, quebrei tudo em funções menores e criei um service que centraliza a maioria das operações, deixei um pouco mais parecido com o springboot.**

**23/03/25: Adicionei novas funções e renomeei outras, deve ter faltado alguma coisa com certeza, mas o projeto ta pronto, não vou parar de mexer nele ainda vou procurar alguns bugs, implementar alguns testes entre outras coisas, vou usar o projeto como laboratório.**

**24/03/25: Dei o projeto como finalizado confesso que implementei algumas coisas que havia deixado faltar hoje então meio que eu "roubei" ja q era pra ter entregado ontem, mas foram coisas pequenas como não tratar as funções de busca caso não tenha nenhum registro e a própria documentação. Ainda tem muita coisa pra melhorar no código, eu não gostei de algumas implementações que fiz, mas vou deixar deste jeito, ou talvez eu faça oq eu disse anteriormente, crie uma tag pra dizer que aquela versão é a versão do desafio e dps eu continuo implementando, não sei, acho que eu já irei iniciar outro projeto, dessa vez mais ambicioso, um projeto fullstack ou até utilizando thymeleaf não sei, eu vou tentar unir um desafio da devdojo com uma ideia que eu mesmo tive e fazer um bem bolado.**

**25/03/25: Apenas fiz algumas refatorações no projeto.**

**26/03/25: Hoje eu fiz um pequeno servidor de arquivos, só para brincar mesmo, fiz um js bem rapido e o backend com springboot, algo me diz que eu vou utilizar isso em algum projeto bem próximo.**

**27/03/25: Passei o dia sem luz :).**

**28/03/25: A luz voltou e eu criei um programinha em angular só pra consumir a api do servidor de arquivos que fiz, vou tomar vergonha na cara e aprimorar meu typescript para fazer minhas interfaces.**

**29/03/25: Hoje eu apenas assisti alguns conteúdos do akita, é sempre bom tomar algumas lições para "voltar" ao eixo e sair da zona de conforto.**

**30/03/25: Hoje eu estudei sobre uma maneira de monitorar alterações em arquivos, acabei descobrindo que o java ja tem uma implementação nativa com WatchService, amanhã mesmo irei testar, vai ser importante para projetos no futuro.**

**31/03/25: Hoje criei o projeto para testar o watchservice, pequeno mesmo só para testar, uni com outro programa pelo qual eu registro usuarios e salvo num arquivo "nome".json e o watchservice conseguiu "rastrear" a alteração e eu consegui também pegar o absolute path oque me ajuda a ter controle sobre qual arquivo que foi alterado, podendo assim utilizar para outras coisas, inclusive pode ser um bom utilitário para arquivos de logs, por exemplo um sisteminha que le os logs das minhas apis, enfim da pra usar em muitos lugares, além disso acabei conhecendo do nada uma classe chamada JFileChooser do swing, achei bem interessante.**

**01/04/25: Até que enfim hoje eu tive coragem de criar um programinha para conectar o meu pc e meu notbook, eu tinha um pouco de receio de expor portas nos meus computadores, mas hoje eu tomei coragem e fiz, agora eu to tentando pensar em algum programa utilitário para fazer. Fiz tudo com ServerSocket e Socket do java.**

**02/04/25: Hoje eu adiantei 2 matérias da faculdade, estou no último trimestre estudando sobre cybersecurity e é mais uma matéria complexa e por enquanto teórica demais (daquelas chatas) mas que é muito importante saber.**

**03/04/25: Hoje eu fiz algo que eu achei sensacional, consegui colocar uma aplicação angular (buildada) dentro do electron.js e tornei a aplicação em desktop nativo, eu achei muito legal, até por que eu ja estou com este projeto de aprender angular e saber que eu posso simplesmente colocar o mesmo front-end da web em um app desktop é sensacional, agora eu também irei procurar alguma forma de fazer o mesmo para mobile, eu ja sei que tem como transformar em PWA mas ainda não implementei, bem foi um projeto simples então ta na hora de fazer algo mais robusto com isso, novidades em breve.**

**04/04/25: Hoje eu estudei sobre tools com langchain4j não apliquei ainda.**

**05/04/25: Commitando esse após meia noite (virada para o dia 6) perdi a streak, mas continuo aki, não me importo com os quadradinhos, hoje foi realmente um dia atípico, mas muito importante, o dia que eu peguei mais folego para continuar a jornada.**

**06/04/25: Segui estudando a documentação do langchain, amanhã irei estudar as tools e os embedded stores.**

**07/04/25: Testei as tools é um recurso muito poderoso para garantir a resposta eficiente da IA de acordo com a aplicação, ainda falta testar as embed stores.**

**08/04/25: Hoje eu assisti a 2 palestras uma sobre RAG e outra sobre concorrência no java, fiz um programinha para testar o ProcessBuilder que da a capacidade de executar scripts shell através do java, acabei testando o script que eu uso para escrever este relatório e não funcionou, mas acho que a culpa foi minha é outro recurso bem legal do java.**

**09/04/25: Hoje dei inicio a um projeto onde irei integrar o processBuilder + langchain4j com as tools, vai ser um facilitador do uso do git, o plano é o aplicativo monitorar uma pasta utilizada pelo usuário para guardar seus projetos, o programa vai buscar apenas os projetos que são repositórios git, já consigo pegar os arquivos que foram modificados e ainda não commitados, a ideia é fazer a IA ler esses arquivos e sugerir commits a partir de suas modificações, vou usar o comando git status --porcelain e mais pra frente o git diff para as comparações. Por enquanto estou apenas utilizando o git status porcelain para poder pegar o absolutepath dos arquivos modificados, ainda não vou criar o repo pois está tudo hardcoded com arquivos pessoais e por segurança ainda não vou subir, mas jájá eu resolvo isso.**

**10/04/25: Hoje Eu implementei a IA no projeto, o texto dos arquivos .java que ainda não foram commitados já estão devidamente sendo entregues para a IA analisar, por enquanto ela analisa apenas um arquivo, mas vou dar um upgrade nesta feature amanhã.**

**11/04/25: Todas as funções (2) agora são chamadas através do function calling do langchain4j, criei um repositório para persistir os arquivos do diretório escolhido pelo usuário. Estou com certa dificuldade de pensar exatamente as features que eu quero desenvolver. A feature de sugerir uma mensagem de commit até está pronta, mas é complicado o llama3.1 sugerir alguma mensagem boa e eu confesso que não sou (ainda) um bom prompt engineer então fica mais dificil, mas de vez enquando ele sugere mensagens boas, mas a idéia é só ser uma sugestão, então no final o usuário vai poder escolher se ele quer usar aquela mensagem ou não. Inclusive no fim é um projeto java para executar comandos git usando IA, espero que eu consiga desenvolver algumas ideias que eu tenho.**

**12/04/25: Hoje eu estudei um pouco de typescript já que um dos planos é ficar bom em angular ainda este ano, li o inicio da doc e fiz alguns exercicios no app mimo, não codei ainda, amanhã farei.**

**13/04/25: Dei uma lida na documentação do typescript e iniciei um projeto para praticar.**

**14/04/25: Li mais uma parte da doc e implementei no projeto.**

**15/04/25: Mesma coisa de ontem, hoje eu li toda parte sobre funções.**

**16/04/25: Mesma coisa que nos ultimos 3 dias, hoje cheguei na sessão de objetos da doc do ts. ( Do nada eu comecei a ler a doc, eu não tinha planejado nada disso, mas vai fazer sentido quando eu voltar pro angular).**

**17/04/25: Terminei o handbook do ts, vou ler mais algumas coisas e começar a aplicar.**

**18/04/25: Iniciei a leitura da documentação do angular.**

**19/04/25: Li sobre declaração de components e signals.**

**20/04/25: Hoje eu tirei o dia para descansar um pouco.**

**21/04/25: Li sobre forms e reactive forms no angular.**

**22/04/25: Voltei ao projeto do monitorador de arquivos, porém retirei o langchain por enquanto, acabei ficando meio perdido na questão de onde utilizar a IA nesse sistema, talvez eu volte a utilizar apenas na sugestão do commit quando o usuário for commitar algo, mas por enquanto vou desenvolver todas as funções e dps eu penso onde eu vou encaixar o tooling ou o RAG tb.**

**23/04/25: Hoje eu dei mais um passo no projeto, ja consigo acessar os arquivos que saem do comando git status e armazená-los corretamente, agora eu preciso pensar no próximo passo.**

**24/04/25: Hoje pratiquei um pouco sobre o data binding do angular (models,inputs, FormsModule(ngModule)) e ainda refatorei um repository do projeto git, estou tentando mudar um pouco a maneira como eu codifico, recebi uma dica muito importante sobre criar funções de uma maneira com que possam ser utilizadas em outros programas e não atrelar tanto o código ao projeto em si, por exemplo ao invés de preencher uma estrutura de dados dentro de uma função que utilizo para salvar paths de arquivos que são repositórios git, eu retiro esse preenchimento, desacoplando a função e simplesmente faço esta função retornar uma lista, agora facilmente poderia criar talvez uma biblioteca de utilitários e declarar esta função la como um identificador de repositórios git. Eu confesso que não pensava assim antes, claro que nem sempre vai da para pensar em uma solução assim, mas é interessante.**


**25/04/25: Em paralelo ao projeto do git iniciarei meus estudos em Jakarta EE, já que eu fui direto do Java SE para o springboot, agora voltarei um pouco atrás para aprender o tão falado Jakarta.**

**26/04/25: Hoje passei o dia INTEIRO setupando um projeto com servlet + jsp ( SÓ O SETUP) mas no final consegui, provavelmente tem alguma maneira mais simples de fazer este setup, mas ta tudo certo, vou criar uma apizinha e linkar com um front-end em angular simples que eu estou fazendo (Só fiz o setup do jsp para brincar, depois eu faço um projeto com ele também).**

**27/04/25: Fiz mais uma revisãozinha em servlets, explorei o HttpServletRequest/Response amanhã testarei mais coisas com jsp também.**

**28/04/25: Criei uma apizinha simples utilizando servlets e consumi com o frontend em angular de um projetinho que eu to usando para estudar.**

**29/04/25: Comecei a ler a doc do angular material que provém componentes prontos ao angular, ja comecei a aplicar no mesmo projeto de ontem.**

**30/04/25: Hoje eu conheci a biblioteca Jsoup que serve para fazer webscrapping, que era um assunto que eu tinha curiosidade de aprender, comecei a fazer os primeiros testes no site books to scrape.**

**01/05/25: Iniciei um projeto onde vou criar um fluxo de login completo com autenticação, angular + JEE com servlets.**

**02/05/25: Passei o client de requisição de axios para httpclient que é nativo do angular, onde aprendi sobre observable e outras coisas.**

**03/05/25: Estudei sobre JWT e irei implementar no projeto amanhã mesmo.(Ainda não sei como)**

**04/05/25: Implementei o fluxo completo com JWT no projeto laboratório hoje, ainda tem muita coisa para melhorar mas ta funcionando, ainda pretendo adicionar o login com o google, github sem precisar de senha com oauth e openid, falta também criptografar a senha do usuário e arrumar um local mais seguro para armazenar os JWTs, não sei se é viável deixar no localstorage mesmo, ja que não tem nenhuma informação sensivel no payload.**

**05/05/25: Li a seção template da doc do angular e fui testando no próprio projeto do jwt, confesso que ainda estou confuso nos ng-container,ng-template e ng-content então provavelmente mais pra frente irei ler novamente, a idéia é que passando agora para as diretivas eu consiga voltar novamente para os outros 3 tópicos mais bem entendido, já que as primeiras 4 sessões são o coração do angular. Mais estou bem satisfeito com o progresso até aqui, é a primeira tecnologia que eu estou aprendendo 100% pela doc e praticando, então eu to bem satisfeito mesmo e irei fazer o mesmo para outras, INCLUSIVE lerei a doc do springboot após o angular. É como se eu tivesse desbloqueado um superPoder, infelizmente só fui desbloquear dps de 2 anos de estudo, mas antes tarde do que nunca.**

**06/05/25: Hoje li a seção diretiva do angular, um recurso muito poderoso para adicionar "features" a determinados componentes ou tags de uma maneira mais simples e organizada.**

**07/05/25: Hoje eu terminei as matérias da faculdade e reli a seção de diretivas da doc do angular.**

**08/05/25: Hoje eu li a seção de DI da doc e a seção routing e reli a de signals, acho que ja é o suficiente para criar algum projeto legal pro portfólio de fato, vou atrás disso ai.**

**09/05/25: Hoje eu inacreditavelmente comecei a revisar css, pois sinto que meu maior problema na hora de desenvolver um layout é o css, então como eu vou precisar criar um software completo eu preciso voltar novamente ao css e revisar oque eu aprendi la atrás.**

**10/05/25: Continuei a revisão de ontem e aprendi muita coisa sobre flexbox que eu não sabia/lembrava.**

**11/05/25: Descanso.**

**12/05/25: Continuei os estudos de css, dessa vez revisei grid o próx conteúdo é tailwind.**

**13/05/25: Ainda não comecei tailwind, terminei de ver alguns conteúdos que eu tinha pronto sobre grid e flexbox e iniciei uma novo estrutura de projeto, talvez esse vá para produção. Adicionando mais um relatório fora do horário padrão, configurei o auth2.0 em um projeto que estou fazendo, ja consigo gerar o JWT do google e posso enviar pro back-end fazer a autenticação, amanhã implementarei isto, to com dor de cabeça.**

**14/05/25: Hoje configurei o OpenID connect do google no projeto e ja tá sendo enviado pro back-end e verificado corretamente, agora precisa de organização e mais alguns detalhes.**

**15/05/25: Comecei a aprender tailwind e to aprendendo mais sobre css no curso de tailwind do que no curso de css em si, ja comecei a aplicar no projeto.**

**16/05/25: Hoje continuei lendo a doc e implementei algumas coisas com tailwind.**

**19/05/25: Tailwind ta me fazendo ter vontade de virar front-end, infelizmente sou péssimo, por enquanto, mas sigo os estudos, além disso implementei o endpoint de autenticação no projeto atual, falta organizar algumas coisas por que eu costumo fazer funcionar e dps organizo mesmo então ainda ta uma bagunça.**

**20/05/25: Hoje continuei estudando tailwind, refatorei o módulo de segurança, porém ainda ta uma bagunça.**

**21/05/25: Hoje refatorei novamente o módulo de segurança e organizei a bagunça, agora eu preciso adicionar algumas validações e ta pronto.**

**22/05/25: Voltei a estudar a documentação das apis do google, estou incomodado com um 403 que da no console antes mesmo de autenticar no google, preciso resolver isso dai, além disso terminei o curso de tailwindcss, deu pra aprender bastante, agora vou utiliza-lo apenas como consulta, além da doc claro.**

**23/05/25: Hoje pratiquei um pouco do tailwind criando um layout do curso.**

**24/05/25: Terminei o responsivo da primeira parte do website do curso.**

**27/05/25: Hoje dei continuidade ao projeto, fazendo a parte de acomodações.**

**29/05/25: Reorganizei minha rotina e dei continuidade a interface.**

**30/05/25: Interface finalizada, agora ja consigo criar interfaces de maneira mais "fácil", oque era o objetivo desde o começo. Agora eu posso voltar pro meu java.**

**03/05/25: 3 dias sem relatório... é um momento conturbado, mas não fiquei parado esses dias, terminei a interface que estava fazendo com o curso de tailwind jaja eu subo pro github, agr eu tenho uma matéria de redes pra estudar em menos de 5 dias :), aos poucos vou colocar tudo no seu devido lugar.**

**09/05/25: Well, terminei o curso de rede aos 45 do segundo tempo, aprendi muita coisa graças a Deus, mas fiquei alguns dias sem codar, devo estar enferrujado, hoje vo voltar pro meu javinha e reiniciar ou iniciar algum projeto.**

**25/05/25: Voltei, não estava parado, fiz bastante coisa nesse meio tempo, agora irei voltar a fazer meus relatórios, hoje eu voltei a estudar o curso de spring security.**
