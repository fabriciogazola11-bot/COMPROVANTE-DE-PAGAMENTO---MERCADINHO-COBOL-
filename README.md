# Sistema de Pagamentos em COBOL

## 📋 Descrição

O **Sistema de Pagamentos em COBOL** é um projeto desenvolvido para simular o funcionamento de um sistema de pagamentos em um caixa comercial. O programa permite registrar o valor de uma compra e realizar o pagamento utilizando diferentes formas de pagamento, emitindo um comprovante ao final da operação.

O projeto foi desenvolvido com fins acadêmicos para praticar os principais conceitos da linguagem **COBOL**, como estruturas de decisão, repetição, cálculos, manipulação de variáveis e organização do código em procedimentos.

---

## 🚀 Funcionalidades

* Pagamento em dinheiro

  * Cálculo de troco.
  * Suporte a pagamento parcial.
  * Atualização automática do saldo restante.

* Pagamento por cartão de crédito

  * Entrada do número do cartão.
  * Entrada do CVV.
  * Escolha da quantidade de parcelas.
  * Simulação de autorização da transação.

* Pagamento por cartão de débito

  * Entrada do número do cartão.
  * Entrada do CVV.
  * Simulação de autorização.

* Pagamento via PIX

  * Entrada da chave PIX.
  * Simulação da geração de QR Code.
  * Confirmação do pagamento.

* Pagamento por boleto

  * Registro do código do boleto.
  * Confirmação da operação.

* Emissão de nota fiscal

  * Simulação da emissão de nota fiscal digital.

* Emissão de comprovante

  * Valor da compra.
  * Status da operação.

---

## 🛠️ Tecnologias Utilizadas

* COBOL
* GnuCOBOL 3.x

---

## 📂 Estrutura do Programa

O sistema é dividido em procedimentos independentes:

* `INICIO`
* `PAGAMENTO-DINHEIRO`
* `PAGAMENTO-CREDITO`
* `PAGAMENTO-DEBITO`
* `PAGAMENTO-PIX`
* `PAGAMENTO-BOLETO`
* `EMITIR-NF`
* `COMPROVANTE`

Essa organização facilita a leitura, manutenção e futuras expansões do projeto.

---

## ▶️ Como Executar

### Compilar

```bash
cobc -x PAGAMENTOS.cob
```

### Executar

**Windows**

```bash
PAGAMENTOS.exe
```

**Linux**

```bash
./PAGAMENTOS
```

---

## 💻 Exemplo de Utilização

```text
====================================
      SISTEMA DE PAGAMENTOS
====================================

Valor da Compra:
150.00

Forma de Pagamento

1 - Dinheiro
2 - Cartão Crédito
3 - Cartão Débito
4 - PIX
5 - Boleto
6 - Nota Fiscal
```

---

## 📚 Conceitos de COBOL Utilizados

* IDENTIFICATION DIVISION
* DATA DIVISION
* WORKING-STORAGE SECTION
* PROCEDURE DIVISION
* DISPLAY
* ACCEPT
* IF / ELSE
* EVALUATE
* PERFORM
* COMPUTE
* MOVE

---

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo demonstrar a implementação de um sistema simples de pagamentos utilizando COBOL, aplicando conceitos fundamentais da linguagem e simulando operações comuns encontradas em sistemas comerciais.

---

## 🔮 Melhorias Futuras

* Validação dos dados do cartão.
* Geração de QR Code real para pagamentos PIX.
* Integração com interface gráfica em Java.
* Registro das transações em arquivo.
* Emissão de comprovante com data, hora e código de autorização.
* Integração com banco de dados.
* Implementação de autenticação de usuários.

---

## 👨‍💻 Autor

**José Fabrício Suter Gazola**

Projeto desenvolvido para fins acadêmicos na disciplina de **Análise e Desenvolvimento de Sistemas (ADS)**.
