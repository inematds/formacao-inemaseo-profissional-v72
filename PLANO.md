# PLANO — inemaSEO 6 · Profissional: vender e entregar SEO + IA como serviço de confiança (v7.2)

Curso 6 de 7 da Formação inemaSEO. Público: freelancer, agência ou consultor (EN: "freelancers, agencies and consultants who want to sell and deliver SEO + AI visibility services honestly"). `lado_card` → curso 7 `formacao-inemaseo-sistemas-v72`. `sub` "Formação inemaSEO · curso 6 de 7".

Visão (Profissional 2030, eventos.inema.pro/prof2030): **construir ficou fácil, confiar não**. O profissional vende diagnóstico, plano, acompanhamento medido e ensino — não "posição 1" nem "500 artigos". Ponte: Formação Vendas com IA (curso 2, Consultoria).

Fontes (não alteradas): `~/projetos/inemaseo-metodo` (METODO "máquina com agentes", "Plano B"; CHECKLIST; `tools/auditoria.sh`), `~/projetos/inemaseo` (`docs/ESTRATEGIA_REFERENCIA_ECOSSISTEMA.md` §4 roadmap e "O que NÃO fazer"; `docs/PLANO_EXECUCAO_SEO.md` §7, §8, anexo D; `scripts/gsc_relatorio_semanal.py`; `reports/semana-2026-10-11.md`; `reports/baseline-2026-09-23.md`), `~/projetos/aiv2026/playbook-aeo-geo.md` (F0, F4, "Resumo comercial"), `~/projetos/inemaseo-sistemas` (auditor, agente-ready e `exemplos/` de 19/10/2026), `~/projetos/prospector-agent/README.md`, área prof2030, pesquisa `wifi/longrun/2026-10-19-formacao-inemaseo-v72/` (TENDENCIAS §7 e item 13; REVISAO §4.2). Números do INEMA só da lista "Casos reais" do BRIEF (mais os exemplos reais do inemaseo-sistemas, autorizados como modelo de relatório).

## As 8 aulas

| # | slug | aula | objetivo (≤ 160) | diagrama | prática ("pronto quando") | fonte |
|---|---|---|---|---|---|---|
| 1 | `o-que-vender` | O que vender: resultado medido sem marca, não "rank #1" | separar o que o cliente pede do que dá para entregar e medir, e escrever a sua oferta de diagnóstico, plano, acompanhamento e ensino | pedido do cliente → promessa que não se cumpre → o que se vende (4 entregas) → como se prova (número sem marca) | 1) posicionamento de 2 linhas sem ferramenta e com o que você não faz; 2) 5 promessas trocadas por entregas medíveis | REVISAO §4.2; ESTRATEGIA "O que NÃO fazer"; TENDENCIAS §7; prof2030; §2.2 |
| 2 | `diagnostico` | Diagnóstico: HTML entregue, prontidão e perguntas nas IAs | montar o diagnóstico de um site em três partes (HTML entregue, prontidão para IA, perguntas neutras nas IAs) e apresentá-lo numa call | call → raio-x (auditoria.sh / auditor) → prontidão (agente-ready) → bateria manual → relatório de 1 página | 1) auditor + agente-ready num site seu (ou autorizado), 3 achados priorizados; 2) bateria v1 de 20 perguntas neutras congelada | `auditoria.sh`; inemaseo-sistemas (exemplos reais 19/10); `aiv2026` F0; §2.8 |
| 3 | `plano-30-90-180` | Do diagnóstico ao plano 30/90/180 | ordenar os achados por impacto × esforço e escrever um plano 30/90/180 dias com métrica de sucesso e dono em cada linha | achados → impacto × esforço → 30 d fundação e medição → 90 d conteúdo → 180 d autoridade e idioma | 1) matriz com 10 achados; 2) plano de 1 página com métrica, dono e "o que não fazer" | ESTRATEGIA §4 (sequência crítica, O que NÃO fazer); PLANO_EXECUCAO §7.2 (metas são hipóteses) e §7.4 |
| 4 | `proposta-escopo` | Proposta e escopo: quatro blocos e os limites | escrever uma proposta de uma página com escopo em quatro blocos, entregáveis, limites e o que o cliente precisa fazer | fundação · conteúdo · medição · visibilidade em IA → entregável → limite → o que o cliente faz | 1) proposta de 1 página; 2) cláusula "o que não prometo" + pré-requisitos do cliente | `aiv2026` "Resumo comercial" e pré-requisitos; TENDENCIAS §7 (faixas só ilustrativas) |
| 5 | `entrega-com-agentes` | Entrega com agentes: uma pasta por cliente | montar a pasta de um cliente com estrutura fixa, portões humanos e segredo fora do repositório, para entregar com agentes sem perder controle | pasta do cliente → agente faz o repetitivo → portão 1 / portão 2 (humano) → publica → observa | 1) pasta modelo com `.gitignore` do `.env`; 2) lista de portões com quem aprova e quanto tempo | METODO "máquina com agentes"; PLANO_EXECUCAO anexo D e §8 (portão nunca é pulado) |
| 6 | `relatorio-mensal` | Relatório mensal ao cliente | montar o relatório mensal de uma página com sem marca, indexação, consultas-alvo, citação nas IAs e uma decisão pedida ao cliente | export semanal + inspeção + consultas-alvo + bateria do mês → 10 linhas no topo → 1 decisão | 1) relatório de 1 mês (seu site); 2) a frase que conta um zero ao cliente sem esconder | `gsc_relatorio_semanal.py`; `semana-2026-10-11.md` (real); `aiv2026` F4; §2.1, §2.5 |
| 7 | `etica-autorizacao` | Ética, risco e autorização por escrito | recusar pelo nome as táticas que o Google trata como spam, escrever a autorização do cliente e deixar claro que diagnóstico de SEO não é pentest | pedido → é spam? → autorização por escrito (escopo, acessos, quem aprova) → executar e registrar | 1) termo de autorização preenchido; 2) tabela pedido → por que recuso → o que ofereço | REVISAO §4.2; CHECKLIST; PLANO_EXECUCAO §8 anti-padrões; prof2030 (LGPD, escopo) |
| 8 | `prospeccao-oferta` | Prospecção e oferta combinada | montar a escada de oferta (ensino → diagnóstico → plano → acompanhamento) e uma lista de 10 prospects com o motivo de cada contato | Treinador → Consultor → Mentor → Auditor → acompanhamento mensal, aplicado ao SEO | 1) escada de oferta com 4 degraus; 2) 10 prospects com o achado público de cada um; plano datado pelo gerador | prof2030; Vendas com IA curso 2; `prospector-agent` (descoberta + portão, não venda de construção) |

