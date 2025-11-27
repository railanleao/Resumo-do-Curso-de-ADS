### INTEGRAÇÃO CONTÍNUA
Integração contínua (CI - Continuous Integration) é o processo de engenharia de software que está sendo amplamente utilizado no movimento DevOps para isolar as mudanças para que elas possam ser imediatamente testadas e relatadas quando são adicionadas à base de código maior. 
O processo de integração contínua é fundamental para a implementação do DevOps. A palavra DevOps é originada a partir da composição dos prefixos Dev (desenvolvimento) e Ops (operações). Ele inclui a automação do desenvolvimento e teste sempre que as alterações no código são feitas.
A metodologia de integração contínua permite que você compartilhe o código e teste fazendo as mudanças no repositório de controle de versão compartilhada. Desta forma, qualquer um pode obter a versão mais recente do código. Isso ajuda a construir, testar e validar o processo completo. DevOps é a união de pessoas, processos e tecnologias para fornecer continuamente valor aos clientes. 
### Vantagens
- Melhora a produtividade do desenvolvedor;
- Ajuda a encontrar os erros mais rápidos;
- É possível entregar as atualizações com maior agilidade;
- Não há surpresas no final porque não há incompatibilidade;
- Há feedback sobre as mudanças locais feitas em todo o sistema;
- Automatiza a compilação e faz o teste de compilação automaticamente;
- Não há processos de integração longos e tensos;
- Verifica a viabilidade do código sem ter que esperar;
- Consenso quando se trata de testes frequentemente automatizados;
- A versão mais recente do teste, demo e lançamento está sempre disponível;
- Os códigos são modulares e menos complexos graças aos checkins frequentes;
- Menor tempo de depuração e mais tempo adicionando novos recursos;
- Máquina de integração dedicada e sistema de feedback contínuo.

## ENTREGA E IMPLANTAÇÃO CONTÍNUA
### Entrega Contínua (CD)
A entrega contínua (CD – Continuous Delivery) permite que as equipes de desenvolvimento automatizem o processo que move o software pelo ciclo de vida de desenvolvimento de software e pode fornecer muitos benefícios ao provisionar uma caixa de ferramentas integrada, incluindo o seguinte:  

  - Reduza o tempo de implantação por meio de testes e desenvolvimento contínuos;
  - Diminua os custos associados ao desenvolvimento de software tradicional;
  - Dimensione o desenvolvimento de software com base no tamanho do projeto;
  - Implante o código automaticamente em cada fase do ciclo de desenvolvimento.
    
A seguir estão algumas das coisas que o pipeline de entrega contínua ajudará você a fazer: 

  - Automatize compilações, testes de unidade e implantação;
  - Edite e envie código usando repositórios Git, rastreamento de problemas e seu IDE baseado na Web (ambiente de desenvolvimento integrado);
  - Crie uma caixa de ferramentas DevOps integrada para criar, implantar e gerenciar seus aplicativos com seus serviços, ferramentas de código aberto e ferramentas de terceiros;
  - Edite seu código de qualquer lugar que você escolher usar seu IDE para criar, editar, executar, depurar e concluir tarefas de controle de origem;
  - Use seu pipeline automatizado para entregar continuamente compilações, testes e implantações de maneira repetível;
  - Melhore a qualidade entendendo seu status de compilação, resultados de verificação de segurança, cobertura de código e cobertura de teste para que você possa avaliar se deve promover seu aplicativo para o próximo ambiente (por meio de portas de política para garantir automaticamente a qualidade antes da promoção).

### Implantação Contínua (CD) 
A implantação contínua (CD - Continuous Deployment) é uma estratégia de desenvolvimento de software em que as alterações de código em um aplicativo são liberadas automaticamente no ambiente de produção. Essa automação é impulsionada por uma série de testes predefinidos. Depois que as novas atualizações passam nesses testes, o sistema envia as atualizações diretamente para os usuários do software. 

