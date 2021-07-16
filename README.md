# Trabalho-Individual-Alex
 
Alex sobre Teoria e Prática<Br>
Havan Labs 2021<Br>

Trabalho Individual 1 -Teoria<Br>
  POO -Programação Orientada a Objetos (POO) é um tipo de programação onde uma ou várias Classes tem características que fazem elas serem um objeto, cada uma delas define a maneira de agir do objeto escolhido, podendo eles terem atributos, você pode interagir diretamente com o Objeto, ele pode ter métodos, atributos entre outros.
  Classes elas contém um Conjunto de Métodos que podem ser eles similares para determinadas funções como uma classe Mensagem onde dentro dela podem ter vários métodos para cada tipo específico de mensagem que o programa quer exibir depois podendo executar dentro da classe só o método que melhor encaixar em outra área do programa. Ela pode guardar atributos ou comportamentos.
  Método é uma função onde você pode executar uma determinada ação dentro da mesma que pode ser usada de outra parte do projeto ou não, receber informações ou não e também   retornar informações ou não da mesma.
  Herança é a derivação de uma classe mãe para filha no caso outra classe, onde a classe filha vai herdar tudo que contém na classe mãe, com Herança podemos fazer essa       reutilização de alguns dados que se repetem em determinadas partes do código. Assim você pode aproveitar as características que são herdadas a partir da classe mãe.
       https://github.com/alexjuniorkuss/Trabalho-Individual-Alex.git
  na imagem acima mostra a classe mãe de onde vai ser herdado o dado id
  ![image](https://user-images.githubusercontent.com/84691695/125984460-38d9a4f1-95b5-4362-add3-f87ebad133e6.png)
  na imagem acima tem uma classe de cliente onde vai utilizar o id da classe mãe para isso ao lado do nome da class coloca : Models para herdar o dado da classe mãe
  ![image](https://user-images.githubusercontent.com/84691695/125984664-29441328-de23-4345-893d-5f91260119b7.png)
    Na imagem acima na tela principal do programa eu crio um obj do cliente e quando eu vou chama-lo no item 2 eu ja posso ter todos os dados tanto id de models quanto os dados do   cliente como nome, sobrenome e idade.
  Composição é compor um conjunto de dados atribuindo uma obrigatoriedade de outro conjunto, por exemplo:
    Um produto em um cadastro ele vai ter seu ID, NOME, DESCRICAO, VALOR e para compor esse conjunto de informações obrigatoriamente esse produto precisa ter uma Categoria, onde a categoria é um conjunto de dados a parte. Então na composição você puxa uma uma cópia da categoria que precisa compor este produto para o mesmo pertencer a uma           Categoria.
    Dentro do projeto podemos ter exemplos que utilizem parâmetros e argumentos por exemplo:
 Existe uma tela de cadastro onde pede para o usuário digitar um dado e se pretende mandar esse dado para um método de validação, então manda-se um ARGUMENTO para o método validar, dentro do método validação vai entrar um parâmetro para retorno do tratamento da validação. Os dois precisam ser do mesmo tipo de dados ou eu defino no               argumento quais parâmetros vão receber cada dado podendo ser por ordem lógica ou por referência do parâmetro
  
      -Argumento: Envia uma string, int ou outro tipo de dado para meu parâmetro
      -Parâmetro: Recebe o argumento enviado.

 Sobrecarga de método é quando usa-se o mesmo método porem com parâmetros diferentes onde na chamada o que pode diferenciar é o argumento mandado. Na imagem abaixo quando é chamado a soma(); sem argumento ele chama o método de soma sem parâmetros e executaria as instruções que daria pra mesma ali, ja no caso se eu passar um argumento ao chamar a soma(5); já chama o 2 método soma o que contém um parâmetro e também executaria os dados que estariam dentro dele.
  
  ![image](https://user-images.githubusercontent.com/84691695/125988239-9539a23e-e822-46ca-a56e-9a6c742482fb.png)
      
O Parâmetro opcional contém alguns dados que podem ser padrões caso o usuário não passe nenhum argumento, caso o usuário passar algum dado para ele substitui, caso               não passar nada fica o parâmetro definido como padrão. Já os Parâmetros nomeados pode ser passado através de nomes que vem das variaveis do método onde cada dado vai ser passado sem a necessidade de estar em ordem para mandar os dados para o método. Um ponto excencial são os argumentos opcionais devem ser deixados na ordem dentro do método por último na sequência pois assim quando for ser passado os argumentos facilita para não causar inconsistência.
  

  
