# Treliça plana


# 1. Como este código funciona?
O código desenvolvido executa tarefas como:
- Cálculo de matrizes de rigidez de elementos do tipo barra, com 4 graus de liberdade globais;
- Transformação de forças, deslocamentos e rigidez do sistema de coordenadas local (do elemento) para o sistema de coordenadas global (estrutura);
- Aplicação da técnica do espalhamento para montagem da rigidez global da estrutura;
- Definição das condições de contorno e de carregamento do problema, bem como os parâmetros geométricos e de material;
- Resolução do sistema de equações lineares utilizando a regra de Cramer.

# 2. Como rodar este código?
Para executar o código, é necessário:
1.	Ter o Python 3.x instalado;
2.	Instalar as bibliotecas SymPy e Math;
3.	Salvar o arquivo do código em um arquivo e executá-lo em um ambiente de desenvolvimento integrad (IDE) como Jupyter Notebook, Google Colab, Visual Basic Studio, entre outros.

# 3. Qual problema este código resolve?
O código resolve um problema clássico de análise estrutural estática linear de uma treliça plana (cuja imagem se encontra no mesmo diretório deste arquivo README) mediante a Regra de Cramer.
