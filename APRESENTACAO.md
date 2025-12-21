# Roteiro de Apresentação - SigTicket
Data: 20/12/2025
## Informações
**Grupo:** [Nome do Grupo]
**Membros:**
- [Vitor Mendes] - [Papel]
- [Jonatha Souza] - [Papel]
- [Roney Menezes] - [Papel]
- [Misael farias] - [Papel]
- [Vinícius Emílio] - [Papel]
**Tempo:** 10 minutos
---
## Estrutura da Apresentação
### 1. Introdução (1 min)
**Apresentador:** [Jonatha]

UNIVERSIDADE FEDERAL RURAL DA AMAZÔNIA
CAMPUS SANTA IZABEL / SISTEMAS DE INFORMAÇÃO 2025.2
ENGENHARIA DE SOFTWARE II – Prof. Fabrício Almeida Araújo

**Pontos:**
- Nome do projeto: SigTicket
- Objetivo: Sistema de gerenciamento de tickets
- Contexto: Sistema legado que recebeu manutenção
---
### 2. Sistema Original (1 min)
**Apresentador:** []
**Pontos:**
- Funcionalidades básicas (criar, listar)
- Problemas identificados na auditoria
- 5 Issues abertas
**Slide/Demo:**
- Mostrar board Kanban inicial
---
### 3. Correções de Bugs (2 min)
**Apresentador:** [Vitor]
**Bug #1: Validação de Status**
- Problema: Aceitava qualquer texto
- Solução: Lista de status válidos
- Demo: Mostrar funcionando
**Bug #2: Validação de Data**
- Problema: Aceitava qualquer texto
- Solução: Validação formato DD/MM/AAAA, regras de negócio
- Demo: Mostrar funcionando
---
### 4. Refatorações (2 min)
**Apresentador:** [Vinícius]
**Issue #3: Senha Hardcoded**
- Problema: Senha no código (inseguro)
- Solução: Arquivo config.py
- Demo: Mostrar config.py
**Issue #4: .gitignore**
- Problema: Arquivos desnecessários versionados

UNIVERSIDADE FEDERAL RURAL DA AMAZÔNIA
CAMPUS SANTA IZABEL / SISTEMAS DE INFORMAÇÃO 2025.2
ENGENHARIA DE SOFTWARE II – Prof. Fabrício Almeida Araújo

- Solução: .gitignore completo
**Issue #5: README**
- Problema: Documentação incompleta
- Solução: README detalhado
- Demo: Mostrar README
---
### 5. Code Review e Melhorias (1 min)
**Apresentador:** [Jonatha]
**Pontos:**
- Code review do Grupo [X]
- Melhorias implementadas
- Aprendizado com outros grupos
---
### 6. Documentação Final (2 min)
**Apresentador:** [Roney]
**Pontos:**
- DOCS.md: Documentação técnica completa
- CHANGELOG.md: Histórico de versões
- Comentários no código
- Versão final: 1.0.0
**Demo:**
- Mostrar estrutura do projeto
- Mostrar exemplo de função documentada
---
### 7. Conclusão (1 min)
**Apresentador:** [Todos]
**Pontos:**
- Resultados alcançados
- Aprendizados principais
- Trabalho em equipe
- Agradecimentos
---

UNIVERSIDADE FEDERAL RURAL DA AMAZÔNIA
CAMPUS SANTA IZABEL / SISTEMAS DE INFORMAÇÃO 2025.2
ENGENHARIA DE SOFTWARE II – Prof. Fabrício Almeida Araújo

## Divisão de Responsabilidades
**[Nome 1]:**
- Preparar introdução
- Conduzir demo do sistema funcionando
**[Nome 2]:**
- Apresentar correções de bugs
- Demo das validações
**[Nome 3]:**
- Apresentar refatorações
- Mostrar config.py e README
**[Nome 4]:**
- Apresentar documentação final
- Mostrar código comentado
---
## Checklist Pré-Apresentação
- [x] Testar sistema antes da apresentação
- [x] Abrir repositório GitHub em aba
- [x] Abrir Codespace pronto para demo
- [x] README.md aberto em aba
- [x] DOCS.md aberto em aba
- [x] Board Kanban aberto em aba
- [x] Cronometrar tempo (máximo 10 min)
- [x] Todos revisaram o que vão falar
- [x] Backup: ter prints caso internet falhe
---
## Demonstração ao Vivo
**Ordem da demo:**
1. **Login**
- Mostrar autenticação funcionando
- Tentar senha errada (mostra validação)
2. **Criar Ticket com Validações**
- Tentar data inválida (mostra erro)
- Tentar data futura (mostra erro)
- Criar com data válida (sucesso)
3. **Listar Tickets**

UNIVERSIDADE FEDERAL RURAL DA AMAZÔNIA
CAMPUS SANTA IZABEL / SISTEMAS DE INFORMAÇÃO 2025.2
ENGENHARIA DE SOFTWARE II – Prof. Fabrício Almeida Araújo

- Mostrar tickets cadastrados
4. **Mudar Status com Validação**
- Tentar status inválido (mostra erro)
- Mudar para status válido (sucesso)
5. **Mostrar Código**
- Função com comentários
- Docstring exemplo
- config.py
**Tempo estimado da demo:** 3-4 minutos
---
## Falas Sugeridas
### Abertura
&quot;Bom dia/Boa tarde! Somos o grupo [X] e vamos apresentar o projeto SigTicket,
um sistema de gerenciamento de tickets que evoluímos durante esta semana.&quot;
### Transição para Demo
&quot;Agora vamos demonstrar o sistema funcionando, mostrando as validações
que implementamos...&quot;
### Encerramento
&quot;Concluindo, conseguimos evoluir um sistema legado, corrigir bugs críticos,
refatorar o código e documentar completamente o projeto. Obrigado pela
atenção!&quot;
---
## Perguntas Possíveis
**P: Por que escolheram arquivo config.py em vez de banco de dados?**
R: Para manter a simplicidade do projeto e focar em boas práticas de
organização de código. Em produção, usaríamos banco de dados.
**P: O sistema persiste os dados?**
R: Não, atualmente os dados são armazenados em memória. É uma limitação
conhecida e está documentada como melhoria futura no DOCS.md.
**P: Como foi trabalhar em equipe?**

UNIVERSIDADE FEDERAL RURAL DA AMAZÔNIA
CAMPUS SANTA IZABEL / SISTEMAS DE INFORMAÇÃO 2025.2
ENGENHARIA DE SOFTWARE II – Prof. Fabrício Almeida Araújo

R: [Resposta do grupo sobre organização, dificuldades, aprendizados]
---