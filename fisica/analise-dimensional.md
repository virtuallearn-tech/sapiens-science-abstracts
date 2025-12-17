# Análise Dimensional

## 1. Conceito
A análise dimensional é uma ferramenta da física que permite **verificar a consistência de fórmulas**, **converter unidades** e **prever relações entre grandezas físicas**.

---

## 2. Grandezas e Unidades
- **Fundamentais:**  
  - Comprimento (\(L\)) – metro (m)  
  - Massa (\(M\)) – quilograma (kg)  
  - Tempo (\(T\)) – segundo (s)  
  - Corrente elétrica (\(I\)) – ampère (A)  
  - Temperatura (\(\Theta\)) – kelvin (K)  
  - Quantidade de substância (\(N\)) – mol  
  - Intensidade luminosa (\(J\)) – candela (cd)

- **Derivadas:** combinam grandezas fundamentais  
  - Velocidade: \(v = L/T\)  
  - Aceleração: \(a = L/T^2\)  
  - Força: \(F = M \cdot L / T^2\)

---

## 3. Princípio da Homogeneidade
- Todas as parcelas de uma equação física devem ter **a mesma dimensão**  
- Exemplo:
\[
S = v t + \frac{1}{2} a t^2
\]
- Verificação:
  - \(v t \rightarrow (L/T) \cdot T = L\)  
  - \(\frac{1}{2} a t^2 \rightarrow (L/T^2) \cdot T^2 = L\)  
- Ambas parcelas têm dimensão \(L\), portanto correta

---

## 4. Conversão de Unidades
- Transformar unidades de uma grandeza usando **fatores de conversão**  
- Exemplo: \(1 \text{ km/h} = \frac{1000 \text{ m}}{3600 \text{ s}} \approx 0,278 \text{ m/s}\)

---

## 5. Previsão de Fórmulas
- Relações físicas podem ser **estimadas** usando dimensões  
- Método da análise dimensional:
  1. Identificar grandezas relevantes  
  2. Representar cada grandeza em termos de \(M, L, T\)  
  3. Encontrar combinação que respeite dimensões

Exemplo: período de um pêndulo \(T \sim \sqrt{\frac{L}{g}}\)  
- \(T\) → \(T\)  
- \(L\) → \(L\)  
- \(g\) → \(L/T^2\)  
- Dimensionalmente: \(\sqrt{L / (L/T^2)} = \sqrt{T^2} = T\) ✅

---

## 6. Aplicações
- Verificação de fórmulas em física e engenharia  
- Conversão de unidades  
- Estimativas aproximadas de grandezas  
- Desenvolvimento de leis físicas e correlação experimental

---

## 7. Resumo Final
- Análise dimensional garante **consistência de equações**  
- Usa símbolos fundamentais: \(M, L, T, I, \Theta, N, J\)  
- Permite conversão de unidades e previsão de fórmulas  
- Essencial para ENEM, problemas de física experimental e engenharia
