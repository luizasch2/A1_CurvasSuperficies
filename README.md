# Estudo sobre as Equações de Frenet e a Função Curvatura em Python

## Introdução
Este projeto foi desenvolvido como parte da disciplina de Curvas e Superfícies na Fundação Getulio Vargas - Escola de Matemática Aplicada (FGV-EMAp). O foco principal é explorar e implementar as Equações de Frenet e a Função Curvatura utilizando Python, com o objetivo de gerar visualizações gráficas de curvas 2D a partir de suas propriedades curvaturais.

## Objetivos
- Compreender e aplicar as Equações de Frenet para descrever curvas no espaço euclidiano.
- Desenvolver uma aplicação em Python para calcular e visualizar a curvatura de curvas 2D.
- Utilizar técnicas de análise numérica para resolver as equações diferenciais envolvidas no processo.

## Metodologia
O trabalho envolve o estudo das equações de Frenet, que consistem em um conjunto de três equações diferenciais ordinárias de primeira ordem. Estas equações são fundamentais para descrever a curvatura e a torção de uma curva. Para desenhar a curva a partir de sua curvatura, abordamos o problema de resolver estas equações diferenciais utilizando métodos numéricos populares, incluindo:
- Método de Runge-Kutta de quarta ordem.
- Método de Euler.

O código foi implementado em Python, utilizando as bibliotecas `matplotlib`, `sympy`, `scipy`, e `numpy` para manipulação matemática e visualização gráfica.

## Requisitos de Software
Para executar o código deste projeto, você precisará instalar as seguintes bibliotecas:
- `matplotlib`: Usada para criar gráficos e visualizações de dados.
- `numpy`: Fundamental para cálculos numéricos e manipulação de arrays.
- `sympy`: Utilizada para cálculos simbólicos.
- `scipy`: Empregada para métodos de análise numérica mais complexos.

## Instalação
Para instalar todas as dependências necessárias, você pode usar o seguinte comando pip:

```bash
pip install matplotlib numpy sympy scipy
```