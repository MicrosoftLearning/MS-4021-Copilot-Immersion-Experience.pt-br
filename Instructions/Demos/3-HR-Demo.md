---
demo:
  title: Demonstração de RH
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração de RH

**Cenário**:  

Simplificar o processo de contratação de uma equipe de Designers de UX, criando uma descrição de cargo customizada, selecionando candidatos com base em seus currículos e elaborando uma estratégia de contratação para alinhar a equipe

## Configuração da demonstração

Os documentos de amostra podem ser encontrados no repositório MS-4021 GitHub [aqui](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

Os arquivos específicos necessários para esta demonstração são:

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **NOTA:** pode levar até 10 minutos para que esses arquivos sejam sincronizados em seu OneDrive após o download. Para evitar atrasos durante a demonstração, certifique-se de que esses arquivos tenham sido baixados e estejam disponíveis em seu OneDrive com bastante antecedência. Se os arquivos não estiverem disponíveis, abra os documentos e copie os links dos arquivos compartilhados para usá-los na demonstração.

## Demonstrações

### Copilot no Word

Vamos iniciar solicitando ao Copilot no Word que gere uma descrição do trabalho.

1. Abra o Word (em seu navegador ou aplicativo da área de trabalho).

1. Na caixa de prompt **“Descreva o que você gostaria de escrever”**, digite o seguinte:

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **OBSERVAÇÃO:** Anexe o arquivo Design_Team_Responsibilities.docx ou cole o link compartilhado diretamente no prompt para garantir que o Copilot tenha acesso ao conteúdo relevante.

1. Depois de revisar e finalizar a descrição do cargo, salve o documento como **GDI_Job_Description.docx** e copie o URL compartilhado para usar na próxima etapa. (Habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Em seguida, usaremos o Copilot Chat para comparar os currículos que recebemos com a descrição do cargo e identificar os melhores candidatos.

1. Abra um navegador e navegue até [M365copilot.com](https://m365copilot.com/).

1. Certifique-se de que o Modo de Trabalho esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/work-mode.png)

1. Na janela de prompt, digite o seguinte:

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **OBSERVAÇÃO:** Anexe os currículos ou faça seu upload para a janela de prompt. Como alternativa, faça referência a cada arquivo usando os links compartilhados ou nomes de arquivo em seu OneDrive.

1. Opcionalmente, você pode pedir ao Copilot Chat para exportar sua resposta para um documento do Word para destacar esse recurso.

### Copilot no Outlook

Por fim, use o Copilot no Outlook para redigir um e-mail para a equipe de contratação sobre os melhores candidatos.

1. Abra o Outlook (no navegador ou no aplicativo da área de trabalho).

1. Selecione **Novo e-mail**.

1. Selecione ** Copilot** na faixa de opções. No menu suspenso, escolha **Rascunho com Copilot**.

1. Na seção **“O que você quer que este e-mail diga?”** janela de prompt, digite o seguinte:

    ```text
    Please draft an email to the hiring team to share that Nestor Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
