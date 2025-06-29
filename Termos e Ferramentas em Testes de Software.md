#CAPITULO I - Termos Relacionados a problemas em Software

	##Bug
		Bug é o nome dado a maus funcionamentos no software/sistema é um erro que pode fazer com que componentes ou o sistema não executem suas funções necessárias, ou seja, são erros encontrados durante o teste, com potencial de causar problemas no funcionamento do sistema.
		Eles podem ter um impacto negativo no desempenho no software, podendo causar perdas de dados, falhas de segurança e insatisfação dos usuários. Por isso, é importante a correção dos bugs o mais rápido possível para garantir a qualidade do produto.

	## Erro
		Em teste de software, **Erro**, é o nome dado a falhas cometidas pelo desenvolvedor durante o ciclo de vida do desenvolvimento do sistema de software, podendo ocorrer em qualquer fase do desenvolvimento, seja ela codificação, o design ou testes. Esses erros geralmente são descobertos posteriomente durante os testes de software.
		Erros e bugs não são a mesma coisa, por mais que sejam muitas vezes confundidos por usuários, sendo erro resultante da ação humana incorreta, como um erro de sintaxe ou na interpretação errada da interpretação dos requisitos. Já o bug, também conhecido como defeito, é a manisfestação visível desse erro no software, ou seja, o comportamento incorreto ou inesperado do programa.
		É possível que existam erros de software que não resultem falhas. Isso ocorre por que falhas são as manifestações visíveis de um erro, que pode ser resolvidos ou compensados antes mesmo que causem uma falha perceptível ao sistema, principalmente em sistemas bem projetados e com mecanismos de tratamento de erros.
	
	## Falha (Failure)
		Falha é o nome dado a um problema que causa uma ação ou falha inesperada ao ser ativado é mais precisamente chamado de falha. Uma falha geralmente no sistema e é causada por um erro cometido durante fase de desenvolvimento. 
		Em testes de automação, as falhas são identificadas por meio de scripts que simulam condições reais e que fazem a verificação do software, e se ele está funcionando conforme o planejado. Uma falha, não corrijida, pode levar a falhas mais graves futuramente, causando a degradação da qualidade do produto, e interromper os serviços prestados pelos provedores. Geralmente, são o problema mais perceptivel de um software, e que afetam muitas vezes os usuários finais do sistema. Em fases finais do desenvolvimento do projeto, as falhas são descobertas durantes alguns testes, como funcionais ou de integração/sistema, alertando assim que podem ter problemas serios no sistema, exigindo ação imediata para evitar problemas maiores futuramente.
	
	## Defeito (Defect)
		Defeito é qualquer imperfeição ou incosistência no produto do software ou em seu processo, sendo também, uma não conformidade. Os defeitos são algo que fazem parte do produto, sendo algo que esta implementada no código de maneira errada.
		Existem difereças entre Bug, Defeito e Erro, sendo um bug uma falha relacionada a um software ou hardware e é persistente. Defeito é uma falha passível de rastreio até a fabricação ou o lado físico de um produto. E já um erro é um resultado inesperado genérico e é o primeiro passo na avaliação de um QA.
	
	##Crash
		O crash de um sistema refere-se a uma falha crítica que resulta na interrupção inesperada do funcionamento de um sistema operacional ou de um app. Um crash pode ser causado por diversos fatores, incluindo erros de software, falhas de hardware ou conflitos entre programas. Quando ocorre um crash, ele geralmente para de responder, e o usuário pode ser forçado a reiniciar o dispositivo para restaurar a funcionalidade.
	
	##Exceção (Exception)
		Em linguagens de programação, exceção é o nome dado a um evento que interrompe o fluxo normal de execução de um programa. Ela indica o ocorrido de uma condição anormal, como um erro, durante a execução do código. Seu tratamento permite lidar com essas condições de forma organizada, evitando que o programa trave ou gere resultados inesperados.
		Essas falhas podem ser resultantes de uma entrada inválida, uma divisão por zero, um arquivo não entrado, etc.
	
	## Hotfix
		Hotfix é um termo utilizado na área da tecnologia da informação que refere-se a uma atualização ou correção rápida aplicada a um software, sendo elas utilizadas para resolver problemas critícos que podem impactar o funcionamento do sistema, como bugs, falhas ou erros que afetam a experiência do usuário. 
		Ele é utilizado para restaurar a funcionalidade do software sem a necessidade de uma atualização completa, que pode ser de um complexidade maior e de maior demora.
	
	## Regressão
		O erro de regressão é a diferença entre o valor observado de uma variável dependente e o valor previsto para ela pelo modelo de regressão.
		Esses erros ocorrem por diversas razões, geralmente relacionados à adequação do modelo aos dados ou à qualidade dos dados em si. Eles buscam encontrar a melhor relação entre variáveis, mas essa relação nem sempre é perfeita , e com erros que podem surgir devido a fatores como: não linearidade, multicolinearidade, outliers, erros de mediação e variáveis não omitidas.

