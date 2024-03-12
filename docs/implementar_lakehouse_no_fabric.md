# Implementar um Lakehouse com o Microsoft Fabric

## Ingestão de um LakeHouse

- **Upload:** carregue arquivos ou pastas locais no lakehouse. Em seguida, é possível explorar e processar os dados do arquivo e carregar os resultados em tabelas.

- **Fluxo de dados (Gen2):**: importe e transforme dados de uma variedade de fontes usando o Power Query Online e carregue-os diretamente em uma tabela no lakehouse.

- **Notebooks:** use os notebooks no Fabric para ingerir e transformar dados e carregá-los em tabelas ou arquivos no lakehouse.

- **Pipelines do Data Factory:** copie dados e orquestre atividades de processamento de dados, carregando os resultados em tabelas ou arquivos no lakehouse.

## Transformação/Análise de dados de um Lakehouse

- **Apache Spark:**: No Fabric da para usar Scala, PySpark e Spark SQL.

- **Ponto de extremidade analítico do SQL:** Cada lakehouse inclui um ponto de extremidade analítico do SQL por meio do qual é possível executar instruções Transact-SQL para consultar, filtrar, agregar e explorar dados em tabelas do lakehouse. 

- **Fluxos de dados (Gen2):** além de usar um fluxo de dados para ingerir dados no lakehouse, é possível criar um fluxo de dados para executar transformações subsequentes por meio do Power Query e, opcionalmente, colocar os dados transformados novamente no lakehouse.

- **Pipelines de dados:** Coordena uma lógica de transformação de dados complexa que opera em dados no lakehouse por meio de uma sequência de atividades (como fluxos de dados, trabalhos do Spark e outras lógicas de fluxo de controle).

## Ingerir dados com um Lakehouse do Microsoft Fabric:

