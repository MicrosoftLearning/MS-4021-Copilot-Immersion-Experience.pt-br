---
demo:
  title: Demonstração de pesquisador e analista
---

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demonstração de pesquisador e analista

Esta demonstração destaca como usar o **Pesquisador** e o **Analista**, dois agentes especialistas integrados ao aplicativo Copilot.  

- O **Pesquisador** ajuda você a lidar com tarefas de pesquisa de várias etapas, combinando dados da Web com os arquivos e o conhecimento da sua empresa.  
- O **Analista** pensa como um cientista de dados hábil, capaz de executar a análise de dados avançada e a execução do Python, mesmo que você não saiba codificar.  

## Configuração da demonstração

Para concluir essas demonstrações, você precisará baixar a [Demonstração de Pesquisador e Analista –Pacote de Conteúdo](https://microsoft.sharepoint.com/:u:/r/teams/MTTCentral/Immersion%20Experience%20Source%20Control/MS-4021%20Copilot%20Immersion%20Experience/Demos/Agent%20Demo%20Sample%20Docs/Researcher%20and%20Analyst%20Demo%20-%20Content%20Pack.zip?csf=1&web=1&e=384sFW), que contém todos os arquivos e recursos necessários.  

> **TIP:** antes de entregar a demonstração, você pode criar um site do SharePoint em seu ambiente de demonstração para armazenar todos os arquivos para facilitar o acesso. Como alternativa, você pode armazenar os arquivos localmente e fazer referência direta a eles em seus prompts usando **/**.  

Para acessar estes agentes:  

- Abra o **aplicativo Copilot** em [m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Use a **navegação à esquerda** para selecionar **Pesquisador** ou **Analista**.  

> **Observação:** você precisará apontar o Pesquisador e o Analista para arquivos internos (SharePoint/OneDrive) para obter insights embasados.

---

## Pontos de discussão

- O **Pesquisador** atua como um consultor bem remunerado: ele pode criar entregas estruturadas e com boas citações combinando arquivos internos, inteligência de concorrentes e fontes da Web.  
- O **Analista** é como ter um cientista de dados disponível: ele cria modelos, executa código Python e visualiza tendências instantaneamente.  
- Ambos os agentes explicam o raciocínio de modo transparente para você validar os resultados.  
- Juntos, aceleram o trabalho estratégico, como planos de marketing, segmentação de clientes, projeções financeiras, para que você possa avançar mais rápido e com confiança.  

---

## Etapas de demonstração

### Pesquisador: criar um plano de marketing

> **IMPORTANTE:** as etapas 1 a 4 devem ser concluídas no início do treinamento (conforme indicado pelo slide 5) para que o Pesquisador tenha tempo suficiente para concluir o primeiro prompt.

1. Abra **Pesquisador** na navegação à esquerda no aplicativo Copilot.  

    ![Captura de tela mostrando o Pesquisador selecionado no menu do M365 Copilot.](../Prompts/Media/researcher.png)  

1. Digite a seguinte solicitação:

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. Anexe arquivos de referência usando `/` (apontar para o SharePoint/OneDrive):  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(Opcional)* **/Contoso - PedalPerks GTM Plan.docx**  

1. Clique em **Enviar**.  

O pesquisador vai:  

- Combinar insights de arquivos internos e da Web.  
- Estruturar um plano de marketing com recomendações sobre canais e estratégia de conteúdo.  
- Citar fontes para que você possa validar o trabalho dele.  

> **Observação:** o pesquisador mostra sua linha de raciocínio ("sequência de ideias") e pode chamar outros agentes quando necessário.  

### Analista: segmentação de clientes e modelagem financeira

1. Abra **Analista** na navegação à esquerda no aplicativo Copilot.  

    ![Captura de tela mostrando o Analista selecionado no menu do M365 Copilot.](../Prompts/Media/analyst.png)  

1. Digite a seguinte solicitação:

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Anexe o arquivo usando **+**:  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![Captura de tela mostrando a anexação de arquivos no Analista.](../Prompts/Media/Analyst-Attach-Files.png)  

1. Clique em **Enviar**.  

O analista vai:  

- Analisar o conjunto de dados.  
- Identificar segmentos de cliente de alto valor.  
- Fornecer visualizações para fazer backup de recomendações.  

### Cenários adicionais de analistas

Você pode executar estes prompts adicionais para variedade. Todos seguem o mesmo padrão: **Prompt → Anexar arquivo → Enviar → Examinar os resultados.**

- **Projeção Financeira**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    Arquivo: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **Desempenho de Vendas**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    Arquivo: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **Desempenho da Campanha**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    Arquivo: **BoulderEV ebike Internal Market Forecast.xlsx**  

## Conclusão principal

- **Pesquisador**: acelera a estratégia e o planejamento com pesquisa de alta qualidade.  
- **Analista**: fornece insights orientados por dados com análises e visualizações avançadas.  

Juntos, o Pesquisador e o Analista encurtam o caminho da **pergunta ao insight**, transformando semanas de esforço em minutos.  

[Voltar ao índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
