# labdio4
Grupos de Recursos e Zonas do Azure
Aprendemos sobre Regiões, replicações, DataCenter (até 3 por região), etc...

O que aprendemos em relação a assinaturas e grupos de gerenciamento:

Uma assinatura pode ter vários grupos de gerenciamento, entretanto, cada grupo somente poderá estar vinculado a uma única assinatura.

Na parte superior no campo pesquisa digitamos Grupos para acessarmos Grupos de Gerenciamento

O grupos de gerenciamento mostram a organização hierárquica dos nossos negócios de forma clara e precisa.
É uma boa maneira de gerenciar os projetos em nuvem, permiitindo gerenciamento de diretrizes de segurança e governança, híbridas ou de várias nuvens.
Implantações de gerenciamento ou plataforma em assinaturas e grupos de gerenciamento separados para carga de trabalho ou dos recursos do aplicativo
É possível lidar e organizar várias regiões do Azure. Fácil de organizar e selecionar recursos de replicação e recuperação de desastres.
A área de design exibe uma representação gráfica e precisa dos recursos gerenciados facilitando a visualização e administração dos mesmos.

  Podemos separa equipes ou serviços. Teremos contabilização precisa em relação a essa estrutura organizacional e também todas as diretrizes de segurança.
  Devemos proteger nossa hierarquia de recursos com RBAC (controle de acesso baseado em função) para operações de grupo de gerenciamento.
  Embora uma árvore de grupos de gerenciamento pode dar suporte a até seis níveis de profundidade é aconselhável ter no máximo de três a quatro níveis para simplificar e agilizar o gerenciamento.

Estrutura hierárquica:
             1-gerenciamento Grupos
         2.0-Ass.   2.1 Ass.   2.2 Ass.         As assinaturas definem limites para as atribuições de políticas do Azure. Algumas aplicações são críticas em relação a segurança
	  3. grupos de Recursos
	4. Recursos
	
Criação de Grupos de gerenciamento:

Selecionar Criar +

		id :  id-Azure-Teste-Gerenciamento-01
		nome: Gerenciamento-01
		
Nome: Gerenciamento-01 ID:id-Azure-Teste-Gerenciamento-01
Nível de Acesso: Proprietário
Caminho:Tenant Root Group / Gerenciamento-01
Grupo de gerenciamento pai: Tenant Root Group
Grupos de gerenciamento filhos:0
Total de assinaturas :0		
	Adicionamos uma assinatura: Azure subscription 1 (c0ee9547-e086-4899-b2ad-1e35275c8cde)
Criamos uma máquina virtual como recurso mas não salvamos porque tivemos medo de cobrança.
Criamos também um banco de dados SQL e criamos uma rede virtual. Também não salvamos.

Tanto a máquina virtual quanto o Banco de Dados já foram descritos em projetos anteriors com detalhes.
Achei desnecessário replicar aqui.
