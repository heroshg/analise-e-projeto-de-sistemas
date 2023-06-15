
# Projeto Hamburgueria Análise e projeto de sistemas

# Apresentação

Damos as boas-vindas à distinta audiência à apresentação do nosso notável Software de Gestão para Estabelecimentos de Hamburgueria. Neste contexto, é com prazer que compartilhamos nosso empenho em desenvolver um sistema excepcionalmente projetado, estrategicamente concebido para atender às demandas específicas das hamburguerias, com ênfase inabalável na eficiência, segurança e inovação.

Por meio dessa poderosa ferramenta tecnológica, temos a convicção de que sua estimada hamburgueria será capaz de aprimorar suas operações, otimizar processos e, acima de tudo, proporcionar uma experiência singular aos clientes, mergulhando-os em uma jornada verdadeiramente memorável.

## Alunos
Heros - 33806632

Isaac - 33941904

Marcos Alves- 34241094

Marcos Paulo - 33897093

Samuel - 34207716

# Backlogs
1: Implementar sistema de cadastro de clientes

2: Adicionar opção de cadastro de endereços dos clientes

3: Criar menu de hambúrguers com opções de sabores, tamanhos e preços

4: Implementar sistema de carrinho de compras para os clientes

5:Adicionar opção de personalização dos hambúrgueres (opções de ingredientes extras, bordas
recheadas, etc.)

6: Implementar sistema de pagamento online
Adicionar opção de pagamento na entrega

7: Criar sistema de acompanhamento de pedidos em tempo real

8: Implementar sistema de avaliação dos clientes sobre as pizzas e serviços

9: Adicionar opção de criação de pedidos recorrentes (assinaturas)

10: Criar sistema de desconto para pedidos em grande quantidade

11: Adicionar opção de entrega programada

Implementar sistema de controle de estoque dos ingredientes dos hambúrgueres

12: Criar relatórios de vendas e faturamento diários, semanais e mensais

Adicionar opção de pedido em grupo (para festas e eventos)

13: Implementar sistema de fidelidade para clientes frequentes

14:Adicionar opção de delivery de bebidas e sobremesas

15: Criar sistema de controle de entregas e roteirização de entregas

16: Adicionar opção de suporte ao cliente via chat online

17: Implementar sistema de promoções e cupons de desconto

18: Criar integração com plataformas de delivery online

19: Adicionar opção de acompanhamento de status do pedido pelo cliente

20: Implementar sistema de gestão de funcionários e controle de escalas de trabalho

# Fluxogramas

## "As is"

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/e6ad3c81-c283-4517-a185-cefdd48ed056)

## "To be"

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/87f07752-e6da-4410-a29f-496e71b3375f)

# Requisitos Funcionais

US001.Como um cliente, eu quero ser capaz de fazer pedidos personalizados de
hambúrgueres, para que eu possa ter um sanduíche que atenda às minhas preferências e
restrições alimentares.

US002.Como um cliente, eu quero poder visualizar o cardápio e as opções de ingredientes
claramente, para que eu possa tomar uma decisão informada sobre o que pedir.

US003.Como um atendente de pedidos, eu quero ser capaz de gerenciar pedidos e
atualizações em tempo real, para que eu possa atender aos pedidos de forma rápida e
eficiente.

US004.Como gerente de restaurante, eu quero ser capaz de gerenciar os estoques de
ingredientes e produtos, para que eu possa garantir que os produtos estejam disponíveis e
que não falte estoque.

US005.Como cliente, eu gostaria de poder visualizar o status atual do meu pedido para que
eu possa acompanhar o progresso da minha entrega e saber quando meu pedido será
concluído.

US006.Como gerente de estoque, eu gostaria de poder receber alertas automáticos quando
um produto atingir o nível mínimo de estoque para que eu possa fazer o pedido de
reposição com antecedência e evitar a falta de produtos em estoque.

US007.Como cliente de uma hamburgueria, eu gostaria de poder fazer um pedido online,
para evitar filas e agilizar o processo de compra.

US008.Como gerente, eu gostaria de poder gerar relatórios personalizados que apresentem
informações detalhadas sobre as vendas, lucros e desempenho financeiro da empresa,
para que eu possa monitorar a saúde financeira do negócio, identificar tendências e tomar
decisões informadas com base nos dados apresentados.

US009.Como entregador, eu quero um sistema que seja capaz de gerenciar rotas eficientes
de entrega, para minimizar o tempo gasto na entrega dos pedidos.

US010.Como entregador, eu quero um sistema que seja capaz de realizar um controle
logístico e de identificação dos pedidos validados por QR code, para que não ocorra de o
cliente receber o pedido trocado ou faltando algum item.

US011.Como entregador, eu quero um sistema capaz de realizar um gerenciamento de
prioridade de pedidos, para que os pedidos que estão atrasados ou com prazo de entrega
mais curto sejam listados primeiro na ordem de entrega.

