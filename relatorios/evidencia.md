# Relatório de Evidência de Testes Manuais

#### **Informações do Teste**
- **Projeto:** [Nome do Projeto]
- **Data do Teste:** [Data do teste]
- **Testador:** [Nome do Testador]
- **Versão do Sistema:** [Versão atual do sistema/teste]
- **Tipo de Teste:** [Ex: Teste de Funcionalidade, Teste de UI, Teste de API]
- **Objetivo do Teste:** [Descrição do objetivo geral do teste]

---

### **Instruções para Preenchimento:**
1. **Caso de Teste**: Descreva brevemente a funcionalidade ou comportamento que está sendo testado.
2. **Passos para Execução**: Detalhe as etapas para realizar o teste, incluindo dados de entrada, ações e interações com o sistema.
3. **Resultado Esperado**: Explique o que o testador espera como resultado do teste (seja um comportamento esperado, mensagem ou resposta específica).
4. **Resultado Obtido**: Descreva o que foi observado após a execução do teste.
5. **Status do Teste**: Registre se o teste foi bem-sucedido ou falhou.
6. **Evidências**: Inclua capturas de tela, logs, vídeos ou outras evidências que suportem os resultados do teste.
7. **Observações**: Inclua quaisquer comentários ou considerações importantes, como erros encontrados, comportamentos inesperados ou melhorias sugeridas.

---

### **Resumo do Teste**

| **Caso de Teste**              | **Passos para Execução**                               | **Resultado Esperado**                            | **Resultado Obtido**                            | **Status**   | **Evidências**       |
|---------------------------------|--------------------------------------------------------|--------------------------------------------------|-------------------------------------------------|--------------|----------------------|
| **Login de Usuário**            | 1. Acesse a página de login. <br> 2. Insira o usuário e senha. <br> 3. Clique em "Entrar". | O usuário é redirecionado para a página inicial do sistema. | O usuário foi redirecionado corretamente para a página inicial. | **Passou**    | [Captura de Tela 1]   |
| **Cadastro de Novo Usuário**    | 1. Acesse a página de cadastro. <br> 2. Preencha os campos obrigatórios. <br> 3. Clique em "Cadastrar". | O sistema exibe uma mensagem de sucesso e o novo usuário é criado. | A mensagem de sucesso foi exibida corretamente, e o usuário foi criado. | **Passou**    | [Captura de Tela 2]   |
| **Validação de Email (API)**    | 1. Realize uma requisição POST para o endpoint `/validate-email`. <br> 2. Envie um email válido. | A API retorna um código de status 200 e a mensagem "Email válido". | A API retornou status 200 e a mensagem correta. | **Passou**    | [Log da Requisição]   |
| **Funcionalidade de Busca**     | 1. Acesse a barra de pesquisa. <br> 2. Digite "produto X". <br> 3. Clique no botão de busca. | Os resultados da busca devem mostrar produtos relacionados ao termo "produto X". | Foram retornados produtos correspondentes à pesquisa. | **Passou**    | [Captura de Tela 3]   |
| **Erro ao Inserir Dados Inválidos (API)** | 1. Realize uma requisição POST para o endpoint `/submit-data`. <br> 2. Envie dados inválidos no corpo da requisição. | A API retorna código de erro 400 e mensagem "Dados inválidos". | A API retornou erro 400 com a mensagem "Dados inválidos". | **Passou**    | [Log da Requisição]   |

---

### **Evidências de Teste**

- **Captura de Tela 1**: [Link ou imagem]
- **Captura de Tela 2**: [Link ou imagem]
- **Log de Requisição**: [Anexo ou link para o arquivo de log]
- **Vídeo do Teste (se necessário)**: [Link para vídeo ou anexo]

---

### **Resumo de Resultados**

- **Total de Casos de Teste**: [Número de casos de teste realizados]
- **Casos de Teste Bem-Sucedidos**: [Número de casos de teste bem-sucedidos]
- **Casos de Teste com Falha**: [Número de falhas, se houver]
- **Taxa de Sucesso**: [Cálculo da taxa de sucesso, ex: 90%]
  
#### **Observações Finais**:
- [Comentários gerais sobre a execução do teste, como dificuldades encontradas, áreas de melhoria ou sugestões para o desenvolvimento.]

---

### **Conclusão**
O teste foi realizado conforme o planejado, com a maioria das funcionalidades sendo validadas com sucesso. Alguns casos de falha foram observados, conforme documentado nas evidências. Recomenda-se investigar as falhas listadas para correção antes do próximo ciclo de desenvolvimento.

---

Este modelo oferece um formato claro para documentar testes manuais e suas evidências, ajudando a manter o controle sobre os resultados e os problemas encontrados durante os testes.