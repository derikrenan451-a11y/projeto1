# Sistema de Monitoramento de Segurança para Ambientes Comerciais

## Visão geral

Este projeto apresenta um MVP (Minimum Viable Product) para um sistema de monitoramento de câmeras de segurança voltado para ambientes comerciais, com foco em lojas, pequenos comércios e estabelecimentos que precisam aumentar a proteção do local, controlar acessos e responder rapidamente a incidentes.

A solução foi pensada para validar a proposta de valor de um sistema que combina:

- monitoramento visual de câmeras;
- autenticação privada por usuário;
- controle de acesso ao painel administrativo;
- botão de pânico para acionamento de emergência;
- mapeamento por satélite para localização do local;
- melhor segurança e resposta em situações críticas.

## Objetivo do MVP

O objetivo principal do MVP é demonstrar que é possível criar uma solução funcional para proteger ambientes comerciais, reduzir riscos e permitir respostas imediatas em caso de incidentes.

A ideia central é oferecer uma base simples, eficiente e segura para:

- acompanhar o ambiente em tempo real;
- controlar quem acessa o sistema;
- reagir rapidamente em situações de emergência;
- identificar o local exato do risco;
- aumentar a segurança e a confiança do gestor ou proprietário.

## Dor que o produto resolve

Estabelecimentos comerciais frequentemente sofrem com:

- ausência de um monitoramento eficiente;
- dificuldades para controlar acessos ao sistema;
- demora na identificação de ameaças ou ocorrências;
- baixa capacidade de resposta rápida em incidentes;
- vulnerabilidade do ambiente diante de ações indevidas.

Este MVP busca reduzir esses riscos com uma solução prática, acessível e voltada para segurança e operacionalidade.

## Público-alvo

O público principal são:

- pequenos e médios comércios;
- lojas de varejo;
- negócios com fluxo constante de clientes e colaboradores;
- gestores e proprietários que buscam mais segurança;
- empresas interessadas em monitoramento e resposta rápida.

## Diferencial da solução

O diferencial do projeto está na combinação de:

- autenticação por usuário;
- monitoramento visual;
- botão de pânico;
- identificação do local por mapeamento geográfico;
- foco em segurança comercial e proteção do ambiente.

## Arquitetura do projeto

A arquitetura do MVP pode ser organizada em camadas:

### 1. Camada de apresentação
Responsável pela interface do sistema, incluindo:

- login;
- dashboard principal;
- painel de monitoramento;
- botão de emergência;
- mapeamento do local.

### 2. Camada de autenticação
Responsável por:

- controle de acesso;
- cadastro de usuários;
- permissões por perfil;
- segurança de sessão.

### 3. Camada de monitoramento
Responsável por:

- visualização de câmeras;
- acompanhamento dos pontos monitorados;
- análise do ambiente em tempo real.

### 4. Camada de alerta e resposta
Responsável por:

- acionamento do botão de pânico;
- registro de incidentes;
- notificação de resposta;
- suporte à tomada de decisão rápida.

### 5. Camada de localização
Responsável por:

- geolocalização do local;
- mapeamento por satélite;
- contextualização da ocorrência.

### 6. Camada de dados
Responsável por armazenar:

- usuários;
- acessos e permissões;
- registros de eventos;
- histórico de incidentes.

## Funcionalidades do MVP

- Login privado para usuários autorizados;
- autenticação segura do painel;
- controle de acesso por perfil;
- visualização de câmeras e monitoramento;
- botão de emergência para sinalizar risco;
- identificação do local por mapeamento geográfico;
- gestão básica de usuários;
- interface simples e funcional.

## Escopo do MVP

Este MVP incluirá funcionalidades essenciais para validar a ideia no mercado. Funcionalidades mais avançadas, como inteligência artificial, automação de alertas e integrações com autoridades, podem ser planejadas para versões futuras.

## Estrutura do repositório

```text
.
├── app/
│   ├── cenario-blue-team_app_config.env
│   └── cenario-blue-team_app_loja_login.py
├── docs/
│   ├── cenario-blue-team_docs_alerta-monitoramento.txt
│   └── cenario-blue-team_docs_inventario-ativos.md
├── entregas/
│   └── cenario-blue-team_entregas_RELATORIO-INCIDENTE.md
├── infra/
│   └── cenario-blue-team_infra_nginx.conf
├── logs/
├── contexto.md
├── dor.md
├── sprint.md
├── README.md
└── LICENSE
```

## Principais arquivos

- `contexto.md`: contexto geral do projeto, público-alvo, cenário e proposta de valor.
- `dor.md`: descrição da dor e do problema que o MVP resolve.
- `sprint.md`: planejamento completo do desenvolvimento, desde a ideação até a entrega do MVP.
- `app/cenario-blue-team_app_loja_login.py`: exemplo de aplicação de login utilizada como base de análise e referência técnica.

## Como executar o projeto

Este repositório contém arquivos de documentação e um exemplo de aplicação de login. Para rodar a aplicação Python localmente:

```bash
cd /home/seginf/Área de trabalho/Cenario
python3 app/cenario-blue-team_app_loja_login.py
```

Para executar a demonstração automática do login:

```bash
cd /home/seginf/Área de trabalho/Cenario
python3 app/cenario-blue-team_app_loja_login.py --demo
```

## Tecnologias e ferramentas

- Python 3
- Git e GitHub
- documentação em Markdown
- estrutura de projeto para MVP
- arquitetura orientada a módulos e camadas

## Equipe

- Klerik
- Rawan
- Luciano
- Rennan

## Roadmap

### Fase 1: Ideação
- definir a dor e o problema;
- validar a oportunidade de mercado;
- mapear o público-alvo.

### Fase 2: Definição do MVP
- priorizar funcionalidades essenciais;
- confirmar escopo da primeira versão;
- estruturar a solução.

### Fase 3: Desenvolvimento
- autenticação e usuários;
- painel principal;
- botão de pânico;
- mapeamento e localização.

### Fase 4: Validação
- testar fluxos principais;
- corrigir falhas;
- preparar entrega final.

## Conclusão

Este projeto representa uma proposta de MVP para um sistema de monitoramento e segurança comercial, com foco em proteção, resposta rápida e controle de acesso. A solução busca resolver uma dor real de negócios que precisam de maior segurança no ambiente, alinhando tecnologia, praticidade e resposta operacional.

O objetivo do MVP é validar a ideia, demonstrar o valor do produto e preparar a base para evoluções futuras em um sistema mais robusto e completo.

## Contato e apresentação

Este repositório foi organizado para servir como base de documentação, estudo e apresentação do MVP. O material pode ser expandido conforme a solução evolui.
