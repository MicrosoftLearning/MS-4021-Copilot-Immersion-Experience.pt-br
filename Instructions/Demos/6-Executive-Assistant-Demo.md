---
demo:
  title: Demonstração do Assistente Executivo
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração do Assistente Executivo

**Cenário**:

Você recebeu a tarefa de resumir a transcrição da última chamada de conferência de lucros para seu executivo. Essa tarefa inclui extrair insights importantes, criar um resumo executivo e preparar uma reunião de acompanhamento.

## Configuração de demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **NOTA:** pode levar até 10 minutos para que esses arquivos sejam sincronizados em seu OneDrive após o download. Para evitar atrasos durante a demonstração, certifique-se de que esses arquivos tenham sido baixados e estejam disponíveis em seu OneDrive com bastante antecedência. Se os arquivos não estiverem disponíveis, abra os documentos e copie os links dos arquivos compartilhados para usá-los na demonstração.

## Etapas de demonstração

### Copilot no Word

Começaremos analisando a transcrição da chamada de lucros mais recente e resumindo os pontos chave para seu executivo.

1. Selecione e abra o arquivo **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** no Word (no navegador ou no aplicativo da área de trabalho).

    > **NOTA:** Você pode querer rolar rapidamente pelo documento para mostrar o tamanho dele e que não é uma tarefa simples resumi-lo.

1. Selecione o ícone Copilot na faixa de opções:

    ![Ícone do Copilot no Word.](../Demos/Media/Copilot-in-word-ribbon.png)

1. O painel do Copilot deve abrir. Digite o seguinte prompt onde está escrito **Pergunte-me algo sobre este documento**:

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. Imagine que seu executivo queira saber o que Satya Nadella discutiu especificamente durante a chamada. Insira o prompt a seguir:

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

   - Mostre como o Copilot inclui referências para cada marcador, permitindo uma navegação rápida para seções específicas.  
   - Clique em uma referência para demonstrar como o Copilot o leva instantaneamente ao conteúdo relevante do documento.

1. Para criar um relatório detalhado, pergunte ao Copilot:

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **Dica:** mencione que este é um prompt complexo e o Copilot pode levar algum tempo para gerar a resposta.

1. Quando o Copilot concluir a análise, selecione o ícone **Copiar** para salvar os resultados para a próxima etapa.

    ![Copiar resultados](../Demos/Media/Copilot-in-word-copy-results.png)


### Copilot Chat

O relatório fornecido pelo Word é um ótimo ponto de partida, mas agora queremos usar o Copilot Chat para nos ajudar a criar um resumo executivo.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).

1. Certifique-se de que o **modo Web** esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Cole a resposta do Copilot no Word no Copilot Chat com o seguinte prompt:

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **Nota:** Limpe qualquer texto estranho do conteúdo copiado para garantir a clareza.

1. Refine o resumo em um formato conciso:

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability. Export to a Word document.
    ```

   - Se o Copilot não exportar o documento, reformule a solicitação: "Salve este resumo como um documento do Word".

1. Com o resumo executivo concluído, pergunte ao Copilot:

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Copilot no Outlook

Nesta demonstração, usaremos o Copilot no Outlook para marcar uma reunião com o executivo e colocá-lo a par de tudo o que aconteceu durante a chamada de conferência de lucros do segundo trimestre.

1. Abra um navegador e navegue até [outlook.office.com](https://outlook.office.com.com/).

1. Na faixa de opções do Outlook, selecione o ícone do Copilot para abrir o painel do Copilot.

1. Use o prompt a seguir para programar uma sincronização:

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. O Copilot deve sugerir uma hora e data para a reunião. O prompt exibe um item de calendário que pode ser enviado ou editado. Selecione **Editar**.

1. Alterne para o assistente de agendamento para mostrar que o tempo sugerido pelo Copilot funciona para o gerente de projetos. Vocês dois devem estar disponíveis.

1. Volte para a guia do evento e selecione **Rascunho com Copilot** no corpo do evento

1. Na janela de prompt, digite o seguinte:

    ```text
    I’m meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. Opcionalmente, antes de selecionar **Manter**, você pode pedir ao Copilot para torná-lo mais longo, mais curto ou alterar o tom da agenda elaborada.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
