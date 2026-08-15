```python
readme_content = """# 🚀 Guia de Comandos Git

Guia prático e direto com os principais comandos Git para gerenciamento de repositórios e padronização de commits com Conventional Commits.

---

## ⚙️ Configurações Iniciais

```bash
git config --global user.name "seu-usuario"
git config --global user.email "seu_email@dominio.com"
git config --global init.defaultBranch main
git config --global --list

```

---

## 📦 Comandos Principais

```bash
# Inicializar / Clonar
git init
git clone <url_do_repositorio>
git remote add origin <url_do_repositorio>

# Versionamento Local
git status
git add .
git commit -m "feat: mensagem do commit"
git branch

# Sincronização Remota
git pull origin main
git push origin main

```

---

## 🏷️ Conventional Commits

| Tipo | Finalidade | Exemplo |
| --- | --- | --- |
| `feat` | Nova funcionalidade | `feat(auth): adiciona login com Google` |
| `fix` | Correção de bug | `fix(cart): corrige cálculo de frete` |
| `docs` | Documentação | `docs(readme): atualiza guia de uso` |
| `style` | Formatação/estilo sem alterar lógica | `style: ajusta espaçamentos` |
| `refactor` | Refatoração de código | `refactor: simplifica validação` |
| `perf` | Melhoria de desempenho | `perf: otimiza query de produtos` |
| `test` | Testes automatizados | `test: adiciona testes unitários` |
| `ci` | Integração Contínua / Deploy | `ci: ajusta pipeline de deploy` |
| `build` | Sistema de build / dependências externas | `build: otimiza bundle` |
| `chore` | Manutenção e tarefas gerais | `chore(deps): atualiza pacotes` |

---

👨‍🏫 **Autor:** Prof. Flávio Ricardo
"""

with open("README-v2.md", "w", encoding="utf-8") as f:
f.write(readme_content)

print("README-v2.md generated successfully.")

```

```text?code_stdout&code_event_index=1
README-v2.md generated successfully.


```

Your Markdown file is ready


Aqui está a versão sintetizada e compacta em um único arquivo:

```markdown
# 🚀 Guia de Comandos Git

Guia prático e direto com os principais comandos Git para gerenciamento de repositórios e padronização de commits com Conventional Commits.

---

## ⚙️ Configurações Iniciais

```bash
git config --global user.name "seu-usuario"
git config --global user.email "seu_email@dominio.com"
git config --global init.defaultBranch main
git config --global --list

```

---

## 📦 Comandos Principais

```bash
# Inicializar / Clonar
git init
git clone <url_do_repositorio>
git remote add origin <url_do_repositorio>

# Versionamento Local
git status
git add .
git commit -m "feat: mensagem do commit"
git branch

# Sincronização Remota
git pull origin main
git push origin main

```

---

## 🏷️ Conventional Commits

| Tipo | Finalidade | Exemplo |
| --- | --- | --- |
| `feat` | Nova funcionalidade | `feat(auth): adiciona login com Google` |
| `fix` | Correção de bug | `fix(cart): corrige cálculo de frete` |
| `docs` | Documentação | `docs(readme): atualiza guia de uso` |
| `style` | Formatação/estilo sem alterar lógica | `style: ajusta espaçamentos` |
| `refactor` | Refatoração de código | `refactor: simplifica validação` |
| `perf` | Melhoria de desempenho | `perf: otimiza query de produtos` |
| `test` | Testes automatizados | `test: adiciona testes unitários` |
| `ci` | Integração Contínua / Deploy | `ci: ajusta pipeline de deploy` |
| `build` | Sistema de build / dependências externas | `build: otimiza bundle` |
| `chore` | Manutenção e tarefas gerais | `chore(deps): atualiza pacotes` |

---

👨‍🏫 **Autor:** Prof. Flávio Ricardo

```

```