A implantação contínua oferece vários benefícios para empresas que buscam dimensionar seus aplicativos e portfólio de TI. Primeiro, ele acelera o tempo de lançamento no mercado, eliminando o atraso entre a codificação e o valor do cliente – normalmente dias, semanas ou até meses. 

### Implantação contínua versus integração contínua 

Outro elemento-chave para garantir uma implantação contínua e perfeita é a integração contínua. Para que a automação dos processos de implantação funcione, todos os desenvolvedores que trabalham em um projeto precisam de uma maneira eficiente de comunicar as mudanças que ocorrem. A integração contínua torna isso possível. 

Normalmente, ao trabalhar no mesmo projeto de desenvolvimento de software, os desenvolvedores trabalham com cópias individuais de uma ramificação principal do código. No entanto, problemas de funcionalidade e bugs podem ocorrer depois que os desenvolvedores mesclam suas alterações na base de código principal, especialmente quando os desenvolvedores trabalham independentemente uns dos outros. Quanto mais tempo eles trabalham de forma independente, maior o risco. 

Com CI, todos mesclam suas alterações de código em um repositório pelo menos uma vez por dia. À medida que as atualizações ocorrem, os testes de compilação automatizados são executados para garantir que todas as alterações permaneçam compatíveis com o branch master. Isso funciona como uma proteção contra falhas para detectar problemas de integração o mais rápido possível. 

### Implantação contínua versus entrega contínua 

A entrega contínua é uma prática de desenvolvimento de software em que o software é construído de tal forma que pode ser lançado em produção a qualquer momento. Para conseguir isso, um modelo de entrega contínua envolve ambientes de teste semelhantes a produção.

Novas compilações executadas em uma solução de entrega contínua são implantadas automaticamente em um ambiente de teste automático de garantia de qualidade que testa qualquer número de erros e inconsistências. Depois que o código passa em todos os testes, a entrega contínua requer intervenção humana para aprovar as implantações em produção. A implantação em si é então realizada pela automação. 

A implantação contínua leva a automação um passo adiante e elimina a necessidade de intervenção manual. Os testes e desenvolvedores são considerados confiáveis o suficiente para que não seja necessária uma aprovação para liberação de produção. Se os testes passarem, o novo código é considerado aprovado e a implantação para produção simplesmente acontece. 

A implantação contínua é o resultado natural da entrega contínua bem feita. Eventualmente, a aprovação manual oferece pouco ou nenhum valor e é apenas lentamente as coisas. Nesse ponto, ela é eliminada e a entrega contínua se torna uma implantação contínua. 

### UTILIZAÇÃO DE FERRAMENTAS PARA CONTROLE DE VERSÕES DE SOFTWARE
O diretório Git é onde o Git armazena os metadados e o banco de dados de objetos de seu projeto. Esta é a parte mais importante do Git, e é o que é copiado quando você clona um repositório de outro computador. 

 O diretório de trabalho é uma simples cópia de uma versão do projeto. Esses arquivos são pegos do banco de dados compactado no diretório Git e colocados no disco para você usar ou modificar. 

 A área de preparo é um arquivo, geralmente contido em seu diretório Git, que armazena informações sobre o que vai entrar em seu próximo commit. É por vezes referido como o “índice”, mas também é comum referir-se a ele como área de preparo (staging area). 

O fluxo de trabalho básico Git é algo assim: 
1) Você modifica arquivos no seu diretório de trabalho. 

2) Você prepara os arquivos, adicionando imagens deles à sua área de preparo. 

3) Você faz commit, o que leva os arquivos como eles estão na área de preparo e armazena essas imagens de forma permanente para o diretório do Git.

Se uma versão específica de um arquivo está no diretório Git, é considerado commited. Se for modificado, mas foi adicionado à área de preparo, é considerado preparado. E se ele for alterado depois de ter sido carregado, mas não foi preparado, ele é considerado modificado. 
A partir deste parágrafo, você encontrará indicações sobre os tópicos mais relevantes sobre Git, no contexto do nosso MF. Essas indicações referem-se a capítulos de uma das principais referências sobre Git, o livro Pro Git (2014). 

