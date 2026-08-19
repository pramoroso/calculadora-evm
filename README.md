# 📐 Calculadora EVM — Gestão de Valor Agregado

Uma calculadora **interativa e gratuita** de _Earned Value Management_ (Gestão de Valor Agregado / GVA), o método do PMBOK para medir o desempenho de custo e prazo de um projeto com números — não com achismo.

> **🔗 Acesse a ferramenta:** https://pramoroso.github.io/calculadora-evm/

---

## O que ela faz

Você informa quatro valores do projeto:

| Entrada | Significado |
|---|---|
| **BAC** | Orçamento no Término (orçamento total planejado) |
| **% Planejado** | Quanto do projeto deveria estar concluído hoje |
| **% Concluído** | Quanto de fato foi entregue |
| **AC** | Custo Real já incorrido |

E a ferramenta calcula, em tempo real:

- **CPI** — Índice de Desempenho de Custo (`EV ÷ AC`)
- **SPI** — Índice de Desempenho de Prazo (`EV ÷ PV`)
- **CV / SV** — Variações de custo e prazo em R$
- **EAC** — Estimativa de custo no término do projeto
- **ETC** — Estimativa de quanto ainda falta gastar
- **VAC** — Sobra ou estouro previsto no final
- **TCPI** — Eficiência necessária no trabalho restante

Tudo acompanhado de um **gráfico comparativo** (planejado × agregado × real) e um **glossário** explicando cada sigla.

## Recursos

- ⚡ 100% no navegador, sem cadastro e sem servidor
- 📱 Responsivo (funciona no celular)
- 🌗 Tema claro e escuro
- 🎯 Semáforo visual (verde / amarelo / vermelho) para leitura imediata dos índices

## Tecnologia

Um único arquivo `index.html` — HTML, CSS e JavaScript puro (_vanilla_), sem dependências ou build. Hospedado gratuitamente via **GitHub Pages**.

## Como rodar localmente

Basta abrir o arquivo `index.html` em qualquer navegador. Sem instalação.

## Licença

Livre para usar, adaptar e compartilhar nos seus projetos. 👊

---

_Ferramenta desenvolvida como peça de portfólio em gestão de projetos._
