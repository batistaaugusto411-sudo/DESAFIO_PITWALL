# 🏁 Pit Wall · GP de São Paulo

Projeto de estudo desenvolvido para a disciplina de Linguagem de Marcação (LIMA), recriando a landing page promocional do GP de São Paulo de F1 em Interlagos utilizando apenas **HTML5** e **CSS3**.

---

## 📸 Demonstração do Projeto

O layout foi desenvolvido focando na fiel reprodução visual da transmissão de Fórmula 1, garantindo responsividade total (desktop e mobile).

- **Header & Hero:** Destaque com efeito de degradê com corte seco em diagonal, imagem em overlay e estatísticas da pista.
- **Zebra de Pista:** Desenvolvida puramente com CSS utilizando `repeating-linear-gradient`.
- **Grid de Pilotos:** Exibição dos cards com as cores oficiais das equipes configuradas via variáveis CSS (`:root`).
- **Tabela de Classificação:** Tabela estilizada com destaque para o líder e cores indicativas por equipe.
- **Formulário de Ingressos:** Layout responsivo com campos customizados (`form-grid`).

---

## 🧰 Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página (`header`, `main`, `section`, `article`, `footer`, `table`, `form`).
- **CSS3:**
  - Variáveis globais (`:root` e `var()`)
  - **Flexbox** para o topo, botões e elementos do hero
  - **CSS Grid** (`auto-fit` e `minmax`) para os cards de pilotos e formulários
  - `repeating-linear-gradient` para a zebra da pista
  - `@media` queries para adaptar o layout a telas móveis (Smartphones e Tablets)
- **Google Fonts:** Importação da fonte oficial *Titillium Web*.

---
## 👤 Autor

**PITWALL** · Projeto de estudo de HTML e CSS 
---

## 📂 Estrutura de Pastas

```text
pit-wall/
├── index.html          # Estrutura HTML da página
├── styles.css          # Estilização completa do layout
├── README.md           # Documentação do projeto
└── img/
    └── piloto.jpg      # Imagem de fundo do hero
