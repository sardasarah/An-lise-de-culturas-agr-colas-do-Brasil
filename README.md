# Análise da produtividade e do lucro das culturas agrícolas ao longo dos anos no Brasil.
Esse projeto tem como objetivo utilizar a ferramenta Excel para analisar dados de sensores de agricultura inteligente, buscando problemáticas para tomada de decisão. Esses dados são de fazendas localizadas em regiões como Índia, EUA e África.

# Detalhes do conjunto de dados
O dataset utilizado possui várias tabelas, para esse projeto foram utilizadas:
- farm_id: Identificador único para cada fazenda inteligente (ex.: FARM0001)
- region: Região geográfica (ex.: Norte da Índia, Sul dos EUA)
- crop_type: Culturas cultivadas: Trigo, Arroz, Milho, Algodão, Soja
- rainfall_mm: Precipitação total recebida em mm
- irrigation_type: Tipo de irrigação: Gotejamento, Aspersão, Manual, Nenhuma
- fertilizer_type: Fertilizantes utilizados: Orgânicos, Inorgânicos, Mistos
- pesticide_usage_ml: Uso diário de pesticidas em mililitros
- yield_kg_per_hectare: Variável alvo: Produtividade da cultura em quilogramas por hectare
- NDVI_index: Índice de Vegetação por Diferença Normalizada (0,3 - 0,9)
- crop_disease_status: estado_doenca

# Nome das tabelas
- ID_Fazenda
- Região
- Tipo_Cultura
- Chuva_mm
- Tipo_Irrigação
- Tipo_Fertilizante
- Uso_Pesticida_ml
- Rendimento_kg_ha
- Índice_Saude_NVDI
- Eficiência Hídrica
- Eficiência de Pesticida
  

# Investigações
1. Encontrar a eficiência hídrica e de pesticida para diferentes plantas e seus devidos filtros para responder o quanto a cultura produz por litro de água e pesticida, a fim de avaliar a produtividade.
2. Avaliar desperdício de recurso hídrico e de agrotóxicos por cultura, dessa forma é possível verificar o quanto de recursos a empresa está jogando fora sem trazer retorno em produção. Essa análise acaba entrando em métricas ambientais, já que se há desperdício, estão gastando mais dinheiro e poluindo o solo (no caso do agrotóxico) sem necessidade.
3. Analisar as eficiências entre si para encontrar qual cultura melhor aproveita os recursos,
 
# Visão Geral dos Dashboards
Dashboard de análise das vendas:
- KPIs(indicador chave de desempenho) de rendimento médio, quantidade de fazendas, eficiência hídrica e de pesticida.
- Gráfico de Combinação Personalizada: Mostra as eficiência de chuva e agrotóxico.
- Gráfico de Colunas Agrupadas: 3 gráfico que evidenciam o desperdício dos dois recursos e 1 gráfico que mostra as culturas mais rentáveis.

# Principais Insights
1. O faturamento mensal da empresa depende de eventos como a Black Friday, uma vez que há um grande pico de receita em novembro. Em contrapartida, janeiro apresenta o menor faturamento registrado, baseando-se no ano de 2017. Na logística, os atrasos são altos em novembro, o que mostra que a empresa não está conseguindo lidar com o volume de pedidos nessa época do ano.
2. Há pouca participação no faturamento total por estados das regiões Nordeste e Norte entre as dez regiões com maior faturamento. Isso mostra que a Olist ainda não conquistou essas regiões em razão da logística da transportadora, já que esta é, a princípio, a culpada pelos atrasos — sendo a região Nordeste a que possui os maiores índices de demora.
3. Cartão de crédito e boleto são as opções mais utilizadas pelos clientes, o que é melhor para a empresa, já que a confirmação do pagamento com essas formas é mais rápida e contribui para diminuir os atrasos.
4. As regiões Norte e Nordeste possuem as maiores quantidades de dias para entrega e, mesmo após a data estimada, ficam atrás de outros estados no cumprimento do prazo de entrega.
5. A logística da Olist é imprevisível para as regiões Norte e Nordeste, pois, ainda que os fretes possam ser mais caros, o pedido pode demorar muitos dias para chegar. Em média, os fretes mais baratos continuam apresentando demora na entrega.
6. A região Sudeste é a que menos demora para receber seus pedidos, principalmente São Paulo, mesmo quando o vendedor é de uma região distante.
7. Entre os culpados pelos atrasos, destaca-se a transportadora; contudo, muitas vezes é o vendedor quem demora para despachar o produto.
8. Produtos da categoria de Beleza são os mais vendidos, porém possuem um dos menores tickets médios, exigindo um volume maior de vendas. Entretanto, a categoria de Relógios possui menos vendas, mas seu ticket médio é alto, sendo interessante para a empresa investir nessa categoria para aumentar o faturamento.
# Conclusão
Os dashboards da Olist oferecem uma visão abrangente da performance de vendas e da logística da empresa. Ao utilizar o Power BI e o DAX, os dashboards fornecem informações valiosas, incluindo:

Relação entre o ticket médio e os produtos.
Evolução da empresa mensalmente e por região.
Formas de pagamento mais usadas pelos clientes. 
Categorias de produtos, que geram mais receita dentro da empresa.
Em quais estados a Olist é mais explorada.
Como a empresa está em relação a demora para entregar o produto, os atrasos e peso do frete no valor do pedido.
Principais culpados pelos atrasos.
Estados com mais atrasos.
A promessa dos fretes.

# Conecte-se comigo
Fique à vontade para se conectar comigo no LinkedIn: [Sarah Costa](www.linkedin.com/in/sarah-costa-a84425290).]
Você também pode entrar em contato comigo por e-mail: sarah.costaepereira@gmail.com
