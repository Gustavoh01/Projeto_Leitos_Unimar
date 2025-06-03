# Documento de Arquitetura

## Histórico de Revisões desde Arquivo

| Data       | Versão | Descrição                | Autor  |
| ---------- | ------ | ------------------------ | ------ |
| 13/05/2025 | 1.0    | Versão inicial           | [Felipe] |
| DD/MM/AAAA | 1.1    | [Descrição da alteração] | [Nome] |

## 1. Introdução

### 1.1 Finalidade

O objetivo principal é explicar como o sistema vai funcionar, mostrando como suas partes se conectam e trabalham juntas para atingir os objetivos do projeto. 1.2 Escopo O nosso foco principal seria automatizar os leitos fazendo assim ser mais rápida e objetiva o atendimento com escolhas objetivas pelo paciente, com o uso da tecnologia tudo seria mais rápido e pratico deixando o paciente mais à vontade cada leito teria um tablet para seu paciente assim ele pode fazer login com suas informações deixando tudo bem claro para o enfermeiro 1.3 Definições, acrônimos e abreviações. No nosso projeto não usaremos. 2 Representação Arquitetural. 2.1 O modelo arquitetural escolhido seria o mvc. 2.2 Escolhemos esse modelo pois é ampla as especificações , tanben porque estamos aprendendo e esse modelo se encaixou bem com nosso projeto. 3 Metas e restrições da arquitetura. 3.1 Metas. Economizar energia Fazer com que os leitos funcionem gastando o mínimo de energia possível. Ter tecnologia inteligente Equipar com sensores e controles para facilitar o uso. fácil acesso e fácil entendimento com logos e desenhos. 3.2 Restrições Limitação de espaço ele precisara se adequar com o espaço do leito. O custo de produção também seria um ponto pesado. Os matérias devem ser de reparo rápido e barato para que o hospital não precise parar dias e dias para a manutenção. 4 Visão de caos de uso.

### 1.2 Escopo

O nosso foco principal seria automatizar os leitos fazendo assim ser mais rápida e objetiva o atendimento com escolhas objetivas pelo paciente, com o uso da tecnologia  tudo seria mais rápido e pratico deixando o paciente mais à vontade cada leito teria um tablet para seu paciente assim ele pode fazer login com suas informações deixando tudo bem claro para o enfermeiro 

### 1.3 Definições, Acrônimos e Abreviações

No nosso projeto não usaremos.

## 2. Representação Arquitetural

### 2.1 Modelo Arquitetural
 O modelo arquitetural escolhido seria o mvc. 
### 2.2 Justificativa

Escolhemos esse modelo pois é ampla as especificações , tanben porque estamos aprendendo e esse modelo se encaixou bem com nosso projeto.

## 3. Metas e Restrições da Arquitetura

### 3.1 Metas

Economizar energia  Fazer com que os leitos funcionem gastando o mínimo de energia possível.
Ter tecnologia inteligente Equipar com sensores e controles para facilitar o uso.
fácil acesso e fácil entendimento com logos e desenhos.

### 3.2 Restrições

Limitação de espaço ele precisara se adequar com o espaço do leito.
O custo de produção também seria um ponto pesado.
Os matérias devem ser de reparo rápido e barato para que o hospital não precise parar dias e dias para a manutenção.

## 4. Visão de Casos de Uso

### 4.1 Diagrama de Casos de Uso

- [uc001](diagramas/casos_de_uso/template_caso_de_uso.md)

### 4.2 Descrição dos Casos de Uso Significativos

[Descrição dos casos de uso mais importantes para a arquitetura]

## 5. Visão Lógica

### 5.1 Visão Geral

O sistema de automação de leitos automotivos é organizado para garantir um funcionamento eficiente, seguro, intuitivo e  rápido.

### 5.2 Padrões de Design Significativos

A padronização do nosso sistema sera minimalista e simples para o entendimento do usuario

### 5.3 Diagramas de Classes

[Diagramas ou referências para os diagramas]

## 6. Visão de Processos

Monitoramento sempre ativo  Sensores trabalham o tempo todo coletando informações como temperatura, pressão e posição do leito, garantindo ajustes precisos.
Controle inteligente O sistema analisa os dados recebidos e faz mudanças automáticas para melhorar o conforto e a segurança dos ocupantes.
Interação fácil  O usuário pode visualizar informações e fazer ajustes manualmente através de uma interface intuitiva.
Conectividade fluida  O sistema conversa com dispositivos externos e redes para compartilhar dados e melhorar a experiência.
Autodiagnóstico e manutenção  Ele verifica continuamente se tudo está funcionando bem e alerta sobre possíveis falhas para evitar problemas.

