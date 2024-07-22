Projeto Desenvolvido na plataforma da Alura!



Neste treinamento, aprendemos mais sobre o Visual Studio Community, a IDE que usamos ao longo de toda essa formação de C# e orientação a objetos. Estudamos também como utilizar interfaces disponibilizadas pela plataforma .NET.
Na classe ContaCorrente, por exemplo, utilizamos a interface IComparable que permite que uma coleção de objetos possa ser ordenada ou classificada.

Nesse projeto, pudemos compreender o que são coleções de objetos, o que são arrays e as similaridades entre esses dois conceitos.
Por exemplo, na classe ByteBankAtendimento, definimos _listaDeContas do tipo List<> (uma classe da biblioteca .NET) e, usando o Generics, determinamos que essa lista receberia somente objetos do tipo ContaCorrente.
Dessa forma, entendemos que o Generics é uma forma de parametrizarmos uma classe ou um método.
Além disso, percebemos que o uso de classes como List<> é muito vantajoso, pois já têm disponibilizados uma série de métodos e funcionalidades (como adição, remoção e consulta) que dão dinamismo e agilidade no desenvolvimento de listas e coleções com C#.

Assim, desenvolvemos uma aplicação console em que é possível cadastrar, listar, remover, ordenar e pesquisar contas-correntes. Executando nosso projeto, podemos digitar 1 para cadastrar uma conta e informar os seguintes dados:

Número da Agência: 58
Saldo inicial: 96
Titular: André
CPF: 1123536
Profissão: Dev C#
Uma vez que o cadastro é realizado com sucesso, voltamos ao menu e podemos listar todas as contas do ByteBank selecionando a opção 2.
Vale lembrar que já temos 3 contas padrões cadastradas no nosso sistema.
Para fazer uma pesquisa, é possível escolher a opção 5 no menu da aplicação.
Em seguida, vamos escolher 3 e consultar contas-correntes cujo número da agência é igual a 94.
Como resultado, veremos a lista que corresponde à busca. Tudo está funcionando como esperado.

Por fim, podemos digitar 6 para encerrar a aplicação.
