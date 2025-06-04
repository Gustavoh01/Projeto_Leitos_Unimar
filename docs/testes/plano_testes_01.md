# Plano de Testes

## Histórico de Revisões

| Data       | Versão | Descrição                | Autor  |
| ---------- | ------ | ------------------------ | ------ |
| 03/06/2025 | 1.0    | Versão inicial           | Gustavo |
| 05/06/2025 | 1.1    | Adição de casos de teste e métricas | Ruan |

## 1. Introdução

### 1.1 Objetivos

O principal objetivo deste plano de testes é descrever a abordagem a ser utilizada para garantir a qualidade e a funcionalidade do sistema de automação de leitos. Visa identificar defeitos, validar os requisitos funcionais e não funcionais, e assegurar que o software atenda às expectativas dos usuários e partes interessadas.

### 1.2 Escopo

O escopo de testes abrange todas as funcionalidades do sistema de automação de leitos, incluindo:

Gerenciamento de leitos (cadastro, atualização, exclusão).
Gerenciamento de clientes/pacientes (internação, alta, movimentação).
Gerenciamento de médicos e enfermeiros (cadastro, associação a pacientes).
Gerenciamento de inventário (adição, remoção, consulta de equipamentos).
Monitoramento de leitos e pacientes.
Interfaces de usuário para administrador, médico, enfermeiro e cliente.
Segurança do acesso aos dados e funcionalidades.
Performance do sistema sob carga.

### 1.3 Definições, Acrônimos e Abreviações

CT: Caso de Teste
RQ: Requisito
UI: User Interface (Interface do Usuário)
UX: User Experience (Experiência do Usuário)
Jira: Ferramenta de gerenciamento de projetos e rastreamento de issues.
GitHub: Plataforma de hospedagem de código-fonte com controle de versão.
Figma: Ferramenta de prototipagem e design de interface.
UML: Unified Modeling Language (Linguagem de Modelagem Unificada)
SOLID: Acrônimo para cinco princípios de design de software: Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.

## 2. Estratégia de Teste
A estratégia de teste será baseada em uma abordagem incremental e iterativa, seguindo a metodologia ágil. Os testes serão realizados em diferentes níveis e tipos para garantir uma cobertura abrangente.

### 2.1 Níveis de Teste

#### 2.1.1 Testes Unitários
Serão realizados testes em módulos e funções individuais do código-fonte para verificar se cada parte funciona conforme o esperado. O desenvolvimento será guiado por testes (TDD) sempre que possível.

#### 2.1.2 Testes de Integração

Serão realizados testes para verificar a comunicação e a interação entre os diferentes módulos e componentes do sistema (ex: integração entre o módulo de gerenciamento de leitos e o módulo de clientes).

#### 2.1.3 Testes de Sistema

Serão realizados testes de ponta a ponta para validar o comportamento completo do sistema, garantindo que todos os requisitos funcionais e não funcionais sejam atendidos em um ambiente integrado.

#### 2.1.4 Testes de Aceitação

Serão realizados testes pelos usuários finais ou representantes do cliente para verificar se o sistema atende aos requisitos de negócio e se é aceitável para implantação.

### 2.2 Tipos de Teste

#### 2.2.1 Testes Funcionais

Serão focados em validar se cada funcionalidade do sistema opera de acordo com as especificações e histórias de usuário. Serão criados casos de teste para cada cenário de uso.

#### 2.2.2 Testes de Performance

Serão realizados para avaliar a capacidade de resposta, estabilidade e escalabilidade do sistema sob diferentes cargas (ex: tempo de resposta ao cadastrar múltiplos leitos, comportamento com muitos usuários logados).

#### 2.2.3 Testes de Segurança

Serão focados em identificar vulnerabilidades no sistema, como falhas de autenticação, autorização, injeção de SQL, exposição de dados sensíveis, etc.

#### 2.2.4 Testes de Usabilidade

Serão conduzidos para avaliar a facilidade de uso, a eficiência e a satisfação do usuário com a interface do sistema. Serão utilizados os protótipos como base para esses testes.

#### 2.2.5 Testes de Regressão

Serão executados periodicamente, especialmente após cada nova funcionalidade ou correção de bug, para garantir que as alterações não introduziram novos defeitos em funcionalidades existentes.

## 3. Recursos

### 3.1 Ambientes de Teste

Ambiente de Desenvolvimento: Máquinas locais dos desenvolvedores para testes unitários e de integração iniciais.
Ambiente de Homologação: Servidor dedicado que simula o ambiente de produção, onde serão realizados testes de sistema e aceitação.
Ferramentas de Banco de Dados: Banco de dados de teste isolado para evitar impacto nos dados de desenvolvimento.

### 3.2 Ferramentas

Gerenciamento de Testes e Bugs: Jira (para rastreamento de casos de teste, defeitos e gestão do ciclo de vida de testes).
Automação de Testes (Unitários): JUnit (Java), Pytest (Python), Jest (JavaScript) - a ser definido com base na tecnologia de desenvolvimento.
Automação de Testes (UI/End-to-end): Selenium, Cypress, Playwright (a ser definido).
Testes de Performance: JMeter, K6 (a ser definido).
Versionamento de Código: Git e GitHub.
Prototipagem/Design: Figma (para testes de usabilidade e visualização de interfaces).

### 3.3 Equipe

Líder de Testes: Responsável pela criação e manutenção do plano de testes, coordenação da equipe de testes, e garantia da qualidade geral.
Engenheiros de Teste: Responsáveis pela criação e execução de casos de teste, automação de testes, e relato de defeitos.
Desenvolvedores: Responsáveis por escrever testes unitários, corrigir defeitos e apoiar os engenheiros de teste.
Product Owner/Representante do Cliente: Responsável por validar os testes de aceitação e fornecer feedback.

