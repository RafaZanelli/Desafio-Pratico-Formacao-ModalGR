# Desafio-Pratico-Formacao-ModalGR

Teste unitário!

Desafio 1

1. *Cadastro bem-sucedido com todos os campos preenchidos corretamente*
 Campos testados e funcionando corretamente

2. *Tentativa de cadastro com o campo 'Nome' vazio*
 Campo 'nome' preenchido e funcionando corretamente!

3. *Tentativa de cadastro com o campo 'CPF' vazio*
 Campo 'CPF' preenchido e funcionado corretamente!

4. *Tentativa de cadastro com o campo 'Email' vazio*
 Campo ‘Email’ preenchido e funcionado corretamente!

5. *Tentativa de cadastro com o campo 'Senha' vazio*
 Campo ‘Senha’ preenchido e funcionado corretamente!

6. *Tentativa de cadastro com o campo 'Confirmar Senha' vazio*
 Campo ‘Confirmar Senha’ preenchido e funcionando corretamente!

7. *Tentativa de cadastro com 'CPF' em formato inválido*
 Cadastro com ‘CPF’ formato valido!

8. *Tentativa de cadastro com 'Email' em formato inválido*
 Cadastro de ‘Email’ com em formato valido!

9. *Tentativa de cadastro com 'Senha' e 'Confirmar Senha' diferentes*
 Cadastro com ‘Senha’ e ‘Confirmar Senha’ funcionando corretamente!

10. *Tentativa de cadastro com 'Senha' abaixo do limite mínimo de caracteres*
 ‘Senha’ abaixo do limite mínimo detectado com sucesso!

11. *Tentativa de cadastro com 'Senha' acima do limite máximo de caracteres*
 ‘Senha’ acima do limite permitido detectado com sucesso!

12. *Tentativa de cadastro com 'Nome' contendo caracteres especiais*
 ‘Nome’ contendo caracteres especiais detectado com sucesso!

13. *Tentativa de cadastro com 'CPF' já cadastrado*
 ‘CPF’ já cadastrado detectado com sucesso!

14. *Tentativa de cadastro com 'Email' já cadastrado*
 ‘Email já cadastrado detectado com sucesso!





Desafio 2 - QA


*Passo a passo para Reproduzir o Erro! *


1. Selecione qualquer produto das opções disponíveis no site.

2. Clique no botão "Adicionar ao Carrinho".

3. Repita adicionando mais do mesmo produto ao carrinho.

4. Uma vez que o número de itens adicionados excede 4(quatro), uma mensagem de 
erro será exibida no (pop-up).

Observação:


Quando adicionamos mais de 4 (Quatro)itens do mesmo produto em nossos 
carrinhos, imediatamente mostra em pop-up com uma mensagem de “Erro” limitando 
o cliente a compra mais de 4 itens do mesmo produto.


O que deve ser permitido!


O cliente deve ter o livre acesso de compra dos produtos selecionado por ele, sendo do 
mesmo ou não, sem aparecer um pop-up de “Erro” impedindo que o cliente compre 
quantos itens ele desejar, A quantidade limite de compra dos produtos tem que ser 
exibidas do lado do produto! 


Comentário importante:


*Quando o cliente atingir o limite máximo de compra, exibir um pop-up com uma 
mensagem mais clara, e mostrando outras alternativas.

*Nosso site deve adicionar um verificador de quantidade disponíveis, para quando o 
usuário for adicionar em seu carrinho, ele já fique ciente da quantidade que ele pode
adicionar, evitando transtornos aos usuários


Resolução/Solução:


1) Retificar o modo de adição de mais de 4 itens dos mesmos produtos, sem causar 
nenhum ‘Erro'.

2) Exibir uma mensagem mais clara, indicando a quantidade máxima permitido de 
compra de cada produto na página do mesmo!

3). Adicionar uma ferramenta para verificar a quantidade disponível do produto antes 
que os usuários adicionem itens no carrinho.

Conclusão:

O Erro de adicionar mais de 4 produtos do mesmo ao carrinho, impossibilita uma 
experiência maravilhosa do usuário e limita a funcionalidade do nosso site
