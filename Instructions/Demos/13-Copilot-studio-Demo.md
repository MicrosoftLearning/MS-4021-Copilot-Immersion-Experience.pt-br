---
demo:
  title: Criar um agente com o Copilot Studio
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# Criar e publicar um agente usando o Copilot Chat

Esta demonstração explica como criar um assistente virtual usando o Copilot Studio por meio do Copilot Chat e publicá-lo no Microsoft 365 Copilot.

## Configuração da demonstração

Para concluir essas demonstrações, você precisará baixar os seguintes arquivos:

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

> **TIP:** antes de entregar a demonstração, você pode criar um site do SharePoint em seu ambiente de demonstração para armazenar todos os arquivos para facilitar o acesso. Como alternativa, você pode armazenar os arquivos localmente e fazer referência direta a eles em seus prompts usando **/**.

## Pontos de discussão

O Copilot Studio nos permite criar copilotos personalizados, adaptados a projetos, departamentos ou bases de dados de conhecimento específicos. Podemos dar a eles uma personalidade, definir seus limites e inserir documentos específicos para garantir respostas embasadas e de alta qualidade.

Nesta demonstração, criaremos um assistente virtual para o projeto de entrega por drone ReleCloud. O assistente saberá tudo o que carregamos e ajudará a responder às perguntas da equipe, poupando tempo e melhorando aumentando produtividade.

## Etapas de demonstração

### Etapa 1 – Navegar até o Copilot Studio

1. Vá para [https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat) e selecione **Criar agente** no trilho direito.

    ![Captura de tela mostrando a criação de um link de agente.](../Prompts/media/create-agent.png)

1. Entre usando as suas credenciais.

### Etapa 2 – Definir seu agente

1. Adicione a seguinte descrição quando solicitado:

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![Captura de tela mostrando o recurso Descrever.](../Prompts/Media/create-agent-through-describe.png)

1. Dê um nome ao assistente:

    ```text
    Drone Delivery Assistant
    ```

1. Se solicitado a confirmar:

    ```text
    Yes, thank you
    ```

1. Se solicitado sobre o que evitar ou enfatizar:

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

1. Se solicitado um tom de voz:

    ```text
    Friendly and professional
    ```

> **IMPORTANTE:**  dependendo do ambiente, talvez não seja solicitado que você forneça todas essas opções. Se não for solicitado, você poderá adicionar essas informações usando a guia **Configurar** no Copilot Studio.

### Etapa 3 – Configurar o agente

1. Clique em **Configurar** para abrir o editor do agente.
1. Examine e, opcionalmente, atualize a seção **Instruções**:

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

1. Role para baixo até a seção **Conhecimento** e clique no balão de texto **Pesquisa por nome ou inserir uma URL**. Selecione **Arquivos** e adicione os seguintes documentos à base de dados de conhecimento do agente:

    - **Delivery Drone Press Release.docx**
    - **Delivery Drone Troubleshooting.docx**
    - **Delivery Drone SOP.docx**
    - **Upselling Opportunities.docx**
    - **Delivery Drone FAQ.docx**

        ![Captura de tela mostrando fontes de conhecimento.](../Prompts/Media/knowledge-sources.png)

### Etapa 4 – Testar seu agente

No painel de teste à direita, tente fazer algumas das seguintes perguntas:

- `Tell me about the ReleCloud Delivery Drone.`
- `How do I fix the drone error code D-101?`
- `What are the upsell opportunities for ReleCloud?`
- `What’s the duration of Phase 1 of the delivery drone project?`

> **IMPORTANTE:**   pode levar algum tempo para que o agente processe os documentos e forneça respostas precisas. Se você receber uma mensagem de erro, espere alguns minutos e tente novamente.

> **TIP:** você também poderá testar por meio do Microsoft Teams quando o agente estiver ativo.

### Etapa 5 – Publicar e compartilhar

1. Clique em **Criar** para publicar o agente.
1. Selecione **Alterar configurações de compartilhamento** e escolha **Qualquer pessoa na organização**.
1. Copie o link de compartilhamento e cole-o em um chat do Teams para facilitar o acesso.

Quando estiver ativo, você poderá interagir com o agente no chat do Teams ou por meio do @mentions.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
