# 1 Storytelling

 ### Blockchain e Drex

Blockchain e Drex, a moeda digital do Banco Central do Brasil (BACEN), estão transformando o sistema financeiro brasileiro, trazendo segurança, transparência e eficiência às transações. O sistema financeiro tradicional enfrenta desafios como lentidão, altos custos e exclusão financeira, dificultando o acesso de pequenos empreendedores e da população em geral. A Blockchain, com sua tecnologia de registros distribuídos, oferece uma solução segura e transparente, eliminando intermediários e reduzindo custos. O Drex, por sua vez, promete democratizar o acesso ao sistema financeiro, permitindo que todos, desde pequenos negócios até grandes corporações, realizem transações de forma rápida, barata e segura. Juntos, Blockchain e Drex não só modernizam o sistema financeiro brasileiro, mas também criam um ambiente mais inclusivo, seguro e eficiente, com potencial para impulsionar o crescimento econômico e a inclusão social no país.

### Problema e Solução Proposta

A plataforma DREX encontra-se atualmente em fase de testes através do Sandbox Real Digital disponibilizado pelo BACEN para algumas instituições financeiras pré-cadastradas. Uma vez que a plataforma seja validada, espera-se que ela entre em operação no ano de 2025 e revolucione o mercado financeiro brasileiro. Uma das principais apostas é no mercado de tokenização, onde um token é a representação digital de ativos reais (RWA - Real World Asset) ou direitos emitidos dentro de uma rede  DLT (Distributed Ledger Technology), no caso da DREX sendo a DLT baseada na plataforma de blockchain Hyperledger Besu onde o comportamento e características de um token é gerenciado por um smart contract.Em relação a utilização de tokens RWA emitidos na plataforma DREX, abre-se uma infinidade de novas aplicações e operações financeiras no Brasil, tais como: vendas de imóveis, terrenos, tokenização do agronegócio, entre outros.
 
Estima-se que, no mundo, a tokenização de ativos movimentará cerca de US$ 16 trilhões até 2030, e o Brasil não estará fora dessa tendência. Uma vez que a plataforma DREX seja lançada, será crucial a rápida adoção e integração da tecnologia por parte das instituições financeiras no Brasil para que elas consigam inovar e acompanhar esse mercado em constante evolução.Baseado no cenário acima, é proposta a criação de uma plataforma de tokenização RWA como serviço (TaaS - Token-As-A-Service) a fim de prover uma solução intuitiva e integrada para o gerenciamento e emissão de tokens na plataforma DREX. Assim, a plataforma de tokenização proverá os serviços necessários às instituições financeiras para poderem operar rapidamente na plataforma DREX, diminuindo o time-to-market e impulsionando a inovação contínua. Será também uma maneira de democratizar a utilização da plataforma DREX, já que nem todas instituições financeiras possuirão recursos e a capacidade técnica necessária para a rápida adoção dessa nova tecnologia. Além disso, a plataforma de tokenização estará trabalhando constantemente em parceria com as instituições financeiras e com o BACEN a fim de criar, emitir e aprovar a emissão de tokens para novos negócios.


# 2 O que esperamos aprender com esse projeto?
Implementar uma nova TaaS integrada à plataforma DREX é um grande desafio que engloba diversas áreas do conhecimento. Podemos citar:
	
1. Know-how de como realizar a integração de uma nova plataforma TaaS ao DREX, especialmente considerando todo o conhecimento específico relacionado à blockchain 	   da Hyperledger Besu.
2. Utilização eficiente de padrões de arquitetura de microsserviços para gerenciar grande volume de dados em tempo real
3. Conhecimento e implementação de padrões regulatórios exigidos pelo Banco Central do Brasil para operação na plataforma DREX
4. Conhecimento na implementação de mecanismos de tokenização e gerenciamento de tokens, incluindo criação de smart contracts de acordo com as normas e regras exigidas pelo Banco Central do Brasil
5. Estar sempre atualizado com as últimas tecnologias e tendências na área de segurança e compliance

# 3 Que perguntas precisam ser respondidas?
### Com o decorrer do projeto, algumas perguntas importantes precisarão ser respondidas:

