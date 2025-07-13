# Cessna-152
Numerical Solution in Python of the Longitudinal Motion Equation of the Cessna 152 and Evolution of the Angle of Attack Under the Influence of Small Perturbations
Cessna-longitudinal-simulation/

# Simulação Numérica – Cessna 152

Este projeto simula numericamente o movimento longitudinal do avião **Cessna 152**, com foco na variação do **ângulo de ataque (α)** após pequenas perturbações. O objetivo é estudar a **estabilidade longitudinal** da aeronave usando métodos numéricos em Python.

---

##  Sobre o Projeto

A simulação considera a formulação **linearizada** do movimento longitudinal e utiliza equações diferenciais ordinárias (EDOs) resolvidas numericamente. O modelo avalia como o nariz da aeronave (arfagem) reage a perturbações no tempo.

---

## Tecnologias utilizadas

- Python 3
- NumPy
- SciPy
- Matplotlib
- Google Colab

---

## Resultados

Neste trabalho, modelamos a dinâmica longitudinal linearizada da aeronave Cessna 152 sob pequenas perturbações em torno de um ponto de equilíbrio em voo nivelado. O sistema foi descrito por quatro variáveis de estado: perturbações na velocidade 𝑈', ângulo de ataque 𝛼', ângulo de inclinação 𝜃 e velocidade angular de arfagem q'.

A partir dos parâmetros físicos e aerodinâmicos do modelo, obtivemos as derivadas de estabilidade, que compuseram a matriz dinâmica 𝐴 do sistema linearizado. Em seguida, implementamos uma simulação numérica via método de Runge-Kutta de 4ª ordem, analisando a resposta temporal do sistema para uma condição inicial com pequenas perturbações.

Além disso, representamos graficamente o campo de vetores no plano de fase (𝛼,𝑞) , evidenciando o comportamento dinâmico ao redor do equilíbrio. Foi possível observar uma trajetória típica de retorno estável, com oscilações amortecidas, representando a resposta natural da aeronave a distúrbios suaves.

A análise dos autovalores da matriz 𝐴 confirmou a presença dos dois modos clássicos da dinâmica longitudinal:

Um modo oscilatório amortecido (com autovalores complexos conjugados), que representa o modo de período curto da aeronave;

Um modo real negativo mais lento, associado ao amortecimento suave do modo phugoid.

Esses resultados mostram que o sistema é estável, pois todos os autovalores possuem parte real negativa, e que a resposta natural do Cessna 152 tende ao equilíbrio após uma perturbação.

Gráficos da simulação mostram como o ângulo de ataque varia com o tempo após a perturbação inicial, ilustrando a resposta dinâmica da aeronave.
---

## Autor

Trabalho acadêmico desenvolvido por **Pablo Machado**  
para a disciplina de **Matemática Computacional III** – UFSM

---
