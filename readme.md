# 🚀 Guia de Comandos Git & Conventional Commits

> Um guia prático, direto e visual para gerenciamento de repositórios, fluxo de trabalho com Git e padronização de commits no mercado de desenvolvimento.

---

## 📌 Sobre o Projeto

Este projeto é uma página de referência rápida (cheatsheet) voltada para estudantes e desenvolvedores front-end / web designers. Reúne desde as configurações essenciais do ambiente local até o fluxo completo de versionamento e boas práticas com **Conventional Commits**.

---

## ⚙️ Comandos de Configuração

Configurações globais essenciais para sincronizar sua máquina com sua conta do GitHub / GitLab:

```bash
# Definir nome de usuário global
git config --global user.name "seu-usuario"

# Definir e-mail global (mesmo da plataforma)
git config --global user.email "seu_email@dominio.com"

# Definir "main" como o nome padrão da branch inicial
git config --global init.defaultBranch main

# Listar e verificar todas as configurações ativas
git config --global --list

```

---

## 📦 Trabalhando com Repositórios

Fluxo prático para inicializar, clonar, versionar e sincronizar código:

### 1. Inicialização e Conexão Remota

```bash
# Inicializar um repositório no diretório atual
git init

# Vincular o repositório local a um repositório remoto
git remote add origin [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)

# Clonar um repositório remoto existente
git clone [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)

```

### 2. Ciclo de Vida dos Arquivos & Commits

```bash
# Verificar status das alterações e arquivos rastreados
git status

# Adicionar todos os arquivos modificados para a staging area
git add .

# Registrar as alterações com uma mensagem descritiva
git commit -m "feat: adiciona estrutura base da página"

# Verificar branches locais e em qual você está
git branch

```

### 3. Sincronização Remota

```bash
# Enviar alterações locais para o repositório remoto
git push origin <nome_da_branch>
# Exemplo: git push origin main

# Puxar e mesclar alterações do repositório remoto
git pull origin <nome_da_branch>
# Exemplo: git pull origin main

```

---

## 🏷️ Padrões de Commit (Conventional Commits)

Adotar uma convenção clara torna o histórico do projeto legível, profissional e compatível com ferramentas automáticas de changelog e versionamento semântico (`SemVer`).

### Estrutura básica:

```text
tipo(escopo-opcional): descrição curta no imperativo

```

### Tabela de Referência:

| Tipo | Quando Usar | Exemplo Prático |
| --- | --- | --- |
| `feat` | Adiciona uma nova funcionalidade ao sistema | `feat(auth): adiciona login com Google` |
| `fix` | Corrige um bug ou comportamento inesperado | `fix(checkout): corrige cálculo do frete com cupom` |
| `docs` | Alterações exclusivas na documentação | `docs(readme): atualiza instruções de instalação` |
| `style` | Formatação, indentação ou espaçamento (sem afetar lógica) | `style(lint): aplica regras do ESLint no controller` |
| `refactor` | Refatoração de código que não altera comportamento externo | `refactor(user): simplifica validação de e-mail` |
| `perf` | Mudança de código com foco direto em performance | `perf(db): adiciona índice na tabela de pedidos` |
| `test` | Adiciona ou ajusta testes automatizados | `test(cart): adiciona testes unitários para desconto` |
| `ci` | Ajustes em scripts e pipelines de Integração Contínua | `ci(deploy): ajusta pipeline de staging` |
| `build` | Mudanças que afetam o sistema de build ou ferramentas | `build(webpack): otimiza minificação do bundle` |
| `chore` | Tarefas rotineiras, configs ou atualização de dependências | `chore(deps): atualiza pacote axios para v1.6.0` |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**
* **CSS3 Moderno**
* **JavaScript Vanilla** (atualização dinâmica de ano no rodapé)

---

## 👨‍🏫 Autor

Criado por **Prof. Flávio Ricardo** 💻

