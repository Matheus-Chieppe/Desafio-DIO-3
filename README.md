# Desafio-DIO-3
Aplicar os conceitos aprendidos em um ambiente prático

Pré-requisitos
Para criar uma instância gerenciada de SQL, você precisa dos seguintes pré-requisitos:

Uma assinatura do Azure. Se você não tem uma assinatura do Azure, crie uma conta gratuita
No caso geral, o usuário precisa ter a função de Contribuidor da Instância Gerenciada de SQL atribuída no escopo da assinatura.
Se o provisionamento for feito em uma sub-rede que já foi delegada para a Instância Gerenciada de SQL do Azure, o seu usuário precisará apenas da permissão Microsoft.Sql/managedInstances/write, atribuída no escopo de assinatura.
O módulo Az.SQL mais recente para a versão atual do PowerShell ou a versão mais recente da CLI do Azure.

ntre no Portal do Azure
Para criar sua instância no portal do Azure, primeiro você precisará entrar no portal do Azure e preencher as informações na página Criar Instância Gerenciada de SQL do Azure.

Para sua instância, siga estas etapas:

Entre no portal do Azure.

No menu esquerdo do portal do Azure, selecione SQL do Azure. Se SQL do Azure não estiver na lista, selecione Todos os serviços e, em seguida, digite SQL do Azure na caixa de pesquisa.

Selecione + Criar para abrir a página Selecionar opção de implantação do SQL. Veja mais informações sobre a Instância Gerenciada de SQL do Azure selecionando Mostrar detalhes no bloco Instâncias gerenciadas de SQL.

Escolha Instância única na lista suspensa e depois selecione Criar para abrir a página Criar instância Gerenciada de SQL do Azure.

Criar banco de dados
Você pode criar um novo banco de dados usando o portal do Azure, o PowerShell ou a CLI do Azure.

Para criar um novo banco de dados para a sua instância no portal do Azure, siga estas etapas:

Acesse a Instância Gerenciada de SQL no portal do Azure.

Na página Visão geral, escolha + Novo banco de dados da sua instância gerenciada de SQL para abrir a página Criar banco de dados gerenciado do SQL do Azure.

Captura de tela da criação de um novo banco de dados no portal do Azure.

Dê um nome para o banco de dados na guia Básico.

Na guia Fonte de dados, selecione Nenhuma para um banco de dados vazio ou restaure um banco de dados a partir do backup.

Defina as configurações restantes nas guias restantes e selecione Revisar + criar para validar suas escolhas.

Use Criar para implantar seu banco de dados.