[Fundamentos de Git](https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Obtendo-um-Reposit%C3%B3rio-Git)
[Branches no Git](https://git-scm.com/book/pt-br/v2/Branches-no-Git-Branches-em-poucas-palavras)
[Distributed Git](https://git-scm.com/book/pt-br/v2/Distributed-Git-Fluxos-de-Trabalho-Distribu%C3%ADdos)
[GitHub](https://git-scm.com/book/pt-br/v2/GitHub-Configurando-uma-conta)
 

Conforme foi apresentado no capítulo Distributed Git .do livro Pro Git, o Gitflow é um fluxo de trabalho legado do Git que no começo era uma estratégia inovadora e revolucionária para gerenciar ramificações do Git. Entretanto, o Gitflow perdeu popularidade para fluxos de trabalho baseados em “troncos”, que hoje são considerados práticas recomendadas para o desenvolvimento moderno e contínuo de softwares e práticas de DevOps. O Gitflow também pode ser difícil de usar com integração/implementação contínuas. 

O desenvolvimento baseado em “tronco” é uma prática de gerenciamento de controle de versão na qual os desenvolvedores fazem o merge de atualizações pequenas e frequentes em um “tronco” ou ramificação principais. Portanto, recomendo fortemente a leitura dos artigos [Desenvolvimento baseado em tronco](https://www.atlassian.com/br/continuous-delivery/continuous-integration/trunk-based-development), [Trunk Based Development (Medium)](https://medium.com/@mateusdecampos/trunk-based-development-1770f5e0dfc1) e [Trunk Based Development (TrunkBasedDevelopment)](https://trunkbaseddevelopment.com/).

Outra referência que certamente contribuirá muito com a sua formação está relacionada aos benefícios oferecidos pelo programa [GitHub Education](https://github.com/education?locale=pt-BR). Este programa oferece aos alunos acesso gratuito a várias ferramentas de desenvolvedor através de parceiros do GitHub. 

Como estudante, você também pode se inscrever para ter acesso aos benefícios do GitHub Student, que incluem acesso ao GitHub Global Campus, um campus digital para que nossa comunidade estudantil do GitHub aproveite alguns dos melhores programas que o GitHub Education tem a oferecer. O GitHub Global Campus inclui o GitHub Student Developer Pack, que oferece acesso gratuito a ferramentas e serviços usados por desenvolvedores profissionais, bem como acesso ao conteúdo da Campus TV, eventos estudantis, GitHub Classroom Assignments e muito mais, para ajudar os alunos em sua carreira técnica. Para obter mais informações, consulte "Inscrever-se para um pacote de desenvolvedor de estudante" e GitHub Education . 

Você também poderá se tornar um Especialista de Campus [GitHub](https://github.com/education/students?locale=pt-BR), um título concedido pelo programa GitHub Campus Experts. Este é um programa de treinamento voluntário oferecido gratuitamente a alunos, professores e membros do corpo docente vinculados a instituições de ensino parceiras do Github. 

Como aluno do programa, além do conhecimento técnico sobre GitHub, você adquirirá as habilidades necessárias para contribuir com a comunidade tecnológica da PUC Minas e terá acesso a um portfólio global com treinamentos promovidos pelo programa. Aproveite, desenvolva e aperfeiçoe suas habilidades de falar em público, escrita técnica, liderança de comunidade e desenvolvimento de software como um Especialista de campus do GitHub. 

O site do [GitHub](https://docs.github.com/en/get-started) também oferece uma vasta documentação sobre recursos oferecidos pelo GitHub, explorada como suporte por toda a comunidade que faz uso da ferramenta, que pode e deve ser explorada por você.  

Outro conteúdo indicado é o curso The Basics of GitHub,Links to an external site. contendo conceitos básicos sobre o GitHub e materiais adicionais para aprendizado na plataforma. 

[GitHub Docs](https://docs.github.com/en/get-started)
