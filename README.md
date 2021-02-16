# Multilayer Perceptron (MLP) câncer de mama

## Multilayer Perceptron (MLP)

Este é um exemplo que pode ser encontrado [aqui também](https://www.youtube.com/watch?v=YH0HuJd-nj8)

\\

https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html


As Redes Neurais são uma estrutura de aprendizado d máquina que tenta imitar o padrão de aprendizagem de redes neurais biológicas naturais. As redes neurais biológicas têm neurônios interconectados com dendritos que recebem entradas, e com base nessas entradas eles produzem um sinal de saída através de um axônio para outro neurônio. Vamos tentar imitar esse processo através do uso de Redes Neurais Artificiais (RNAs), que apenas nos referiremos como redes neurais a partir de agora. O processo de criação de uma rede neural começa com a forma mais básica, um único ``perceptron``.   


Vamos começar nossa discussão falando sobre o Perceptron! 

Um Perceptron tem uma ou mais entradas, um viés (bias), uma função de ativação e uma única saída. O Perceptron recebe entradas, multiplica essas entradas por algum peso e passa-as para uma função de ativação para produzir uma saída. Há muitas funções de ativação possíveis tais como a função logística, uma função trigonométrica, uma função de step, etc. Também nos certificamos de adicionar um viés para o Perceptron, isso evita problemas onde todas as entradas poderiam ser iguais a zero (significado Nenhum peso multiplicativo teria um efeito).



![alt text](https://miro.medium.com/max/1250/1*cuTSPlTq0a_327iTPJyD-Q.png)
