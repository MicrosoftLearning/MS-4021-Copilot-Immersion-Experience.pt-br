---
demo:
  title: Demonstração do gerente de negócios
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração do gerente de negócios

**Cenário**:

Analise o desempenho das vendas e o feedback dos clientes para solucionar um problema de produto e, em seguida, colabore com sua equipe para planejar melhorias.

## Configuração de demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **NOTA:** pode levar até 10 minutos para que esses arquivos sejam sincronizados em seu OneDrive após o download. Para evitar atrasos durante a demonstração, certifique-se de que esses arquivos tenham sido baixados e estejam disponíveis em seu OneDrive com bastante antecedência. Se os arquivos não estiverem disponíveis, abra os documentos e copie os links dos arquivos compartilhados para usá-los na demonstração.

## Etapas de demonstração

### Copilot no Excel

1. Inicie o Excel (em seu navegador ou aplicativo da área de trabalho) e abra o arquivo **EV_Charger_Sales_Analysis_v1.xlsx**.

1. **Navegue até a guia "Vendas por produto"**  no arquivo Excel.

1. Selecione **Copilot** na faixa de opções do Excel e, em seguida, selecione **Habilidades do aplicativo** para abrir o painel do Copilot.

1. Use o Copilot para calcular a receita mensal:  

   Vamos começar descobrindo qual categoria do seu negócio está gerando mais receita. Esta planilha contém três anos de dados de vendas, com milhares de linhas mostrando vendas por produto por mês. Embora seja uma tarefa rotineira, esse volume de dados pode ser difícil de manejar. Você pode pedir ao Copilot para calcular rapidamente a receita mensal por produto.

   Insira o prompt a seguir:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - O Copilot sabe como fazer isso e quais dados referenciar nas guias.
    - O Copilot criará um plano para executar esses números, executa esse plano mostrando seu trabalho à medida que avança e solicitará que você faça perguntas ou repita a solução alcançada.
    - Selecione **+Inserir coluna** e, em seguida, navegue de volta para a guia **Vendas por Produto**.

1. Use o Copilot para analisar a receita inserindo o seguinte prompt no painel do Copilot:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - O Copilot executará os números e criará um gráfico de barras que pode ser adicionado à sua pasta de trabalho.
    - Selecione **+Adicionar a uma nova folha** e, em seguida, navegue de volta para a guia **Vendas por produto**.

1. Agora, use o Copilot para destacar produtos com vendas baixas inserindo este prompt:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - O Copilot aplicará formatação condicional, ajudando-o a identificar os produtos que não estão atendendo aos seus padrões.

1. **Navegue até a guia "Avaliações"** para analisar o feedback dos clientes.

1. Peça ao Copilot para resumir as principais preocupações inserindo o seguinte prompt:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - O Copilot analisará o feedback e exporá as três principais preocupações dos clientes. Parece que a velocidade de carregamento é um problema emergente.

1. Em seguida, destaque as avaliações que mencionam a velocidade de carregamento inserindo este prompt:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - O Copilot destacará todas as avaliações relevantes no conjunto de dados.

### Copilot Chat

Agora que identificamos a velocidade de carregamento lenta como um problema importante, use o **Copilot Chat** para explorar mais o problema e identificar possíveis soluções.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).  

1. Certifique-se de que o **Modo Web** esteja selecionado.  

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Para pesquisar o problema, insira o seguinte prompt:
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Revise o resumo do Copilot e peça contexto adicional ou tendências recentes, se necessário.  

1. Opcionalmente, refine a saída:
   - Pergunte ao Copilot sobre tendências ou tecnologias recentes que abordam a eficiência do carregador EV:

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - Solicite insights da concorrência:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. Peça ao Copilot para elaborar cinco perguntas estratégicas para fazer ao líder do projeto de carregadores EV:

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot no Outlook

Nesta demonstração, usaremos o Copilot no Outlook para marcar uma reunião com o líder do projeto responsável pela linha de produtos de carregadores EV para discutir possíveis soluções.

1. Abra um navegador e navegue até [outlook.office.com](https://outlook.office.com.com/).

1. Na faixa de opções do Outlook, selecione o ícone do Copilot para abrir o painel do Copilot.

1. Na janela de prompt, digite o seguinte:

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. O Copilot deve sugerir uma hora e data para a reunião. o prompt exibe um item de calendário que pode ser enviado ou editado, selecione **Editar**.

1. Alterne para o assistente de agendamento para mostrar que o tempo sugerido pelo Copilot funciona para o gerente de projetos. Vocês dois devem estar disponíveis.

1. Volte para a guia do evento e selecione **Rascunho com Copilot** no corpo do evento

1. Na janela de prompt, digite o seguinte:

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. Opcionalmente, antes de selecionar **Manter**, você pode pedir ao Copilot para torná-la mais longa, mais curta ou alterar o tom da agenda redigida.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
