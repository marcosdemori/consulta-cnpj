# 🚀 MegaOnline - CNPJ Pro (v2.0)

Aplicação web moderna para consulta de CNPJ com interface estilo SaaS, resiliência de dados e visualização avançada.

👉 Acesse online: [https://marcosdemori.github.io/consultar-cnpj/](https://marcosdemori.github.io/consultar-cnpj/)

---

## 🧠 Visão Geral

O MegaOnline evoluiu para um **dashboard empresarial resiliente**. O grande diferencial desta versão é a **Camada de Abstração Dual-API**, que garante que a ferramenta continue funcionando mesmo que a API principal atinja limites de requisição ou apresente instabilidade.

## 🛠️ Novidades da Versão 2.0

### 🔄 Resiliência Dual-API (Hybrid Fetch)
- **API Primária:** [cnpj.ws](https://publica.cnpj.ws) para dados detalhados e Inscrições Estaduais nativas.
- **API de Fallback:** [CNPJá Open](https://open.cnpja.com) acionada automaticamente em caso de erros ou limites (Rate Limit 429)[cite: 1].
- **Normalização Inteligente:** Os dados de ambas as fontes são unificados em um formato padrão para o dashboard.

### 📦 Consulta em Massa Avançada
- **Interface Otimizada:** Nova tabela em grid que suporta até 50 CNPJs por lote sem quebras de layout[cite: 1].
- **Exibição de IE:** Agora a Inscrição Estadual é exibida diretamente na listagem em massa[cite: 1].
- **Status Visual:** Indicadores de sucesso/erro limpos (sem nomes técnicos de APIs), mantendo o foco no resultado.

## 🔍 Funcionalidades Principais

- **📊 Dashboard Profissional:** Visualização completa de dados cadastrais, sócios, CNAEs e cronologia.
- **🧾 Regime Tributário:** Identificação de MEI, Simples Nacional e Regimes Ordinários com datas de opção[cite: 1].
- **🧠 Score Empresarial:** Sistema de pontuação exclusivo baseado em múltiplos fatores de confiabilidade.
- **💾 Histórico Local:** Armazenamento automático das últimas consultas no navegador (localStorage).
- **📋 Copy-to-Clipboard:** Clique em qualquer campo (CNPJ, IE, Endereço) para copiar instantaneamente.
- **📊 Exportação Total:** Gere relatórios em CSV das consultas em massa com todos os campos unificados[cite: 1].

## 🖥️ Tecnologias

- **Frontend:** HTML5, CSS3 (Variáveis dinâmicas), JavaScript Vanilla (Zero frameworks).
- **Consumo de Dados:** Fetch API com tratamento de erros assíncronos e retentativa.
- **Layout:** Flexbox e CSS Grid para total responsividade.

## 🌐 Deploy

Hospedado via **GitHub Pages**. Para rodar localmente, basta clonar o repositório e abrir o arquivo `index.html` em qualquer navegador moderno.

## 👨‍💻 Autor

Desenvolvido por **Marcos De Mori Laiola**