US012.Como entregador, eu quero um sistema capaz de atualizar o status dos pedidos em
tempo real, para que seja possível o cliente ver a confirmação de retirada, tempo estimado
de chegada e a confirmação da entrega.

US013.Como cliente, eu quero poder fazer uma pré-encomenda com antecedência para que
meu pedido esteja pronto quando eu chegar à hamburgueria, evitando a espera na fila.
US014.Como cliente, quero que disponibilize um sistema de promoções e cupões para
fornecer desconto aos clientes.

US015.Como cliente, quero que disponibilize um sistema de rastreamento para o meu
pedido, onde eu consiga localizar em tempo real meu lanche.

US016.Como cliente quero um sistema que disponibiliza fazer pagamentos online ou
quando é retirado na residência.

US017.Como cliente desejo um sistema que deve permitir que os funcionários registrem
sua presença e gerenciem seu horário de trabalho. Também deve permitir que o gerente
atribua tarefas e monitore o desempenho de cada membro da equipe.

US018.Como cliente desejo um sistema que deve gerar relatórios detalhados sobre vendas,
pedidos, estoque, desempenho do funcionário e outras métricas importantes. Esses
relatórios ajudam os gerentes a tomar decisões informadas sobre a operação.

US019.Como cliente desejo um sistema que deve ser integrado com as redes sociais da
hamburgueria, permitindo que os clientes compartilhem suas experiências, visualizem fotos
de pratos e façam comentários.

US020.Como cliente desejo um sistema de fidelidade, é uma maneira eficaz de
recompensar os clientes fiéis. O sistema deve permitir que os clientes acumulem pontos
com base em suas compras e ofereça descontos e promoções exclusivas.

# Requisitos Detalhados

## 1.Função: Gerenciamento de pedidos em tempo real
Descrição: O sistema deve ser capaz de gerenciar os pedidos em tempo real, permitindo
que o atendente de pedidos possa visualizar os pedidos em tempo real, receba notificações
de novos pedidos e atualizações, possa alterar o status dos pedidos e possa gerenciar as
informações de pagamento.

Entradas: Os dados que serão inseridos no sistema incluem o nome do cliente, o pedido, o
método de pagamento, o status do pedido e informações de contato.

Origem: Os dados são originados pelo atendente de pedidos que está recebendo os
pedidos diretamente dos clientes.

Saídas: As saídas incluem atualizações em tempo real sobre o status do pedido,
notificações para o atendente de pedidos sobre novos pedidos ou atualizações e as
informações de pagamento.

Destino: As saídas serão entregues ao atendente de pedidos, aos clientes e ao sistema de
pagamento.

Ação: O sistema deve ser capaz de gerenciar e atualizar os pedidos em tempo real, exibir
informações sobre o status do pedido para o atendente de pedidos e enviar notificações
para o atendente de pedidos quando houver novos pedidos ou atualizações.

Requer: O sistema requer um banco de dados para armazenar as informações do pedido,
um mecanismo de notificação para alertar o atendente de pedidos sobre novos pedidos e
atualizações e uma conexão estável com a Internet para permitir a transmissão de dados
em tempo real.

Pré-condição: O sistema deve estar funcionando corretamente, e o atendente de pedidos
deve estar disponível para receber os pedidos.

Pós-condição: O status do pedido deve ser atualizado em tempo real, e o atendente de
pedidos deve ser capaz de gerenciar e atualizar o status do pedido conforme necessário.

Efeitos colaterais: Pode haver uma sobrecarga no sistema em momentos de pico de
pedidos, o que pode afetar a velocidade de processamento de pedidos. Além disso, pode
haver uma sobrecarga na equipe de atendimento ao cliente se houver muitos pedidos a
serem gerenciados simultaneamente.

## 2.Função: Detalhe de estoque

Descrição: Essa função tem como objetivo fornecer informações detalhadas sobre o
estoque de ingredientes e produtos disponíveis na hamburgueria.

Entradas: Não há entradas necessárias para essa função.

Origem: Sistema de gerenciamento de estoque da hamburgueria.

Saídas: Relatório contendo informações sobre a quantidade de cada ingrediente e produto
disponível no estoque, data da última reposição de estoque, data prevista para a próxima
reposição de estoque e quantidade mínima necessária para manter o estoque.

Destino: Gerente de estoque da hamburgueria.

Ação: O sistema de gerenciamento de estoque gera um relatório detalhado sobre o estoque
atual dos produtos e ingredientes da hamburgueria.

Pré-condição: O sistema de gerenciamento de estoque da hamburgueria deve estar
atualizado com as informações mais recentes sobre o estoque de ingredientes e produtos.

Pós-condição: O gerente de estoque recebe um relatório detalhado sobre o estoque atual da
hamburgueria, permitindo que ele faça pedidos de reposição de estoque com antecedência
e evite a falta de produtos em estoque.

Efeitos colaterais: Não há efeitos colaterais conhecidos para essa função.

