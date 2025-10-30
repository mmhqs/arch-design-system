# Design System ⚙️
No presente repositório, é apresentada uma proposta de Design System para um sistema. Um Design System (DS) estabelece a consistência da interface, atuando como uma "fábrica de componentes" que garante uma experiência de usuário unificada e acelera a entrega de novas funcionalidades. 

Vale destacar que o DS é apenas a "carroceria" profissional do carro; ele depende de uma arquitetura de software funcional e eficiente para ser o "motor". Se a arquitetura (APIs, banco de dados, serviços) for lenta ou mal estruturada, o resultado será um aplicativo que não suporta a carga de pedidos, falha no checkout ou demora para carregar o cardápio. Portanto, a arquitetura eficiente garante que o sistema escale em performance, enquanto o Design System garante que ele escale em produto e experiência, permitindo ao sistema crescer de forma rápida e robusta.

Grupo: 
- Érica
- Gustavo Campos
- Gustavo Ceolin
- Joana Morais
- Kayler
- Luís Miguel
- Mariana Almeida Henriques

## 1. Contexto do sistema
O **Pizza Delivery** nasceu como um projeto familiar, onde a simplicidade era refletidos em um site direto e funcional, pensado para os clientes do bairro. No entanto, o sucesso da receita foi além das expectativas, e a plataforma sofreu um crescimento explosivo, trazendo um desafio de escalabilidade que a arquitetura original não suportava.

<img src="images/imagem1.png" alt="Pizza Delivery" width="500">

Uma nova arquitetura foi pensada para o sistema, de modo a atender os desafios apresentados. No entando, do ponto de vista de design, esse crescimento acelerado resultou em uma "colcha de retalhos". A experiência do usuário tornou-se inconsistente, com botões, fluxos de checkout e alertas visuais diferentes a cada tela, confundindo clientes fiéis e novos. O que era um charme caseiro virou um gargalo de desenvolvimento, tornando a manutenção lenta e a expansão da marca impossível, evidenciando a necessidade crítica de um Design System para unificar e profissionalizar a plataforma.

## 2. Fundamentos do Design System
A ideia principal que norteia o Design System proposto é o conceito de uma pizzaria caseira que está expandindo mas que não quer perder sua cara familiar, acolhedora e de excelente qualidade. Para isso, foram definidos alguns fundamentos apresentados a seguir.

### 2.1. Paletas de cores
A ideia é usar cores quentes e apetitosas, mas com tons um pouco mais suaves e terrosos para manter o ar aconchegante, evitando cores vibrantes e "fast-food" demais.

<img src="images/imagem2.png" alt="Paleta" width="500">

Primária (Massa Fresca)
- Humm_Red (#E03C3C / R:224 G:60 B:60) - Um vermelho tomate, que remete à base da pizza e ao calor do forno. Forte, mas não agressivo.

Secundária (Queijo Quente): 
- Queijo_Amarelo (#FFD700 / R:255 G:215 B:0) - Um amarelo mostarda/ouro, que lembra o queijo derretido e a borda crocante.
- Acento (Azeitona): Azeitona_Verde (#4CAF50 / R:76 G:175 B:80) - Um verde folha de manjericão/azeitona, para botões de sucesso ou pequenos destaques.

Neutros (Base de Pedra):
- Pedra_Clara (#F5F5F5 / R:245 G:245 B:245) - Para fundos e superfícies claras.
- Pedra_Média (#CCCCCC / R:204 G:204 B:204) - Para bordas, divisores e textos mais discretos.
- Pedra_Escura (#424242 / R:66 G:66 B:66) - Para textos principais e ícones.

Feedback (Molho Secreto):
- Sucesso: Manjericão_Sucesso (#66BB6A / R:102 G:187 B:106) - Um verde vibrante, mas natural.
- Erro: Pimenta_Vermelha (#EF5350 / R:239 G:83 B:80) - Um vermelho alerta, porém amigável.
- Aviso: Aviso_Cheddar (#FFA726 / R:255 G:167 B:38) - Um laranja que lembra queijo cheddar, para alertas.

## 3. Estilo arquitetural

---

## 4. Componentização e domínio
---

## 5. Padrões de comunicação
---

## 6. Persistência e banco de dados

---

## 7. Escalabilidade e performance

---

## Segurança

---

## Observabilidade
