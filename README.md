# 🚀 MegaOnline - Consulta de CNPJ

Aplicação web moderna para consulta de CNPJ com interface estilo SaaS, análise empresarial e visualização avançada de dados.

👉 API utilizada: https://publica.cnpj.ws  
👉 Acesse online: https://marcosdemori.github.io/consulta-cnpj/

---

## 🧠 Visão Geral

O projeto evoluiu de uma simples consulta para um **dashboard completo de empresas**, inspirado em plataformas profissionais como CNPJA.

Agora você não apenas consulta um CNPJ — você **analisa a empresa**.

---

## 🔍 Funcionalidades

### 📊 Consulta de Empresas
- Consulta em tempo real via API pública
- Visualização completa dos dados cadastrais
- Interface estilo dashboard profissional

Inclui:
- Razão social
- Nome fantasia
- Situação cadastral
- Endereço completo
- Telefones e e-mail
- CNAE (principal e secundários)
- Inscrições estaduais

---

### 🧾 Regime Tributário Inteligente
- Identificação automática de:
  - MEI
  - Simples Nacional
  - Lucro Real / Presumido

Exibe:
- ✔ Regime atual
- 📅 Data de entrada no regime
- 🔁 Histórico (entrada / exclusão)

Tratamento robusto da API (aceita `true`, `"Sim"`, `"S"`, etc).

---

### 🧠 Score Empresarial (tipo Serasa)
Sistema de pontuação de **0 a 1000**, baseado em:

- Situação cadastral
- Tempo de atividade
- Capital social
- Regime tributário
- Sócios
- Inscrição estadual
- Contato (telefone/email)

Exibe:
- Nota da empresa
- Classificação (Muito bom / Bom / Regular / Atenção)
- Motivos da pontuação

---

### 👥 Pesquisa de Sócios
- Busca entre empresas consultadas
- Filtro por nome
- Visualização consolidada

---

### 📦 Consulta em Massa
- Input de múltiplos CNPJs
- Consulta sequencial automática
- Tabela de resultados
- Exportação CSV

---

### ⚡ UX e Funcionalidades Extras
- ⌨️ Busca com ENTER
- 📋 Clique para copiar dados
- 💾 Histórico de consultas (localStorage)
- 🌙 Dark / Light mode
- 📱 Layout responsivo
- 🔄 Feedback visual de carregamento

---

## 🖥️ Tecnologias

- HTML5
- CSS3 (Custom Properties)
- JavaScript (Vanilla)
- API pública: https://publica.cnpj.ws

---

## 📦 Como usar

1. Baixe o arquivo:

2. Abra no navegador:

3. Digite um CNPJ válido e clique em **Consultar**

---

## 🌐 Deploy

Pode ser hospedado facilmente em:

- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages

---

## ⚠️ Limitações

- API pública pode ter rate limit (HTTP 429)
- Score empresarial é estimado (não oficial)
- Dependência de disponibilidade da Receita Federal

---

## 🔮 Próximas melhorias

- [ ] Sistema de login
- [ ] Backend próprio (cache + proxy API)
- [ ] Planos pagos (SaaS)
- [ ] Exportação Excel avançada
- [ ] Dashboard de prospecção
- [ ] Score mais avançado (machine learning)

---

## 👨‍💻 Autor

Desenvolvido por **Marcos De Mori Laiola**

---

## 📄 Licença

Uso livre para projetos pessoais e comerciais.