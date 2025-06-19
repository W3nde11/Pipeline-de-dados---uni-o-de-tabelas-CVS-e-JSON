<H1>📊 Projeto Pipeline de Dados com Python</H1>
<P>Este projeto tem como objetivo demonstrar a construção de um pipeline de dados utilizando Python em um ambiente Linux Ubuntu via WSL (Windows Subsystem for Linux). O pipeline abrange desde a aquisição e leitura de dados, até a transformação, organização e salvamento final, utilizando boas práticas de Engenharia de Dados, programação funcional e orientação a objetos.</P>

<h2>🛠️ Tecnologias Utilizadas</h2>

  <ul>
      <li>Python 3.x</li>  
      <li>Jupyter Notebook (.ipynb)</li>
      <li>Linux Ubuntu (WSL)</li>
      <li>Bibliotecas: csv, json</li>
      <li>Comandos Shell (wget, mkdir, etc.)</li>
  </ul>


<h2>📁 Estrutura do Projeto</h2>

pipeline_dados/

    pipeline_dados/
    │
    ├── dados_raw/              # Dados brutos
    ├── notebooks/              # Notebooks Jupyter com exploração inicial
    ├── scripts/                # Scripts Python (ETL, classes, utilitários)
    ├── dados_processed/        # Relatórios gerados ao final do pipeline .CSV
    └── README.md               # Documentação do projeto


<h2>🔄 Funcionalidades do Pipeline</h2>
<h3>🔹 Exploração e Aquisição de Dados</h3>
<ul>
    <li>Uso de comandos Linux (mkdir, wget) para organização e download de dados.</li>
    <li>Leitura de arquivos com open(), csv.DictReader, readlines() e json.load().</li>
</ul>

<h3>🔹 Processamento e Transformação</h3>
<ul>
    <li>Estruturação dos dados com keys(), get(), items() e extend().</li>
    <li>Renomeação de colunas com for e manipulação de dicionários.</li>
    <li>Criação de listas de listas com get() e for.</li>
    <li>Salvamento de dados com csv.DictWriter e csv.writer.</li>
</ul>

<h3>🔹 Arquitetura do Pipeline</h3>
<ul>
    <li>ETL (Extract, Transform, Load):</li>
    <li>Criação de funções modulares para cada etapa do pipeline.</li>
    <li>Refatoração para aplicação de paradigma de orientação a objetos.</li>
    <li>Criação da classe Dados, com atributos e métodos especializados.</li>
    <li>Geração de relatórios contendo:</li>
    <ul>
        <li>Quantidade de dados lidos</li>
        <li>Dados processados e armazenados</li>
        <li>Caminhos dos arquivos gerados</li>
    </ul>
</ul>

<h3>🔹 Organização do Código</h3>
<ul>
    <li>Separação entre exploração e execução final.</li>
    <li>
        Código refatorado para fácil manutenção e reutilização.    
    </li>
    <li>Utilização de scripts automatizados para facilitar a execução do pipeline.</li>
</ul>

<h2>🧠 Alinhamento com o Cliente</h2>
<p>Durante o desenvolvimento do pipeline, foram realizadas reuniões com o cliente para:</p>

<ul>
    <li>Validar a estrutura e formato dos dados.</li>
    <li>Definir a melhor forma de armazenamento.</li>
    <li>Identificar necessidades específicas para transformação de colunas e geração de relatórios.</li>
    <li>Refatorar o projeto conforme novas demandas surgiram.</li>
</ul>

<h2>🚀 Como Executar</h2>
<ol>
    <li>Abra o terminal no WSL (Ubuntu)</li>    
    <li>Clone o repositório e acesse a pasta do projeto:</li>

    git clone https://github.com/W3nde11/Pipeline-de-dados---uni-o-de-tabelas-CVS-e-JSON.git
    cd pipeline_dados
        
  <li>Instale os pacotes necessários (se aplicável)</li>
    
    pip install -r requirements.txt
    
  <li>Execute o pipeline via Jupyter ou script Python:</li>   
    <ul>
        <li> Via notebook: </li>
          
    jupyter notebook notebooks/exploracao.ipynb
  
  <li> Via script:</li>
            
    python scripts/fusao_mercado.py
        
</ol>


<h2>📋 Relatórios Gerados</h2>
<ul>
    <li>Arquivo .csv com dados limpos e estruturados</li>
    <li>Log com informações de execução</li>
    <li>Relatório final com estatísticas do pipeline</li>
</ul>

<h2>🧩 Contribuições Futuras</h2>
<ul>
    <li>Integração com banco de dados relacional</li>
    <li>Monitoramento com logs estruturados</li>
    <li>Testes unitários para validação do pipeline</li>
</ul>

<h2>📄 Licença</h2>
<p>Este projeto está licenciado sob a MIT License.</p>
