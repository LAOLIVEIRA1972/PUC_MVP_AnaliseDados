<div align="center">
<h1><b>MVP Análise de Dados e Boas Práticas</b></h1>
<h3>Pós-Graduação em Ciência de Dados e Analytics <br>
Pontifícia Universidade Católica do Rio de Janeiro (PUC-Rio)</h3>
</div>
<br>
<div>

<b>Disciplina</b><br>
Análise Exploratória e Pré-Processamento de Dados</br><br>

<b>Objetivo</b><br>
Dado um conjunto de características referentes a paradas programadas em plataformas petrolíferas, o objetivo é prever a duração, em número de dias, de cada ocorrência. Como a variável de interesse é uma medida quantitativa contínua, o problema é caracterizado como um problema de regressão supervisionada.</br><br>

<b>Conteúdo do repositório</b>
<ol>

<li>O arquivo dataset_plataformas.xlsx é o dataset utilizado neste trabalho, composto por um conjunto de dados multivariado contendo informações referentes a paradas programadas de plataformas petrolíferas de uma empresa específica do setor.</li>

<li>O arquivo mvp_Analise_Dados.ipynb corresponde ao Notebook do trabalho, contendo rotinas de leitura do dataset, análise exploratória e pré-processamento dos dados.</li>
</ol>
<br>
<b>Estrutura do Notebook</b><br><br>

O notebook está organizado nas seguintes seções principais:
<ul>
  <li>1- Descrição do Problema
    <ul>
      <li>1.1- Objetivo</li>
      <li>1.2- Hipóteses do Problema</li>
      <li>1.3- Tipo de Problema</li>
      <li>1.4- Seleção de Dados</li>
      <li>1.5- Descrição do Dataset</li>
    </ul>
  </li>
  <li>2- Importação das Bibliotecas Necessárias e Carga de Dados</li>
  <li>3- Análise de Dados
    <ul>
      <li>3.1- Informações Gerais
        <ul>
          <li>3.1.1- Total de Instâncias e Tipos de Atributos</li>
          <li>3.1.2- Verificação de Valores Nulos</li>
          <li>3.1.3- Verificação de Registros Duplicados</li>
          <li>3.1.4- Verificação das Primeiras Linhas do Dataset</li>
          <li>3.1.5- Verificação das Últimas Linhas do Dataset</li>
        </ul>
      </li>
      <li>3.2- Estatísticas Descritivas</li>
      <li>3.3- Visualizações e Análise de Correlações
        <ul>
          <li>3.3.1- Média e Desvio Padrão de Duração de Paradas por Tipo de Plataforma</li>
          <li>3.3.2 - Histograma</li>
            <ul>
              <li>3.3.2.1- Duração das paradas</li>
              <li>3.3.3.2- Idade das plataformas</li>
            </ul>
          <li>3.3.3 - Matriz de Correlação</li>
          <li>3.3.4- Boxplot</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>4- Pré-Processamento de Dados
    <ul>
      <li>4.1- Limpeza dos dados
        <ul>
          <li>4.1.1- Tratamento de Valores Ausentes (Missing Values)</li>
          <li>4.1.2- Tratamento de Outliers</li>
        </ul>
      </li>
      <li>4.2- Feature Engineering e Feature Selection</li>
      <li>4.3- Separação do Dataset entre Treino e Teste</li>
      <li>4.4- Normalização e Padronização</li>
    </ul>
  </li>  
  <li>5- Conclusão</li>
</ul>

<br>
<b>As hipóteses investigadas neste estudo são as seguintes:</b>

<ol>
<li>Determinados tipos de plataformas estão associados a paradas programadas de maior duração?</li>
<li>Existe correlação entre a idade da plataforma e a duração da parada programada, considerando que equipamentos mais antigos podem demandar maior atenção de manutenção?</li>
<li>Paradas realizadas em plataformas afretadas apresentam menor duração (maior otimização) do que aquelas realizadas em plataformas próprias?</li>
<li>Considerando que operações em maiores profundidades tendem a ser mais complexas, as paradas programadas em lâminas d’água rasas geralmente apresentam menor duração?</li>
<li>O tipo de operação (produção ou injeção) e a existência de restrição à queima de gás durante a parada influenciam a sua duração?</li>
</ol>
</div>