1. Como será a escalabilidade da plataforma à medida que o número de clientes e transações aumentar?
2. Quais são exatamente todos os requisitos mínimos de segurança e compliance necessários para operar o negócio?
3. Quão trabalhoso será a integração de uma nova plataforma ao DREX?
4. Qual o plano de contingência caso haja algum problema na plataforma?
5. Quais são os requisitos mínimos exigidos pelo Banco Central para permitir a integração da plataforma ao Sistema Financeiro Nacional via DREX?
6. É necessário a utilização de um mecanismo de cache tal como Redis? Se sim, onde?

# 4 Quais são os nossos principais riscos?
Para garantir o sucesso na implementação de tecnologias como Blockchain e Drex, precisamos responder a várias perguntas e considerar os principais riscos. Em primeiro lugar, devemos definir claramente o problema específico que estamos resolvendo com essas tecnologias e como elas melhoram ou substituem o sistema atual. Também é crucial avaliar a viabilidade técnica, questionando se a infraestrutura tecnológica existente é adequada para suportar a implementação dessas tecnologias e se existem restrições técnicas a serem superadas. Além disso, precisamos entender o impacto econômico do Drex na economia digital e nos sistemas de pagamento do Brasil, bem como seu efeito em consumidores e empresas. As implicações regulatórias também devem ser consideradas, assegurando que estamos em conformidade com as leis nacionais e internacionais. Outro aspecto crítico é a segurança: precisamos garantir a segurança e a privacidade das transações, identificar possíveis vulnerabilidades e planejar como mitigá-las. A adoção e a educação são igualmente importantes; devemos garantir que consumidores e empresas adotem e compreendam essas novas tecnologias, desenvolvendo estratégias de educação e treinamento necessárias.A sustentabilidade e a manutenção também são fatores a serem considerados, pois é necessário avaliar os custos contínuos de operação e manutenção e garantir a sustentabilidade a longo prazo da solução. Entre os principais riscos, destaca-se o risco de ataques cibernéticos, como hacking ou fraudes digitais, que podem comprometer a integridade do Blockchain ou do Drex. Além disso, existe o risco de baixa adoção pelo público devido à falta de entendimento, desconfiança ou dificuldades técnicas. Além disso, precisamos considerar o impacto econômico adverso que a introdução do Drex pode ter, como a desestabilização econômica ou o efeito negativo sobre o sistema financeiro tradicional. Por fim, a reputação é um risco a ser considerado, já que falhas na implementação ou uso podem prejudicar a reputação das instituições envolvidas. Portanto, essas perguntas e riscos precisam ser considerados e endereçados de maneira estratégica para garantir o sucesso na implementação dessas novas tecnologias. 

# 5 Crie um plano para aprender o que precisamos para responder a perguntas específicas.

**1. Como será a escalabilidade da plataforma à medida que o número de clientes e transações aumentar?**
Realizar testes de carga e simulação de alto tráfego para entender como a plataforma se comporta com um aumento no número de clientes e transações além de estabelecer uma estratégia de monitoramento contínuo para identificar gargalos de performance.

**2. Quais são exatamente todos os requisitos mínimos de segurança e compliance necessários para operar o negócio?**
Em relação aos requisitos de compliance, consultar as normas e diretrizes do Banco Central do Brasil (BCB) e de entidades reguladoras participantes, além de identificar os requisitos específicos de segurança da informação, proteção de dados (LGPD), prevenção à lavagem de dinheiro (PLD/FT), entre outros.
Em relação a segurança, realizar uma análise de risco detalhada para identificar potenciais vulnerabilidades, garantir que a implementação de criptografia de rede esteja de acordo com as normas regulatórias e estabelecer políticas de governança e auditoria para garantir conformidade contínua.

**3. Quão trabalhoso será a integração de uma nova plataforma ao DREX?**
Para responder a essa pergunta, será necessário primeiramente analisar a documentação técnica e APIs fornecidas pelo Banco Central para o DREX, além de avaliar a complexidade das chamadas de API, formatos de dados, e requisitos de segurança para a integração. Após, desenvolver um plano de integração e validação das funcionalidades em um ambiente de teste integrado.