#CAPITULO II - Tipos de Testes
	
	## Teste manual
		O teste manual é um tipo de teste de software que envolve testers que executam casos de teste passo a passo, permitindo a observação dos resultados em primeira mão, sem depender de scripts ou ferramentas automatizadas.
		Esse tipo de teste é indicado em cenários que demandam flexibilidade, exploração, avaliação da experiência do usuário e testes de curto prazo, se destacando quando a automação não é viável ou quando a intuição e o julgamento humano são cruciais para identificar problemas e avaliar a usabilidade. Eles são mais adequados em alguns testes, como os exploratórios, usabilidade e aceitação, testes de baixo volume ou testes ad-hoc, testes de compatibilidade, em ambientes que estão em início de desenvolvimento e os que requerem feedback rápido.
		Os testes manuais são vantajosos pois permitem que o projeto tenha uma maior percepção e um julgamento humano, com uma flexibilidade e adaptabilidade dos meios da realização dos testes, são ótimos também para projetos pequenos, pois são mais economicamente viáveis, são fáceis de implementar e possuem uma ampla diversidade de casos de teste, além de terem um feedback de imediato do tester.
		Porém eles possuem desvantagens perante ao teste automatizado, como por exemplo serem mais demorados, e são mais sujeitos ao erro humano; possuem também uma eficiencia menor, por serem tarefas repetitivas, e tem graves problemas em relação a escabilidade para a realização deles.
		
	## Teste Automatizado
		Os testes automatizados são recursos muito utilizados no desenvolvimento de software, em que o objetivo principal é facilitar a etapa de teste por meio de ferramentas específicas, sendo, dessa forma, pré-programar o que será testado para agir apenas quando for necessário.
		É indicado utilizar eles quando forem testes repetitivos e regressivos, ou seja, quando os testes precisam ser executados e realizados por diversas vezes, ou testes de necessitam de um volume grande de dados ou casos, quando eles possuem testes em múltiplas plataformas e configurações, em diferentes máquinas, com diversas configurações de hardware ou software. Em testes critícos para a negócios e estabilidade do sistema, testando seu funcionamento interno e, se seus requisitos estão funcionando da maneira ideal. Os testes de performance e carga do seu sistema, para saber se eles aguentam performar com grandes volumes de dados, e para testar ambientes de integração contínua e entrega contínua (CI/CD), que permite aos desenvolvedores receber um rápido feedback do código, visando detectar e garantindo que apenas códigos de alta qualidade sejam implementados no sistema.
		E por fim, em testes de integração de API e em testes unitários. Eles são rápidos e focados apenas em pequenos componentes do sistema, ou na comunicação entre os módulos do sistema.
		Esses testes são vantajosos em casos de :
		**Velocidade e Eficiência**;
		**Repitibilidade e Consistência**;
		**Detecção precoce de bugs**;
		**Redução de custos a longo prazo**;
		**Melhora da qualidade de software**;
		**Maior cobertura de testes**;
		**Feedback rápido para desenvolvedores**;
		**Liberação de testadores para tarefas mais complexas**.
		
		Porém, assim eles também possuem algumas desvantagens claras, como:
		**Custo inicial elevado**;
		**Manuntenção Contínua**;
		**Necessidade de Habilidades Específicas**;
		**Não Substituem Testes Manuais Completamente**;
		**Fragilidade (Testes quebradiços)**;
		**Falsos resultados de positivo ou negativo**;
		**Nem todos os softwares podem ser automatizados de forma eficiente**.
		
	## TDD
		TDD ou Teste Driven Developement, é uma técnica de desenvolvimento de software que se relaciona com o conceito de verificação e validação e se baseia em um ciclo curto de repetições, em que o dev escreve um caso de teste automatizado que define uma melhoria desejada ou uma nova funcionalidade, e então é produzido o código que possa ser validado pelo teste para posteriomente o código ser refatorado para um código sob padrões aceitáveis.
		Eles são indicados em casos onde seus beneficios são maximimados, como:
		
		- **Projetos com requisitos bem definidos e estáveis**: Diz respeito à compreensão clara do que um software deve fazer, fica muito mais fácil escrever testes antes de implementar a funcionalidade. Requisitos estáveis significam menos refatoração de testes, tornando o processo mais eficiente.
		
		- **Sistemas de alta criticidade ou com baixa tolerância a falhas **:Em aplicações financeiras, médicas, aeroespaciais ou qualquer sistema onde um erro pode ter consequências graves, o TDD oferece uma camada extra de segurança. A garantia de significavamente o risco de falhas.
	
	    - **Bases de código legadas sem coberturas de testes** : Embora seja um desafio inicial, aplicar o TDD ao refatorar ou adicionar novas funcionalidades a um código legado sem testes pode ser extremamente benéfico. Começar com testes para as novas partes ou para as funcionalidades que serão modificadas ajuda a criar uma rede de segurança e a garantir que as mudanças não quebrem o que já existe.
	    
		- **Equipes que buscam melhoria continua na qualidade do código** : O TDD incentiva a escrita de código limpo, modular e fácil de manter. Ao pensar primeiro nos testes, os desenvolvedores são naturalmente levados a criar um design de software mais coeso e com menor acoplamento, facilitando futuras manutenções e evoluções.
		
		- **Projetos que exigem alta manutennibilidade e escabilidade a longo prazo** : Com uma suíte de testes robusta criada via TDD, a manutenção do sistema se torna mais segura e menos propensa a introduzir novos bugs. Isso é crucial para sistemas que precisam evoluir e escalar ao longo do tempo.
		
		- **Desenvolvimento de bibliotecas ou APIs**: Ao criar componentes que serão utilizados por outros desenvolvedores, a garantia da correta funcionalidade é primordial. O TDD ajuda a garantir que a API se comporte exatamente como esperado em diferentes cenários, funcionando como uma espécie de "documentação viva" da interface.
		
		- **Ambientes de integração contínua (CI/CD)**: O TDD se encaixa perfeitamente em pipelines de CI/CD, onde os testes automatizados são executados a cada commit. Isso permite uma detecção rápida de regressões e garante que o software esteja sempre em um estado de entrega, acelerando o ciclo de desenvolvimento.
		
		Vantagens do TDD: 
		- **Qualidade de Código Aprimorada:** Código mais limpo, modular e com menor acoplamento.
	    - **Redução de Bugs:** Detecção e correção de erros logo no início do desenvolvimento.
	    - **Maior Cobertura de Testes:** Garante que a maioria do código seja testada.
		- **Refatoração Segura:** Permite melhorias no código sem introduzir novos erros.
		- **Documentação Viva:** Testes servem como documentação executável do sistema.
		- **Feedback Rápido:** Ciclo "Vermelho-Verde-Refatorar" oferece retorno imediato.
		- **Aumento da Confiança:** Desenvolvedores se sentem mais seguros ao fazer alterações.
		- **Facilita CI/CD:** Integra-se perfeitamente com pipelines de entrega contínua.
		
		Desvantagens do TDD:
		- **Curva de Aprendizagem:** Requer tempo para que a equipe domine a metodologia.
		- **Tempo Inicial Aumentado:** Pode parecer mais demorado no começo, mas compensa a longo prazo.
		- **Risco de Testes Ruins:** A eficácia depende da qualidade dos testes escritos.
		- **Dificuldade com Código Legado:** Desafiador de aplicar em sistemas sem testes prévios.
		- **Não é para Todos os Projetos:** Pode não ser ideal para prototipagem rápida ou requisitos muito voláteis.
		- **Falsa Sensação de Segurança:** Se os testes não cobrirem todos os cenários, pode haver lacunas.
		- **Foco Excessivo em Testes Unitários:** Não substitui a necessidade de outros tipos de testes (integração, sistema, etc.).

