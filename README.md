# Desafio Patterns Java

Este repositório contém uma solução que explora os conceitos de Padrões de Projeto em Java. Durante o desafio, busquei aplicar diversos padrões para criar uma aplicação robusta e reutilizável. A proposta foi não apenas entender a teoria por trás de cada padrão, mas também implementá-los de forma prática, utilizando boas práticas de design de software.

## Padrões de Projeto Utilizados
1. **Singleton**: Garante que uma classe tenha uma única instância e fornece um ponto de acesso global a essa instância.
2. **Facade**: É um padrão de projeto estrutural que fornece uma interface simplificada (mas limitada) para um sistema complexo de classes, biblioteca, ou framework.
3. **Id**:É utilizada para indicar ao JPA qual atributo de uma entidade será a chave primária da tabela no banco de dados.  
4. **Model**: Permite configurar classes e interfaces do cliente e do endereco que são configurados também aqui.
5. **Strategy**: Define uma família de algoritmos, encapsula cada um e os torna intercambiáveis.
Facade: Fornece uma interface simplificada para um conjunto de interfaces em um subsistema, facilitando seu uso.
6. **Builder**: Permite a criação de um objeto complexo, passo a passo, sem expor sua representação interna.

##Estrutura do Projeto

O projeto está estruturado de forma a demonstrar a aplicação de cada um dos padrões mencionados. Cada diretório dentro de src/ contém um exemplo prático de um padrão de design específico.

##Como Rodar

1. Clone este repositório:

```bash
git clone https://github.com/Dvd-coder-art/-Design-Patterns-com-Java/desafio-patterns-java.git
```

2. Navegue até o diretório do projeto:

```bash
cd desafio-patterns-java
```

3. Compile e execute o projeto:

```bash
mvn clean install
mvn exec:java
```

## Conclusão

A prática de padrões de projeto é essencial para a criação de sistemas escaláveis e fáceis de manter. Ao longo deste desafio, pude entender melhor como aplicar esses conceitos no desenvolvimento de soluções em Java.