## 7. Visão de Implantação

### 7.1 Diagrama de Implantação

O sistema funciona como um organismo inteligente, cuidando de tudo para oferecer conforto e segurança. Os sensores estão sempre atentos, captando informações como temperatura e posição para garantir ajustes automáticos. No centro de decisões, o sistema analisa esses dados e escolhe as melhores configurações para o usuário. A interface permite que tudo seja acompanhado e ajustado de forma simples e intuitiva. Com conexões inteligentes, o sistema conversa com outros dispositivos para funcionar de maneira integrada. E para evitar dores de cabeça, a manutenção automatizada identifica problemas antes que eles aconteçam, garantindo um funcionamento contínuo e sem preocupações.

### 7.2 Descrição dos Nós

O sistema funciona como um organismo inteligente, cuidando de tudo para oferecer conforto e segurança. Os sensores estão sempre atentos, captando informações como temperatura e posição para garantir ajustes automáticos. No centro de decisões, o sistema analisa esses dados e escolhe as melhores configurações para o usuário. A interface permite que tudo seja acompanhado e ajustado de forma simples e intuitiva. Com conexões inteligentes, o sistema conversa com outros dispositivos para funcionar de maneira integrada. E para evitar dores de cabeça, a manutenção automatizada identifica problemas antes que eles aconteçam, garantindo um funcionamento contínuo e sem preocupações.

## 8. Visão de Implementação

### 8.1 Visão Geral

A Arquitetura é bem estruturada com a utilização do modelo MVC que tem especificações sobre cada parte como, Model-esquematização de um "Banco de Dados",View- que seria a visualizalização do sistema e controller para administração de partes
r
### 8.2 Camadas

Ele tem sensores que ficam de olho na temperatura, na pressão e na posição do leito para garantir ajustes automáticos. A parte de processamento analisa essas informações e decide o que precisa ser ajustado para melhorar a experiência do usuário. Tudo pode ser acompanhado e personalizado por meio de uma interface simples e intuitiva.Ele tem sensores que ficam de olho na temperatura, na pressão e na posição do leito para garantir ajustes automáticos. A parte de processamento analisa essas informações e decide o que precisa ser ajustado para melhorar a experiência do usuário. Tudo pode ser acompanhado e personalizado por meio de uma interface simples e intuitiva.

## 9. Visão de Dados



### 9.1 Modelo de Dados

Leito:
ID, Número, Tipo, Status (Disponível, Ocupado, etc.), Setor, Equipamentos, Data de Ocupação/Liberação.
Paciente:
ID, Nome, Diagnóstico, Data de Admissão/Alta, Leito Alocado, Profissional Responsável.
Profissional de Saúde:
ID, Nome, Especialidade, Leitos Atribuídos.
Equipamento:
ID, Tipo (Ventilador, Monitor), Status, Leito Associado.
Setor:
ID, Nome (UTI, Enfermaria), Capacidade.
Histórico de Ocupação:
ID, Leito, Paciente, Data de Ocupação/Liberação.
Relacionamentos:
Leito - Paciente: 1:N (um leito pode ter um paciente).
Leito - Equipamento: 1:N (um leito pode ter vários equipamentos).
Paciente - Profissional de Saúde: N:M (vários profissionais podem atender a um paciente).
Leito - Setor: 1:N (um leito pertence a um setor).
Fluxo de Dados:
Cadastro de paciente e alocação de leito.
Monitoramento de equipamentos e histórico de ocupação.
Tecnologias:
Banco de Dados: Relacional (MySQL, PostgreSQL).
Frontend: React.js, Angular.
IoT: Para monitoramento em tempo real de leitos e equipamentos

## 10. Tamanho e Performance

O sistema precisa ser rápido para atender a situações de emergências. Ele deve aguentar muitos dados com centenas de pacientes simultâneos. Deve ter uma boa proteção de dados para que nada de particular do paciente seja exposto.
## 11. Qualidade

[Atributos de qualidade e como são atendidos pela arquitetura]

## 12. Princípios SOLID Aplicados

LSP,OCP,SRP

## 13. Padrões de Design Utilizados

Design centrado no usuário (DCU) e UI Design (Design de Interface do Usuário) são áreas interconectadas que se concentram em criar experiências digitais eficazes e agradáveis para o usuário

>[!TIP]
>Ao longo do desenvolvimento, revise este documento para garantir que a implementação esteja alinhada com a arquitetura planejada. Documente as decisões arquiteturais importantes, incluindo as alternativas consideradas e os motivos da escolha final.
