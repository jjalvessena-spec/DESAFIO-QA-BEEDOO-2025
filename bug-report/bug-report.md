
# Relatório de Bugs

Este documento contém os bugs identificados durante a execução dos testes
funcionais e exploratórios da aplicação avaliada.

---

## Metodologia Utilizada

Os bugs foram documentados com base em uma adaptação do padrão IEEE 829,
com abordagem de testes ágeis, priorizando clareza, rastreabilidade e fácil
reprodução pelos times de desenvolvimento e produto.

---

## Lista de Bugs

### BUG-001 – Exemplo de bug (modelo)

**Descrição:**  
Erro ao realizar ação X com dados inválidos.

**Ambiente:**  
- Navegador: Google Chrome  
- Sistema Operacional: Windows  
- Ambiente: Homologação  

**Severidade:** Alta  
**Prioridade:** Alta  

**Pré-condição:**  
Usuário acessou a aplicação.

**Passos para reprodução:**  
1. Acessar a página X  
2. Preencher o campo Y com valor inválido  
3. Clicar em enviar  

**Resultado esperado:**  
O sistema deve exibir mensagem de erro.

**Resultado atual:**  
A ação é concluída sem validação.

**Evidências:**  
Link do Google Drive (prints ou vídeo)

**Observações:**  
Validação ausente no front-end e back-end.