**4. Qual o plano de contingência caso haja algum problema na plataforma?**
Será necessário criar um plano de recuperação de desastres (DRP) que inclua redundância de sistemas e failover automático e estabelecer um plano de comunicação para notificar stakeholders em caso de falhas significativas. Durante a operação, é importante conduzir testes periódicos de recuperação para validar a eficácia do plano de contingência e documentar e revisar regularmente o plano de contingência para incorporar melhorias e mudanças.

**5. Quais são os requisitos mínimos exigidos pelo Banco Central para permitir a integração da plataforma ao Sistema Financeiro Nacional via DREX?**
Para isso seria necessário entrar em contato com o Banco Central para obter uma lista detalhada de requisitos para integração com o Sistema Financeiro Nacional via DREX. Também, é importante participar de seminários, workshops ou reuniões organizadas pelo Banco Central para entender as expectativas e melhores práticas.

**6. É necessário a utilização de um mecanismo de cache tal como Redis? Se sim, onde?**
Para realizar essa análise é necessário analisar padrões de acesso e consulta de dados para identificar áreas de alta latência e validar através de testes de carga se a utilização de Redis pode realmente melhorar a performance.

 # 6 Crie um plano para reduzir riscos.
Segue abaixo alguns dos principais planos que podem ser seguidos para mitigar riscos apresentados:

Em um primeiro momento, para definir claramente o problema e a viabilidade técnica, é importante entrar em contato com o Banco Central para obter uma lista detalhada de requisitos para integração com o Sistema Financeiro Nacional via DREX. Também, é importante participar de seminários, workshops ou reuniões organizadas pelo Banco Central para entender em detalhes a plataforma DREX.

Em relação ao impacto econômico e regulação, uma alternativa seria conduzir estudos de impacto econômico para prever como o Drex afetará a economia digital e os sistemas de pagamento no Brasil e avaliar os efeitos potenciais em consumidores, empresas e o sistema financeiro tradicional.

Para garantir a conformidade regulamentar é importante revisar e garantir conformidade com todas as leis e regulamentações nacionais aplicáveis à implementação da plataforma DREX. Além disso, estabelecer canais de comunicação regulares com órgãos reguladores para garantir alinhamento contínuo é outra prática importante.

Sobre a segurança e privacidade, podemos citar que um bom plano para reduzir riscos seria conduzir auditorias de segurança e testes de penetração regulares para identificar e corrigir vulnerabilidades. Além disso, garantir a correta implementação de criptografia ponta-a-ponta e autenticação multifator.

Para mitigar os riscos relacionados à adoção e educação referente a nova plataforma, uma ideia seria implementar programas de treinamento para empresas e clientes que utilizarão a plataforma TaaS.

# 7 Quem são as partes interessadas?
Em um primeiro momento podemos dizer que as partes interessadas nessa nova plataforma TaaS seriam as instituições financeiras com sede no Brasil e cadastradas na CVM, aptas a operarem no Sistema Financeiro Nacional. Além disso, podemos também ver o Banco Central como uma possível parte interessada, já que a plataforma TaaS seria uma maneira de democratizar a utilização da plataforma DREX, já que nem todas instituições financeiras possuirão recursos e a capacidade técnica necessária para a rápida adoção dessa nova tecnologia. Considerando pela perspectiva de negócio, os investidores da plataforma TaaS também podem ser considerados uma parte interessada, já que interessa a eles o sucesso e crescimento da plataforma.

# 8 O que eles esperam ganhar?

Focando basicamente nos clientes da plataforma TaaS, eles esperam ganhar:

**1. Facilidade de Integração:** Uma interface simplificada para integração com o Drex, permitindo que as instituições financeiras possam criar e gerenciar tokens com menor complexidade técnica.

**2. Performance:** a utilização de padrões como CQRS, microsserviços e comunicação baseada em eventos garantirá que a plataforma suporte grandes volumes de transações com baixa latência.

**3. Segurança:** A plataforma oferecerá uma infraestrutura segura para emissão e transferência de tokens, cumprindo com os requisitos regulatórios e de conformidade.

# 9 Quem são os usuários?
Os principais usuários são:
1. Instituições financeiras com sede no Brasil e cadastradas na CVM aptas a operarem no Sistema Financeiro Nacional, incluindo o DREX.

