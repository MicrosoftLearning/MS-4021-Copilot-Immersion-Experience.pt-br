---
demo:
  title: Demonstração de TI
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração de TI

**Cenário**:  

Como gerente de infraestrutura de TI, você está planejando instalar um novo produto de segurança de rede na sua rede corporativa.

## Configuração da demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **NOTA:** pode levar até 10 minutos para que esses arquivos sejam sincronizados em seu OneDrive após o download. Para evitar atrasos durante a demonstração, certifique-se de que esses arquivos tenham sido baixados e estejam disponíveis em seu OneDrive com bastante antecedência. Se os arquivos não estiverem disponíveis, abra os documentos e copie os links dos arquivos compartilhados para usá-los na demonstração.

## Demonstrações

### Copilot Chat

Vamos começar pedindo ao Copilot para criar um plano de implementação do projeto.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).

1. Certifique-se de que o modo Web esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Na janela de prompt, digite o seguinte:

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **NOTA:** Os prompts baseados em funções ajudam o Copilot a entender as responsabilidades e o contexto do usuário, melhorando a relevância e a especificidade da saída.

1. Agora, vamos refinar o plano do projeto pedindo ao Copilot para adicionar novas seções ao plano do projeto:

    Digite o seguinte prompt:

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Por fim, faça com que o Copilot gere o plano de projeto proposto em um documento do Word:

    Digite o seguinte prompt:

    ```text
    Please export the project plan to a Word document.
    ```

1. Selecione o link que o Copilot fornece ao arquivo recém-criado para baixá-lo na pasta Downloads. Mova o arquivo para sua pasta do OneDrive e abra-o. Copie o URL compartilhado do documento (habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot no Word

Agora pediremos ao Copilot que expanda essas estratégias e elabore propostas sobre como implementá-las.

1. Abra o Word (em seu navegador ou aplicativo da área de trabalho).

1. Na caixa de prompt **O que você deseja que o Copilot esboce?** digite o seguinte:

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **NOTA:** Os colchetes indicam que um documento está sendo referenciado.
    > 1. Especificação do Produto CipherGuard.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Plano de Implementação do Projeto.docx = Use o link copiado na demonstração anterior.
    > Ao fazer referência a um documento, você pode colar o link diretamente ou fazer referência ao nome do arquivo, se ele estiver disponível em seu OneDrive.

1. Selecione **Manter** ou, se o tempo permitir, demonstre como ajustar o documento usando o Copilot.

1. Quando terminar, salve o documento como **Contoso_Project_Plan.docx** e copie o URL compartilhado (habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot no PowerPoint

Agora usaremos o Copilot para gerar uma apresentação em PowerPoint com base na nova proposta de implementação do produto CipherGuard da Contoso.

1. Inicie o Microsoft PowerPoint a partir do seu navegador [PowerPoint.new](https://PowerPoint.new) ou use o aplicativo da área de trabalho.

1. Abra uma nova apresentação em branco.

1. No painel do Copilot, selecione o prompt "Criar apresentação a partir de arquivo".

1. Cole o link compartilhado para o documento **Contoso_Project_Plan.docx** e selecione **Enviar**.

    O prompt completo deve ter a seguinte aparência:

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. O Copilot começa a gerar slides com base no plano do projeto, fornecendo uma estrutura de tópicos juntamente com recursos como notas do orador, imagens, layouts de slides e um rótulo de Confidencialidade geral.

    > **NOTA:** A geração de slides pode levar até dois minutos, dependendo da complexidade do documento e do número de slides.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