## 3.Função: Gerenciar rotas eficientes para entrega dos pedidos

Descrição: Permite ao entregador gerenciar as rotas de entrega de pedidos de forma
eficiente, considerando a localização dos clientes e a proximidade das entregas.

Entradas: Lista de pedidos a serem entregues, endereço de cada cliente e localização atual
do entregador.

Origem: Usuário do sistema.

Saídas: Lista de pedidos organizada em um rota eficiente de entrega, Instruções para o
entregador seguir a rota.

Destino: Sistema de gerenciamento de entregas.

Ação: O sistema deve receber a lista de pedidos e a localização do entregador, calcular a
rota mais eficiente de entrega e fornecer as instruções para o entregador seguir a rota.
Requer Banco de dados de pedidos, Sistema de geolocalização, Mapas digitais.

Pré-condição: O entregador deve ter acesso ao sistema de gerenciamento de entregas,
Existem pedidos registrados no banco de dados.

Pós-condição: A lista de pedidos é organizada em uma rota eficiente de entrega , O
entregador recebe as instruções para seguir a rota.

Efeitos colaterais: Melhoria na eficiência da entrega, com redução do tempo e custo de
entrega. Possibilidade de atrasos ou erros na entrega caso o sistema não calcule a rota
mais eficiente.

## 4.Função: Permitir que os clientes realizem o pagamento de seus
pedidos pela internet.

Descrição: O sistema de pagamentos online deve permitir que os clientes selecionem o
método de pagamento desejado (cartão de crédito, cartão de débito, etc.) e informem os
dados necessários para a transação, como o número do cartão, data de validade e código
de segurança.

Entradas: Método de pagamento escolhido pelo cliente
Informações do cartão de crédito ou débito (número do cartão, data de validade e código de
segurança),valor total do pedido.

Origem: Cliente da hamburgueria.

Saídas: Confirmação do pagamento bem-sucedido ou falha na transação,
Recibo ou comprovante de pagamento,
Atualização do status do pedido no sistema da hamburgueria (de "pendente" para
"processando")

Destinos:Plataforma de pagamento,
Sistema de gerenciamento de pedidos da hamburgueria

Ação: Realizar a transação financeira em nome do cliente.

Requer: Conexão segura com a plataforma de pagamento,
verificação de autenticidade dos dados do cartão de crédito ou débito,
verificação de saldo ou limite disponível no cartão de crédito ou débito.

Pré-condições: Cliente deve ter selecionado um pedido e estar na etapa de finalização da
compra.
Cliente deve ter um método de pagamento válido.

Pós-condições:Pagamento bem-sucedido: o valor total do pedido é debitado do cartão do
cliente e o status
do pedido é atualizado para "processando".

Falha na transação: o cliente é notificado sobre o problema e deve tentar novamente com
um método de pagamento diferente ou verificar com a instituição financeira a causa do
problema.

Efeitos colaterais:
O sistema deve garantir a segurança dos dados financeiros do cliente.

O sistema deve garantir a conformidade com os padrões de segurança financeira e proteção
ao consumidor.

O sistema deve garantir a atualização dos dados de pagamento no sistema de
gerenciamento de pedidos da hamburgueria.

## 5.Função: Geração de relatórios detalhados sobre vendas,
pedidos, estoque, desempenho do funcionário e outras métricas
importantes.

Descrição: O sistema deve gerar relatórios detalhados e personalizáveis para que os
gerentes possam acessar informações importantes sobre a operação da hamburgueria.

Entradas: Dados de vendas, pedidos, estoque e desempenho do funcionário.

Origem: Dados gerados pelo sistema da hamburgueria.

Saídas: Relatórios personalizados contendo informações detalhadas sobre vendas,
pedidos, estoque, desempenho do funcionário e outras métricas importantes.

Destinos: Gerentes da hamburgueria que precisam acessar informações para tomar
decisões informadas sobre a operação.

Ação: O sistema gera relatórios personalizados com base nos dados de entrada e as
configurações de relatórios selecionadas pelo gerente.

Requer: O sistema precisa ter acesso a dados precisos e atualizados sobre vendas,
pedidos, estoque e desempenho do funcionário.

Pré-condições: Os dados de entrada devem ser precisos e atualizados.

Pós-condições: O sistema gera um relatório personalizado com base nas configurações
selecionadas pelo gerente.

Efeitos colaterais: Nenhum efeito colateral conhecido

# Requisitos não-funcionais

RNF001.Usabilidade: O sistema deve ser fácil de usar e entender, com uma interface clara
e intuitiva para os usuários. Isso inclui botões grandes e bem posicionados, uma linguagem
clara e concisa e feedback visual para confirmar as ações do usuário.

RNF002.Desempenho: O sistema deve ser capaz de lidar com picos de tráfego e processar
pedidos rapidamente. Isso inclui um tempo de resposta rápido, capacidade de
processamento e armazenamento suficiente para lidar com grandes volumes de dados.

