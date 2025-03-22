# DIO-azure-cloud
Estarei documentando aqui o meu resumo do que aprendi na aula sobre Ambiente Cloud e Arquitetura no Azure, como proposto no desafio da DIO (Digital Innovation One).

Basicamente, explorei os fundamentos da computação em nuvem e como o Azure facilita a criação, o gerenciamento e a escalabilidade de recursos. Aprendi sobre grupos de recursos, que organizam tudo o que criamos, e como configurar máquinas virtuais para rodar aplicações na nuvem. Além disso, vi a importância do monitoramento e do controle de custos, que são essenciais para usar a nuvem de forma eficiente. 


# Criando Minha Conta no Azure
- Criei minha conta no Azure acessando portal.azure.com, clicando em "Comece gratuitamente" e seguindo os passos. Confirmei e-mail e telefone, e pronto, conta criada.

# Explorando o Portal
- O painel do Azure é organizado em um dashboard personalizável. Adicionei atalhos para os serviços mais usados, como Máquinas Virtuais e Banco de Dados. Naveguei pelo Azure Marketplace para ver os serviços disponíveis e explorei o Azure Cloud Shell para executar comandos diretamente no navegador.

# Criando Meu Primeiro Grupo de Recursos
- Tudo no Azure começa com um grupo de recursos, que serve para organizar e gerenciar serviços. No menu "Grupos de Recursos", cliquei em "Criar", defini um nome, escolhi a região "East US" e finalizei a criação. Agora posso adicionar máquinas virtuais, bancos de dados e outros serviços dentro desse grupo.

# Minha Primeira Máquina Virtual
- Criei uma máquina virtual acessando "Máquinas Virtuais" e clicando em "Criar". Escolhi Windows Server 2019 como sistema operacional, um tamanho de VM adequado (Standard_B1s) e configurei a rede virtual. Defini um usuário e senha para acesso remoto via RDP. Após a criação, conectei-me à VM usando o Remote Desktop.

# Monitorando Tudo
- Usei o "Azure Monitor" para acompanhar o desempenho dos recursos. Configurei métricas para monitorar CPU, memória e uso de disco da máquina virtual. Criei alertas para me notificar caso a CPU ultrapasse 80% de uso. Também utilizei o Log Analytics para coletar logs detalhados do sistema.

# Controlando os Custos
- Acessei o "Custos e Faturamento" para configurar um orçamento e definir um limite de gastos. Configurei alertas para avisar quando atingir 50% e 80% do orçamento. Ativei a visualização detalhada para acompanhar o consumo de cada recurso dentro do meu grupo.

# Aprendendo Mais
- Explorei a documentação oficial do Azure, que contém tutoriais e exemplos úteis sobre implementação de serviços e automação. Testei o uso do Azure CLI para gerenciar recursos via terminal. O suporte do Azure também oferece planos de atendimento para dúvidas mais avançadas.
