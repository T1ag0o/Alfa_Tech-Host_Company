# AlfaTech - Web Hosting Company Website

A two-page website for a web hosting company, built with HTML and CSS for study purposes.

## 1. Goal

Present the company and its services, and show the pricing plans so visitors can choose the best one.

**Target users:** people and companies looking for a web hosting service.

## 2. Tech Stack

- HTML5 (semantic tags)
- CSS3 (custom properties, Flexbox, Grid)
- No JavaScript and no frameworks

## 3. Pages

| Page    | File          | Purpose                                                   |
| ------- | ------------- | --------------------------------------------------------- |
| Home    | `home.html`  | Information about the company and who the services help   |
| Pricing | `plan.html` | Full table comparing the four plans                       |


## 4. Design Tokens

### Font (Google Fonts)

| Name    | Role                                   |
| ------- | -------------------------------------- |
| Poppins | The whole project (titles, text, menu) |


### Colors

| Value                  | Suggested use                                      |
| ---------------------- | -------------------------------------------------- |
| `#fff`                 | Page background, text on blue/dark backgrounds     |
| `#f1f3f7`              | Light gray sections and table header cells         |
| `#f6f6f6`              | Light gray details (credit bar, alternating rows)  |
| `#a89f9f`              | Secondary text                                     |
| `#233032`              | Dark bar (call to action), main text               |
| `#2f86d6`              | Main brand blue (header, hero, buttons, highlights)|
| `#a8a4a4`              | Secondary text / small details                     |
| `rgba(47, 134, 214, 1)`| Blue glow (`box-shadow`) around the pricing cards  |


### Sizes

> To be defined. Suggested: use `rem` units and save them as CSS variables.

## 5. Page Structure

### 5.1 Home (`home.html`)

1. **Header** – white background. Logo (left) and menu (right): *Informações*, *Planos*, *Preços*, *Contato*.
2. **Hero** – blue background. Text on the left and an illustration on the right.
   - Small text: "Simples - Fácil de usar - 10x mais rápido!"
   - Title: "O melhor serviço de hospedagem na web para o seu site."
   - Paragraph: "Obtenha o melhor velocidade para o seu site. Não perca mais clientes por causa de lentidão na sua hospedagem."
3. **Call-to-action bar 1** – dark background (`#233032`).
   - "Hospede o seu site por apenas R$29 por mês"
   - "Também temos planos gratuitos. Adquira já o seu."
   - Blue button: **TABELA DE PREÇOS**
4. **Why choose us** – title: "Existem diversos serviços de hospedagem de sites. Porque você deve **nos escolher?**" (the last words in blue). Three columns with icon, title and text:

   | Title                | Text                                                              |
   | -------------------- | ----------------------------------------------------------------- |
   | Fácil de configurar  | Facilmente configurável em plataformas CMS populares - Wordpress, Joomla... |
   | Servidores 100% Online | Same text pattern                                               |
   | Suporte 24/7         | Same text pattern                                                 |

5. **Plans summary** – light gray background (`#f1f3f7`). Title: "Pague **somente** pelo que for usar. Sem cobranças adicionais!" and a card with a blue glow, with four columns:

   | Plan         | Description                       | Users       | Domains         | Space      | Extras                                  |
   | ------------ | --------------------------------- | ----------- | --------------- | ---------- | --------------------------------------- |
   | Pessoal      | Indicado para uso pessoal         | 1 usuário   | 1 Domínio Grátis | 200GB SSD | Ofertas especiais, Suporte Ilimitado    |
   | Profissional | Indicado para profissionais de T.I. | 10 usuários | 2 Domínios Grátis | 500GB SSD | Ofertas especiais, Suporte Ilimitado  |
   | Empresarial  | Indicado para empresas            | 25 usuários | 2 Domínios Grátis | 1TB SSD   | Ofertas especiais, Suporte Ilimitado    |
   | Big Techs    | Indicado para grandes empresas    | 50 usuários | 3 Domínios Grátis | 2TB SSD   | Ofertas especiais, Suporte Ilimitado    |

6. **Call-to-action bar 2** – blue background, dark button.
   - "Mais de 20.000 pessoas confiam na AlfaTech! Seja um deles você também!"
   - Dark button: **TABELA DE PREÇOS**
7. **Footer** – white background. Logo and contact info:
   - Telefone & Whatsapp: (21) 99999-5555
   - E-mail: suporte@alfatech.com
   - Endereço: Av Ayrton Senna, 3000 - Barra da Tijuca - Rio de Janeiro
   - "© AlfaTech - Soluções em hospedagem - Todos os direitos reservados"
8. **Credit bar** – light gray: "Desenvolvido por 'nome do aluno'" (the name in blue).

### 5.2 Pricing (`plan.html`)

1. **Header** – blue background. Logo (left) and menu (right) with white text: *Home*, *Informações*, *Planos*, *Contato*.
2. **Pricing table** – centered, with the plans in the columns and the features in the rows.
   - Plan names (small, gray): Pessoal, Profissional, Empresarial, Big Techs
   - Prices (large, bold): **GRÁTIS**, **R$29**, **R$59**, **R$99**
   - First column and the plan header cells use the light gray background.
3. **Footer** – blue background, logo and copyright text.
4. **Credit bar** – light gray: "Desenvolvido por 'nome do aluno'".

## 6. Pricing Table Content

A dot (●) means the feature is included.

| Feature                       | Pessoal   | Profissional   | Empresarial       | Big Techs         |
| ----------------------------- | --------- | -------------- | ----------------- | ----------------- |
| Monitoramento de rede         | 3 redes   | 10 redes       | 20 redes          | 50 redes          |
| Dashboard                     | 1 dashboard | 5 dashboards | 10 dashboards     | 25 dashboards     |
| Usuários                      | 1 usuário | 5 usuários     | 10 usuários       | 25 usuários       |
| Relatório de atualização      | Toda hora | A cada 30 minutos | Quase em tempo real | Tempo real*     |
| Relatórios de emails          | ●         | ●              | ●                 | ●                 |
| Transações ilimitadas         | ●         | ●              | ●                 | ●                 |
| Rastreador de pagamento       | ●         | ●              | ●                 | ●                 |
| Exportação de dados           | ●         | ●              | ●                 | ●                 |
| Conversor de moeda            |           | ●              | ●                 | ●                 |
| Acesso à API                  |           | ●              | ●                 | ●                 |
| Restrição de IP               |           |                | ●                 | ●                 |
| Feed personalizado            |           |                | ●                 | ●                 |
| Limite de importação de dados | Último ano | Últimos 2 anos | Últimos 3 anos   | Últimos 3 anos    |
| Retenção de dados             | Tempo de vida | Tempo de vida | Tempo de vida   | Tempo de vida     |
| Suporte                       | Email     | Email & chat   | Email & chat      | Email, chat & voice |

## 7. Style Notes

- All page text is in Portuguese (Brazil).
- The brand blue (`#2f86d6`) is used in the hero, buttons, highlighted words and the pricing page header/footer.
- Menu items are uppercase.
- Both pages share the same logo, footer style and credit bar. Create the same structure in both files.
- The pricing cards on the home page have a blue glow: `box-shadow: 0 0 20px rgba(47, 134, 214, 1)`.
- Both **TABELA DE PREÇOS** buttons link to `plan.html`.

## 8. Suggested Folder Structure

```
alfatech/
├── home.html
├── plan.html
├── README.md
├── styles/
│   ├── variables.css
│   └── main.css
└── images/
   ├── logos/
   └── icons/
```
