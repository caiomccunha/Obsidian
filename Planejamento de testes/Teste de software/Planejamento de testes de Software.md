# I - Nome do Projeto:

	A de Agro - Versão 1.0;
#  II - Objetivo do Teste:

		Garantir que as funcionalidades de Cadastro de usuários, cadastro de demandas e postagem estejam funcionando corretamente, conforme os requesitos estabelecidos anteriormente.

# III - Escopo do teste:

	- Funcionalidades que serão testadas: 
		- Cadastro de usuários (POST);
		- Edição de usuários (PUT);
		- Exclusão de usuários (DELETE);
		- Listagem de usuários (GET);
		- Criação de demandas (POST);
		- Edição de demandas (PUT);
		- Exclusão de demandas (DELETE);
		- Listagem de demandas (GET);
		- Realização de postagens no sistema (POST);
		- Edição de postagens (PUT);
		- Exclusão de postagens (DELETE);
		- Listagem de postagens (GET);
		- Validar os campos obrigatórios do sistema;
	
	- Funcionalidades dora do escopo do teste:
		- Integração entre os sistemas;

# IV - Funcionalidades a serem testadas (Quadro)

![[Pasted image 20250702190114.png]]
# V- Estratégia de Teste:

	- Tipo de teste: Manual + automatizado (validação de campos e informações cruciais);
	- Técnicas utilizadas: Caixa branca, teste unitário, teste funcional;
	- Ferramentas JUnit (Backend), Insomnia (API);

# VI - Ambiente do Teste:
	- Sistema Operacional : Windows 11;
	- Backend :  Spring Boot 3.5.0;
	- Banco de dados: MySQL 8.4.3;
# VII - Critérios de Entrada e Saída:
	-Entrada:
		-Funcionalidades implementadas;
		-API documentada no swagger;
	
	-Saída:
		- 100% dos testes executados;
		- Pelo menos 90% dos testes com sucesso;
		- Nenhum erro crítico aberto;