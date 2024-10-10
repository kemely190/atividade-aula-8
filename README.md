O código cria um sistema que gerencia informações de pessoas. Você pode cadastrar, atualizar e exibir os dados de duas pessoas diferentes.

Instruções de compilação e execução:
1. Compile o código: Abra um terminal, navegue até a pasta onde os arquivos estão salvos e digite  javac *.java . Isso irá criar um arquivo executável.
2. Execute o código: Depois de compilar, digite  java Main  no terminal para iniciar o programa.

Exemplo  de uso:
1. Cria duas pessoas: João com CPF 123.456.789-00 e 30 anos, e Maria com CPF 987.654.321-00 e 25 anos.
2. Cadastra as pessoas: João como Pessoa 1 e Maria como Pessoa 2.
3. Mostra os dados das pessoas: Nome, CPF e idade de cada uma.
4. Atualiza os dados da Pessoa 1: Muda o nome para "João Silva" e a idade para 31 anos.
5. Mostra novamente os dados da Pessoa 1: Agora com o nome e idade atualizados.


Para acessar esses dados, você precisa usar métodos especiais chamados getters e setters.
O código usa uma técnica chamada encapsulamento. Isso significa que os dados de cada pessoa (nome, CPF e idade) são protegidos dentro da classe  pessoa .
Para acessar esses dados, você precisa usar métodos especiais chamados getters e setters. 
- Getters são usados para ler os dados. Por exemplo,  pessoa1.getNome()  retorna o nome da Pessoa 1.
- Setters são usados para modificar os dados. Por exemplo,  pessoa1.setNome("João Silva")  muda o nome da Pessoa 1 para "João Silva".
 

 
