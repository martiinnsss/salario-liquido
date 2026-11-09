# Calculadora de Salário Líquido 2026

Página web que calcula quanto recebes realmente ao fim do mês em Portugal, depois de IRS e Segurança Social.

**Problema que resolve:** numa proposta de emprego só aparece o salário bruto, e as tabelas de retenção de IRS são difíceis de ler. Aqui metes o bruto e vês logo o líquido, mês a mês e no ano.

🔗 **Experimenta online:** https://martiinnsss.github.io/salario-liquido/

## Funcionalidades

- Retenção na fonte de IRS pelas **tabelas oficiais de 2026** para Portugal continental (Despacho n.º 233-A/2026)
- Situações: não casado, casado com dois titulares e casado com um titular, com dependentes
- **Segurança Social** de 11%
- **Subsídio de refeição** em cartão ou dinheiro, com os limites de isenção de 2026 (10,46 €/dia em cartão, 6,15 €/dia em dinheiro); o que passar do limite é tributado
- Subsídios de férias e de Natal **pagos à parte ou em duodécimos**
- Resumo anual: bruto, IRS retido, Segurança Social e líquido
- Gráfico com a divisão do salário entre o que recebes, IRS e Segurança Social
- Funciona no computador e no telemóvel, sem instalar nada

## Como usar

Abre o ficheiro `index.html` no browser.

## Limitações

- A retenção na fonte é um adiantamento: o imposto final só se apura na declaração anual de IRS
- Não inclui IRS Jovem, pessoas com deficiência, Açores e Madeira, nem o ajuste excecional de novembro de 2026 (nesse mês retém-se só metade)
- As tabelas têm de ser atualizadas todos os anos

## Tecnologias

HTML · CSS · JavaScript (sem bibliotecas nem frameworks)

---
Feito por **Gonçalo Martins** — estudante de Engenharia Informática e Aplicações.
