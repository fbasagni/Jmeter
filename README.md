# Testes de Performance com JMeter  📎

Este repositório contém um cenário de teste realizado pela ferramenta JMeter e em anexo está o HTML Report do caso de teste e também uma análise referente aos resultados. 

# Informações sobre o Repositório  📌

Blazedemo_teste.jmx: Arquivo JMX do cenário para aplicação do teste na ferramenta JMeter;

Blazedemo_test.csv : Arquivo CSV ao qual contém os resultados gerados pela ferramenta;

README.md : Informaçoes referente à finalidade do projeto;

Relatório_Blazedemo_test.pdf : Relatório em arquivo PDF referente à análise realizada através do HMTL Report gerado;

index.html : Arquivo do HTML report gerado


# Como Utilizar  ⚛️

   ## Pré-requisitos
   
Apache JMeter: Certifique-se de ter o Apache JMeter instalado em sua máquina. 

O JMeter é um Java puro, este aplicativo deve ser executado corretamente em qualquer sistema que tenha compatibilidade Java implementação

   ## Passos para Executar os Testes

Após a instalação, abra o JMeter:

   - Selecione o arquivo Blazedemo_teste.jmx no JMeter.


   ## Configurar os Testes:

   - Revise as informações contidas no arquivo JMX e realize o upload do arquivo CSV do caso de testes (o mesmo irá realizar a gravação de todas as informações geradas pela ferramenta!)
   - Após a execução do teste


   ## Geração de relatório:

   - Dento da pasta do caso de teste, criar uma pasta à parte "HTML Report"
   - Localizar no menu "Tools" > Generate HTML Report > Results file (CSV - Selecionar o arquivo CSV, ao qual contém as informações gravadas) > user.properties file (pasta JMeter > bin > selecionar o arquivo "user.properties") > Output directory (selecionar a pasta criada "HTML Report") > Generate Report > Para visualização, clicar na pasta e selecionar o arquivo Index

 
