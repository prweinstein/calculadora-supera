# 📊 Exemplo Detalhado de Cálculo

Este documento apresenta um exemplo prático de como a calculadora funciona.

## 🧮 **Cenário de Exemplo**

### **Dados de Entrada:**

* **Valor Base:** R$ 200,00
* **Data de Vencimento:** 01/07/2025 (terça-feira)
* **Data de Pagamento:** 13/07/2025 (domingo)
* **Configurações:** Multa 2%, Juros 1% ao mês

***

## ⚙️ **Processo de Cálculo**

### **1. Verificação do Vencimento**

* **01/07/2025** é uma **terça-feira**
* ✅ **É dia útil** (não é fim de semana nem feriado)
* **Vencimento efetivo:** 01/07/2025 (sem prorrogação)

### **2. Ajuste da Data de Pagamento**

* **13/07/2025** é um **domingo**
* ❌ **Não é dia útil** (fim de semana)
* **Próximo dia útil:** 14/07/2025 (segunda-feira)
* **Pagamento efetivo:** 14/07/2025

### **3. Cálculo dos Dias de Atraso**
Atraso = Data Pagamento Efetiva - Data Vencimento Efetiva Atraso = 14/07/2025 - 01/07/2025 Atraso = 13 dias


### **4. Cálculo da Multa**
Multa = Valor Base × Percentual de Multa Multa = R
200
,
00
×
2
M
u
l
t
a
=
R
200,00×2Multa=R 200,00 × 0,02 Multa = R$ 4,00


### **5. Cálculo dos Juros (Mensal)**
Meses de atraso = Dias de atraso ÷ 30 Meses de atraso = 13 ÷ 30 = 0,4333 meses

Juros = Valor Base × Percentual de Juros × Meses de atraso Juros = R
200
,
00
×
1
J
u
r
o
s
=
R
200,00×1Juros=R 200,00 × 0,01 × 0,4333 Juros = R$ 0,87


### **6. Valor Total**
Total = Valor Base + Multa + Juros Total = R
200
,
00
+
R
200,00+R 4,00 + R
0
,
87
T
o
t
a
l
=
R
0,87Total=R 204,87


***

## 📋 **Resultado Final**

| Item                  | Valor         |
| --------------------- | ------------- |
| **Valor Base**        | R$ 200,00     |
| **Multa (2%)**        | R$ 4,00       |
| **Juros (1% ao mês)** | R$ 0,87       |
| **Total a Pagar**     | **R$ 204,87** |

### **Informações Adicionais:**

* **Dias de atraso:** 13 dias úteis
* **Data efetiva do pagamento:** 14/07/2025 (próximo dia útil)
* **Observação:** Pagamento com atraso - multa e juros aplicados

***

## 🎯 **Cenários Especiais**

### **Vencimento em Feriado**

Se o vencimento fosse **04/03/2025** (Carnaval - terça-feira):

* **Vencimento prorrogado** para 05/03/2025 (quarta-feira)
* **Cálculo de atraso** feito a partir de 05/03/2025

### **Pagamento no 1º Dia Útil**

Se o pagamento fosse feito em **05/03/2025** (primeiro dia útil após Carnaval):

* **Resultado:** R$ 200,00 (sem multa nem juros)
* **Observação:** "Multa e juros não cobrados - pagamento no primeiro dia útil após vencimento em feriado"

***

## 📖 **Fórmulas Utilizadas**

### **Para Juros Mensais:**
Juros = Valor Base × (% Juros ÷ 100) × (Dias de Atraso ÷ 30)


### **Para Juros Diários:**
Juros = Valor Base × (% Juros ÷ 100) × Dias de Atraso


### **Multa:**
Multa = Valor Base × (% Multa ÷ 100)


***

## ⚖️ **Fundamentos Legais**

* **Multa máxima:** 2% (Art. 52 do CDC)
* **Juros máximos:** 1% ao mês (12% ao ano - CDC)
* **Prorrogação:** Vencimento em feriado/fim de semana é prorrogado para próximo dia útil
* **Tolerância:** Pagamento no 1º dia útil após vencimento em feriado não gera multa/juros
