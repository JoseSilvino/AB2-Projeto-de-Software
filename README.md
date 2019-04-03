# AB2-Projeto-de-Software
Prova da AB2 da disciplina Projeto de Software

# Padrão 1: Iterator
  .Motivação : Percorrer a hash sem precisar de um keySet e de if para verificar se o objeto não é null
  
  .Solução : Criando uma interface e uma classe com os métodos necessários para iterar uma lista.
  
  .Vantagens : Com o iterator , podemos acessar as informações da hash sem necessáriamente ver como foi todo o processo , deixando o código mais limpo.
  
  .Desvantagens : Caso outra lista precise ser tratade de forma diferente , como retirar o anterior ao atual , precisariamos de outra classe implementando a interface.
  
# Padrão 2: Strategy
   .Motivação : Permitir que o código fique mais limpo , sem muitos if e else.
   
   .Soluçao : Uma interface com os métodos necessários para usar ao inves de if e else, e classes a implementando.
   
   .Vantagem : Deixa o código mais limpo , para no caso de alguem o ver , somente ao ler o nome do método utilizado saber o que o mesmo faz , sem ter que ver todos os if e else.
   
   .Desvantagem : A necessidade de criar outras interfaces e classes para possibilitar utilizar os métodos corretos.
   
# Padrão 3: Singleton
  .Motivação : Não precisar instanciar outras vezes algo que não se altera.
  
  .Solução : Impedir que as classes que não se alteram de serem instanciadas novamente.
  
  .Vantagem : Menos gasto da memória.
  
  .Desvantagem : 
# Classes alteradas por
  .Singleton : Login,Criar_Usuário
   
  .Strategy : EditGUI 
   
   .Criadas : StrategyInterface,Nome,Password,Civil,Nick.
   
  .Iterator :  Logado.
  
   .Criadas : IteratorInterface,Iterator