RNF003.Segurança: O sistema deve ser seguro e protegido contra ameaças externas,
como hackers e malware. Isso inclui criptografia de dados, autenticação de usuários e
backups regulares para evitar a perda de dados em caso de falhas de segurança.

RNF004. Portabilidade: O sistema deve ser portátil e funcionar em diferentes dispositivos e
plataformas. Isso significa que o sistema deve ser compatível com diferentes navegadores,
sistemas operacionais e dispositivos móveis.

RNF005. Escalabilidade: Um software de hamburgueria deve ser capaz de lidar com um
grande volume de pedidos e clientes. Isso significa que ele deve ser escalável e capaz de
se adaptar a picos de tráfego sem afetar a qualidade do serviço. Além disso, deve ser
possível adicionar novos recursos e funcionalidades para atender às necessidades em
constante mudança do negócio.

RNF006. Disponibilidade: O software de hamburgueria deve estar disponível o tempo todo
para garantir que os pedidos possam ser feitos e processados a qualquer hora do dia. Para
isso, é preciso garantir que o software esteja hospedado em servidores confiáveis e tenha
redundância em caso de falhas.

RNF007. Facilidade de manutenção: Um software de hamburgueria deve ser fácil de manter
e atualizar. Isso significa que ele deve ter um código limpo e modular, documentação clara e
ferramentas de diagnóstico para identificar e corrigir problemas rapidamente.

RNF008. Integração com outros sistemas: É importante que o software de hamburgueria
possa se integrar com outros sistemas, como sistemas de pagamento, sistemas de entrega
e sistemas de gerenciamento de estoque. Isso permite que o negócio possa operar de
forma mais eficiente e integrada.

RNF009. Desempenho: A hamburgueria deve garantir que o tempo de resposta do sistema
seja adequado e que não ocorram interrupções ou quedas de conexão durante o processo
de atendimento. Isso inclui a rapidez na preparação dos pedidos e a agilidade no
processamento do pagamento.

RNF010. Conformidade: A hamburgueria deve estar em conformidade com as leis e
regulamentações aplicáveis, como normas de segurança alimentar, de acessibilidade, de
saúde ocupacional, entre outras. Também deve cumprir com as normas éticas, sociais e
ambientais, tais com a utilização de insumos sustentáveis, a valorização de trabalhadores e
fornecedores, e o uso de tecnologia que minimize o impacto ambiental)

RNF011. Segurança: A hamburgueria deve garantir a segurança dos clientes e dos
funcionários. Isso inclui medidas como a higiene adequada dos alimentos, o controle da
temperatura e o armazenamento correto dos ingredientes, a segurança contra incêndios e o
controle do acesso aos equipamentos perigosos.

RNF012. Confiabilidade: A hamburgueria deve ser confiável e estar disponível para os
clientes a qualquer momento. Isso pode incluir o uso de sistemas de backup, redundância
de servidores, monitoramento constante da disponibilidade do sistema, entre outras
medidas para garantir a disponibilidade e confiabilidade do sistema.

RNF013. Portabilidade: O sistema do aplicativo deve ser programado em java, para ser
mais fácil caso precise de uma alteração dentro do código.

RNF014. Desempenho: O app deverá ter um tempo de resposta de menos de 1 minuto para
dar mais dinamismos nas ações dentro do aplicativo.

RNF015. Segurança: O aplicativo deverá ter um sistema de proteção contra ataque
externos,onde ele identifica e impede o invasor.

RNF016. Usabilidade: O aplicativo deverá ser fácil e interativo, para um melhor
entendimento quando for utilizá-lo.

RNF017. Adaptabilidade: o sistema deve ser capaz de se adaptar às necessidades
específicas da hamburgueria, permitindo personalização e configuração de acordo com as
preferências do cliente.

RNF018. Acessibilidade: o sistema deve ser acessível para pessoas com deficiência,
incluindo recursos como opções de áudio e suporte para leitores de tela.

RNF019. Integração: O sistema deve ser capaz de se integrar com outros sistemas, como o
sistema de gerenciamento de estoque ou o sistema de gerenciamento de funcionários.

RNF020. Custo: O sistema deve ser econômico e oferecer um bom custo-benefício para a
hamburgueria, de modo a não comprometer a sua rentabilidade.

# Casos de Uso


# Caso de uso 1: Alteração de senha

## Introdução:
Este caso de uso é ativado quando o usuário selecionar a opção “Alterar Senha” dentro do
menu “Usuário” no módulo web.

## Objetivo:
Possibilitar que o usuário altere a senha de acesso ao sistema.

##Requisitos funcionais:

RF016
Consultar acesso

RF018
Alterar senha

RF025
Recuperar acesso


##Requisitos não funcionais:

RNF008
O módulo deverá operar somente no modo web via navegador

## Atores: 

Administrador

 Atendente

Gerente

## Documentos Relacionados
 Diagrama de Classes – Módulo de segurança

