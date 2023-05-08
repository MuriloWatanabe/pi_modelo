o# Projeto Integrador - Modelo

Início de projeto 27/02/2023.

Alunos: Murilo Watanabe(https://github.com/MuriloWatanabe), Phelipi Moser (https://github.com/PhelipiM) e William Nunes (https://github.com/Nunes-Willi)

Links do projeto:

-   [Link do projeto](https://github.com/MuriloWatanabe/pi_modelo)

<!-- # Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.
   

# Desenvolvimento

-   As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
-   Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.

## 2- Empréstimo

**Gerenciamento de uma biblioteca**

Uma ONG, chamada Sala Arco Íris, ajuda crianças de baixa renda em sua educação básica. Atualmente, recebeu uma doação de mais de 1000 livros e está montando a sua biblioteca. Eles querem emprestar os livros para as crianças e os pais das crianças. Apesar de
terem um computador e as estantes necessárias à disposição nessa nova biblioteca, não possuem verba suficiente para um leitor de impressão digital ou para produção
de carteirinhas para todas as crianças. Para isso, eles precisam de um sistema que gerencie todo o acervo, empréstimos, livros disponíveis, etc. mas que isso ocorra de maneira simples e sem necessidade de novos gastos. Também é importante que haja relatórios, permitindo o controle dos empréstimos e dos livros disponíveis no acervo.

## 3- Ordem de Serviço (O.S.)

**Manutenção de computadores**

Sr. Sálvio, nosso cliente, fez um curso de manutenção de celulares e smartphones e decidiu abrir um negócio, onde ele é responsável pelos consertos e sua esposa Marília realiza os atendimentos aos clientes. Com sua visão empreendedora, ele sentiu a necessidade de um software que auxilie
sua esposa nas tarefas diárias. Para isso, ele deseja um sistema que gerencie os clientes, orçamentos, serviços e retirada dos equipamentos. Sendo um negócio pequeno, é muito importante que ele consiga ter relatórios que lhe ajudem na gestão da
empresa, como dos status dos serviços. -->

# Situação Problema

<!-- **Nessa parte a equipe deve descrever a situação problema que será resolvida pelo sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

-   Pesquise sobre empresas do ramo escolhido
    para entender como funcionam;
-   Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
-   Simule uma situação real. Lembre-se que são
    propostas com empresas fictícias, sendo assim,
    você terá que tomar certas decisões sobre como
    a empresa funciona em relação às coisas que
    não estão definidas no documento base (por
    exemplo, no caso da padaria, dizemos que seu
    Genival contratou mais funcionários, mas saber
    quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a
    empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas: -->

-   **Introdução**: Olá nós somos a empresa DevCar, trabalhamos com revenda de carro desde 27/02/2023.Os donos da empresa são: Murilo Watanabe, Phelipi Moser e William Nunes. E ao todo possuimos cinco funcionários: Atendente(Vendedor); Gerente de  Estoque.
  
-   **Situação-problema**: <!--Aborde em detalhes como a empresa funciona, procurando seguir umaordem lógica dos acontecimentos e organizando parágrafos diferentes para cada coisa diferente que for explicar (como faria em uma redação);--> A empresa funciona da seguinte forma, um cliente vem até a loja física procurar um veículo, o atendente ô recepiciona anotando todas as caracteristicas do carro desejado pelo cliente através de um bloco de orçamento, ao terminar o processo de anotação é enviado um orçamento/pedido para o gerente de estoque fazer uma análise de crédito através do sistema de revenda, após a finalização da análise é enviado uma autorização de revenda ao vendedor, que avisará o anfitrião da conclusão do orçamento/pedido, iniciando assim a parte de documentação realizada pelo vendedor e o agendamento e autorização da revenda do veículo.
  
   **Conclusão**: <!--tenha um parágrafo de conclusão focando nos problemas que você notou dentro da situação problema analisada e aponte brevemente como um software poderia ajudar a resolvê-los.;--> A ideia do software é de sistematizar todo o processo de gerenciação de relatórios, dada as informações do cliente e do estoque, o foco do software é de facilitar as informações dos carros que entram e saiem do estoque.

# Descrição da proposta

A nossa proposta de solução para a empresa é implementar um sistema integrado que automatize o processo de venda de veículos, incluindo o registro digital das características do veículo pelo atendente, análise de crédito automatizada, notificações automáticas para o vendedor, documentação digitalizada e agendamento automatizado de revendas. Essas soluções visam agilizar o processo, reduzir o uso de papel e aumentar a eficiência operacional da empresa.
<!-- Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá **explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará**. Pense nesse texto como uma **introdução ao seu cliente** do que você pretende fazer por ele, para que ele confirme se realmente está dentro do
desejado e permita sua continuidade.

**Alguns pontos importantes a se destacar são:** -->

  **Qual o foco de ação do software**
  
  Foco principal do software e de procurar e organizar a pesquisa e orçamentos dos carros para os clintes.  <!--relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails. -->

**Os níveis de usuário do sistema**. 
   
   A Prioridade seja que o acesso em geral apenas que o atendente ò tenha, mas alguns funcionários também poderão se utilizar ao sistema.  <!--Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos diferentes, etc.-->

**O que poderá ser feito no software**.

Orçamento,ánalise de compra e venda, e gerenciamento de informações do cliente.
<!-- Apenas o principal, sem pensar em
    telas ou detalhes específicos, pois isso será feito em outro momento. -->

 **Se houver mais de um nível de usuário**

 As principais diferenças entre os niveis de atendente e gerente de estoque seria a manipulação de informações entre cliente e veículo, por exemplo o atendente lidaria com o orçamento e pesquisa de dados atendidos pelos clientes,e o gerente lidaria com gerenciamento de dados sobre os veículos(entrada,saída,data,características,valor e etc..)
 <!-- ressaltar as diferenças entre
        eles na descrição da proposta.

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
miprecisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo. -->


**Regras de negócio**



 - Regra de negócio de entrada de dados dos veiculos 

RN001-

RN002-

RN003-

RN004-

RN005-
  
 - Regra de ngócio de pedido
  
RN01- Iniciando o pedido: O gerente fala dos veículos que estão na loja e no estoque, para que o cliente anasalise e escolha o veículo que deseja;

RN02- Verificação no estoque: Após a escolha, o gerente envia para o gerenciador de estoque o veículo escolhido pelo cliente;

RN03- Após verificação do estoque: O gerenciador do estoque vai alertar se há o veículo desejado. Caso haja o produto seguir para a quarta regra, caso oposto encerrar pedido;

RN04- Coleta de dados: Para a continuação do pedido o gerente deve pegar todos os dados do cliente e de seu veículo desejado;

RN05- Transferência de documetos: Após a confirmação do pedido o gerente deve fazer as tranferência dos documentos do carro para o cliente;

RN06- Após transferência dos documentos o atendente deve confirmar a aprovação do veículo para o cliente;



<!-- RN006- Esteja presente nas redes sociais: Use as redes sociais para divulgar seus carros e manter seus clientes informados sobre novidades, promoções e eventos.

RN007- Ofereça financiamento: Para atender às necessidades de todos os clientes, ofereça opções de financiamento e leasing.

RN008- Invista em publicidade: Invista em publicidade em canais estratégicos, como revistas de carros, jornais locais, rádio e televisão.

RN009- Ofereça serviços adicionais: Ofereça serviços adicionais, como seguro de carro, transferência de propriedade, revisões e manutenção.

RN010- Atenda bem seus clientes: Treine sua equipe para atender bem seus clientes e estar sempre disponível para ajudá-los em suas necessidades. A boa reputação e o boca-a-boca são fundamentais para o sucesso de qualquer negócio. -->

**5.4 Requisitos funcionais**

**ENTRADA**
RF01 -Sistema de cadastro de clientes: O sistema deve permitir o cadastro de clientes com as seguintes informações: Dados necessários: nome completo, cpf, endereço, número de telefone, e-mail e outras informações relevantes.Usuários: Vendedor/Administrador

<!-- **Cadastro de veículos** -->
RF02 - Sistema de cadastro de veículos: O sistema deve permitir o cadastro de veículos com as seguintes informações: Nome, Marca, Ano , Cor, Quilometrageme outras informações.

RF02 - Gerenciamento de conta do cliente: um sistema para que os administradores possam gerenciar suas contas, atualizando suas informações dos clientes como dados pessoais, dados de pagamento, histórico de pedidos e outras informações.

**PROCESSO**

**quais tipos de funcionarios**

RF03 - Autenticação do **funcionarios**: um sistema para autenticar o cliente ao fazer login em sua conta antes de realizar uma compra, para garantir a segurança das informações pessoais e de pagamento do cliente.

RF04 - Venda:(**alterar para compras física**) um sistema para permitir que os clientes adicionem itens ao carrinho de compras, visualizem o total de sua compra e façam alterações antes de finalizar o pedido.

RF05 - pagamentos: um sistema seguro e confiável para processar os pagamentos dos clientes por meio de várias opções, como cartões de crédito, PayPal ou outros métodos de pagamento. **tipos de pagamento**


**tela de transferencia de documentos**

RF06 - Confirmação de pedido: um sistema para enviar uma confirmação de pedido para o cliente, incluindo informações sobre o produto, preço total, informações de envio e estimativa de tempo de entrega.


**SAÍDA**
**relatórios??????**



<!-- Um requisito funcional deve ser estruturado da seguinte forma:

Nome do requisito funcional: descrição do requisito.
Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.

*5.4.1 Nome do requisito funcional*

<!-- R.F. 99 - Nome do requisito funcional: é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional) seguida da numeração, para melhor identificação do requisito, acrescido do formato “Substantivo + onde será feita a ação”. Por exemplo:

R.F. 01 - Registro de Funcionários
R.F. 15 - Gerenciamento de consultas
R.F. 04 - Débito em conta corrente
Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números. -->

*5.4.2 Descrição do requisito funcional*

Descrição do requisito: local para descrever a função deste requisito.

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa. Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de usuários. Outro exemplo é algo que faz sentido apenas para um software, como a própria autenticação. -->

**6.4 Estrutura do requisito não funcional**

R.N.F. 01 - Navegador homologado: O sistema deverá ser homologado somente para o navegador Google Chrome.

R.N.F. 02 - Processador: É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.

R.N.F. 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de Ram para melhor performance.

R.N.F. 04 - Arquitetura: A arquitetura que será utilizada para criação do sistema será Rest.

R.N.F. 05 - Conexão com banco de dados: Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.

Sistema de Ordem de Serviço:

RNF 01 - O sistema deverá rodar em qualquer navegador como Chrome, Opera, Fire Fox, Safari e Microsoft Edge

R.N.F. 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o CSS3 e o HTML5, além das bibliotecas de jQuery e Javascript.

R.N.F. 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Java.

R.N.F. 04- Interoperabilidade: O banco de dados será o Mysql, com a linguagem SQL de banco, sendo todo produzido através do mysql Workbench .
R.N.F. 05- Forma de uso do software: O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.
R.N.F. 06- Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados.
R.N.F. 07- Autenticação: Para realizar o acesso ao sistema é necessário ter um usuário de autenticação criado pelo administrador, além da possibilidade de solicitar um envio de redefinição de senha.
R.N.F. 08- Web Server: O servidor web utilizado será o Apache Tomcat, nas versões mais atualizadas. R.N.F. 08- Níveis de segurança: O software terá diferentes tipos de acesso para cada tipo de login, tendo as permissões ideais a função de cada um.