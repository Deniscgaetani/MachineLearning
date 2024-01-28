1.  Entre no [portal do Azure](https://portal.azure.com) usando `https://portal.azure.com`suas credenciais da Microsoft.
    
2.  Selecione **\+ Criar um recurso** , pesquise _Machine Learning_ e crie um novo recurso **do Azure Machine Learning com as seguintes configurações:**
    *   **Assinatura** : _sua assinatura do Azure_ .
    *   **Grupo de recursos** : _Crie ou selecione um grupo de recursos_ .
    *   **Nome** : _Insira um nome exclusivo para seu espaço de trabalho_ .
    *   **Região** : _Selecione a região geográfica mais próxima_ .
    *   **Conta de armazenamento** : _observe a nova conta de armazenamento padrão que será criada para seu espaço de trabalho_ .
    *   **Cofre de chaves** : _Observe o novo cofre de chaves padrão que será criado para seu espaço de trabalho_ .
    *   **Insights de aplicativo** : _observe o novo recurso padrão de insights de aplicativo que será criado para seu espaço de trabalho_ .
    *   **Registro de contêiner** : Nenhum ( _um será criado automaticamente na primeira vez que você implantar um modelo em um contêiner_ ).
3.  Selecione **Revisar + criar** e selecione **Criar** . Aguarde a criação do seu espaço de trabalho (pode demorar alguns minutos) e, em seguida, vá para o recurso implantado.
    
4.  Selecione **Launch Studio** (ou abra uma nova guia do navegador e navegue até [https://ml.azure.com](https://ml.azure.com?azure-portal=true) e entre no Azure Machine Learning Studio usando sua conta da Microsoft). Feche todas as mensagens exibidas.
    
5.  No estúdio Azure Machine Learning, você deverá ver seu espaço de trabalho recém-criado. Caso contrário, selecione **Todos os espaços de trabalho** no menu à esquerda e selecione o espaço de trabalho que você acabou de criar.

6.  <ol>
  <li>
    <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">No </font></font><a href="https://ml.azure.com?azure-portal=true"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure Machine Learning Studio</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , veja a </font><font style="vertical-align: inherit;">página </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Automated ML (em </font></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Authoring</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ).</font></font></p>
  </li>
  <li>
    <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Crie um novo trabalho de ML automatizado com as seguintes configurações, usando </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Next</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> conforme necessário para avançar pela interface do usuário:</font></font></p>
  <li>
    <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Envie o trabalho de treinamento. </font><font style="vertical-align: inherit;">Ele inicia automaticamente.</font></font></p>
  </li>
  <li>
    <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Espere o trabalho terminar. </font><font style="vertical-align: inherit;">Pode demorar um pouco – agora pode ser um bom momento para uma pausa para o café!</font></font></p>
  </li>
</ol>
