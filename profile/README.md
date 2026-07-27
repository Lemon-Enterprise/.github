# Lemon-Enterprise

> Tecnologia, design e experiências digitais construídas com propósito.

## Visão geral

A **Lemon-Enterprise** é a marca responsável pela criação de produtos, ferramentas e experiências digitais do ecossistema Lemon. Unimos engenharia de software, design de produto e criatividade para transformar ideias em soluções úteis, consistentes e memoráveis.

Este repositório representa a base técnica da **Lemon Studio Framework**, um dos produtos do ecossistema. A empresa trabalha com uma visão simples: tecnologia deve ser poderosa para quem constrói e agradável para quem usa.

## Propósito

Criar produtos digitais claros, acessíveis e duráveis, capazes de ajudar pessoas e equipes a explorarem suas ideias com mais liberdade.

## Missão, visão e valores

| Pilar | Compromisso |
| --- | --- |
| **Missão** | Transformar problemas reais em experiências digitais de alta qualidade. |
| **Visão** | Ser uma referência em produtos independentes, criativos e tecnicamente excelentes. |
| **Qualidade** | Preferimos soluções simples, bem pensadas e sustentáveis. |
| **Criatividade** | Tecnologia e design são partes da mesma conversa. |
| **Autonomia** | Criamos ferramentas que dão mais poder a quem cria. |
| **Evolução** | Aprendemos, iteramos e melhoramos continuamente. |

## Ecossistema Lemon

```text
Lemon-Enterprise
├── Lemon Studio Framework
│   └── Framework modular para jogos 2D em Lua e LÖVE
├── Lemon Studio
│   └── Espaço de criação, prototipagem e experiências interativas
└── Próximos produtos
    └── Ferramentas, jogos e produtos digitais em desenvolvimento
```

### Lemon Studio Framework

Uma framework modular para desenvolvimento de jogos 2D em Lua com LÖVE. Ela inclui gerenciamento de cenas, câmera, entrada, física, animações, áudio, interface, persistência, entidades e linha de comando.

- API pública consistente com o prefixo `LS`.
- Arquitetura modular, sem dependências externas.
- Licença Apache-2.0.
- CLI local: `lemon new meu-jogo`.

Consulte a documentação técnica em [README.md](README.md).

## Como trabalhamos

### 1. Entendemos o problema

Antes de escrever código, definimos o objetivo, o público, o contexto e o resultado que torna o produto útil.

### 2. Prototipamos cedo

Exploramos rapidamente ideias de interação, interface e tecnologia. Protótipos existem para reduzir incertezas, não para esconder decisões.

### 3. Construímos com intenção

Cada componente deve ter uma responsabilidade clara, nomes compreensíveis e espaço para evoluir. A simplicidade é uma escolha de arquitetura.

### 4. Testamos a experiência

Validamos não apenas se algo funciona, mas se é compreensível, fluido e agradável de usar.

### 5. Evoluímos publicamente

Documentação, mudanças e decisões devem ser claras para quem usa, mantém ou contribui com os produtos Lemon.

## Padrões de produto

| Área | Diretriz |
| --- | --- |
| **Experiência** | Interfaces devem priorizar clareza, retorno imediato e acessibilidade. |
| **Design** | Cada detalhe visual precisa reforçar a função, não competir com ela. |
| **Engenharia** | Código modular, documentação objetiva e dependências conscientes. |
| **Desempenho** | O produto deve ser rápido no uso cotidiano, inclusive em máquinas modestas. |
| **Privacidade** | Coletar apenas o necessário e comunicar isso de forma transparente. |
| **Sustentação** | Preferir soluções que possam ser mantidas e entendidas no futuro. |

## Tecnologias e áreas de atuação

A Lemon-Enterprise explora e desenvolve soluções nas seguintes áreas:

- Jogos e experiências 2D interativas.
- Ferramentas para criadores e desenvolvedores.
- Produtos web e interfaces de produto.
- Automação, prototipagem e sistemas criativos.
- Design de interação e identidade visual digital.
- Frameworks, bibliotecas e utilitários open source.

As tecnologias são escolhidas pelo contexto do produto. No caso da Lemon Studio Framework, a base é **Lua + LÖVE 11.5+**.

## Estrutura deste repositório

```text
LemonStudioFramework/
├── lemon/                 # Módulos da Lemon Studio Framework
├── tools/                 # Ferramentas da CLI lemon
├── main.lua               # Demonstração jogável
├── conf.lua               # Configuração do LÖVE
├── lemon.bat              # Atalho da CLI para Windows
├── index.html             # Website institucional da framework
├── README.md              # Documentação técnica da framework
├── LEMON-ENTERPRISE-README.md
└── LICENSE                # Apache-2.0
```

## Início rápido

### Executar a demonstração

Instale o [LÖVE](https://love2d.org/) 11.5 ou superior e, na raiz deste repositório, execute:

```text
love .
```

No Windows, você também pode usar:

```text
.\lemon run
```

### Criar um jogo novo

```text
.\lemon new meu-jogo
cd meu-jogo
love .
```

## Contribuições

Contribuições são bem-vindas quando melhoram a clareza, a estabilidade ou a utilidade dos produtos Lemon.

Antes de propor uma mudança:

1. Descreva o problema que a alteração resolve.
2. Mantenha a API pública consistente com a convenção `LS`.
3. Atualize a documentação quando o comportamento mudar.
4. Prefira mudanças pequenas, objetivas e fáceis de revisar.
5. Preserve a compatibilidade sempre que for possível.

## Licença

Este projeto é distribuído sob a licença [Apache-2.0](LICENSE).

## Contato e presença

Os canais públicos da Lemon-Enterprise podem ser incluídos aqui quando estiverem definidos:

| Canal | Endereço |
| --- | --- |
| Website | Em breve |
| E-mail | Em breve |
| Comunidade | Em breve |
| Redes sociais | Em breve |

---

**Lemon-Enterprise** — construindo tecnologia com clareza, personalidade e propósito.
