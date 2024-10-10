Exercício - Abstração

Siga os passos:

1- Criar uma superclasse chama ProvaUniversidade contendo um construtor que receba 2 notas: AV1 e AV2;
2-Criar um método na superclasse chamado calcularMedia que calculará a média final do aluno na universidade;
3- Criar duas subclasses chamadas ProvaUCB e ProvaFafifo que herdarão a superclasse ProvaUniversidade;
4- Criar um método em cada subclasse chamado aprovado que retorna um valor booleano (true ou false) para informar se o aluno foi aprovado ou não nauniversidade;
5- Na UCB o aluno será aprovado se possuir média aritmética igual ou superior a 7, e na Fafifo o aluno será aprovado se possuir média aritmética superior ou igual a 6;
6- Dentro do método aprovado de cada subclasse deverá ser chamado o método da superclasse chamado calcularMedia, para calcular a média do aluno e retornar se o aluno foi aprovado ou não;
7- Criar uma classe chamada Teste que conterá apenas o método main para testar as classes criadas anteriormente;
8- Neste método deve-se criar um objeto do tipo ProvaUCB e um objeto do tipo ProvaFafifo, e para cada objeto deve-se passar as notas da AV1 e da AV2 do aluno;
9- Chamar o método aprovado para cada objeto criado e informar na tela se o aluno foi aprovado ou não em cada instituição.