#CAPITULO III - **Ferramentas de Teste Automatizados** :  

	##JUnit:
		É um framework de código aberto para escrita e execução de testes unitários em Java. É uma das ferramentas mais antigas e amplamente utilizadas para testes em projetos Java, sendo um pilar no desenvolvimento orientado a testes (TDD) para essa linguagem. O JUnit utiliza a linguagem java e é bastante utilizada para testes unitários, além de ser empregada também na etapa de desenvolvimento, frequentemente de forma contínua durante a escita do código.
	##Cypress:	
		É uma ferramenta de teste de ponta a ponta (end-to-end), projetada para aplicações web. Ele é construído sobre o ambiente do Node.js e executa os testes diariamente no navegador, o que permite uma depuração facilitada e uma visualização em tempo real do que está acontecendo durantes os testes. 
			Essa ferramenta é utilizada em sistemas web, ou seja, em aplicações que rodam no navegador, independente do framework de frontend (React, Angular, Vue, etc), ou do backend.
			O cypress permite que testes de interface do usuário, testes de integração, testes de ponta a ponta e testes de API, sejam automatizados. 
	##Swagger: 
		É um conjunto de ferramentas de código aberto que ajuda a projetar, construir, documentar e consumir API RESTful. Ele não é uma ferramenta de teste no sentido de "executar testes" diretamente, mas sim uma especificação para descrever APIs. A ferramenta mais famosa que implementa essa especificação é o Swagger UI, que gera uma documentação interativa da API a partir de sua especificação.
		
		**Como ele ajuda nos testes de API?** Swagger ajuda nos testes de API de várias maneiras:
		- **Documentação Interativa:** O Swagger UI fornece uma interface web onde os desenvolvedores e testadores podem visualizar todos os endpoints da API, seus parâmetros de requisição, formatos de resposta e códigos de status. Isso facilita a compreensão de como a API deve funcionar.
	    
		- **Teste Manual Simplificado:** Através do Swagger UI, é possível enviar requisições para os endpoints da API diretamente da interface da documentação e ver as respostas. Isso permite que testadores e desenvolvedores realizem **testes manuais e exploratórios** de forma rápida e eficiente, sem a necessidade de ferramentas externas como Postman ou Insomnia para requisições básicas.
		    
		- **Geração de Cliente/Servidor:** A especificação OpenAPI (usada pelo Swagger) pode ser utilizada para gerar automaticamente código de cliente (para consumir a API) ou de servidor (para implementar a API), o que ajuda a manter a consistência e a reduzir erros de implementação.
		    
		- **Base para Testes Automatizados:** Ferramentas de teste automatizado de API (como Postman, Newman, ou frameworks de teste programáticos) podem importar a especificação OpenAPI/Swagger da sua API. Isso permite que os testes sejam gerados e executados automaticamente, garantindo que a API continue funcionando conforme sua descrição.
