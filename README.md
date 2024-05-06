# Análise de personalidade dos clientes
  O objetivo geral é a identificação de segmentos e tipos de consumidores com alto potencial do investimento, o repósitório é uma análise introdutória por meio do Excel.
  
### Datasets
  O presente projeto tem como objetivo analisar o conjunto de dados "Customer Personality Analysis", disponível na plataforma Kaggle (https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis), no formato CSV. Este Datasets contém informações gerais sobre as características e comportamentos de 2.240 clientes, dividindo em 29 variáveis, podendo ser dividida em grupos: demográficas. comportamentais e consumo.
  Durante a importação, foi necessário realizzar a conversação das variáveis do tipo númerica para o formato real. Essa conversação garante a precisão dos cálculos e análises. 
  
### Tratamento de dados atipicos e criação de novas variáveis
  Foram identificados e eliminados 7 registros de clientes que não possuiam informações sobre o local de compra.
  Um registro foi excluido devido à discrepância significativa entre a sua renda anual e o penúltimo maior salário anual registrado.
  Duas coluynas que não apresentavam informações na documentação foram removidas.
  Utilizando funções do Excel, operações e data, foram criadas seis novas colunas com base em dados existentes:
  * **Total de filhos**: Soma o número de filhos em diferentes idades de cada cliente.
  * **Salário médio mensal**: Divide a renda anual pela quantidade de meses.
  * **Ano de cadastro**: Extrai o ano a partir da data de cadastro do cliente.
  * **Gastos totais**: Soma todos os gastos realizados por cada cliente.
  * **Total de compras**: Contabiliza o número total de compras realizadas por cada cliente.
  * **Média por compra**: Divide o total de gastos pelo total de compras.

### Análise
Ao longo da análise, um produto é desenvolvido com base nos princípios de storytelling aprendidos em um curso introdutório na plataforma Alura, disponibilizado na imagem abaixo. O relatório a seguir apresenta a análise realizada, as conclusões obtidas e os desafios encontrados durante o processo.
<p align ='center'>
  <img src = "https://github.com/caiquebrenneck/CustomerPersonalityAnalysis/assets/98063397/5c13bf52-5f76-40c9-9918-2d8c6cba6231" height = '600'/>
</p>

### Relatório

  O Merkat Kaggle possui 2.233 clientes cadastrados em seu banco de dados.
  O departamento de vinhos é responsável por maiis de 50% do faturamento total, superando o departamento de carnes em 300 milhões de reais.
  
  A loja física detém cerca 50% do valor faturado e o catálogo contribui com quase 22%. É necessário aumentar o acesso dos clientes ao catálogo e oferecer failidades para impulsionar a adesão às compras, podendo oferecer maior variedade de vinhos, visto o seu poder de compra. 
  
  É preciso de informações das campanhas de marketing realizadas, para analisar e comparar seus resultados para definir uma nova estratégia. Por enquanto, averigamos que a segunda campanha tevce o meor retorno, atraindo menos de 50 clientes. A última campanha, em contrapartida, foi um sucesso, com um público de 300 clientes, dobro do da penúltima.
  
  No entanto, isso representa apenas 13,5% dos clientes cadastrados. Ao analiusar o faturamento, 92% do total provém de clientes que não aderiram às ofertas. Porém, não tem como confirmar a eficiência das ofertas, é necessário um teste de controle, comparando o desempenho, ou o retorno financeiro, com e sem as promoções.

  A análise das personalidades dos clientes revela que os melhores clientes do Merkat Kaggle são aqueles que:
  
  * Não possuem filhos, representando mais de 80% do faturamento e do total de compras.
  * Possuem nível superior completo ou em andamento, representando cerca de metade da base de clientes.
  * Têm renda mensal média entre 5 e 7 milhões de reais, faixa que abrange praticamente 75% dos clientes.

  Outros caracteristicas não apresentaram resultados significativos, indicando que sua participarção no faturamento é superior a 50%.

### Desafios

  Esta foi a minha primeira experiência com tabelas dinâmicas, o que se traduziu em um importante processo de aprendizagem. Abordou-se o domínio de técnicas de seleção, agrupamento e divisão de dados, visando à construção de uma tabela eficiente que facilite a criação de gráficos. O desafio mais significativo residiu na construção de um gráfico com sobreposição em barra, indicando o total de clientes aderentes às ofertas e a parcela que as aceitou pela primeira vez. Intuitivamente, reconheci a viabilidade da construção, o que motivou a questão de, apesar do total, quem aceitou pela primeira vez, com o objetivo de verificar se a campanha era capaz de atrair novos clientes.
  
  Gostaria de expressar minha gratidão ao André Yukio por sua generosidade em compartilhar seus valiosos conhecimentos no clube.






