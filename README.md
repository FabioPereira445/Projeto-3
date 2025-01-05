# EDA e Análise de Crédito com SQL
 <img src="image/project1_2.jpeg.png" alt="Uma bela paisagem" width="1000" height="500" title="Clique para ampliar">
 <h2>1. Introdução</h2>
<P>No cenário atual de mercado, instituições financeiras enfrentam desafios significativos para entender e atender melhor seus clientes, otimizando ofertas de produtos e serviços de crédito. Este projeto visa realizar uma análise detalhada dos dados de crédito dos clientes utilizando ferramentas e técnicas de SQL, com o objetivo de identificar padrões e gerar insights valiosos.</P>
 

 <h3> 1.2 Objetivo</h3>
 <p>O objetivo do projeto é realizar uma análise detalhada dos dados de crédito utilizando SQL para identificar padrões e insights sobre os clientes, otimizando campanhas de marketing e revisando critérios de concessão de crédito.
</p>

<h2>2.0.Dados</h2>
<p>Os dados representam informações de clientes de um banco e contam com as seguintes colunas:</p>

<ul>
  <li><strong>idade</strong>: idade do cliente</li>
  <li><strong>sexo</strong>: sexo do cliente (F ou M)</li>
  <li><strong>dependentes</strong>: número de dependentes do cliente</li>
  <li><strong>escolaridade</strong>: nível de escolaridade do cliente</li>
  <li><strong>salario_anual</strong>: faixa salarial do cliente</li>
  <li><strong>tipo_cartao</strong>: tipo de cartão do cliente</li>
  <li><strong>qtd_produtos</strong>: quantidade de produtos comprados nos últimos 12 meses</li>
  <li><strong>iteracoes_12m</strong>: quantidade de iterações/transações nos últimos 12 meses</li>
  <li><strong>meses_inativo_12m</strong>: quantidade de meses que o cliente ficou inativo</li>
  <li><strong>limite_credito</strong>: limite de crédito do cliente</li>
  <li><strong>valor_transacoes_12m</strong>: valor das transações dos últimos 12 meses</li>
  <li><strong>qtd_transacoes_12m</strong>: quantidade de transações dos últimos 12 meses</li>
</ul>
<strong>Ferramentas Utilizadas:</strong>

<strong>Dataset:</strong> O dataset está disponível em um endereço do GitHub.
<strong>Armazenamento:</strong> O dataset foi inserido no AWS S3 Bucket da AWS Amazon.
<p><strong>Consultas:</strong> As consultas SQL foram realizadas utilizando o AWS Athena da AWS Amazon.</p>

<p>A tabela foi criada no <strong>AWS Athena</strong> junto com o <strong>S3 Bucket</strong> com uma versão dos dados disponibilizados em: <a href="https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset">https://github.com/andre-marcos-plistas/ebac-course-utils/tree/main/dataset</a></p>




<h3>3.0 Bibliotecas Python Utilizadas</h3>
<h3> Manipulação de dados</h3>
<img src="image/img_numpy(1).svg" alt="Uma bela paisagem" width="75" height="25" title="img_pandas(1)">
<img src="image/img_pandas(1).svg" alt="Uma bela paisagem" width="75" height="25" title="img_numpy(1)">
<h3> EDA</h3>
<img src="image/img-google-data-studio.svg" alt="Uma bela paisagem" width="75" height="25" title="SQL">
<img src="image/img-google-data-studio.svg" alt="Uma bela paisagem" width="75" height="25" title="S3">
<img src="image/img-google-data-studio.svg" alt="Uma bela paisagem" width="75" height="25" title="Athena">

<h2>4.0 Conclusão:</h2>
Essas foram algumas análises extraídas do dataset de crédito.  

Alguns insights interessantes:

- A maior parte dos clientes possui renda até 40K
- A maior parte dos clientes é masculino!
- A escolaridade não parece influenciar no limite nem no tipo do cartão
- Os clientes com maiores limites são em sua maioria homens
- Os clientes com menores limites são em sua maioria mulheres
- Dentre os menores limites não há presença de cartão platinum
- A faixa salarial impacta diretamente no limite de crédito
- Não existem clientes com salário anual acima de 60K do sexo feminino