## Pré-Condições

 O usuário ter selecionado o menu “Alterar Senha”;

 O sistema ter carregado a tela “Alteração de Senha”.

## Pós-Condições
 A senha deverá ter sido alterada na tabela “Usuario” do banco de dados.

## Fluxo Principal
P-1
O sistema gera um código aleatório (captcha) e exibe no espaço da figura

P-2
O usuário preenche sua identificação (usuário), a senha atual, a nova senha, a confirmação
da nova senha e os caracteres do código aleatório (A-1) (A-2)

P-3
O usuário aciona o botão “Confirmar” (A-3)

P-4
O sistema valida a senha (E-1) (E-2)

P-5
O sistema emite a mensagem “Senha alterada com sucesso.”

P-6
Este caso de uso é finalizado


## Fluxos alternativos

10.1.
(A-1) O usuário não lembra do usuário ou senha

A-1.1
O usuário aciona o botão (esqueci usuário/senha)

A-1.2
O caso de uso “UC006 – Recuperar usuário/senha” é iniciado

A-1.3
Este caso de uso é finalizado.

10.2
(A-2) O usuário não visualiza código aleatório

A-2.1
O usuário aciona o botão “Não consegui visualizar”

A-2.2
Este caso de uso retorna ao fluxo principal (P-1)

10.3
(A-3) O usuário cancela a alteração

A-3.1 O usuário aciona o botão “Cancelar”

A-3.2 O sistema cancela a operação

A-3.3 Este caso de uso é finalizado


## Fluxos de Exceção
11.1.
(E-1) Confirmação de senha nova não confere com a nova senha

E-1.1
O sistema identifica que a nova senha fornecida e a confirmação da senha são diferentes

E-1.2
O sistema emite a mensagem “A confirmação da Nova Senha não confere!”

E-1.3
Este caso de uso retorna ao fluxo principal (P-2)

11.2
(E-2) Campo Requerido Não Fornecido ou Inválido

E-2.1
O usuário não preenche ou preenche incorretamente um campo requerido

E-2.2
O sistema emite a mensagem “Campo requerido ausente ou inválido!”

E-2.3
Este caso de uso retorna ao fluxo principal (P-2)







## Protótipo de Tela

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/f7950198-6ab9-4ec7-a1a4-ea401e6e265c)


## Regras de negócio

R-1
O usuário não pode utilizar as 3 últimas senhas cadastradas

R-2
A senha deve conter letras maiúsculas e minúsculas, números e caracteres especiais



##  PCT005 - Alteração de senha

## Observações:
 Não se aplica

## Anexos:
 Não se aplica.
 

# Caso de uso 2 CRUD básico de produtos

## Introdução
Este caso de uso é ativado quando um usuário com privilégios de administrador ou gerente
acessa o módulo de gestão de produtos e seleciona a opção CRUD Básico de Produtos.

## Objetivo
Permitir que um usuário com privilégios de administrador ou gerente realize operações de
criação, leitura, atualização e exclusão (CRUD) de produtos no sistema.

## Requisitos funcionais

RF001 Cadastrar Produto

RF002 Consultar Produto

RF003 Atualizar Produto

RF004 Excluir Produto


## Requisitos não funcionais
   
RNF001 O sistema deve permitir a criação, atualização e exclusão de produtos em
lote

RNF002 O sistema deve permitir a importação e exportação de dados em formato
CSV

RNF003 O sistema deve permitir a ordenação e filtragem de produtos por nome,
preço e categoria

## Atores

Administrador

Gerente

## Documentos relacionados
Diagrama de classes do módulo de gestão de produtos

## Pré-condições
• O usuário ter acesso ao módulo de gestão de produtos

O sistema ter carregado a tela inicial do CRUD básico de produtos

##  Pós-condições
 As operações de CRUD realizadas pelo usuário deverão ter sido salvas no banco de dados
do sistema

##  Fluxo principal
P-1 O sistema exibe a lista de produtos cadastrados

P-2 O usuário seleciona a opção "Cadastrar Novo Produto"

P-3 O sistema exibe o formulário de cadastro de produtos

P-4 O usuário preenche os campos obrigatórios e aciona o botão "Cadastrar"

P-5 O sistema valida os campos preenchidos e salva o novo produto no banco de

dados

P-6 O sistema exibe a mensagem "Produto cadastrado com sucesso!"

P-7 O usuário seleciona a opção "Consultar Produto"

P-8 O sistema exibe a lista de produtos cadastrados

P-9 O usuário seleciona um produto da lista e aciona o botão "Editar"

P-10 O sistema exibe o formulário de edição de produtos, com os campos
preenchidos com os valores atuais do produto

P-11 O usuário atualiza os campos desejados e aciona o botão "Atualizar"

P-12 O sistema valida os campos atualizados e salva as alterações no banco de
dados

P-13 O sistema exibe a mensagem "Produto atualizado com sucesso!"

P-14 O usuário seleciona um produto da lista e aciona o botão "Excluir"

