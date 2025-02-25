---
demo:
  title: Demonstração Financeira
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração Financeira

**Cenário**:  

Você é um analista financeiro da Contoso, responsável por avaliar o desempenho das vendas e o posicionamento de mercado no setor de carregamento de veículos elétricos. Sua meta é analisar os dados de vendas, gerar insights e preparar um resumo para sua equipe.

## Configuração da demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Copiloto no Excel  

Use o Copilot no Excel para analisar dados de vendas, identificar as principais tendências e calcular métricas financeiras.

1. Inicie o Excel e abra o arquivo  

1. Abra **Finance_Sales_Analysis.xlsx** no Excel (no navegador ou no aplicativo da área de trabalho).  

1. Navegue até a guia **“Vendas por Produto”**.  

1. Use o Copilot para classificar a tabela inserindo o seguinte prompt:  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - O Copilot classifica a tabela e atualiza o conjunto de dados.  
    - Selecione **"Aplicar"** após a classificação.  

1. Insira uma coluna "Receita total"  

    Use o seguinte prompt no painel do Copilot:  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - O Copilot cria a nova coluna e aplica a fórmula.  
    - Selecione **“Inserir coluna”**.  

1. Gerar uma Tabela de Resumo de Vendas para 2024  

    Insira o seguinte prompt no painel Copilot:  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - O Copilot gera uma tabela de resumo.  
    - Selecione **"Adicionar a uma nova Folha de Dados"** para armazenar a tabela separadamente.  
    - Certifique-se de que a tabela inclua **apenas dados de 2024**.  
    - Navegue de volta para a guia **"Vendas por produto"** ou selecione **"Voltar aos dados"** na última resposta do Copilot.  

1. Identifique o produto mais vendido  

    Insira o seguinte prompt no painel Copilot:  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - O Copilot analisa o conjunto de dados e fornece o produto mais vendido.
    - Navegue de volta para a guia **"Vendas por produto"** ou selecione **"Voltar aos dados"** na última resposta do Copilot.  

1. Classificar clientes por receita

    - Navegue até a planilha **“Clientes”** no Excel.

    Insira o seguinte prompt no painel Copilot:  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - O Copilot classifica os clientes por **receita anual**.  
    - Selecione **"Aplicar"** após a classificação.  

1. Calcular receita média por cliente

    Digite a seguinte solicitação:  

    ```text
    Calculate the average revenue per customer.
    ```  

    - O Copilot calcula a média e adiciona o resultado.  
    - Selecione **"Inserir linha"** para armazenar o valor da receita média.  

1. Encontre o setor que está usando mais energia  

    Insira o seguinte prompt no painel Copilot:  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - O Copilot processa os dados e retorna o setor com o maior consumo de energia.

1. Salve o documento. Copie o URL compartilhado do documento (habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Use o Copilot Chat para comparar o desempenho financeiro com benchmarks e concorrentes do setor.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).

1. Certifique-se de que o Modo Web esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Na janela de prompt, digite o seguinte:

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. Agora, peça ao Copilot Chat para comparar isso com os concorrentes:

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. por fim, peça ao Copilot para exportar o histórico de chats até o momento para um documento do Word:

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. Selecione o arquivo vinculado para fazer o download e, em seguida, abra o documento.

1. Selecione **Habilitar Edição**.

1. O arquivo deve ter um título semelhante a “**Charging_industry_Financial_Summary.docx**”. Copie o URL compartilhado do documento (habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot no Word

Use o Copilot no Word para resumir os insights financeiros em um e-mail para nossa equipe.

1. Abra um novo documento do Word (em seu navegador ou aplicativo da área de trabalho).

1. Na caixa de prompt **“Descreva o que você gostaria de escrever”**, digite o seguinte:

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **OBSERVAÇÃO:** Anexe o arquivo Charging_industry_Financial_Summary.docx criado na tarefa anterior ou cole o link compartilhado diretamente no prompt para garantir que o Copilot tenha acesso ao conteúdo relevante.

1. Revise a saída do Copilot. Antes de selecionar **Manter**, refine a resposta perguntando ao Copilot:

    ```text
    Shorten this email draft
    ```

1. Outros refinamentos opcionais:

    - peça ao Copilot para reformular as seções para um tom mais profissional.
    - Expanda com seções adicionais.
    - Torne-o menos formal

1. Após terminar, você pode selecionar **Manter**
