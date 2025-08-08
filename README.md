# Exercício de Fixação 4 - Cálculo das Raízes de uma Equação do 2º Grau

Este projeto em C# lê os coeficientes `a`, `b` e `c` de uma equação quadrática da forma:

ax² + bx + c = 0

e calcula as raízes reais da equação utilizando a fórmula de Bhaskara.

---

## Como funciona

1. O programa solicita ao usuário que digite os valores de `a`, `b` e `c`.
2. Calcula o valor do delta (Δ), onde:
   
Δ = b² - 4ac

3. Verifica se:
- `a` é diferente de zero, para garantir que é uma equação do 2º grau.
- `delta` é maior ou igual a zero, para garantir raízes reais.

4. Se alguma das condições não for satisfeita, exibe a mensagem:

Impossível de Calcular !!!

5. Caso contrário, calcula as raízes `r1` e `r2`:

r1 = (-b + √Δ) / (2a)
r2 = (-b - √Δ) / (2a)

6. Exibe as raízes com 5 casas decimais.
