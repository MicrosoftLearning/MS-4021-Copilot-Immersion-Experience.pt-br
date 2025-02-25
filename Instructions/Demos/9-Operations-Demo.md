---
demo:
  title: Demonstração de operações
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração de operações

## Cenário

Você é um Operations Manager na Contoso, responsável pela aquisição de fornecedores e pela execução do projeto. Sua meta é analisar RFPs anteriores, extrair os critérios-chave de seleção e elaborar uma nova RFP para uma iniciativa futura.

## Configuração da demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **NOTA:** pode levar até 10 minutos para que esses arquivos sejam sincronizados em seu OneDrive após o download. Para evitar atrasos durante a demonstração, certifique-se de que esses arquivos tenham sido baixados e estejam disponíveis em seu OneDrive com bastante antecedência. Se os arquivos não estiverem disponíveis, abra os documentos e copie os links dos arquivos compartilhados para usá-los na demonstração.

## Demonstrações

### Copilot no Word

Vamos começar fazendo algumas perguntas ao Copilot no Word sobre um documento de Solicitação de Proposta (RFP).

1. Abra o Word (em seu navegador ou aplicativo da área de trabalho).
1
1. Abra o seguinte documento: [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. Selecione o ícone Copilot na faixa de opções do Word para abrir o painel de bate-papo.

    ![captura de tela mostrando a guia Modo de trabalho.](../Demos/Media/copilot-ribbon-word.png)

1. No painel Bate-papo, selecione ou insira o prompt:

   ```text
   Summarize this document
   ```

1. Em seguida, insira o seguinte prompt:

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. Em seguida, peça ao Copilot para criar um modelo de RFP inserindo:

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **NOTA:** Não há necessidade de copiar o conteúdo gerado, pois usaremos um documento de modelo pré-criado na demonstração a seguir. No entanto, você pode demonstrar como copiar a resposta do Copilot ou inseri-la no documento, se for relevante para o seu público.

### Copilot Chat

Agora que resumimos o documento de RFP e criamos um modelo de RFP, vamos usar o Copilot Chat para resumir os requisitos do projeto para uma nova RFP.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).  

1. Certifique-se de que o **Modo Web** esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Digite a seguinte solicitação:

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **NOTA:** Os colchetes indicam que um documento está sendo referenciado. Use o link: [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. Em seguida, peça ao Copilot para extrair os critérios de seleção do fornecedor:

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. Em seguida, peça ao Copilot para criar uma RFP com base nas diretrizes do projeto:

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **NOTA:** Os colchetes indicam que um documento está sendo referenciado.

1. **Copie a RFP gerada** para sua área de transferência para uso na próxima demonstração.

1. Opcionalmente, peça ao Copilot para exportar a RFP gerada para um documento do Word.

### Copilot no Outlook

Por fim, use o Copilot no Outlook para redigir um e-mail para fornecedores em potencial resumindo o documento da RFP.

1. Abra o Outlook (no navegador ou no aplicativo da área de trabalho).

1. Selecione **Novo e-mail**.

1. Selecione ** Copilot** na faixa de opções. No menu suspenso, escolha **Rascunho com Copilot**.

1. Na seção **“O que você quer que este e-mail diga?”** janela de prompt, digite:

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **NOTA:** Cole o conteúdo da RFP que você copiou da demonstração anterior.

1. Depois que o rascunho for gerado, você poderá usar o recurso **Ajustar** para modificar o tom, o comprimento ou o nível de formalidade.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
