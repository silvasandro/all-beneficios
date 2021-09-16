<img src="https://user-images.githubusercontent.com/49214236/133658727-a471666f-4b00-48cb-b010-33953ff6a55a.png">

<!-- # All-Benefícios -->

<h1 align="center">Projeto Gerenciamento </br> de Cartões de Beneficio </h1>

 ## Grupo all-Benefícios
 
 <!--ts-->
   * Rafael - https://github.com/CasteloRafael
   * Luisa Menezes - https://github.com/LuisaMenezesDeMattos
   * Max
   * Silvio
   * José - @https://github.com/zeth-I
   * Sandro Silva - @https://github.com/silvasandro
<!--te-->

<h4 align="center"> 
	🚧  Java 🚀 Em construção...  🚧
</h4>


## Descrição do Projeto
<p align="left">
Escrever um programa em Java que seja capaz de gerenciar vários cartões de benefício. </br> Para essa versão, os cartões gerenciados serão:
</p>
 
 <!--ts-->
   * Vale Alimentação
   * Vale Refeição
   * Vale combustível
<!--te-->

<p align="left">
Todos os cartões têm atributos e comportamentos muito parecidos, que são:
</p>



<!--ts-->
  
   * [Saldo](#Saldo)
      * O valor que o cartão tem naquele momento
      
      
   * [Transações](#Transações)
      * Uma lista que registra os detalhes de cada transação de compra.
           
      
   * [Sistema anti-fraude](#Sistema-anti-fraude)
      * Não devemos passar duas compras do mesmo valor no mesmo estabelecimento em um período de 30 segundos (Período curto para facilitar os testes).
	
Não devemos passar três compras no mesmo cartão dentro do mesmo minuto.

 * [Saldo](#Saldo)
      * O valor que o cartão tem naquele momento
      

 * [Senha](#Senha)
      * Todo cartão deve ter sua senha de uso.


 * [Nome do beneficiário](#Nome-do-beneficiário)
      * O valor que o cartão tem naquele momento


 * [Validade](#Validade)
      * O valor que o cartão tem naquele momento


 * [Negar compra](#Negar-compra)
      * Por falta de saldo
      * Pelo sistema anti-fraude
      * Pela data de validade


 * [Extrato do cartão](#)
      * O valor que o cartão tem naquele momento


 * [Mostrar saldo atual](#)
      * O valor que o cartão tem naquele momento


 * [Adicionar nova transação](#)
      * O valor que o cartão tem naquele momento


## Uma transação deve conter os seguintes dados:
 * Valor
 * Data e hora
 * Localização
 * Estabelecimento



## Um estabelecimento deve conter os seguintes dados:

 * Nome
 * Identificador (Pode ser um número sequencial)
 * Tipo


### Nosso programa deverá gerenciar cartões de mais de um beneficiário, </br> ou seja, ao iniciar o programa, devemos cadastrar um beneficiário,</br> seus três cartões com senha, inicializar cada cartão com um valor fictício entre 200 e 1000 e uma validade para cada cartão, que inclusive a data pode ser ontem, para demonstrar que se o cartão estiver fora do prazo de validade, a compra irá ser negada. Ao acabar o cadastro do beneficiário e dos seus cartões, o sistema poderá repetir o ciclo ou entrar no modo de gerenciamento de cada cartão, onde os métodos do cartão poderão ser acessados e adicionar novas transações.

<!--te-->




