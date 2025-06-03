## Diário de Desenvolvimento - Projeto Integrador de Engenharia de Software

**Grupo:** Gustavo Henrique Costa dos Santos; Ruan Padilha; Davi Lucas Telles; Kaua Guilherme Izzo Braga; Gabriel Mesquita da Silva; Felipe Stuque;

**Integrantes:** Gustavo Henrique Costa dos Santos, Ruan Padilha, Davi Lucas Telles, Kaua Guilherme Izzo Braga, Gabriel Mesquita da Silva, Felipe Stuque, João Pedro

---

## Semana 10

### Informações Básicas

**Data:** 15/04/2025
**Membros presentes:** Todos
**Tema da semana:** Modelagem de Requisitos - Diagrama de Classes

### Atividades Realizadas

**Descrição das atividades:**

- Desenvolvimento do Diagrama de Classes Inicial do projeto.
- Organização e revisão final dos Diários de Bordo das semanas anteriores e da atual.

**Artefatos produzidos:**

- Diagrama de Classes - [Link para o repositório ou ferramenta de diagramação] (ex: link para o Mermaid no GitHub, draw.io, Lucidchart)
- Diário de bordo da semana - [Link para o repositório ou localização] (ex: link para o repositório do projeto)

**Distribuição de tarefas:**

- Gustavo Henrique: Responsável pela organização dos Diários de Bordo e criação do Diagrama de Classes em código (Mermaid).
- Ruan Padilha: Colaborou na definição das classes e seus atributos para o Diagrama de Classes.
- Felipe Stuque: Auxiliou na criação do Diagrama, revisando a estrutura das classes.
- Gabriel Mesquita: Auxiliou na criação do Diagrama, contribuindo com a identificação de relacionamentos.
- Davi Lucas: Auxiliou na criação do Diagrama, verificando a consistência dos atributos.
- Kaua Braga: Auxiliou na criação do Diagrama, revisando a clareza das associações.
- João Pedro: Contribuiu com a validação das classes e métodos no diagrama.

### Dificuldades e Soluções

**Desafios encontrados:**

- Entender como fazer um diagrama de classes usando a sintaxe dos códigos do Mermaid.
- Dificuldade em abstrair as entidades do sistema em classes com responsabilidades claras.

**Soluções adotadas:**

- Para entender como funciona o Mermaid: Exploramos a documentação oficial do Mermaid e exemplos online, além de realizar testes em um editor de código.
- Para abstrair as entidades: Realizamos sessões de discussão em grupo para definir as classes, atributos e métodos com base nas histórias de usuário.

**Conhecimentos adquiridos:**

- Utilização da ferramenta Mermaid para criação de Diagramas UML em formato de texto.
- Princípios de Modelagem Orientada a Objetos e como aplicá-los em um Diagrama de Classes.

### Reflexão sobre Aplicação dos Conceitos

**Conceitos teóricos aplicados:**

- Modelagem de Requisitos: A criação do Diagrama de Classes é uma forma de visualizar a estrutura do sistema com base nos requisitos.
- Orientação a Objetos: Aplicamos os conceitos de classes, atributos, métodos e relacionamentos.

**Insights obtidos:**

- A criação do Diagrama de Classes é um passo fundamental para a fase de implementação, pois fornece uma "planta" do sistema.
- A ferramenta Mermaid facilita a criação e manutenção de diagramas diretamente no código.

**Conexões com conteúdos anteriores:**

- A criação do Diagrama de Classes é baseada nas histórias de usuário e nos requisitos levantados e refinados nas semanas anteriores de Modelagem de Requisitos.

### Próximos Passos

**Planejamento para próxima aula:**

- Esperar o Professor opinar sobre os diagramas realizados para possíveis ajustes.
- Iniciar a pesquisa sobre Prototipagem e Design de Interface.

**Tarefas pendentes:**

- Finalizar os últimos detalhes dos diários de bordo - Responsável: Gustavo.

**Objetivos para próxima semana:**

- Ter o Diagrama de Classes validado e pronto para ser a base da implementação.
- Iniciar a fase de Prototipagem, começando com rascunhos de telas.

### Registros Visuais

```mermaid
classDiagram
    Leito <|-- Cliente
    Leito <|-- Medico
    Medico <|-- Cliente
    Leito <|-- Enfermeiros
    Leito <|-- Adiministrador
    Cliente <|-- Adiministrador
    Medico <|-- Adiministrador
    Enfermeiros <|-- Adiministrador
    Inventario <|-- Adiministrador
    Leito <|-- Inventario
    
    class Leito{
      +String Nome
      +String localizacao
      +int Número
      +Cadastrar()
      +Atualizar()
      +Excluir()
    }
    class Cliente{
      +String Nome
      +int Idade
      +int CPF
      +String Genero
      +String Laudo
      +Adicionar()
      +Remover()
    }
    class Medico{
      +String Nome
      +int Idade
      +String Genero
      +String Especialidade
      +Float Turno
      +Consultar()
    }
    class Adiministrador{ 
        +String Nome
        +int Número_de_Identificacao
        +Monitoramento()
        +Consultar_Equipamentos()
    }
    class Inventario{
        +String Itens
        +String Equipamentos_Emergencia
        +String Equipamentos_Cirurgicos
        +String Equipamentos_Controle
        +Adicionar_Equipamentos()
        +Remover_Equipamentos()
        +Consultar_Id_Equipamentos()
     }
    class Enfermeiros{ 
      +String Nome
      +int Idade
      +String Genero
      +String Especialidade
      +Float Turno
      +Consultar()
    }