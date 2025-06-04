# Relatório Técnico - Entrega Parcial

**Data:** 11/04/2025  
**Versão:** 1.0  
**Equipe:**

- [Nome do Membro 1] - [Papel/Responsabilidade]  
- [Nome do Membro 2] - [Papel/Responsabilidade]  
- [Nome do Membro n] - [Papel/Responsabilidade]  

## 1. Resumo Executivo

O projeto visa automatizar os leitos hospitalares, oferecendo maior conforto e agilidade no atendimento aos pacientes. Cada leito contará com um tablet para o paciente, que poderá realizar login e acessar informações de forma prática, além de permitir ajustes automáticos ou manuais do leito. Já foram definidos o modelo arquitetural e as interfaces iniciais para profissionais de saúde e pacientes.

## 2. Introdução

### 2.1 Objetivo do Projeto

O objetivo do projeto é desenvolver um sistema de automação de leitos hospitalares, com foco em eficiência energética, facilidade de uso e integração com tecnologias modernas.

### 2.2 Escopo

O escopo abrange a criação de um sistema automatizado para os leitos, onde cada paciente poderá realizar login em um tablet instalado em seu leito, facilitando a comunicação com o enfermeiro e permitindo ajustes automáticos e manuais.

### 2.3 Metodologia

A equipe está utilizando o modelo arquitetural MVC (Model-View-Controller) para organizar o desenvolvimento do sistema, além de metodologias ágeis (como sprints semanais) para iterar e validar funcionalidades.

## 3. Análise de Requisitos

### 3.1 Requisitos Funcionais

- Cadastro e alocação de pacientes aos leitos.  
- Ajustes automáticos e manuais de posição e configurações do leito.  
- Interface para enfermeiros e profissionais de saúde acompanharem o estado do leito e do paciente.  
- Interface para o paciente realizar ajustes manuais e visualizar informações.

### 3.2 Requisitos Não Funcionais

- Baixo consumo de energia.  
- Alta disponibilidade e confiabilidade, principalmente em situações de emergência.  
- Interface intuitiva e de fácil uso, com ícones e imagens claras.  
- Segurança e confidencialidade dos dados dos pacientes.

### 3.3 Matriz de Rastreabilidade

Atualmente, a matriz de rastreabilidade está em elaboração e será concluída na próxima fase, garantindo que todos os requisitos sejam mapeados e implementados.

## 4. Arquitetura e Design

### 4.1 Visão Geral da Arquitetura

O sistema adota o modelo **MVC**:  
- **Model**: responsável por gerenciar dados como pacientes, leitos e equipamentos.  
- **View**: interface do usuário (enfermeiro e paciente).  
- **Controller**: coordena as interações entre Model e View, recebendo comandos e atualizando o estado do sistema.

### 4.2 Diagramas

*(Diagramas arquiteturais e de interface serão desenvolvidos na próxima fase.)*

### 4.3 Decisões de Design

- Adoção do padrão **MVC** por facilitar a organização e manutenção do sistema.  
- Integração com tecnologias web modernas para permitir interfaces dinâmicas e responsivas.  
- Uso de interfaces intuitivas e adaptadas ao ambiente hospitalar.

### 4.4 Protótipos

*(Protótipos de interface em desenvolvimento, utilizando conceitos de usabilidade e clareza visual.)*

## 5. Implementação Atual

### 5.1 Funcionalidades Implementadas

- Estrutura inicial do sistema organizada em partes bem definidas (Model, View, Controller).  
- Interface inicial para login e visualização de dados básicos dos leitos e pacientes.  

### 5.2 Tecnologias Utilizadas

- **Frontend**: React.js ou Angular para a interface do usuário.  

### 5.3 Código-fonte

*(Estrutura inicial criada, repositório em fase de organização e versionamento.)*

## 6. Testes

### 6.1 Abordagem de Teste

Testes iniciais focados na integração entre a interface de usuário e a estrutura de dados, além de validações de desempenho e consistência das informações apresentadas.

### 6.2 Testes Realizados

- Testes manuais de cadastro e atualização de dados dos leitos e pacientes.  
- Verificação da responsividade e clareza da interface.

### 6.3 Resultados

Resultados satisfatórios até o momento, com comunicação funcional entre as partes do sistema e interfaces de usuário em funcionamento.

## 7. Progresso do Projeto

### 7.1 Cronograma

- Etapa de definição de arquitetura: **concluída**  
- Criação da estrutura inicial do sistema: **concluída**  
- Interface inicial e funcionalidades básicas: **em andamento**

### 7.2 Sprints Concluídas

- Sprint 1: Estruturação da arquitetura e organização inicial do sistema.  
- Sprint 2: Interface inicial e comunicação com as partes do sistema.

### 7.3 Métricas

- Velocidade de desenvolvimento alinhada às expectativas da equipe.  
- Boa comunicação e divisão de responsabilidades entre os membros da equipe.

## 8. Desafios e Soluções

### 8.1 Principais Desafios

- Limitação de espaço físico para os equipamentos que acompanham o leito.  
- Garantir o baixo consumo de energia em todas as partes do sistema.  
- Custo de produção e manutenção.

### 8.2 Soluções Adotadas

- Uso de materiais de fácil reparo e baixo custo para minimizar tempo de manutenção.  
- Implementação de práticas de otimização para consumo energético.  

## 9. Próximos Passos

### 9.1 Funcionalidades Planejadas

- Finalizar interface para pacientes e enfermeiros.  
- Implementar ajustes automáticos de leito com base em configurações padrão.  
- Aprimorar as funcionalidades de login e configuração dos leitos.

### 9.2 Melhorias Previstas

- Otimização do consumo de energia do sistema.  
- Aprimoramento da interface para torná-la ainda mais intuitiva.

### 9.3 Cronograma Atualizado

*(Novo cronograma será apresentado na próxima reunião de equipe.)*

## 10. Lições Aprendidas

- A importância de um modelo de arquitetura claro para facilitar ajustes futuros.  
- Necessidade de considerar restrições físicas e orçamentárias logo no início do projeto.

## 11. Conclusão

O projeto encontra-se em fase de estruturação e implementação inicial, com progresso satisfatório e foco em garantir uma solução eficiente, segura e fácil de usar para pacientes e profissionais de saúde.

## 12. Anexos

Sem.

> [!NOTE]  
> Este relatório representa o estado do projeto na data da entrega parcial. Alterações e evoluções ocorrerão na segunda fase do desenvolvimento.
