## Teste 1 — Login com dados inválidos

**Cenário:** Usuário tenta fazer login com senha incorreta na Shopee  

**Ambiente:** Navegador web (Google Chrome)  

**Passos:**
1. Acessar o site da Shopee  
2. Clicar em "Entrar"  
3. Inserir e-mail válido  
4. Inserir senha incorreta  
5. Clicar em login  

**Resultado esperado:**
O sistema deve impedir o login e exibir mensagem de erro informando que os dados estão incorretos  

**Resultado obtido:**
O sistema exibiu mensagem informando que o e-mail ou senha estão incorretos, impedindo o login  

**Status:** ✅ Aprovado

## Teste 2 — Login com campos vazios

**Cenário:** Usuário tenta fazer login sem preencher os campos  

**Passos:**
1. Acessar o site da Shopee  
2. Clicar em "Entrar"  
3. Não preencher e-mail e senha  
4. Clicar em login  

**Resultado esperado:**
O sistema deve impedir a ação de login e indicar que os campos são obrigatórios    

**Resultado obtido:**
O botão de login permanece desabilitado (cor mais clara), impedindo o envio do formulário sem preenchimento dos campos  

**Status:**
✅ Aprovado

## Teste 3 — Login com e-mail inválido

**Cenário:** Usuário tenta fazer login com formato de e-mail inválido  

**Passos:**
1. Acessar o site da Shopee  
2. Clicar em "Entrar"  
3. Inserir e-mail inválido (ex: abc)  
4. Inserir qualquer senha  
5. Observar comportamento do sistema  

**Resultado esperado:**
O sistema deve identificar o formato inválido de e-mail e impedir o login  

**Resultado obtido:**
O sistema não permite o envio do formulário com e-mail inválido, mantendo o botão de login desabilitado ou exibindo validação no campo  

**Status:** ✅ Aprovado
