<h1>ETL de dados não ordenados ("não-estruturados")</h1>

  <p>Visualizar dados em tabela, muitas vezes, pode ser desconfortável, principalmente quando são dados que, por si só, podem gerar algum desconforto, como no caso de dados financeiros, mais ainda quando se trata de finanças pessoais. </p>
  <p><b>Visualizar esses dados em gráficos pode ser muito mais fácil, rápido e confortável.</b></p>
  <p>Para apresentar informações em visuais é preciso ter uma base de dados organizada e bem estruturada, a qual, para ser obtida precisa passar por um processo de ETL (extract, transform and load).
  
  <h2>Projeto - ETL e visualização com Power BI</h2>
  <ul>
    <p>A fim de construir um dashboard que permite ver as despesas e receitas pessoais mensais, acompanhar gastos e ter uma visão anual da vida financeira, utilizei uma base de dados não ordenados onde desenvolvi o ETL para obtenção dos dados estruturados.</p>
  
![ETL_dados_final1](https://user-images.githubusercontent.com/73675930/163903996-2b5b7125-aca3-43b4-aa79-45fed7c481a7.png)
</ul>

   <h3><b>Etapas do ETL:</b></h3>
    <ul>
      <li>filtrar linhas nulas
      <li>excluir de colunas sem dados importantes
      <li>renomear colunas a serem utilizadas
      <li>transformar cabeçaçho em linha
      <li>transposição da tabela
      <li>promever primeira linha a cabeçalho
      <li>obter coluna ano_mês
      <li>remover colunas desnecessárias
      <li>transformar colunas em linhas
      <li>ajuste dos dados (tipo, ...)
        <li>Uma tabela de cadastro de despesas foi utilizadas para adicionar o id dos itens à tabela de dados.<li>
    </ul>
    
   <h3>Resultado final - Visualização dos dados</h3>
        <p>Para construção do dashboard, a base de dados foi dividida em dados de despesas por grupo, despesas por subgrupos e receitas, e também, utilizado a base de dados de cadastro.
    
![image](https://user-images.githubusercontent.com/73675930/163906365-12b410b8-4c05-4cb1-a1a2-5e40c8a86231.png)

O dashboard completo pode ser acessado clicando <a href="https://app.powerbi.com/view?r=eyJrIjoiM2ZhMjI3OGEtMDAyMS00ODY3LThiOWYtOTM4NGFjZDA3NTk2IiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9&pageName=ReportSection">aqui</a>.


    
