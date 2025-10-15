# 💳 Simulador de Taxas de Máquinas de Cartão

## 🧾 Descrição

Este é um simulador web interativo que compara quanto você receberá em diferentes operadoras de máquinas de cartão (como **Nubank, Itaú, Mercado Pago**, entre outras) com base:

- no valor da venda;
- no número de parcelas;
- e nas taxas praticadas por cada operadora.

O objetivo é identificar **qual operadora entrega o maior valor líquido**, facilitando a escolha do melhor parceiro para recebimentos via cartão.

---

## ⚙️ Funcionalidades

- Entrada do **valor da venda (R$)**.
- Seleção da **quantidade de parcelas** (Débito, Crédito de 1x até 12x).
- Simulação automática das taxas praticadas por cada operadora:
  - Itaú (Visa/Master e Elo)
  - Nubank
  - Mercado Pago
  - PágBank
- Cálculo do **valor líquido a receber** após desconto das taxas.
- Destaque em **verde** para a **melhor opção** de recebimento.

---

## 📊 Como funciona o cálculo?

Para cada operadora:
- A taxa correspondente ao número de parcelas é aplicada.
- Uma taxa adicional fixa de **1.00%** é somada (processamento, antecipação etc.).
- O valor final é calculado subtraindo essa porcentagem do valor da venda.

---

## 📦 Estrutura do Projeto

