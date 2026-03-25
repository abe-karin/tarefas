Monitoramento de Estudos e Tarefas

Este projeto consiste em um notebook Python desenvolvido para automatizar o acompanhamento de atividades de estudo. Ele permite carregar registros de uma planilha Excel, realizar o tratamento de dados (limpeza) e gerar visualizações sobre o tempo dedicado a cada matéria.

📋 Funcionalidades

    Carregamento de Dados: Integração com arquivos .xlsx via biblioteca pandas.

    Tratamento de Dados: Preenchimento automático de valores ausentes em notas para evitar distorções na análise.

    Análise Agregada: Soma do tempo total gasto por cada disciplina.

    Visualização: Geração de gráficos de barras para facilitar a compreensão da distribuição do tempo de estudo.

🚀 Tecnologias Utilizadas

    Python 3.12

    Pandas: Manipulação e análise de dados.

    Matplotlib: Criação de visualizações estáticas e interativas.

    Openpyxl: Suporte para leitura de arquivos Excel.

🔧 Como Executar

    Certifique-se de ter o Python instalado em sua máquina.

    Instale as dependências necessárias executando:
    Bash

    pip install pandas openpyxl matplotlib

    Prepare um arquivo chamado arquivo.xlsx contendo pelo menos as colunas: Matéria, Tempo_Gasto (min) e Nota.

    Execute as células do notebook tarefas.ipynb em sequência.

📊 Exemplo de Visualização

O script gera um gráfico de barras que correlaciona as disciplinas com o tempo investido, ajudando a identificar quais áreas estão recebendo maior foco no cronograma.