# Monitoramento do Nível do Rio Guaíba e Planejamento de Evacuação

**Integrantes:**
- Eduardo Ulisses Pereira da Silva – RM566339  
- Eduardo Duran Del Ciel – RM562017  
- Henrique Guedes Silvestre – RM562474  

---

## 🌎 GLOBAL SOLUTION – Aplicação Prática do Modelo

Este projeto propõe uma solução baseada em sensoriamento e modelagem matemática para o monitoramento do nível do Rio Guaíba em Porto Alegre, visando auxiliar na tomada de decisões em situações de risco de enchentes.

A ideia central é utilizar sensores para medir o nível do rio em tempo real e aplicar um modelo polinomial que permita prever seu comportamento. A partir disso, alertas automáticos (via app, SMS ou sirenes) podem ser disparados em caso de risco iminente, contribuindo para a evacuação segura de áreas afetadas.

---

## 📍 Cidade Escolhida
- **Cidade:** Porto Alegre – RS  
- **Rio Monitorado:** Rio Guaíba  

---

## 📊 Tabela de Nível do Rio (10 dias consecutivos de chuva)

| Dia        | Data       | Nível do Rio (m)   |
|------------|------------|--------------------|
| 1          | 29/04/2024 | 1.31               |
| 2          | 30/04/2024 | 1.50 (estimado)    |
| 3          | 01/05/2024 | 2.00 (estimado)    |
| 4          | 02/05/2024 | 3.17               |
| 5          | 03/05/2024 | 5.31               |
| 6          | 04/05/2024 | 5.35               |
| 7          | 05/05/2024 | 5.35               |
| 8          | 06/05/2024 | 5.33               |
| 9          | 07/05/2024 | 5.20 (estimado)    |
| 10         | 08/05/2024 | 5.00 (estimado)    |

---

## 🧮 Modelagem Polinomial

Foi utilizada uma função polinomial de grau 3 para aproximar o comportamento do nível do rio ao longo dos dias.

- **Domínio:** Dias {1, 2, ..., 10}  
- **Imagem:** {1.31, 1.50, 2.00, 3.17, 5.31, 5.35, 5.35, 5.33, 5.20, 5.00}  
- **Nível Máximo:** 5.35 metros (dias 04/05 e 05/05)

---

## 📈 Gráfico Gerado

O gráfico a seguir representa:

- A curva polinomial ajustada (grau 3);
- Os dados reais de nível do rio;
- A linha de risco estabelecida em 3,0 metros;
- Os dias que ultrapassaram o nível de risco.
