# Relatório de Ocorrências de Testes Manuais

#### **Informações do Teste**
- **Projeto:** [Nome do Projeto]
- **Data do Teste:** [Data do teste]
- **Testador:** [Nome do Testador]
- **Versão do Sistema:** [Versão do sistema/teste]
- **Objetivo do Teste:** [Descrição do objetivo geral do teste]

---

### **Instruções para Preenchimento:**
1. **ID da Ocorrência**: Um identificador único para cada ocorrência.
2. **Descrição da Ocorrência**: Descrição detalhada do erro ou problema encontrado.
3. **Severidade**: Classificação do impacto do problema (ex: Crítico, Alto, Médio, Baixo).
4. **Passos para Reproduzir**: Passos detalhados para reproduzir a falha.
5. **Resultado Esperado**: Descrição do que o comportamento ou resultado esperado seria.
6. **Resultado Obtido**: Descrição do comportamento observado (erro, falha, comportamento inesperado).
7. **Status da Ocorrência**: Indica se a ocorrência foi resolvida, pendente ou em andamento.
8. **Evidências**: Inclua capturas de tela, logs, vídeos ou outros tipos de evidências que documentem a falha.
9. **Data de Resolução (se aplicável)**: Se o problema foi resolvido, coloque a data da correção.

---

### **Resumo das Ocorrências**

| **ID da Ocorrência** | **Descrição da Ocorrência**                                    | **Severidade** | **Passos para Reproduzir**                                                                 | **Resultado Esperado**                                   | **Resultado Obtido**                                     | **Status**      | **Evidências**       | **Data de Resolução** |
|----------------------|-----------------------------------------------------------------|----------------|-------------------------------------------------------------------------------------------|---------------------------------------------------------|---------------------------------------------------------|-----------------|----------------------|-----------------------|
| **OC001**            | Erro de login com usuário válido.                              | Crítico        | 1. Acesse a página de login. <br> 2. Insira credenciais válidas. <br> 3. Clique em "Entrar". | O usuário deve ser redirecionado à página inicial.       | O usuário foi redirecionado para uma página de erro.    | **Pendente**    | [Captura de Tela 1]   | -                     |
| **OC002**            | Formulário de cadastro não valida campos obrigatórios.         | Alto           | 1. Acesse a página de cadastro. <br> 2. Deixe campos obrigatórios em branco. <br> 3. Clique em "Cadastrar". | O sistema deve exibir mensagens de erro para campos obrigatórios não preenchidos. | Não houve validação, o formulário foi enviado em branco. | **Pendente**    | [Captura de Tela 2]   | -                     |
| **OC003**            | Resposta da API com erro 500 ao enviar dados inválidos.       | Alto           | 1. Realize uma requisição POST para o endpoint `/submit-data`. <br> 2. Envie dados inválidos. | A API deve retornar erro 400 e uma mensagem explicativa. | A API retornou erro 500 sem mensagem explicativa.       | **Em andamento** | [Log da Requisição]   | -                     |
| **OC004**            | O botão de "Buscar" não responde quando clicado.               | Médio          | 1. Acesse a barra de pesquisa. <br> 2. Clique no botão de "Buscar" sem inserir nenhum termo. | O sistema deve exibir resultados padrão ou mensagem de erro. | O sistema não respondeu ao clique no botão.            | **Resolvido**    | [Captura de Tela 3]   | 06/03/2025            |
| **OC005**            | Página de erros não está sendo exibida corretamente.          | Baixo          | 1. Acesse uma URL inválida no sistema.                                                    | O sistema deve exibir uma página de erro amigável.      | A página de erro exibe um erro 404 padrão sem estilo.   | **Resolvido**    | [Captura de Tela 4]   | 06/03/2025            |

---

### **Evidências das Ocorrências**

- **Captura de Tela 1**: [Link ou imagem]
- **Captura de Tela 2**: [Link ou imagem]
- **Log de Requisição**: [Anexo ou link para o arquivo de log]
- **Vídeo da Ocorrência**: [Link para vídeo ou anexo]

---

### **Observações Finais:**

- **Ongoing Issues**: A ocorrência **OC003** (erro 500 na API) está em andamento, aguardando a investigação pela equipe de backend.
- **Soluções Implementadas**: As ocorrências **OC004** e **OC005** foram resolvidas com a atualização do sistema e a melhoria da validação de campos.

---

### **Conclusão**
As ocorrências documentadas acima foram analisadas e as respectivas evidências foram coletadas. As falhas de maior severidade estão sendo tratadas pela equipe de desenvolvimento, enquanto as falhas de menor impacto já foram corrigidas.

---

Esse modelo de **relatório de ocorrências** permite um acompanhamento detalhado das falhas identificadas durante os testes manuais, facilitando a comunicação entre a equipe de testes e a equipe de desenvolvimento para a correção dos problemas encontrados.