### Criação de conta com domínio de e-mail incorreto

### Ambiente
- **Sistema Operacional:** Windows 10
- **Navegador/Versão:** Google Chrome Versão 153.0.8010.52

### Passos para Reproduzir
1. Acesse a página [BugBank](https://bugbank.netlify.app/)
2. Clique no botão 'Registrar'
3. Digite um e-mail cujo domínio esteja incorreto, por exemplo, seunome@gmail.**cmo**
4. Preencha o restante dos campos e clique no botão 'Cadastrar'

### Resultado Atual
- O sistema permite a criação da conta com o domínio de e-mail incorreto.

### Resultado Esperado
- O sistema deveria enviar uma mensagem de erro indicando que o campo 'e-mail' está incorreto e não permitir que o usuário crie a conta.

### Evidências
![O e-mail com erro de digitação no domínio](/Imagens/BugBank2.png)
![A mensagem de conta criada com sucesso](/Imagens/BugBank1.png)