P-15 O sistema exibe a mensagem "Tem certeza de que deseja excluir o produto
selecionado?"

P-16 O usuário confirma a exclusão do produto

P-17 O sistema remove o produto selecionado do banco de dados e exibe a
mensagem "Produto excluído com sucesso!"

P-18 Este caso de uso é finalizado

## Fluxos alternativos
10.1. (A-1) Produto não encontrado
    
A-1.1 O sistema emite a mensagem “Produto não encontrado!”

A-1.2 Este caso de uso retorna ao fluxo principal (P-1)

10.2. (A-2) O usuário deseja adicionar uma imagem ao produto

A-2.1 O usuário aciona o botão “Adicionar Imagem”

A-2.2 O sistema exibe a tela de seleção de imagem do dispositivo

A-2.3 O usuário seleciona a imagem do produto no dispositivo

A-2.4 O sistema exibe a imagem selecionada na tela de cadastro do produto

A-2.5 O caso de uso retorna ao fluxo principal (P-3)

10.3. (A-3) O usuário deseja remover uma imagem do produto

A-3.1 O usuário aciona o botão “Remover Imagem”

A-3.2 O sistema exibe a mensagem “Deseja realmente remover a imagem?”

A-3.3 O usuário confirma a exclusão da imagem

A-3.4 O sistema remove a imagem do produto

A-3.5 O caso de uso retorna ao fluxo principal (P-3)

10.4. (A-4) O usuário cancela a operação de cadastro/edição de produto
A-4.1 O usuário aciona o botão “Cancelar”

A-4.2 O sistema cancela a operação

A-4.3 Este caso de uso é finalizado

## Fluxos de exceção

11.1. (E-1) Erro ao gravar dados

E-1.1 O sistema não consegue gravar as informações do produto no banco de dados

E-1.2 O sistema emite a mensagem “Erro ao gravar os dados do Produto!”

E-1.3 Este caso de uso retorna ao fluxo principal (P-3)

11.2. (E-2) Dados inválidos

E-2.1 O usuário não preenche ou preenche incorretamente um campo requerido

E-2.2 O sistema emite a mensagem “Campo requerido ausente ou inválido!”

E-2.3 Este caso de uso retorna ao fluxo principal (P-2)

## 12. Protótipo de tela  
![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/9a9cdbed-5b74-4606-8cab-3bc80fe60b61)


##  Regras de negócio

R-1 O sistema não deve permitir a inserção de dois produtos com o mesmo código.

R-2 Os dados do produto devem ser armazenados em uma base de dados.

R-3 Os produtos só poderão ser excluídos se não houverem pedidos associados.

14. Casos de teste

##  PCT006 
– Consulta de Produtos
## PCT007 
– Cadastro de Produtos
##  PCT008
– Edição de Produtos
## PCT009 
– Exclusão de Produtos
## Observações
• Não se aplica.

## Anexos

• Diagrama de Classes – módulo de produtos.


# Caso de uso 3 Função Core de Pedidos

## Introdução:
Este caso de uso é ativado quando o usuário seleciona a opção "Fazer Pedido" no menu principal do aplicativo da hamburgueria.

## Objetivo:
Possibilitar que o usuário faça um pedido de produtos da hamburgueria.

## Requisitos funcionais:

RF003 
Selecionar produto

RF004
Adicionar produto ao carrinho 

RF005
Remover produto do carrinho 

RF006
Ver carrinho

RF007
Finalizar pedido


## Requisitos não funcionais:

RNF003
O aplicativo deverá operar em smartphones com sistema operacional iOS e Android.

RNF005
O aplicativo deverá ser capaz de atualizar dinamicamente os preços dos produtos em tempo real.


## Atores: 

• Usuário

• Funcionário da Hamburgueria

## Documentos Relacionados

• Diagrama de Classes – Módulo de Pedidos

Pré-Condições

• O usuário deve ter acessado o aplicativo da hamburgueria.
• O usuário deve estar autenticado no aplicativo.

## Pós-Condições

• O pedido deverá ter sido registrado no banco de dados da hamburgueria.

• O usuário deverá ser redirecionado para a tela de confirmação do pedido.

## Fluxo Principal

P-1
O sistema exibe a lista de produtos disponíveis.

P-2
O usuário seleciona um ou mais produtos.

P-3
O usuário adiciona os produtos selecionados ao carrinho.

P-4
O sistema exibe o carrinho com os produtos adicionados.

P-5
O usuário remove algum produto do carrinho (se necessário).

P-6
O usuário finaliza o pedido.
P-7
O sistema exibe a tela de confirmação do pedido e registra o pedido no banco de dados da hamburgueria.

P-8
Este caso de uso é finalizado.


## Fluxos alternativos

10.1.
O usuário decide cancelar o pedido.

A-1.1
O usuário clica no botão "Cancelar Pedido".

A-1.2
O sistema cancela o pedido e redireciona o usuário para a tela principal do aplicativo.

