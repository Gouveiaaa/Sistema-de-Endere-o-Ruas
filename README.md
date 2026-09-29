Sistema de Cadastro de Indivíduos e Endereços

Um projeto simples em Java para exemplificar conceitos de **Programação Orientada a Objetos (POO)**, demonstrando a associação entre classes (`Individuo` e `Endereco`), manipulação de atributos privados via *Getters e Setters* e exibição de dados no console.

Funcionalidades

- **Mapeamento de Endereço:** Modela atributos de localização como rua, número, cidade e cor/característica do imóvel.
- **Cadastro de Indivíduo:** Armazena dados pessoais (nome, CPF) e associa um objeto `Endereco` à pessoa.
- **Associação de Objetos:** Demonstra o relacionamento "tem-um" (*has-a*), onde um `Individuo` possui um `Endereco`.

Tecnologias Utilizadas

- **Linguagem:** Java (JDK 8 ou superior)
- **Paradigma:** Programação Orientada a Objetos (POO)

Estrutura do Código

```text
src/
├── Endereco.java       # Modelagem do endereço (rua, numero, cidade, cor)
├── Individuo.java      # Modelagem da pessoa e associação com Endereco
└── ListaEnderecos.java # Classe principal com o método main para execução
