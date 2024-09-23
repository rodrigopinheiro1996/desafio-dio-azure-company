## Relatório de Caracterização do Projeto: Integração e Transformação da Base de Dados "Azure_Company"

Neste projeto, foi criada uma instância do MySQL a partir de uma conta no Azure. Usando o ambiente Bash do Azure, foi desenvolvido um banco de dados de teste chamado Azure_Company, no qual foram inseridos dados fictícios para simular um cenário real.

Após a criação e inserção dos dados, realizou-se a integração entre o MySQL do Azure e o Power BI, possibilitando a visualização e manipulação dos dados diretamente na plataforma de análise.

Em seguida, aplicaram-se algumas pequenas transformações nos dados dentro do Power BI, incluindo:

Conversão dos valores de salário para o formato decimal fixo, assegurando maior precisão.
Remoção dos valores nulos na coluna super_ssn, tornando os dados mais consistentes.
Separação da coluna endereço em quatro novas colunas: número, rua, cidade e estado, facilitando a análise geográfica e organizacional.
Remoção de colunas desnecessárias para simplificar a visualização e análise dos dados.
Embora fosse possível aplicar fusões entre diferentes tabelas para criar uma nova tabela consolidada com informações combinadas, optei por realizar apenas pequenas transformações para manter o projeto mais enxuto e direto ao ponto.

Por fim, foi criado um relatório simples no Power BI para facilitar a visualização dos dados e das transformações aplicadas. Vale lembrar que todos os dados utilizados são fictícios e têm caráter meramente ilustrativo.

![image](https://github.com/user-attachments/assets/bd93d489-3f93-42c2-89ea-1a5885fd55c9)

![image](https://github.com/user-attachments/assets/e20deee0-753c-4b29-a0ed-b76dac396931)

![image](https://github.com/user-attachments/assets/1c4981fe-8878-4ead-a83a-c1d6a975e7be)

![image](https://github.com/user-attachments/assets/17e2a7c0-ab0d-44ca-98b4-2ff242e7ffbc)
