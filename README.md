# 🍪 Caseirinhos do Ju - Landing Page de Alta Conversão

Este é o repositório do site oficial do **Caseirinhos do Ju**, um negócio artesanal de alimentos caseiros (pães, biscoitos amanteigados e casadinhos). O site foi desenvolvido com foco total em **conversão mobile**, projetado para transformar visitantes em pedidos reais diretamente no WhatsApp do Anderson Júnior (Junin).

---

## 🎯 Objetivo do Projeto
Maximizar as vendas do negócio local através de uma experiência de utilizador rápida, simples e altamente persuasiva. Cada botão de produto gera automaticamente uma mensagem personalizada para o WhatsApp do negócio, agilizando o processo de atendimento e fecho do pedido.

---

## 🎨 Identidade Visual e Comunicação
* **Estilo Visual:** Artesanal, caseiro, aconchegante e familiar.
* **Paleta de Cores:** Cores quentes e suaves baseadas em tons de creme, bege, caramelo e marrom-escuro para evocar a sensação de "feito com amor".
* **Tom de Voz:** Humano, afetuoso, regional e muito próximo do cliente.

---

## 🧭 Estrutura do Site (SPA - Single Page Application)
O site foi construído num formato de página única com navegação suave através do menu fixo:
1. **Início (Hero Section):** Proposta de valor clara, imagem apelativa e o CTA (Call to Action) principal.
2. **Diferenciais:** Três blocos em destaque detalhando os pontos fortes do negócio (Produção artesanal, Encomendas sob pedido e Atendimento rápido).
3. **Quem Somos:** Seção institucional humanizada contando a história do Anderson Júnior e a missão da marca.
4. **Catálogo de Produtos:** A secção mais importante, com cartões individuais para cada produto e botões de encomenda dedicados.
5. **Botão Flutuante:** Acesso rápido ao WhatsApp visível a todo o momento em qualquer ponto da página.

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica e acessível.
* **Tailwind CSS (via CDN):** Framework utilitário para um design moderno, totalmente responsivo (Mobile-First) e desenvolvimento ultra-rápido.
* **Google Fonts:** Combinação das famílias *Inter* (para máxima legibilidade nos textos) e *Playfair Display* (para um toque rústico e artesanal nos títulos).

---

## ⚙️ Como Alterar os Links do WhatsApp

Caso precise de alterar o número de telefone ou as mensagens automáticas no futuro, localize os links no ficheiro `index.html` que seguem o padrão da API do WhatsApp:

```text
[https://wa.me/5527996511588?text=Sua%20Mensagem%20Aqui](https://wa.me/5527996511588?text=Sua%20Mensagem%20Aqui)
