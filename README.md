# Formação Engenheiro de Dados
Esse repositório trata do Curso Formação Engenharia de Dados: Domine Big Data! da Udemy do Professor Fernando Amaral.
<br>
<br>
O repositório conta com as pastas indicando as unidades do curso, junto com os slides e scripts de desenvolvimento práticos realizados.
<br>
<h2>O que é abordado no curso:</h2>
<ul>
  <li>Engenharia de Dados com Python</li>
  <li>ETL e Data Crawlers</li>
  <li>Introdução ao Ecossitema Hadoop</li>
  <li>Spark com Databricks</li>
  <li>Data Lake (Amazon Redshift)</li>
  <li>Modelo de banco de dados Relacional</li>
  <li>Computação em Nuvem (AWS)</li>
  <li>Aplicações em Streaming (Amazon Kinesis)</li>
  <li>Gerenciamento de serviços pela CLI</li>
  <li>NoSQL</li>
  <li>Data Warehouse Moderno</li>
  <li>Modelo de banco de dados Dimensional</li>
  <li>Linguagem SQL</li>
</ul>
<br>
<h2>Projeto Final I</h2>
O Projeto Final 1 do curso traz algumas atividades práticas.
<br>
<br>
Foi desenvolvido consultas SQL para geração de informação e conhecimento para a área de análise de dados.
<br>
<br>
Para a realização da atividade foi criado um ambiente no AWS Redshift (Cluster).
<br>
<br>
Foi criado um banco de dados Northwind.
<br>
<br>
E dentro desse banco de dados foram desenvolvidas as consultas que estão no repositório, para resolver problemas de negócio do dia-a-dia de uma corporação, simulando o trabalho de um Engenherio de Dados.
<br>
<br>
<strong>Etapas:</strong>
<ul>
  <li>1. Criar cluster no Redshift</li>
  <li>2. Criar banco de dados Northwind</li>
  <li>3. Criar estrutura do Banco de Dados:</li>
  <li>4. Criar credenciais para Copy</li>
  <li>5. Fazer upload dos arquivos vcs para um bucket qualquer(S3)</li>
  <li>6. Executar copy para carregar dados</li>
  <li>7. Realizar as atividades de consulta (estão na pasta do repositório)</li>
</ul>
<br>
<h2>Projeto Final II</h2>
O Projeto Final 2 do curso traz algumas atividades práticas.
<br><br>
Nesse projeto foi criado uma aplicação em Streaming usando o Amazon Kinesis.
<br><br>
Foram criados produtores de dados em Python, simulando um Parque Eólico, o qual gera dados dos sensores de energia, temperatura e pressão.
<br><br>
Esses dados são passados para o Kinesis Data Streams, logo em seguida para o Kinesis Data Firehouse para serem aramazenados em um Bucket do S3, para que por fim pudessem ser passados ao AWS Glue. Assim fazendo consultas finais utilizando o Athena.
<br><br>
Os scripts dos produtores de dados estão no repositório.