*Material de apoio pedagógico para formação em Web Design e Front-End.*
"""

with open("README.md", "w", encoding="utf-8") as f:
f.write(readme_content)

print("README.md generated successfully.")

```

```text?code_stdout&code_event_index=1
README.md generated successfully.


```

Your Markdown file is ready


Aqui está a versão formatada e pronta para o seu repositório:

```markdown
# 🚀 Guia de Comandos Git & Conventional Commits

> Um guia prático, direto e visual para gerenciamento de repositórios, fluxo de trabalho com Git e padronização de commits no mercado de desenvolvimento.

---

## 📌 Sobre o Projeto

Este projeto é uma página de referência rápida (*cheatsheet*) voltada para estudantes e desenvolvedores front-end / web designers. Reúne desde as configurações essenciais do ambiente local até o fluxo completo de versionamento e boas práticas com **Conventional Commits**.

---

## ⚙️ Comandos de Configuração

Configurações globais essenciais para sincronizar sua máquina com sua conta do GitHub / GitLab:

```bash
# Definir nome de usuário global
git config --global user.name "seu-usuario"

# Definir e-mail global (mesmo da plataforma)
git config --global user.email "seu_email@dominio.com"

# Definir "main" como o nome padrão da branch inicial
git config --global init.defaultBranch main

# Listar e verificar todas as configurações ativas
git config --global --list

```

---

## 📦 Trabalhando com Repositórios

Fluxo prático para inicializar, clonar, versionar e sincronizar código:

### 1. Inicialização e Conexão Remota

```bash
# Inicializar um repositório no diretório atual
git init

# Vincular o repositório local a um repositório remoto
git remote add origin [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)

# Clonar um repositório remoto existente
git clone [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)

```

### 2. Ciclo de Vida dos Arquivos & Commits

```bash
# Verificar status das alterações e arquivos rastreados
git status

# Adicionar todos os arquivos modificados para a staging area
git add .

# Registrar as alterações com uma mensagem descritiva
git commit -m "feat: adiciona estrutura base da página"

# Verificar branches locais e em qual você está
git branch

```

### 3. Sincronização Remota

```bash
# Enviar alterações locais para o repositório remoto
git push origin <nome_da_branch>
# Exemplo: git push origin main

# Puxar e mesclar alterações do repositório remoto
git pull origin <nome_da_branch>
# Exemplo: git pull origin main

```

---

## 🏷️ Padrões de Commit (Conventional Commits)

Adotar uma convenção clara torna o histórico do projeto legível, profissional e compatível com ferramentas automáticas de changelog e versionamento semântico (`SemVer`).

### Estrutura básica:

```text
tipo(escopo-opcional): descrição curta no imperativo

```

### Tabela de Referência:

| Tipo | Quando Usar | Exemplo Prático |
| --- | --- | --- |
| `feat` | Adiciona uma nova funcionalidade ao sistema | `feat(auth): adiciona login com Google` |
| `fix` | Corrige um bug ou comportamento inesperado | `fix(checkout): corrige cálculo do frete com cupom` |
| `docs` | Alterações exclusivas na documentação | `docs(readme): atualiza instruções de instalação` |
| `style` | Formatação, indentação ou espaçamento (sem afetar lógica) | `style(lint): aplica regras do ESLint no controller` |
| `refactor` | Refatoração de código que não altera comportamento externo | `refactor(user): simplifica validação de e-mail` |
| `perf` | Mudança de código com foco direto em performance | `perf(db): adiciona índice na tabela de pedidos` |
| `test` | Adiciona ou ajusta testes automatizados | `test(cart): adiciona testes unitários para desconto` |
| `ci` | Ajustes em scripts e pipelines de Integração Contínua | `ci(deploy): ajusta pipeline de staging` |
| `build` | Mudanças que afetam o sistema de build ou ferramentas | `build(webpack): otimiza minificação do bundle` |
| `chore` | Tarefas rotineiras, configs ou atualização de dependências | `chore(deps): atualiza pacote axios para v1.6.0` |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**
* **CSS3 Moderno**
* **JavaScript Vanilla** (atualização dinâmica de ano no rodapé)

---

## 👨‍🏫 Autor

Criado por **Prof. Flávio Ricardo** 💻

*Material de apoio pedagógico para formação em Web Design e Front-End.*