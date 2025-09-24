---
demo:
  title: Demonstração jurídica
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração jurídica

**Cenário**:  

Você é um consultor jurídico da Contoso, responsável por avaliar se o Software de Triagem de Currículos de IA da empresa está em conformidade com a Lei de IA da UE. Seu objetivo é pesquisar riscos legais, redigir um resumo executivo e comunicar recomendações à liderança.

## Configuração da demonstração

Não há documentos de amostra necessários para esta demonstração.

## Demonstrações

### Copilot Chat

Vamos começar pesquisando a Lei de Inteligência Artificial da UE e seu potencial impacto na ferramenta de contratação de IA da Contoso.

1. Abra um navegador e navegue até [M365Copilot.com](https://m365Copilot.com/).

1. Certifique-se de que o **Modo Web** esteja selecionado.

    ![captura de tela mostrando a guia do modo web.](../Prompts/Media/web-mode.png)

1. Na janela de prompt, digite o seguinte:

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Analise a resposta do Copilot e faça anotações sobre os riscos legais relevantes e os requisitos de conformidade.

1. Agora faremos ao Copilot uma série de perguntas de acompanhamento para coletar mais informações:

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. Agora pergunte ao Copilot para resumir todas as informações até o momento:

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. Selecione o hiperlink que o Copilot fornece para o novo documento do Word para abri-lo.

1. Depois de aberto, selecione **Habilitar edição** e, em seguida, ative "Salvamento automático". Selecione sua conta do OneDrive quando solicitado.

1. Copie o URL compartilhado para usar na próxima etapa. (Habilite o Salvamento Automático e selecione sua conta do OneDrive, se solicitado).

    ![Compartilhar link](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot no Word

Agora, vamos redigir um resumo executivo descrevendo os riscos jurídicos e as recomendações para a liderança da Contoso.

1. Abra uma nova instância do Word, no navegador ou no aplicativo da área de trabalho.

1. Na caixa de prompt **“Descreva o que você gostaria de escrever”**, digite o seguinte:

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **NOTA:** Anexe o documento ou cole o link compartilhado diretamente no prompt para garantir que o Copilot possa acessar o conteúdo relevante.

1. Revise a saída do Copilot. Antes de selecionar **Manter**, refine a resposta perguntando ao Copilot:

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. Outros refinamentos opcionais:

    - Pergunte ao Copilot para reformular as seções adotando um tom mais profissional.
    - Solicite uma versão mais curta e concisa se o resumo for muito longo.
    - Expanda com seções adicionais.

1. Depois de revisar e finalizar o documento, **Copie o Resumo Executivo gerado** para sua área de transferência para usá-lo na próxima demonstração.

### Copilot no Outlook

Por fim, redigiremos um e-mail para a liderança da Contoso resumindo nossas descobertas e as próximas etapas.

1. Abra o Outlook (no navegador ou no aplicativo da área de trabalho).

1. Selecione **Novo e-mail**.

1. Selecione ** Copilot** na faixa de opções. No menu suspenso, escolha **Rascunho com Copilot**.

1. Na seção **“O que você quer que este e-mail diga?”** janela de prompt, digite:

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **NOTA:** Cole o conteúdo do Resumo Executivo que você copiou da demonstração anterior.

1. Depois que o rascunho for gerado, você poderá usar o recurso **Ajustar** para modificar o tom, o comprimento ou o nível de formalidade.

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
