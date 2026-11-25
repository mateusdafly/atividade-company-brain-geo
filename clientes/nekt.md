# Nekt

> **Empresa real.** Este dossiê foi montado só com **informação pública**, lida em **2026-11-25** nas páginas listadas no fim. Sites mudam: **leia de novo as páginas antes de usar qualquer dado** e registre a data da sua leitura.

## Em uma frase

A Nekt se descreve como **uma plataforma de contexto para agentes de IA**: conecta as fontes de dados de uma empresa, organiza e governa esses dados, e entrega tudo a agentes (Claude, ChatGPT e outros) por um servidor MCP, além de SQL e API.

## Como ela se descreve

A empresa usa **duas formulações** em páginas diferentes. As duas são dela:

| Formulação | Onde aparece |
|---|---|
| "A plataforma de contexto para agentes de IA" | Home em português (`nekt.com/pt`) e FAQ |
| "The data platform for AI agents" | `llms.txt` do site, em inglês |

Escolher como descrever a Nekt nos artigos é uma decisão sua. Registre a escolha no Brain.

## O que a Nekt faz (segundo o próprio site)

Em três etapas, que a home chama de **"Conecte. Governe. Sirva."**

| Etapa | O que o site diz |
|---|---|
| **Conecte** | "300+ conectores": SaaS, bancos de dados, planilhas, webhooks. Dá para configurar no app ou pedir ao agente, pelo chat. |
| **Governe** | Transformar com SQL, Python ou PySpark; camadas (a home mostra **Raw, Trusted e Service**); permissões, histórico e linhagem; um **context graph** onde se registra o que cada métrica significa. |
| **Sirva** | **Servidor MCP**, **Data API**, SQL e destinos nativos; envio de dados de volta a CRM e plataformas de anúncio. |

Casos de uso listados no menu do site: relatórios e análises; atendimento ao cliente com IA; relatórios automatizados; análise histórica e preditiva; performance e ativação de marketing.

## Onde os dados ficam

- Por padrão, na **Nekt Cloud**, "então você não precisa ter um data warehouse próprio" (FAQ).
- O FAQ diz que a Nekt "pode rodar na sua própria conta GCP ou AWS". A página de planos lista "Traga sua própria nuvem (BYOC)" **dentro do plano Growth**. Confira se as duas páginas dizem a mesma coisa.
- Depois de cancelar, os dados ficam disponíveis para exportação por **90 dias** (FAQ).

## Planos e preços públicos (leitura de 2026-11-25)

| Plano | Preço | O que o site destaca |
|---|---|---|
| Free | R$ 0 por mês | Usuários ilimitados, context graph, MCP Gateway, warehouse gerenciado, 3 fontes e 3 destinos, 1 workspace ativo |
| Starter | A partir de R$ 375 por mês | Tudo do Free, mais fontes e destinos ilimitados, Platform API e Data API, versionamento no GitHub, 7 dias de logs de auditoria |
| Growth | A partir de R$ 2.495 por mês | Tudo do Starter, mais permissões no nível dos dados, tokens com escopo por agente, BYOC, MFA, 30 dias de logs |
| Enterprise | Sob consulta | Tudo do Growth, mais SSO, migração feita pela Nekt, SLAs e suporte dedicado |

- **Cobrança por créditos:** "um crédito é uma execução de pipeline"; execuções com falha não contam (FAQ e página de planos).
- A página tem **simulador de limites** (runs, processamento, dados lidos, armazenamento). Os valores acima são "a partir de" e **mudam com o simulador**.
- **Todo preço entra no artigo com a data da leitura.**

## O que a Nekt diz que substitui (e que não substitui)

Segundo o FAQ:

- **Substitui:** ferramentas de ingestão (cita Fivetran e Airbyte), o orquestrador (cita Airflow), o data warehouse (BigQuery, Snowflake, Redshift) e o reverse ETL (Hightouch, Census).
- **Não substitui:** ferramentas de BI (Looker Studio, Metabase, Power BI) nem de automação como o n8n. "Ela alimenta todas elas."

Isso é o que **a Nekt diz** sobre produtos de terceiros. Qualquer comparação nos artigos exige conferir o que cada um deles faz, em fonte própria e com data.

## Para quem vende

O site fala com times de dados e com times de negócio que querem dar aos agentes de IA dados confiáveis e definições de métricas (receita, clientes ativos, funil). Os exemplos da home são de receita, marketing e customer success. Quem está no seu perfil de público, em que momento e com que dúvida é **tarefa sua** (Brain, `02-publico.md`).

## O que a Nekt afirma sobre si (auto-declarado)

Tudo aqui é **a Nekt falando de si**. Nos artigos, só como "segundo a Nekt", com data. Não trate como fato verificado.

| Afirmação | Onde | Cuidado |
|---|---|---|
| "300+ conectores" | Home, FAQ | O número pode variar entre páginas e a documentação. Compare e registre a divergência, se houver. |
| "SOC 2 Type II compliant" | `llms.txt`, que aponta para `nekt.com/soc2` | Leia a página `/soc2` e use a formulação exata dela. |
| Demonstrações na home (ex.: "US$ 42.180 em novo MRR em setembro") | Home | **Dados de exemplo da demonstração**, com empresas fictícias na tela. Não são resultado de cliente. |
| "A confiança de empresas em crescimento no mundo todo" | Home | Faixa de logos. Logo na home **não é** caso publicado. Só cite cliente que tenha fonte pública própria. |

## Cuidado com a identidade

Há outras empresas com nome parecido (por exemplo, uma plataforma de vendas chamada Nektar). **Pesquise e registre no Brain quais são, e como evitar a confusão** em um artigo que seja lido por uma IA.

## O que o site não resolve (trate como hipótese até achar fonte)

- Quantos clientes a Nekt tem e quem pode ser citado.
- Origem e tamanho da empresa: o site e o cadastro oficial podem não contar a mesma história. **Pesquise antes de afirmar** que é brasileira, americana ou outra coisa.
- Desempenho (tempo de resposta, volume máximo) fora dos exemplos da home.
- Roteiro de produto (o que vem depois).
- Preço de Enterprise.

## O que você precisa pesquisar

- O que é, de fato, uma "plataforma de contexto" ou "context layer", e como difere de data warehouse, ETL, catálogo de dados, camada semântica e RAG.
- O que é MCP, e o que significa um agente "ler e escrever" dados por um servidor MCP.
- Que perguntas um time de dados ou de RevOps faz antes de dar acesso de dados da empresa a um agente de IA.
- O que Fivetran, Airbyte, Airflow, Hightouch e Census **realmente** fazem (fonte e data), se você for comparar.
- O que a documentação (`docs.nekt.com`) diz que o site não diz.

## Fontes lidas em 2026-11-25

- Home em português: https://www.nekt.com/pt
- Planos: https://www.nekt.com/pt/pricing
- Suporte e FAQ: https://www.nekt.com/pt/support
- `llms.txt`: https://www.nekt.com/llms.txt
- Documentação: https://docs.nekt.com