A-1.3
Este caso de uso é finalizado.

10.2
O usuário decide adicionar mais produtos.

A-2.1
O usuário clica no botão "Continuar Comprando".

A-2.2
O sistema redireciona o usuário para a lista de produtos disponíveis.

A-2.3
Este caso de uso retorna ao passo P-1.


## Fluxos de Exceção

11.1.
O produto selecionado não está disponível.

E-1.1
O sistema identifica que o produto selecionado não está mais disponível.

E-1.2
O sistema emite a mensagem "Produto não disponível no momento".

E-1.3
Este caso de uso retorna ao passo P-2.

11.2
O carrinho está vazio.

E-2.1
O sistema identifica que o carrinho está vazio.

E-2.2
O sistema emite a mensagem "Carrinho Vazio".

E-2.3
Este caso de uso retorna ao passo P-1.

11.3.
O usuário tenta finalizar o pedido sem ter adicionado nenhum produto.

E-3.1
O sistema identifica que o usuário tentou finalizar o pedido sem ter adicionado nenhum produto







## Protótipos de Tela
![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/076c2889-d5da-4d61-ae57-35cc93b0e256)


## Regras de negócio

R-1
Os produtos adicionados ao pedido não podem ultrapassar o valor máximo permitido pelo cliente.

R-2
O pedido deve conter pelo menos um produto.

R-3
O cliente pode escolher a forma de pagamento e o endereço de entrega.


## PCT003 - Realizar Pedido

## Observações
• O pedido só será efetivado após a confirmação do pagamento pelo cliente.

## Anexos
• Não se aplica.



# Caso de uso 4: Consulta/Relátorio de vendas

## Introdução:
Este caso de uso é ativado quando o usuário seleciona a opção “Consultar Vendas” ou “Relatório de Vendas” no menu principal do sistema de gestão da hamburgueria.

## Objetivo:
Permitir que o usuário consulte informações e gere relatórios de vendas realizadas pela hamburgueria.

##Requisitos funcionais:

RF019
Consultar vendas

RF020
Gerar relatório de vendas



## Requisitos não funcionais:

RNF009
O módulo deverá operar somente no modo web via navegador


## Atores: 

 Administrador;
 
• Gerente;

• Atendente.


## Documentos Relacionados

• Diagrama de Classes – módulo de vendas;

• Especificação de Requisitos – módulo de vendas.

## Pre-Condições

• O usuário selecionou a opção “Consultar Vendas” ou “Relatório de Vendas” no menu principal;

• O sistema carregou a tela de consulta de vendas ou de geração de relatórios.
Pós-Condições

• O usuário deverá ter visualizado as informações das vendas consultadas ou gerado o relatório de vendas.
Fluxo Principal

P-1

O sistema exibe a tela de consulta de vendas ou de geração de relatórios (A-1).

P-2

P-2 O usuário seleciona os critérios de consulta ou de geração de relatório, como período de data, tipo de venda, forma de pagamento, entre outros (A-2).

P-3

P-3 O usuário aciona o botão “Consultar” ou “Gerar Relatório” (A-3).

P-4

P-4 O sistema processa a consulta ou a geração de relatório (E-1).


P-5

P-5 O sistema exibe os resultados da consulta ou o relatório gerado (A-4).

P-6

P-6 Este caso de uso é finalizado.


## Fluxos alternativos
10.1.

Tela de consulta ou geração de relatórios não carrega corretamente
A-1.1

O sistema identifica que ocorreu um erro no carregamento da tela
A-1.2

O sistema exibe uma mensagem de erro e retorna ao menu principal

A-1.3
Este caso de uso é finalizado

10.2
Usuário não preenche todos os campos obrigatórios

A-2.1
 O sistema identifica que o usuário não preencheu todos os campos obrigatórios
 
A-2.2
sistema emite a mensagem “Preencha todos os campos obrigatórios” e retorna ao fluxo principal 

10.3
 Usuário cancela a consulta ou geração de relatório


3.1
O usuário aciona o botão “Cancelar”


3.2
A-3.2 O sistema cancela a operação


3.3
A-3.3 Este caso de uso é finalizado


## Fluxos de Exceção

11.1. Erro ao processar consulta ou geração de relatório


E-1.1
O sistema identifica que ocorreu um erro ao processar a consulta ou a geração de relatório

E-1.2
O sistema exibe uma mensagem de erro e retorna ao fluxo principal 

## Protótipos de Tela

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/7d4bff09-f13f-4baa-a734-6ba72c62b74d)




## Regras de negócio

R-1

R-1 O relatório de vendas só pode ser gerado por usuários com permissão de gerente.

R-2

R-2 O relatório deverá conter as informações de vendas do período selecionado pelo usuário.

R-3

R-3 O relatório deverá ser gerado em formato PDF e disponibilizado para download.


R-4

R-4 O relatório deve ser gerado com base nas informações contidas no banco de dados do sistema.

R-5