## 4. Cronograma

Atividade	Início	Término	Responsável
Elaboração Plano de Testes	03/06/2025	05/06/2025	Líder de Testes
Criação de Casos de Teste	06/06/2025	14/06/2025	Engenheiros de Teste
Configuração Amb. Teste	06/06/2025	10/06/2025	Equipe de Desenvolvimento
Testes Unitários	Contínuo	Contínuo	Desenvolvedores
Testes de Integração	Contínuo	Contínuo	Engenheiros de Teste, Desenvolvedores
Testes de Sistema (Fase 1)	17/06/2025	28/06/2025	Engenheiros de Teste
Testes de Usabilidade	24/06/2025	28/06/2025	Engenheiros de Teste, PO
Geração de Relatórios (Parcial)	27/06/2025	30/06/2025	Líder de Testes

## 5. Critérios

### 5.1 Critérios de Entrada

Todos os requisitos definidos e aprovados.
Ambiente de teste configurado e estável.
Build do software disponível para teste.
Testes unitários e de integração iniciais concluídos (com taxa de sucesso mínima de 80%).
Ausência de defeitos críticos ou bloqueadores conhecidos.

### 5.2 Critérios de Saída

Todos os casos de teste planejados executados (cobertura mínima de 95%).
Taxa de sucesso dos casos de teste funcionais superior a 90%.
Todos os defeitos críticos e de alta prioridade corrigidos e retestados.
Defeitos de média e baixa prioridade documentados e com plano de tratamento.
Os objetivos de performance e segurança definidos foram atingidos.
O Product Owner aprovou o sistema nos testes de aceitação.

### 5.3 Critérios de Suspensão e Retomada

Suspensão:
Identificação de um defeito bloqueador que impede a continuidade dos testes em uma funcionalidade crítica.
Instabilidade severa do ambiente de teste.
Mais de 20% dos casos de teste críticos falhando na primeira execução.
Retomada:
Correção do defeito bloqueador ou estabilização do ambiente de teste.
Nova build do software com as correções implementadas.
Revisão e validação da equipe de testes.

## 6. Matriz de Risco e Contingência

| Risco     | Probabilidade      | Impacto            | Estratégia de Mitigação |
| --------- | ------------------ | ------------------ | ----------------------- |
| Atraso na entrega das builds | Média | Alto | Comunicação frequente com a equipe de desenvolvimento; buffer no cronograma.
]            |
| Falha no ambiente de teste | Média | Alto/Médio/Baixo Médio | 	Documentação de setup do ambiente; backups regulares; equipe de suporte dedicada.           |
| Requisitos incompletos/ambíguos     | Baixa  Alto| 	Refinamento contínuo dos requisitos; workshops de elicitação; revisão de histórias de usuário.                   |

## 7. Casos de Teste

| ID   | Descrição   | Requisito | Pré-condições | Passos   | Resultado Esperado | Prioridade         |
| ---- | ----------- | --------- | ------------- | -------- | ------------------ | ------------------ |
| CT01 | 	Cadastro de novo leito | RQ_LEITO01     | 	Usuário logado como Administrador        | 1. Acessar a tela de "Gerenciamento de Leitos".&lt;br>2. Clicar no botão "Adicionar Leito".&lt;br>3. Preencher os campos "Nome do Leito", "Localização" e "Número".&lt;br>4. Clicar em "Salvar". | O novo leito é exibido na lista de leitos cadastrados com sucesso.        | Alta |
| CT02 | RQ_CLIENTE02 | Leito disponível cadastrado; Paciente existente.    | . Acessar a tela de "Gerenciamento de Clientes".&lt;br>2. Selecionar um paciente existente.&lt;br>3. Clicar na opção "Internar Paciente".&lt;br>4. Selecionar um leito disponível na lista.&lt;br>5. Confirmar a internação.      | O paciente é associado ao leito e o status do leito muda para "Ocupado".|       | Alta |
| ...  | ...         | ...       | ...           | ...      | ...                | ...                |

## 8. Métricas

Número de Casos de Teste Executados: Total de casos de teste que foram executados.
Número de Casos de Teste Passados/Falhados: Contagem de casos de teste que passaram ou falharam.
Taxa de Sucesso de Casos de Teste: (Casos Passados / Casos Executados) * 100%.
Número de Defeitos Encontrados: Total de defeitos reportados.
Defeitos por Prioridade: Distribuição dos defeitos por prioridade (Crítica, Alta, Média, Baixa).
Tempo Médio de Resolução de Defeitos: Tempo médio para corrigir um defeito desde o relato até a validação.
Cobertura de Teste: Porcentagem de requisitos/código cobertos pelos testes.

## 9. Relatórios

Relatório de Progresso Semanal: Atualização semanal sobre o status dos testes, casos de teste executados, defeitos encontrados e métricas chave.
Relatório de Defeitos: Documento detalhado de todos os defeitos encontrados, incluindo descrição, passos para reprodução, severidade, prioridade e status.
Relatório de Sumário de Testes: Relatório final que resume todo o ciclo de testes, incluindo escopo, estratégia, resultados, métricas, lições aprendidas e recomendações.

## 10. Aprovação

| Nome   | Papel   | Assinatura | Data       |
| ------ | ------- | ---------- | ---------- |
| Gustavo Henrique Costa dos Santos | Líder de Testes | 03/06/2025 |
| [Nome] | [Papel] |            | DD/MM/AAAA |

