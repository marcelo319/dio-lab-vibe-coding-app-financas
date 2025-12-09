# 💸 App de Organização de Finanças Pessoais com Vibe Coding
Prd refinado

# PRD - Aplicativo de Organização de Finanças Pessoais via Chat

## 1. Contexto

Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas com o usuário em linguagem natural. A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

O aplicativo deve seguir princípios de Design Universal para garantir acessibilidade e usabilidade para o máximo de usuários possível, independentemente de suas capacidades, idade ou contexto de uso.

## 2. Problema

Muitas pessoas desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual de dados e oferecem pouca personalização. A experiência de uso é frequentemente complexa e desmotivadora, especialmente para iniciantes em educação financeira.

Este aplicativo resolve esse problema oferecendo:
- Uma experiência de conversa natural e intuitiva
- Recomendações automáticas e personalizadas de economia
- Interface acessível e inclusiva seguindo padrões de Design Universal

## 3. Público-Alvo

Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes em controle financeiro. Inclui usuários de diferentes:
- Faixas etárias
- Níveis de alfabetização digital
- Capacidades físicas e cognitivas
- Contextos socioeconômicos

## 4. Princípios de Design Universal

O aplicativo deve seguir os 7 princípios do Design Universal:

1. Uso equitativo - Interface utilizável por pessoas com diferentes capacidades
2. Flexibilidade de uso - Acomodar preferências e habilidades individuais
3. Uso simples e intuitivo - Fácil de entender, independente da experiência do usuário
4. Informação perceptível - Comunicar informações de forma eficaz para todos os usuários
5. Tolerância ao erro - Minimizar riscos e consequências de ações acidentais
6. Baixo esforço físico - Usar de forma eficiente e confortável com mínimo de fadiga
7. Tamanho e espaço para aproximação e uso - Apropriado independente do tamanho corporal, postura ou mobilidade do usuário

## 5. Funcionalidades-Chave

### 5.1. Sistema de Múltiplas Contas
- Criar e gerenciar até 4 contas diferentes
- Identificação simplificada: Conta 1, Conta 2, Conta 3, Conta 4
- Possibilidade de personalizar nomes das contas (ex: "Conta Pessoal", "Conta Trabalho", etc.)
- Visualização consolidada ou individualizada

### 5.2. Registro de Gastos via Chat
- Interface de conversa em linguagem natural
- Aceitar entradas como: "Gastei 50 reais no mercado na conta 1"
- Suporte a diversos formatos de entrada (texto, voz quando possível)
- Confirmação visual clara das transações registradas

### 5.3. Classificação Automática
- Categorização inteligente de transações (alimentação, transporte, lazer, etc.)
- Aprendizado baseado no histórico do usuário
- Possibilidade de correção manual simples

### 5.4. Metas Financeiras
- Definir metas de economia por conta ou consolidadas
- Acompanhamento visual do progresso
- Alertas e motivação para atingir objetivos

### 5.5. Agente Financeiro (Assistente IA)
- Análise de padrões de gastos
- Dicas personalizadas de economia
- Linguagem amigável e educativa
- Respostas em português claro e acessível

### 5.6. Relatórios Personalizados
- Visualizações simples e compreensíveis
- Relatórios por conta individual ou consolidados
- Gráficos acessíveis com alternativas textuais
- Exportação de dados quando necessário

## 6. Requisitos de Acessibilidade

### 6.1. Interface Visual
- Alto contraste e cores acessíveis (WCAG 2.1 AA mínimo)
- Tamanhos de fonte ajustáveis
- Ícones claros com rótulos textuais
- Suporte a modo escuro e claro

### 6.2. Interação
- Navegação por teclado completa
- Compatibilidade com leitores de tela
- Feedback tátil e visual para ações
- Botões e áreas de toque com tamanho adequado (mínimo 44x44px)

### 6.3. Conteúdo
- Linguagem simples e direta
- Instruções claras e objetivas
- Mensagens de erro compreensíveis e construtivas
- Suporte a múltiplos idiomas (começando por português)

## 7. Plano de MVP

### 7.1. Telas Principais

