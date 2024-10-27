Projeto TP01 - ETL com Pentaho Kettle

Autores

Nome do Autor: Bruno Enes

Número de aluno: 25992


Estrutura de Arquivos

README.md: Arquivo que fornece uma visão geral do projeto, incluindo as descrições dos arquivos e as instruções para execução.

Diretórios e Arquivos do Projeto

tp01-25992/: Pasta raiz do projeto

doc/tp01\_25992\_doc.pdf: Documento do projeto, incluindo uma explicação detalhada sobre o desenvolvimento, metodologias aplicadas, transformações ETL e jobs configurados.

dataint/: Diretório contendo as transformações e jobs do Pentaho Kettle utilizados para a execução do processo ETL.

Transformações: Arquivos .ktr que contêm as transformações de dados do projeto.

Jobs: Arquivos .kjb que contêm a sequência dos jobs para execução das transformações e envio de e-mail.

data/input/: Pasta onde estão os dados de entrada, em formato CSV, necessários para o processo ETL, como:

clientes.csv: Dados dos clientes que serão filtrados e processados.

produtos.csv: Lista de produtos com descrições e preços.

data/output/: Pasta onde os arquivos de saída gerados pelo processo são armazenados.

src/: Pasta contendo código complementar ao projeto, incluindo arquivos XSL e scripts auxiliares.

Execução do Projeto

Ferramentas Utilizadas

Pentaho Data Integration (PDI): Para executar o processo ETL e manipular as transformações e jobs.

Instruções para Executar

Importar Transformações e Jobs:

Abra o Pentaho Data Integration (Spoon) e importe os arquivos de transformação (.ktr) e jobs (.kjb) localizados na pasta dataint/.

Configurar Caminhos de Arquivo:

Verifique os passos de entrada e saída para garantir que os caminhos apontem para os arquivos nas pastas data/input/ e data/output/.

Executar os Jobs:

No Spoon, execute os jobs  localizados em dataint/. Este job realizará a leitura dos dados, executará as transformações e enviará o e-mail configurado.

Visualizar Resultados:

Abra e visualize o arquivo clientes\_filtrados.xml.