Aula 8 fecha com `mapa` (4 degraus: oferta, diagnóstico, entrega, acompanhamento) + `gerador` (as 8 aulas).

## Simconversa da aula 2 — "call de diagnóstico com a dona da clínica"

Personagem: dona de clínica de fisioterapia com site (ficção rotulada). Ensina: medir antes de prometer (F0), separar marca × sem marca (§2.2), só leitura sem autorização, o relatório de 1 página.

| fala | cliente | opções (nota → destino) |
|---|---|---|
| `abre` | "quero aparecer em 1º no Google e no ChatGPT; quanto custa?" | perguntar o que ela mede hoje e de onde vêm os clientes (2 → `medicao`) · "garanto 1º lugar em 90 dias" (0 → `fim-promessa`) · passar preço de pacote de artigos (0 → `fim-pacote`) |
| `medicao` | "o site recebe visitas, meu sobrinho olhou" | propor diagnóstico só de leitura: HTML, prontidão, 20 perguntas nas IAs (2 → `acesso`) · pedir senha do painel e da hospedagem já (1 → `senha`) |
| `senha` (desvio) | "te passo a senha por WhatsApp?" | recusar: autorização por escrito e acesso de leitura no próprio painel (1 → `acesso`) · aceitar (0 → `fim-senha`) |
| `acesso` | "e o que você me entrega?" | relatório de 1 página: 3 achados, o número sem marca, as perguntas em que ela não aparece, um plano (2 → `ia`) · relatório de 80 páginas da ferramenta (0 → `fim-ferramenta`) |
| `ia` | "o diagnóstico mostra que estou no ChatGPT?" | mostra o resultado da bateria manual naquele dia, que varia; repete todo mês (2 → `fim-bom`) · "a ferramenta X dá a nota oficial de IA" (0 → `fim-nota`) |

Somas: direto 2+2+2+2 = 8; desvio 2+1+1+2+2 = 8 (não passa). Máximo = 8.

## Decisões tomadas sozinho
- Saídas reais do auditor e do agente-ready (inema.club, 19/10/2026, `inemaseo-sistemas/exemplos/`) entram na aula 2 com selo "real", como modelo de relatório; o ensino das ferramentas fica no curso 7.
- `gsc_relatorio_semanal.py` vive no repo de trabalho (privado) do INEMA: a aula 6 mostra o uso e a saída real de 11/10, sem link para o script.
- Bateria F0 do aiv2026 previa automação por API; aqui, pela régua de 2026, é manual (20–30 perguntas, 4–5 assistentes, todo mês).
- Metas numéricas do PLANO_EXECUCAO (impressões, cliques por fase) eram hipóteses e não entram; a aula 3 ensina que meta de plano é hipótese a recalibrar no dia 30.
- Prospector Agent entra só como ideia de descoberta + portão humano; a venda de redesenho em massa é mostrada como construção que perde valor (prof2030).
- Faixas de preço: só as de TENDENCIAS §7 (US$ 500–7.500 auditoria; mensal de pequena empresa US$ 2.000–6.000), "de fornecedores dos EUA, adapte ao seu mercado". Preço detalhado aponta para o curso 2 de Vendas com IA.
