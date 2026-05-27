# Prompt and Artificial Intelligence
Professor: José Maia Neto

Sprint 01

Problema:
O desafio aborda a ausência de mecanismos integrados em eletropostos comerciais para gerenciar a potência, registrar o ciclo da sessão e aplicar políticas de tarifação e pagamento. A proposta consiste em desenvolver uma plataforma para orquestrar a recarga comercial, registrar dados da sessão e acionar regras de cobrança dinâmica. 

# Projeto: GoodWezinho
O GoodWezinho é um chatbot feito e treinado para ser um assistente a um usuario que seja dono de um carro eletrico.
Ele foi pensado para resolver o problema de falta de informação a respeito de carregadores eletricos (especialmente, os da GoodWe), conseguindo fornecer quanto custa para um "abastecimento" com base no veículo do usuario, onde ele pesquisa o modelo com base no nosso banco de dados, recebe o valor da capacidade da bateria, e faz uma conta simples de quanto custa e quanto tempo demoraria para carregar o carro, com base no carregador de 22KW, o mais potente da GoodWe!
Ele tambem tem um banco de dados "imaginario" de locais com carregadores da GoodWe, como essa informação não é publica, nós adicionamos todos os shoppings da zona sul de São Paulo apenas para mostrar do que o GoodWezinho é capaz! Ele consegue calcular qual shopping é o mais proximo do seu local, para te informar! Futuramente, estes dados podem ser substituidos com as informações reais de onde tem carregadores da GoodWe.
O GoodWezinho tambem tem informações de vendas dos carregadores da linha HCA G2, para caso o usuário tenha interesse em comprar um!

Para o preço: colocamos uma taxa de R$: 0.50 para cada KWh carregado, levando em conta que essa taxa em carregadores comerciais gira em torno disso.
Para o tempo: apenas uma conta simples para saber o tempo com base na bateria do carro.
Para o Local: Ele pergunta onde o usuario está, e com base na resposta, pesquisa qual é o shopping no banco de dados dele mais proximo da localização fornecida.
Para a venda do carregador: ele tem as informações do preço, modelo, e capacidade de carregamento dos 3 modelos disponiveis, e consegue te recomendar um com base no seu perfil. As informações são retiradas do proprio PDF da GoodWe sobre a linha HCA-G2, utilizando RAG

Futuramente, queremos implementar duas funções: uma para saber se os carregadores estão em uso, e outra para saber quanto tempo falta para a carga completa do carro, o que é totalmente possivel no contexto de hoje!

Com isso, o GoodWezinho combate a falta de informação a respeito dos carregadores elétricos, possuindo local, e conseguindo gerar respostas interativas com base no modelo do carro, além de vender os proprios carregadores, para residencias ou uso comercial.

# MEMBROS
Guilherme Figueira Velloso - RM 568827

José Augusto Ribeiro Freire Manfrinato - RM 571151

Lais da Silva Dias - RM 569943

João Augusto Poloniato Telles - RM 571443

Thiago Soalheiro Diamantino - RM 569316

Kauan Damasceno de Lima - RM 573727
