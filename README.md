# TENKiTER Modas — Backup do Projeto

Backup completo do projeto do site **tenkitermodas.com.br**, reunindo os códigos backend (Google Apps Script), os relatórios/páginas gerados e o repositório do site.

## 📁 Estrutura

| Pasta | Conteúdo |
|-------|----------|
| `apps-script/` | Códigos backend em Google Apps Script |
| `relatorios/` | Relatórios e páginas HTML gerados |
| `site/` | Cópia do repositório do site (`pablofonteneleadv/tenkiter-catalogo`) |

## 📄 Conteúdo detalhado

### `apps-script/`
- **`funcionario-codigo-3.8.gs.txt`** — Backend do módulo de Treinamento + Acessos (v3.8). Inclui cache do conteúdo de treinamento (manuais + provas), controle de sessão/permissões a cada abertura e leitura da aba `ConfigQuiz`.
- **`catalogo-codigo-4.8.gs.txt`** — Backend do Catálogo (v4.8). Inclui métricas de **pessoas únicas** no funil (entraram / viram peças / tocaram no WhatsApp), por dia, hora e origem.

### `relatorios/`
- **`tenkitermodas-otimizacao-cadastro.html`** — Relatório de otimização do cadastro.
- **`tenkitermodas-review.html`** — Relatório de review.
- **`tenkitermodas-audit.html`** — Relatório de auditoria.

### `site/`
Cópia integral do repositório `pablofonteneleadv/tenkiter-catalogo` (114 arquivos): páginas HTML, scripts JS, service workers, ícones, manifest PWA e demais assets do site.

## 🔗 Origens dos arquivos
- **Apps Script** — objetos do projeto hospedados em `imserver.teamily.ai`
- **Relatórios** — páginas publicadas em `static.teamily.ai/sites/...`
- **Site** — `github.com/pablofonteneleadv/tenkiter-catalogo`

## 📅 Data do backup
15 de outubro de 2026

---
*Este é um repositório de **backup** — não é o ambiente de produção do site.*