3. De uma perspectiva interna da plataforma, todos os colaboradores com acesso a ela tais como desenvolvedores, administrativo, compliance, segurança, etc.
# 10 O que eles estão tentando realizar? 
1. Instituições financeiras - estão utilizando os serviços fornecidos pela plataforma TaaS com o objetivo de terceirizar todo processo de gerenciamento e emissão de tokens na plataforma DREX, diminuindo o time-to-market e custos de implantação.

2. Colaboradores - utilizam os serviços fornecidos pela plataforma para manter a operação do negócio.
# 11 Qual o pior que pode acontecer?
Ao criar uma plataforma de tokenização baseada na plataforma DREX, o pior que poderia acontecer, na nossa opinião, seria a fraca adoção do mercado a essa nova tecnologia ou descontinuação do DREX por motivos secundários (políticos, orçamentários, etc). Isso impactaria diretamente a plataforma de tokenização, possivelmente inviabilizando o negócio como um todo.
# 12 Desenhe uma arquitetura
Segue abaixo uma proposta de arquitetura para a plataforma de tokenização integrada ao DREX:
![Captura de Tela 2024-08-17 às 09 49 31](https://github.com/user-attachments/assets/ba548056-6173-46c8-9f76-1fa257145e94)
# 13 Faça uma descrição de cada um dos componentes que você desenhou

**1. API Gateway:**
Centraliza e gerencia as solicitações API vindas das instituições financeiras, aplicando regras de segurança, autenticação e roteamento para os microservices apropriados. Utiliza protocolo HTTPS/REST para lcomunicação com clientes

**2. Auth0 Authentication Server:**
Autentica e autoriza os usuários e clientes da plataforma, integrando-se com o API Gateway.

**3. Token Manager:**
Microsserviço responsável pela criação, emissão, e gerenciamento de tokens. Conecta-se com o Smart Contract Manager através da Fila de Mensagens. Além disso, utiliza CQRS para separar comandos de consultas através da utilização de um Event Store e Read Storage para cada microsserviço, garantindo eficiência em operações de grande volume.

**4. Smart Contract Manager:**
Microsserviço responsável por gerenciar o ciclo de vida dos contratos inteligentes, desde a criação até a implementação e monitoramento. Comunica-se com o Microsserviço Drex Integration através da Fila de Mensagens.

**5. Drex Integration:**
Microsserviço responsável por auxiliar na integração com a rede Drex, baseada em Hyperledger Besu, para registrar e gerenciar contratos e transações na blockchain. Utiliza protocolo RPC para comunicação.
- Protocolos: Utiliza RPC e outros protocolos específicos da blockchain.
- Ponto Crítico: Latência na comunicação com a blockchain e garantias de consistência e integridade das transações registradas.

**6. Event Store:**
Banco de Dados único para cada microsserviço

**7. Read Storage:**
Materialize View utilizada pelo query model do padrão CQRS. Esse banco de dados de leitura é atualizado através eventos enviados pelo Command Model utilizando a Fila de Mensagens 

**8. Microsserviços de Sustentação:**
Aqui é citado um conjunto de microsserviços extras mas considerados fundamentais para a operação/sustentação da plataforma TaaS. Apesar de não estarem diretamente ligados ao core business, eles são citados aqui com o intuito de enfatizar a existência de complexidade adicional envolvida na criação da plataforma.

**9. Fila de Mensagens:**
Esse componente representa o padrão pub-sub onde microsserviços se comunicam via eventos. É um padrão útil para diminuir o acoplamento entre serviços, ser escalável e tolerante a falhas.

**10. Command Service / Command Model:**
Modelo de escrita utilizado pelo padrão CQRS

**11. Query Model / Query Model:**
Modelo de leitura utilizado pelo padrão CQRS

**12. REST API:**
Adaptador do microsserviço utilizado para comunicação via REST API

**13. HyperLedger Besu - Fullnode:**
Nós criados através da plataforma DREX para permitir a conexão de agentes externos à plataforma.

# 14. Descreva requisitos que você (s) considera importante e por quê? (Mínimo 5) 
**Segurança -** dado que estamos propondo uma solução para o sistema financeiro, a implementação de uma política de segurança sólida e robusta é fator essencial para a credibilidade e sucesso da solução. Utilização de API Gateway, Servidor de autenticação Auth0, cripitografia de ponta a ponta, implementação de políticas de controle, teste e validação entre outros pontos, são fatores fundamentais.
**Escalabilidade -** Arquitetura baseada em microservices que permite a escala horizontal de componentes individuais, especialmente para o Token Manager e o Drex Integration.
**Comunicação em Tempo Real -** Utilização de uma fila de mensagens para comunicação assíncrona e baseada em eventos entre microservices, essencial para a integridade e sincronização dos estados na plataforma.
**Integração com a Plataforma Drex -** A conexão com a rede DLT do Drex via Drex Integration deve ser eficiente e segura, utilizando protocolos como RPC e garantindo a consistência dos registros na blockchain.
Latência da Rede e Desempenho - Minimizar a latência, especialmente nas interações com a plataforma Drex, que pode ter requisitos específicos de performance.
# 15 Sobre o que o diagrama ajuda você a raciocinar/pensar?
O diagrama apresenta os principais componentes necessários para a implementação da plataforma TaaS, destacando os principais usuários da plataforma e a integração necessária com a rede do Sistema Financeiro Nacional e os principais microsserviços do core business. Sobre a implementação da plataforma, o diagrama apresenta em alto nível alguns dos principais padrões e conceitos que devem ser levados em consideração, tais como padrão de microsserviços, pub-sub (eventos), autenticação via API Gateway, que são padrões relacionados a questões fundamentais tais como comunicação em tempo real, escalabilidade e segurança. 
Com a criação de microsserviços independentes, o diagrama nos permite tratar cada aspecto da plataforma de forma isolada, facilitando o desenvolvimento, testes e manutenção. Isso também torna possível escalar e aprimorar partes específicas sem afetar o sistema como um todo.
Adicionar o conjunto de Microsserviços de Sustentação nos faz refletir a respeito da complexidade adicional necessária para criar uma plataforma TaaS completa.
O diagrama também abre espaço para discussões relacionadas à integração com a plataforma DREX. Mencionar de forma explícita a Rede do Sistema Financeiro Nacional, incluindo as entidades validadoras (Banco Central e SELIC), também abre espaço para discussões relacionadas a questões regulatórias existentes para a operação da plataforma proposta.
# 16 Quais são os padrões essenciais no diagrama?
**Padrão CQRS:** é a separação das operações de leitura e escrita. Isso permite a adoção de ferramentas otimizadas para cada uma das operações e aumento da performance, já que transações serão executadas em um banco separado do que escrita.
**Padrão Pub-Sub / Fila de Mensagens:** Comunicação assíncrona entre microsserviços baseada em eventos a fim de diminuir o acoplamento entre eles, tornar o sistema escalável, tolerante a falhas e flexível.
**API Gateway:** Ponto de entrada único para requisições HTTP de REST APIs. Além disso, o API Gateway centraliza questões de autenticação e autorização, roteamento de requisições, incluindo questões de monitoramento e logging.
**Padrão Microsserviço:** é um padrão que permite dividir e atacar o problema de forma isolado, onde objetiva-se a criação de um novo microsserviço cada subdomínio de negócio com o mínimo de acoplamento possível entre eles. 
# 17 Existem padrões ocultos?
Sobre padrões ocultos, pode-se citar:
	**Utilização de Redis Cache:** Esse padrão não é explicitamente mencionado, mas é uma opção bem difundida no mercado para armazenar em cache dados frequentemente acessados ou demorados de processar, melhorando a performance e reduzindo a latência.
	**Balanceamento de Carga:** Distribui o tráfego de entrada entre os microsserviços para garantir a disponibilidade e a escalabilidade. O balanceamento de carga não foi explicitamente mencionado por ser considerado uma otimização de infraestrutura, logo, não sendo objetivo principal neste diagrama.
# 18 Qual é o Metamodelo? 
Metamodelo baseado em domínio, principalmente pelo fato de enfatizarmos a utilização do padrão de microsserviço.
# 19 Pode ser discernido no diagrama único? 
Sim. A utilização da simbologia da arquitetura hexagonal torna explícito que estamos utilizando um padrão de microsserviços (sub-domínios)
# 20 O diagrama está completo? 
O objetivo do diagrama é demonstrar em alto nível os principais (1) usuários, (2) módulos necessários para a implementação de uma plataforma TaaS, (3) integrações com a plataforma DREX, (4) principais agentes externos relacionados e (5) principais padrões arquiteturais utilizados na implementação da plataforma. O objetivo é fornecer ao leitor um ponto de partida para discussão. Com base nisso, acreditamos que o diagrama esteja completo.
Todavia, é claro que questões mais técnicas e de infraestrutura foram omitidas, tais como utilização de cache, balanceamento de carga, questões regulatórias e normas técnicas.
# 21 Poderia ser simplificado e ainda assim ser eficaz? 
Bem, poderíamos abstrair informações a respeito da Rede DREX e mencionar os microsserviços de sustentação de forma a deixar claro que há vários, mas que estamos apenas citando alguns para que o usuário tenha uma noção da dimensão do trabalho envolvido. No desenho original pode ser que o usuário assuma que os microsserviços de sustentação citados são aqueles já definidos e que não há possibilidades de mudança, o que não é verdade. Entretanto, o foco do diagrama não é esse, apesar de acharmos importante citar que há, sim, vários outros microsserviços envolvidos que não sejam os do core business.
Proposta de simplificação:
![Captura de Tela 2024-08-17 às 09 52 08](https://github.com/user-attachments/assets/4c2ccdd7-32ae-4b89-95f5-24e45acaae80)

# 22 Houve alguma discussão importante que vocês tiveram como equipe?
Acreditamos que uma discussão relevante que tivemos foi relacionada a inserir ou não mais informações a respeito de padrões de segurança, dado que esse é um ponto chave do sucesso da plataforma. Entretanto, apesar de importante, achamos que inserir mais informações sobre segurança tiraria o foco do diagrama (descrito anteriormente) além de inserir no desenho uma série de informações de mais baixo nível que seriam difíceis de representar através de um desenho sem ser por escrito.
# 23 Que decisões sua equipe teve dificuldade para tomar?
A definição dos microsserviços core business foi um pouco difícil de realizar, dado que a divisão de microsserviços baseado em sub-domínios requer um entendimento muito profundo do negócio. Como estamos basicamente criando uma solução que é um novo modelo de negócio para a nova plataforma DREX, foi preciso ler a fundo conceitos de blockchain, DREX, hyperledger besu, tokenização, TaaS, smart contracts, integração com o DREX, e associar essas informações ao conceito de microsserviços. 
# 24 Que decisões foram tomadas sob incerteza?
Acreditamos que tenha sido a decisão de não deixar explícito a utilização de Redis cache, apesar de acharmos que muito provavelmente a utilização de cache será necessária para performance e experiência do usuário. 
# 25 Houve algum ponto de decisão sem retorno que o forçou a desistir de uma determinada escolha?
Podemos citar a questão de expandir em mais detalhes como a integração seria realizada entre lllas plataformas TaaS e DREX. Entretanto, ao analisar as questões técnicas, observou-se uma ampla variedade de informações englobando padrões e políticas do Banco Central, funcionamento da ledge Hyperledger Besu, questões de segurança e autenticação que, juntas, poderiam ser expandidas em um novo diagrama relativamente complexo. Como o objetivo do diagrama é demonstrar a existência dessa integração e os principais atores envolvidos, e não o seu funcionamento e implementação em si, foi decidido por não incluir esses detalhes adicionais.
# 26 Desenhe 3 Arquiteturas com o projeto que você desenvolveu na aula em cada uma das camadas do C4 (subir somente a imagem jpg/jpeg):
# Nível Contexto
![Captura de Tela 2024-08-17 às 09 54 18](https://github.com/user-attachments/assets/53aa819a-d82d-4c38-9f72-e3c8721b65d8)

# Nível Container
![Captura de Tela 2024-08-17 às 09 54 35](https://github.com/user-attachments/assets/42f0de87-b056-408d-958d-e769592e4c4d)

# Nível Componente
![Captura de Tela 2024-08-17 às 09 54 54](https://github.com/user-attachments/assets/1f012f9f-17c2-401e-b8c5-4191c18a3d95)