R-5 O usuário deverá selecionar um período para a geração do relatório de vendas

R-6

R-6 Caso o período selecionado seja maior que um mês, o relatório deverá ser gerado separadamente para cada mês do período selecionado.


## PCT004 – Geração de Relatório de Vendas
## Observações
• Não se aplica 
## Anexos
• Não se aplica.

# Caso de uso 5 Gerenciamento de estoque

##Introdução:

Este caso de uso é ativado quando o usuário seleciona a opção "Gerenciamento de Estoque" no menu "Administração" do sistema

## Objetivo:

Possibilitar que o usuário gerencie o estoque de produtos da hamburgueria.

## Requisitos funcionais:
RF003 
Consultar estoque

RF004
Adicionar produto ao estoque

RF005
Alterar quantidade de produto no estoque

RF006
Remover produto do estoque






## Requisitos não funcionais:
RNF003
O módulo deverá operar somente no modo web via navegador


## Atores: 

• Administrador

• Gerente

## Documentos Relacionados

• Diagrama de Classes – Módulo de Estoque
Pré-Condições
• O usuário ter selecionado o menu "Gerenciamento de Estoque".
• O sistema ter carregado a tela "Gerenciamento de Estoque".

## Pós-Condições
• O estoque deverá ter sido atualizado na tabela "Produto" do banco de dado.

Fluxo Principal

P-1
O usuário seleciona a opção "Consultar estoque"

P-2
O sistema exibe uma lista com os produtos cadastrados e suas respectivas quantidades em estoque

P-3
O usuário seleciona a opção "Adicionar produto"

P-4
O sistema exibe a tela "Adicionar produto ao estoque"

P-5
O usuário preenche os campos com as informações do produto (nome, quantidade, valor unitário, fornecedor, validade) e aciona o botão "Adicionar"

P-6
O sistema valida as informações e atualiza a tabela "Produto"

P-7
 O sistema exibe a mensagem "Produto adicionado ao estoque com sucesso"
 
P-8
Este caso de uso é finalizado.


## Fluxos alternativos

10.1. O usuário seleciona a opção "Alterar quantidade de produto"

A-1.1 O sistema exibe a tela "Alterar quantidade de produto no estoque"

A-1.2 O usuário seleciona o produto a ser alterado e preenche a nova quantidade

A-1.3 O sistema valida as informações e atualiza a tabela "Produto"

A-1.4 O sistema exibe a mensagem "Quantidade de produto alterada com sucesso"

A-1.5 Este caso de uso retorna ao fluxo principal (P-2)

10.2. O usuário seleciona a opção "Remover produto"

A-2.1 O sistema exibe a tela "Remover produto do estoque"

A-2.2 O usuário seleciona o produto a ser removido e aciona o botão "Remover"

A-2.3 O sistema valida as informações e atualiza a tabela "Produto"

A-2.4 O sistema exibe a mensagem "Produto removido do estoque com sucesso"

A-2.5 Este caso de uso retorna ao fluxo principal (P-2)

## Fluxos de Exceção

11.1. (E-1) Quantidade Inválida

E-1.1 O sistema identifica que a quantidade fornecida é inválida

E-1.2 O sistema emite a mensagem “Quantidade inválida!”

E-1.3 Este caso de uso retorna ao fluxo principal (P-3)

11.2. (E-2) Produto Não Encontrado

E-2.1 O sistema não encontra o produto informado

E-2.2 O sistema emite a mensagem “Produto não encontrado!”

E-2.3 Este caso de uso retorna ao fluxo principal (P-2)

11.3. (E-3) Falha ao Atualizar Estoque

E-3.1 O sistema identifica que ocorreu uma falha ao atualizar o estoque

E-3.2 O sistema emite a mensagem “Falha ao atualizar o estoque!”

E-3.3 Este caso de uso retorna ao fluxo principal (P-4)





## Protótipos de Tela

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/3fc1432d-5659-40af-9a07-415832f433fb)




## Regras de negócio

R-1
 Apenas usuários com perfil de administrador podem acessar esta função.
 
R-2
O estoque mínimo definido para cada produto não pode ser menor que zero.






## Casos de teste

• PCT005 – Adicionar Produto ao Estoque
• PCT006 – Atualizar Produto no Estoque
• PCT007 – Remover Produto do Estoque
## Observações
• Não se aplica.

Anexos
• Não se aplica.


# Diagrama geral de casos de uso


![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/91bb58c8-db5e-4ab6-8a18-776944242ef9)



# Diagrama de Classes e Dados

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/4d25f122-d816-4713-ad6b-3989bd818e32)


# Diagramas de sequência


## Caso de uso 1:  Alteração de senha

![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/92d8e48d-6cb0-46ab-8eb5-60bbe91e81ca)


## Caso de uso 3: Função Core de Pedidos


![image](https://github.com/heroshg/analise-e-projeto-de-sistemas/assets/114421814/bcfe3d34-df96-499f-b38c-92e8f92b30f0)


















