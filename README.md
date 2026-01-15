# FEA_python


# 1. Como este código funciona?

O código gera aleatoriamente uma matriz $A\in\mathbb{R}^{n\times n}$ e um vetor $b\in\mathbb{R}^{n}$, e executa:

1. **Eliminação progressiva** (formação de $U$ e modificação de $b$)  
2. **Substituição regressiva** para obter $x$  
3. **Verificação** computando $U,x$ e o **erro médio** após a eliminação  
4. **Métricas**: contagem de FLOPs soma/subtração e multiplicação/divisão por etapa e totais, além do **tempo de CPU**

> Para $n<11$, o programa imprime $A$, $b$, $U$ (matriz após eliminação), $b^*$ (vetor após eliminação) e $x$.
# 2. Como rodar este código?
Para executar o código, é necessário:
1.	Ter o Python 3.x instalado
2.	Instalar a biblioteca SymPy:
3.	pip install sympy
4.	Salvar o código em um arquivo, por exemplo:
5.	analise_trelica.py
6.	Executar no terminal ou ambiente Python:
7.	python analise_trelica.py

# 3. Qual problema este código resolve?
O código resolve de forma eficiente um problema clássico de análise estrutural de treliças, demonstrando:
•	a formulação matemática do MEF;
•	a montagem da matriz de rigidez global;
•	a aplicação de métodos numéricos para solução de sistemas lineares
