# Caso de Uso: [ID]

## Nome

[Nome do caso de uso]

## Descrição

[Descrição breve do caso de uso]

## Atores

- [Ator primário]
- [Atores secundários, se houver]

## Pré-condições

1. [Pré-condição 1]
2. [Pré-condição 2]
3. [Pré-condição n]

## Fluxo Básico

1. [Passo 1]
2. [Passo 2]
3. [Passo n]

## Fluxos Alternativos

### [Alternativa 1]

1. [Passo 1]
2. [Passo 2]
3. [Passo n]

### [Alternativa 2]

1. [Passo 1]
2. [Passo 2]
3. [Passo n]

## Fluxos de Exceção

### [Exceção 1]

1. [Passo 1]
2. [Passo 2]
3. [Passo n]

### [Exceção 2]

1. [Passo 1]
2. [Passo 2]
3. [Passo n]

## Pós-condições

1. [Pós-condição 1]
2. [Pós-condição 2]
3. [Pós-condição n]

## Requisitos Relacionados

- [Requisito 1]
- [Requisito 2]
- [Requisito n]

## Interface de Usuário

[Descrição ou referência a protótipos/mockups]

## Diagrama

```mermaid
classDiagram
    Leito <|-- Cliente
    Leito <|-- Medico
    Medico <|-- Cliente
    Leito<|-- Enfermeiros
    Leito <|-- Adiministrador
    Cliente<|-- Adiministrador
    Medico<|-- Adiministrador
    Enfermeiros<|-- Adiministrador
    Inventario<|-- Adiministrador
    Leito<|-- Inventario
    Leito : +String Nome
    Leito : +String localizacao
    Leito : +int Número
    Leito: +Cadastrar()
    Leito: +Atualizar()
    Leito: +Excluir()

    class Cliente{
      +String Nome
      + int Idade
      + int CPF
      + String Genero
      + String Laudo
      +Adicionar()
      +Remover()
    }
    class Medico{
      +String Nome
      +int Idade
      +int Genero
      +String Especialidade
      +Float Turno
      +Consultar()
    }
    class Adiministrador{ 
        +String Nome
        +int Número de Identificacao
        +Monitoramento()
        +Consultar Equipamentos()
    }
    class Inventario{
        +String Itens
        +String Equipamentos Emergencia
        +String Equipamentos Cirurgicos
        +String Equipamentos Controle
        +Adicionar Equipamentos()
        +Remover Equipamentos()
        +Consultar Id Equipamentos()
     }
    class Enfermeiros{ 
      +String Nome
      +int Idade
      +int Genero
      +String Especialidade
      +Float Turno
      +Consultar()
    }
```
