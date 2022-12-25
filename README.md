# Challenge-Data-Science-Alura-2ed
Proposta do desafio:

A imobiliária InsightPlaces, situada na cidade do Rio de Janeiro, está enfrentando dificuldades para alugar e vender imóveis. Em uma pesquisa de como empresas semelhantes operam no mercado, a InsightPlaces percebeu que esse problema pode estar relacionado aos valores dos imóveis e às recomendações realizadas em seu site.

Dentro desse contexto, como podemos definir de forma eficiente os preços dos imóveis lidando com grandes volumes de dados? É importante recomendar imóveis utilizando outro critério? O que precisa ser feito?

Você faz parte do time de Ciência de Dados e Big Data da InsightPlaces e ficou responsável por auxiliar no processo de análise de dados dos imóveis, que estão localizados em alguns bairros da cidade do Rio de Janeiro.

Esse projeto tem algumas etapas como: ler e fazer o tratamento do histórico dos preços de imóveis no Rio de Janeiro, construir um modelo de regressão para precificar imóveis e, por último, criar um recomendador de imóveis. Para cada uma dessas etapas, vamos utilizar a ferramenta PySpark, que oferece uma melhor performance ao trabalharmos com grandes volumes de dados.

Descrição de cada variável do dataset
*   id ->	Código de identificação do anúncio no sistema da InsightPlaces
*   tipo_unidade ->	Tipo de imóvel (apartamento, casa e outros)
*   tipo_uso ->	Tipo de uso do imóvel (residencial ou comercial)
*   area_total ->	Área total do imóvel (construção e terreno)
*   area_util ->	Área construída do imóvel
*   quartos ->	Quantidade de quartos do imóvel
*   suites ->	Quantidade de suítes do imóvel
*   banheiros ->	Quantidade de banheiros do imóvel
*   vaga ->	Quantidade de vagas de garagem do imóvel
*   caracteristicas ->	Listagem de características do imóvel
*   andar ->	Número do andar do imóvel
*   endereco ->	Informações sobre o endereço do imóvel
*   valores ->	Informações sobre valores de venda e locação dos imóveis
