# Propriedades Dinâmicas e Topológicas do Mapa Logístico

[![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)](#)
[![Instituição](https://img.shields.io/badge/UNESP-FEIS-blue)](https://www.feis.unesp.br/)
[![Área](https://img.shields.io/badge/%C3%81rea-Matem%C3%A1tica%20%2F%20Sistemas%20Din%C3%A2micos-orange)](#)

Este repositório contém o **Relatório Final de Iniciação Científica (IC)** intitulado **"Propriedades Dinâmicas e Topológicas do Mapa Logístico"**, desenvolvido no Departamento de Matemática da Universidade Estadual Paulista "Júlio de Mesquita Filho" (UNESP) - Faculdade de Engenharia de Ilha Solteira.

---

## 👨‍💻 Autoria e Orientação

* **Aluno:** Pedro Henrique da Silva Zonta  
  📧 *Email:* [pedro.zonta@unesp.br](mailto:pedro.zonta@unesp.br)
* **Orientador:** Prof. Dr. Danilo Antonio Caprio  
  📧 *Email:* [danilo.caprio@unesp.br](mailto:danilo.caprio@unesp.br)
* **Instituição:** Universidade Estadual Paulista (UNESP) — Câmpus de Ilha Solteira (FEIS/Departamento de Matemática)  
* **Data:** Setembro de 2026  

---

## 📖 Resumo do Trabalho

O trabalho dedica-se ao estudo de noções fundamentais da teoria dos **sistemas dinâmicos discretos**, com ênfase na análise da **família logística**:

$$f_{\mu}(x) = \mu x(1 - x), \quad \mu \in \mathbb{R}_{+}$$

Demonstra-se como pequenas variações no parâmetro $\mu$ alteram drasticamente a estrutura do sistema, provocando o surgimento de bifurcações, conjuntos de Cantor, e comportamento caótico imprevisível.

Para viabilizar a análise rigorosa dos conjuntos de Julia cheios e das órbitas, utiliza-se a **dinâmica simbólica** no espaço de sequências $\Sigma_2$ e a **aplicação shift** ($\sigma$), provando a **conjugação topológica** entre os sistemas.

---

## 🗂️ Estrutura do Relatório

1. **Sistemas Dinâmicos Discretos:** Conceitos iniciais, tempo discreto e exemplos de evolução populacional.
2. **Definições Elementares:** Órbitas futuras/passadas, pontos fixos, periódicos, eventualmente periódicos, conjuntos estáveis/instáveis ($W^s, W^u$), pontos críticos e a técnica do retrato de fase.
3. **Hiperbolicidade e Bifurcação:** Classificação de pontos fixos/periódicos (atratores, repulsores e neutros), bifurcação de ponto de sela (*saddle-node*) e duplicada de período (*period-doubling*).
4. **Família Logística:** Estudo do parâmetro $\mu$, análise de estabilidade nos intervalos $0 < \mu \le 1$, $1 < \mu < 3$, surgimento de ciclos periódicos e a formação do **Conjunto de Cantor** para $\mu > 2 + \sqrt{5}$ (e $\mu > 4$).
5. **Dinâmica Simbólica:** Espaço de sequências infinitas $\Sigma_2$, métrica $d[s,t]$, Teorema da Proximidade e propriedades da **aplicação Shift** ($\sigma$).
6. **Conjugação Topológica:** Definição do **Mapa Itinerário** $S: \Lambda 	o \Sigma_2$, prova de que $S$ é um homeomorfismo e satisfaz $S \circ F_\mu = \sigma \circ S$. Introdução ao conceito de semi-conjugação.
7. **Caos:** Definição rigorosa de Caos no sentido de Devaney (dependência sensível às condições iniciais, transitividade topológica e densidade de pontos periódicos). Prova do comportamento caótico de $F_\mu$ para $\mu > 2 + \sqrt{5}$ e de $F_4(x) = 4x(1-x)$.

---

## 🎯 Principais Resultados

* **Bifurcações e Estabilidade:** Mapeamento preciso da perda de estabilidade de pontos fixos e criação de novos ciclos periódicos à medida que o parâmetro evolui.
* **Geometria Fratal:** Demonstração de que o conjunto de pontos cujas órbitas permanecem limitadas no intervalo $[0,1]$ para $\mu > 2+\sqrt{5}$ forma um conjunto de Cantor $\Lambda$.
* **Equivalência Dinâmica:** A conjugação topológica entre $F_\mu$ em $\Lambda$ e o mapa shift em $\Sigma_2$ permite transpor propriedades complexas de $F_\mu$ para a álgebra simples de sequências binárias.
* **Caracterização do Caos:** Prova formal de que o mapa logístico atende a todos os critérios de Devaney para comportamento caótico.

---

## 📚 Referência Principal

* DEVANEY, Robert L. **An Introduction to Chaotic Dynamical Systems**. 3rd ed. CRC Press, 2022.

---

## 📄 Arquivos do Repositório

* `IC.pdf`: Relatório final completo em formato PDF contendo todas as demonstrações matemáticas, gráficos e análises detalhadas.
