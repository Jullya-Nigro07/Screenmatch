# 🎬 Screenmatch

---

![Status](https://img.shields.io/badge/Status-Em%20andamento-yellow)
![Linguagem](https://img.shields.io/badge/Linguagem-Java-red)
![IDE](https://img.shields.io/badge/IDE-IntelliJ%20IDEA-blue)

Esse projeto está em andamento... pois é um script de estudo do curso Java na Alura.

---

## ✨ Visão Geral do Projeto

**Screenmatch** é um projeto de estudos em Java, focado em **Orientação a Objetos (POO)** e manipulação de coleções. Ele simula uma plataforma de streaming, modelando filmes e séries como objetos para praticar:

* **Modelagem de Domínio:** Criação de classes e atributos para entidades (Filme, Série, Título)
* **Cálculos e Lógica:** Soma de tempo de visualização e cálculo de médias de avaliação
* **Manipulação de Coleções:** Ordenação, filtragem e iteração de listas de títulos

> 📝 **Nota:** Esta é uma aplicação de linha de comando (CLI), focada puramente na lógica de backend

---

## 🚀 Como Rodar o Projeto

Siga estes passos simples para colocar o Screenmatch em funcionamento:

1.  **Clone o repositório:**
   
    ```bash
    git clone [https://github.com/Jullya-Nigro07/screenmatch.git](https://github.com/Jullya-Nigro07/screenmatch.git)
    ```
    
2.  **Abra no IDE:** Use seu Ambiente de Desenvolvimento Integrado (IDE) Java favorito (IntelliJ IDEA, Eclipse, VS Code c/ extensão Java)

3.  **Compile e Execute:**
    * Compile o projeto.
    * Execute a classe principal (`Main`, `Principal` ou similar) para interagir com as funcionalidades na linha de comando
      
---

## ✅ Funcionalidades Principais

* **Definição de Objetos:** Criação de instâncias de `Filme` e `Série` com atributos como Título, Duração, Ano de Lançamento e Classificação.
  
* **Gerenciamento de Coleções:**
    * Adicionar novos títulos à lista.
    * Ordenar a lista por diferentes critérios (nome, duração, ano).
    * Iterar e exibir todos os títulos.
    
* **Métricas:**
    * Cálculo do **tempo total necessário** para assistir a todos os títulos da lista.
    * Média de avaliação de títulos.

---

## 🧑‍💻 Tecnologias e Conceitos

Este projeto é um excelente ponto de partida para consolidar conhecimentos em:

* **Java (Linguagem)**
* **Orientação a Objetos (POO):** Encapsulamento, Herança, Polimorfismo
* **Coleções Java:** Uso de `List`, interfaces `Comparable` e `Comparator` para ordenação
* **Estrutura de Pacotes/Classes:** Organização de código em um projeto Java robusto

---

## 💡 Próximos Passos & Possíveis Melhorias

O projeto é aberto a melhorias! Algumas ideias para quem quiser evoluir este código:

1.  **Integração com API Externa:** Conectar-se a APIs como OMDb para buscar dados de filmes automaticamente
2.  **Nova Interface:** Transformar a aplicação CLI em uma **API REST** ou um **Front-end Web** para facilitar a visualização e interação
3.  **Persistência de Dados:** Adicionar um banco de dados (SQL, NoSQL) ou salvar em arquivo (JSON) para manter as listas entre execuções
4.  **Robustez:** Melhorar a validação de entrada e o tratamento de exceções
