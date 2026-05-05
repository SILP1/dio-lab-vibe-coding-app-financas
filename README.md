# 💸 Saúde Financeira App

Aplicativo conversacional que ajuda pessoas a cuidarem da sua saúde financeira de forma prática e acessível. Substitui planilhas e formulários por uma experiência de chat com um agente financeiro inteligente.

🔗 **Demo:** [saudefinanceiraapp.lovable.app](https://saudefinanceiraapp.lovable.app)

---

## O que o App Faz

- **Registrar gastos via conversa** em linguagem natural
- **Classificar automaticamente transações** em categorias
- **Definir e acompanhar metas financeiras:**
  - Para quem está no negativo: foco em corte de gastos desnecessários
  - Para quem está no positivo: foco em planos futuros e investimentos
- **Receber dicas personalizadas** do Agente Financeiro
- **Visualizar relatórios simples**, incluindo gráficos de pizza para distribuição dos investimentos

### Benefícios

- **Praticidade** — registrar gastos sem esforço
- **Clareza** — relatórios visuais fáceis de entender
- **Motivação** — metas adaptadas à realidade financeira
- **Evolução** — jornada do controle básico até investimentos

### Roadmap Futuro

- Integração com bancos e corretoras
- Relatórios avançados de rentabilidade
- Gamificação: conquistas por metas atingidas (ex.: "Você saiu do vermelho!", "Primeiro investimento realizado!")
- Educação financeira progressiva: conteúdos que evoluem conforme o usuário avança

---

## PRD

> Documento refinado com auxílio do GitHub Copilot

```markdown
# PRD - Aplicativo de Saúde Financeira

## Contexto
Quero criar um aplicativo de Saúde Financeira que funcione por meio de conversas com o
usuário. A ideia é facilitar o controle financeiro de forma simples e natural, sem
formulários manuais ou planilhas complexas.

## Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita
entrada manual e pouca personalização. Quero resolver isso com uma experiência de
conversa e recomendações automáticas de economia.

## Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação,
principalmente iniciantes.

## Funcionalidades-Chave
- Registrar gastos via chat em linguagem natural
- Classificar automaticamente as transações
- Definir e acompanhar metas financeiras para quem está no negativo: foco em corte de
  gastos desnecessários
- Definir e acompanhar metas financeiras para quem está no positivo: foco em planos para
  o futuro e investimentos
- Receber dicas de economia do "Agente Financeiro"
- Visualizar relatórios simples e personalizados, incluindo gráfico de pizza nos
  investimentos

## Plano de MVP

### Principais Telas
- Tela de Conversa: interação com o Agente Financeiro
- Tela de Metas: duas modalidades — sair do negativo (redução de gastos) e planejar o
  futuro (investimentos)
- Tela de Relatórios: gráficos simples, incluindo pizza para distribuição dos
  investimentos
- Tela de Configurações: perfil e preferências

### Recursos Necessários
- Processamento de linguagem natural
- Motor de classificação automática
- Banco de dados para transações e metas
- Visualizações gráficas (pizza e linha)
- Agente Financeiro com linguagem educativa

### Validação Inicial
- Teste com usuários em diferentes situações (negativo e positivo)
- Métricas: facilidade de uso, clareza das metas, utilidade dos relatórios
- Iteração rápida com base em feedback

## Roadmap Futuro
- Integração com bancos e corretoras
- Relatórios avançados de rentabilidade
- Gamificação: conquistas por metas atingidas (ex.: "Você saiu do vermelho!",
  "Primeiro investimento realizado!")
```

---

## Interações com as IAs

### GitHub Copilot — Refinamento do PRD

<img width="949" alt="Conversa Copilot 1" src="https://github.com/user-attachments/assets/5a752c24-afd7-404a-b09c-e28fed62faff" />

<img width="842" alt="Conversa Copilot 2" src="https://github.com/user-attachments/assets/80a9612c-f6ee-4e15-9efa-e88d4b5a9a8f" />

### Lovable — Construção do App

Prompts utilizados:

1. `Quero criar um aplicativo de Saúde Financeira que funcione por meio de conversas com o usuário.`
2. `Implementar um onboarding guiado no primeiro acesso para eu definir meu objetivo e preferências antes de começar a registrar gastos no chat.`
3. `Melhorar o classificador para respeitar minhas categorias preferidas e sugerir novas categorias quando eu registrar despesas diferentes.`

<img width="1740" alt="Conversa Lovable 1" src="https://github.com/user-attachments/assets/7581b4e1-29c3-4c92-ba6d-9cfb9d03f66b" />

<img width="2513" alt="Conversa Lovable 2" src="https://github.com/user-attachments/assets/af0c7eca-fbac-4a8b-b6e2-3af5f36961a6" />

---

## Reflexão sobre o Processo

### O que funcionou bem

- Organizar o PRD em seções facilitou a compreensão
- Iterações como mudar para "Saúde Financeira" e incluir o gráfico de pizza foram incorporadas de forma ágil
- Diferenciar usuários em "negativo" e "positivo" trouxe valor e deixou o app mais próximo da realidade das pessoas

### O que não funcionou como o esperado

- Algumas partes do detalhamento inicial estavam genéricas e precisaram ser refinadas (ex.: público-alvo, relatórios visuais)
- Ainda falta pensar em como testar com usuários reais para confirmar se a experiência conversacional realmente substitui planilhas
- Faltou crédito no Lovable para concluir o projeto

### O que aprendi sobre conversar com IAs

- Iteração com a IA ajuda a construir e refinar ideias passo a passo
- Quanto mais específico o comando, mais útil e preciso o resultado
- É possível solicitar sugestões e colaborar com a IA ao longo do projeto

