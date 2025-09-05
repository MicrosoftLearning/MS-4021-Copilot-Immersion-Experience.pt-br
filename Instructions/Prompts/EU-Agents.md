---
task:
  title: Experiência de imersão – agentes (usuários de negócios)
---

## Experiência de imersão – agentes (usuários de negócios)

Descubra como Microsoft 365 Copilot e o Copilot Studio podem ajudar a resolver desafios diários de produtividade criando um **agente simples baseado em recuperação**. Este exercício simplificado orientará você na identificação de um problema comum, explorando como a IA pode ajudar e criando um agente simples para testar.  

Você realizará três tarefas:

- Identificar uma dificuldade de produtividade  
- Explore como a IA pode ajudar na recuperação e na organização  
- Criar e testar um agente simples no **Copilot Studio**  

> **Observação:** Os prompts de exemplo são fornecidos para ajudar você a começar. Fique à vontade para personalizá-los conforme a sua situação.  
>
> Se você quiser ajuda para gerar ou refinar prompts, experimente o <a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">agente do Treinador de prompts</a>, que pode sugerir, melhorar e avaliar prompts para obter melhores resultados com o Copilot.

### Tarefa 1: Identificar um desafio de produtividade  

Pense em um problema comum no seu trabalho diário, algo que o atrasa ou dificulta a localização ou a organização de informações. Você pode refletir individualmente ou usar o **Copilot Chat** como parceiro para ajudar a gerar ideias e detectar dificuldades comuns.

Exemplos:

- Localizar a versão mais recente de um documento  
- Coletar atualizações de vários emails ou chats  
- Lembrar detalhes de projetos ou reuniões anteriores  

**Etapas:**  

- Abra uma nova guia do navegador e vá para [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat). 

- A guia **Modo de trabalho** deve estar selecionada no **Copilot Chat**.  

   ![Captura de tela mostrando a guia Modo de trabalho no Copilot Chat.](../Prompts/Media/work-mode.png)  

    **Exemplo de prompt:**

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### Tarefa 2: Explore as ideias de solução de IA com o Pesquisador  

Use o **Agente Pesquisador** para explorar como o Copilot ou os agentes podem ajudar com o desafio escolhido.

**Etapas:**  

- No menu do Copilot Chat, expanda **Agentes** e selecione **Pesquisador**.  

   ![Captura de tela mostrando o Pesquisador selecionado no menu do M365 Copilot.](../Prompts/Media/researcher.png)  

- Experimente um prompt de exemplo como este:  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > **TIP:** Mantenha o foco em casos de uso práticos e diários, como descobrir rapidamente um documento ou extrair atualizações de várias fontes.
  
    > **Observação:** o pesquisador pode levar 5–10 minutos para concluir, dependendo da sua solicitação. Suas respostas são altamente detalhadas, portanto, durante a operação, tente executar o mesmo prompt no Copilot Chat. Comparar os dois resultados é uma ótima maneira de ver como cada ferramenta aborda a tarefa.
    
### Tarefa 3: Compilar e testar seu agente  

Agora, crie um agente de recuperação simples no **Copilot Studio** para resolver seu desafio.  

**Etapas:**  

1. No menu do **Copilot Chat**, selecione **Criar agente**.

   ![Captura de tela mostrando a criação de um link de agente.](../Prompts/Media/create-agent.png)  

1. Na guia **Descrever**, trace a função do agente. Por exemplo:  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![Captura de tela mostrando como descrever o agente com o prompt de exemplo preenchido.](../Prompts/Media/create-agent-through-describe.png)  

1. Selecione a guia **Configurar** e adicione uma fonte de conhecimento (por exemplo, **Meus Emails** ou **Minhas reuniões e chats do Teams**).

    ![Captura de tela mostrando a seção de fontes de conhecimento no construtor de agentes.](../Prompts/Media/knowledge-sources.png)

1. Teste seu agente usando o painel **Teste** e refine conforme necessário.  
1. Selecione **Criar** para publicar seu agente e começar a usá-lo.  

> **TIP:** Até mesmo um agente muito simples, como um que ajuda você a encontrar arquivos de projeto recentes, pode mostrar o poder da recuperação em seu trabalho diário.