**Tela 1: Onboarding**
- Boas-vindas e explicação simples do conceito
- Configuração inicial das contas
- Tutorial interativo básico

**Tela 2: Chat Principal**
- Interface de conversa limpa e acessível
- Campo de entrada de texto grande e visível
- Histórico de conversas recentes
- Botões de ação rápida (adicionar gasto, ver saldo)

**Tela 3: Dashboard**
- Visão geral das 4 contas
- Saldo atual de cada conta
- Resumo de gastos do mês
- Acesso rápido a relatórios

**Tela 4: Relatórios**
- Seleção de conta ou visão consolidada
- Gráficos simples de gastos por categoria
- Comparação mensal
- Exportação de dados

**Tela 5: Metas**
- Lista de metas ativas
- Progresso visual de cada meta
- Criação de novas metas via chat ou formulário simples

**Tela 6: Configurações**
- Preferências de acessibilidade
- Personalização das contas
- Ajustes de notificações
- Gerenciamento de dados

### 7.2. Recursos Técnicos Necessários

**Frontend**
- Framework responsivo e acessível (React, Vue ou similar)
- Biblioteca de componentes com suporte a acessibilidade
- Sistema de design consistente
- Armazenamento local para funcionamento offline

**Backend**
- API para processamento de linguagem natural
- Banco de dados para armazenamento de transações
- Sistema de classificação automática (ML básico ou baseado em regras)
- Geração de insights e recomendações

**Integrações**
- Serviço de NLP para entender comandos em português
- Sistema de notificações
- Backup e sincronização de dados (opcional no MVP)

### 7.3. Validação Inicial

**Fase 1: Protótipo e Testes de Usabilidade**
- Criar protótipo navegável de alta fidelidade
- Testar com 10-15 usuários do público-alvo
- Incluir usuários com diferentes necessidades de acessibilidade
- Coletar feedback sobre clareza, facilidade de uso e utilidade

**Fase 2: Beta Fechado**
- Desenvolver MVP funcional
- Convidar 50-100 usuários para teste por 30 dias
- Métricas de sucesso:
  - Taxa de engajamento (uso semanal)
  - Número de transações registradas
  - Satisfação do usuário (NPS)
  - Taxa de conclusão do onboarding
  - Feedback qualitativo sobre acessibilidade

**Fase 3: Ajustes e Lançamento**
- Implementar melhorias baseadas no feedback
- Realizar testes de acessibilidade formais
- Preparar documentação e tutoriais
- Lançamento público gradual

## 8. Métricas de Sucesso

### 8.1. Engajamento
- Usuários ativos semanais superior a 60%
- Média de 5+ transações registradas por semana
- Taxa de retenção de 30 dias acima de 40%

### 8.2. Usabilidade
- Taxa de conclusão do onboarding acima de 80%
- Tempo médio para registrar uma transação inferior a 30 segundos
- NPS (Net Promoter Score) acima de 40

### 8.3. Acessibilidade
- Conformidade WCAG 2.1 nível AA
- Feedback positivo de usuários com necessidades especiais
- Zero barreiras críticas identificadas em auditorias

## 9. Diferencial Competitivo

- Experiência conversacional natural em português
- Design Universal genuíno, não apenas requisitos mínimos de acessibilidade
- Foco em simplicidade sem sacrificar funcionalidade
- Agente financeiro educativo e motivador
- Suporte a múltiplas contas de forma intuitiva

## 10. Roadmap Futuro (Pós-MVP)

- Integração com bancos e cartões de crédito
- Reconhecimento de voz aprimorado
- Categorias personalizadas
- Compartilhamento de metas em família
- Versão desktop
- Insights mais avançados com IA
- Suporte a moedas internacionais
- Gamificação de metas financeiras

## 11. Considerações Finais

Este PRD prioriza a criação de uma ferramenta verdadeiramente inclusiva e acessível, que respeita a diversidade de seus usuários. O sucesso do produto será medido não apenas pela adoção, mas pela capacidade de empoderar pessoas de todos os perfis a tomarem controle de suas finanças pessoais de forma sustentável e positiva.

