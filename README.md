1. Defina classe abstrata e apresente situações em que a mesma pode ser útil. 
Classes abstratas é responsável por "moldar" as outras classes, ou seja ela é a "classe mãe" e as "classes filhas" vão ser moldadas através dela. É importante porque ela tem uma "base" para outras e vão herdam propriedades da "classe mãe". 

2. Defina herança e apresente situações em que a mesma pode ser útil. 
A herança são características que serão (herdadas) da mãe para com sua filha, ou seja são atributos e métodos, que serão moldados para as futuras subclasses, pois servirá com um molde para as classes filhas exemplo: uma classe mãe: (nome, sobrenome) classe filha:(nome= José, sobrenome= Roseno). A importância da herança é que se torna mais organizado, simples, extensibilidade e apresenta polimorfismo.

(OBS: POLIMORFISMO: várias formas de fazer uma coisa);

3. Defina subclasse e superclasse através de exemplos. 
superclasse: classe mãe;
subclasse: classe filha:
superclasse é a classe responsável por moldar as subclasses. 

4. Como acessar os atributos de uma classe e da sua superclasse? 

5. É possível herdar apenas alguns atributos ou métodos de uma superclasse quando uma subclasse a estende? Justifique. 

6. Cite particularidades das classes abstratas. 

7. Uma classe que estende uma classe abstrata pode deixar de implementar um dos seus métodos abstratos? 

8. Qual é a relação existente entre as classes definidas pelo usuário com a classe Object? 

9. Explique os métodos da classe Object, dê exemplos de uso. 

10. Defina sobrescrita e sobrecarga de métodos.

11. Crie uma interface chamada Desenho com o método public void desenhar(). Crie as seguintes classes concretas: Retângulo, Círculo, Quadrado e Pessoa. Todas as classes devem implementar a interface Desenho.
	Crie uma classe chamada CadastroDeDesenhos com um atributo chamado desenhos e os métodos para adicionarDesenho e desenharTodos.
Crie uma classe Principal para realizar as seguintes tarefas:
		Instanciar um objeto da classe CadastroDeDesenhos;
Instanciar um objeto de cada classe concreta específica;
Adicionar os desenhos ao cadastro de desenhos;
Chamar o método desenharTodos;

Depois, explique onde está acontecendo o polimorfismo no código criado.
