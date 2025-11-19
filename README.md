# Testes de Performance com Apache JMeter – Projeto Blazedemo


Este projeto apresenta um cenário simples e objetivo de testes de performance utilizando o Apache JMeter.  
A ideia é demonstrar, de forma clara, como estruturo um plano de teste, executo o cenário, coleto os resultados e consolido a análise em um relatório técnico.

O cenário foi executado sobre a aplicação Blazedemo, permitindo observar o comportamento da aplicação sob carga e entender como ela responde a múltiplas requisições simultâneas.


---


## 1. Objetivo do Projeto

O propósito deste repositório é demonstrar:

- Como criar e organizar um plano de teste no JMeter.  
- Como estruturar requisições, grupos de usuários e coleta de resultados.  
- Como interpretar métricas de performance (tempo de resposta, throughput, erros).  
- Como transformar os dados coletados em uma análise clara e objetiva.  
- Como manter um fluxo organizado de execução, evidências e documentação técnica.

Este projeto reflete a forma como trabalho diariamente com performance: clareza, organização e foco em comunicar o comportamento real da aplicação.


---


## 2. Por que este projeto é importante

Mais do que executar um teste, este projeto demonstra práticas fundamentais de uma análise de performance profissional:

### Comunicação simples e direta
Cenário pensado para que qualquer pessoa — técnica ou não — consiga entender o que está sendo validado.

### Estrutura organizada do plano de teste
O arquivo `.jmx` apresenta um plano limpo, modular e fácil de manter.

### Uso do CSV e HTML Report
Os resultados são coletados em CSV e transformados em um relatório visual que facilita a leitura de métricas como percentis, tempo médio e taxa de erros.

### Análise baseada em evidências
O arquivo PDF apresenta a interpretação do comportamento observado, consolidando conclusões baseadas nos dados coletados.

### Demonstração prática de competências
O projeto reúne os elementos essenciais de uma análise profissional: construção do cenário, execução, leitura e documentação das métricas.


---


## 3. Estrutura do Repositório

```plaintext

Jmeter/
├── Blazedemo_teste.jmx # Plano de teste criado no JMeter
├── Blazedemo_test.csv # Resultados brutos da execução
├── index.html # Relatório HTML gerado com o CSV
├── Relatório_Blazedemo_test.pdf # Análise técnica dos resultados
└── README.md # Documentação do projeto
```


---


## 4. Tecnologias Utilizadas

- Apache JMeter  
- Java (necessário para rodar o JMeter)  
- CSV  
- HTML Report  
- PDF para relatório técnico  
- Aplicação alvo: Blazedemo

---


## 5. Como Executar

### Pré-requisitos

- Apache JMeter instalado  
- Java instalado na máquina

### Passo a passo

1. Abra o Apache JMeter.  
2. Carregue o arquivo:

Blazedemo_teste.jmx


3. Execute o teste clicando em **Start**.  
4. O arquivo de resultados será gerado como:



Blazedemo_test.csv


---


## 6. Gerando o Relatório HTML

1. Crie uma pasta chamada:

HTML Report


2. No JMeter, vá em:

Tools > Generate HTML Report


3. Preencha os campos:

- **Results file** → selecione o arquivo `.csv`  
- **User properties file** → selecione `user.properties` da pasta `/bin` do JMeter  
- **Output directory** → selecione a pasta `HTML Report`


4. Depois, abra o arquivo:

index.html


Esse relatório exibe gráficos, percentis, taxas de erro e detalhes importantes sobre o comportamento da aplicação.


---


## 7. Relatório de Análise (PDF)


O arquivo:

Relatório_Blazedemo_test.pdf


inclui:
- Descrição do cenário  
- Principais métricas coletadas  
- Interpretação dos gráficos  
- Conclusões sobre a performance da aplicação  

---


## 8. Considerações Finais

Este projeto demonstra de forma prática como estruturo e analiso testes de performance.  
Ele evidencia organização, clareza, análise orientada a dados e documentação técnica objetiva.

Também pode servir como base para cenários mais complexos ou como referência da minha abordagem ao trabalhar com performance.


---