A implementação deve ser iterativa, com testes constantes de usabilidade e acessibilidade em cada etapa do desenvolvimento.



Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

## Prints ou pequenos vídeos das interações com a IA;
  Crie um app sobre finanças pessoais com base no seguinte PRD (Product Requirements Document)
  Gostaria que a criação parecesse com um APP com tela de validação e senha, senti também a ausência de uma área para extratos e graficos, você poderia consertar o código para que ficasse como necessito?
  
Resultado:
https://papo-facil-dinheiro.lovable.app
-  <img width="752" height="596" alt="image" src="https://github.com/user-attachments/assets/d8335a2c-2ceb-44f6-bc74-a80bd1d0b05b" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
    Controla as finanças pessoais em 4 contas principais que podem ser mudadas de nome Pensei em conta principal ou seja uma conta do banco onde faço meus movimentos, conta 2 conta de investimentos, conta 3 conta de metas e a conta 4 deixada como um coringa. Futuramente fazer a integração da conta 1 com a importação de arquivos ofx disponiveis no banco para se ter um melhor controle financeiro. Um ícone criado para saldos constando as 4 contas outro ícone criado para os relatórios e graficos e um ícone de configuração para que possa ser mudado o nome das contas, conforme na figura acima.

#### Resumo copilot.
🌟 FinChat — Suas Finanças em Conversa
✨ O que é?
FinChat é um aplicativo de controle financeiro pessoal que transforma o jeito de lidar com dinheiro: simples, acessível e baseado em conversas naturais. Sem planilhas, sem complicações — apenas você e seu assistente financeiro conversando sobre sua vida financeira.

💬 Como Funciona?
Interface de chat intuitiva em português

Registro de gastos com frases como: “Gastei 50 no mercado”

Confirmação visual clara e motivacional

Categorias automáticas e contas personalizadas

🧠 Inteligência que Ajuda
Agente financeiro com IA que analisa seus hábitos

Dicas personalizadas para economizar

Metas financeiras com acompanhamento visual

Relatórios simples e acessíveis

📱 Exemplo Real
Entrada R$ 1.000,00 Descrição: 1000 de salário na conta principal Categoria: Outros Conta: Conta Principal Horário: 08:59 💬 “Ótimo! Continue assim para alcançar suas metas!”

🧭 Navegação Simples
🗨️ Chat

📊 Dashboard

📄 Extrato

🎯 Metas

⚙️ Ajustes

♿ Design Universal
FinChat foi criado para todos, com base nos 7 princípios do Design Universal:

Uso simples e intuitivo

Baixo esforço físico

Informações perceptíveis

Compatível com leitores de tela

Fontes ajustáveis e modo escuro

Navegação por teclado e toque acessível

🚀 MVP em Ação
Onboarding interativo

Chat principal com histórico

Dashboard com visão geral

Relatórios por conta e consolidados

Metas visuais e motivadoras

Configurações acessíveis

📈 Métricas de Sucesso
+60% de usuários ativos semanais

+5 transações por semana por usuário

NPS acima de 40

Conformidade WCAG 2.1 AA

🏆 Diferenciais
Experiência conversacional natural em português

Design inclusivo de verdade

Agente financeiro educativo e motivador

Suporte a múltiplas contas com simplicidade

🔮 Futuro Promissor
Integração com bancos e cartões

Reconhecimento de voz

Compartilhamento de metas

Versão desktop

Gamificação e insights avançados

FinChat é mais do que um app — é um parceiro para transformar sua relação com o dinheiro. Simples, acessível e inteligente.

### Uma breve **reflexão sobre o processo**:
   Gostei muito de ter aprendido a trabalhar com vibe code. Sem um pingo de conhecimento técnico poder montar um app foi o máximo. 
### funcionou bem?
    Sim, mas como relatei vou utilizar os créditos diários para ir aprimorando o app
### O que não funcionou como o esperado?
   No inicio ele não criou uma tela de login corrigido com uma interação, corrigido o erro acabaram-se os creditos. 
### O que aprendeu sobre conversar com IAs?
 tudo é muito acessivel dinamico e rápido, muito interessante.
> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
