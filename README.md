# Oraculo-Reading-Guide
Guia de leitura para entender o Oraculo, um classificador de boletins de ocorrência policiais.

# 1. Oraculo

Inicie por uma leitura completa do sistema, presente nos artigos e trabalhos acadêmicos que descrevem o sistema:

- (Artigo) [Matos, et. al, 2022](./academic/Artigo-Oraculo.pdf). Descrição resumida do modelo de aprendizado.

- (TCC) [Matos, 2022](./academic/TCC-Helder.pdf). Descrição completa do modelo de aprendizado e da implantação do sistema na SIAC.

# 2. Conceitos

Em seguida, estude os tópicos a seguir em sequência:

- [Artificial Intelligence](./books-papers/RUSSEL-NORVIG-Artificial_Intelligence_4th.pdf). Conhecido como AIMA, é leitura obrigatória para todos os pesquisadores em IA. Os fundamentos de IA estão apresentados nos capítulos 1, 2, 3 e 4. Capítulos posteriores serão revisitados em tópicos futuros.
- [Knowledge Discovery in Databases - KDD](./books-papers/1996-fayyad.pdf): é o processo de sistema baseado em conhecimento mais tradicional, em que a maioria dos trabalhos acadêmicos se baseia.
- [Cross-Industry Standard Process for Data Mining - CRISP-DM](./books-papers/ModelerCRISPDM.pdf): é uma derivação do KDD, serve para propósitos de mercado e indústria, e é o que foi aplicado de fato no Oraculo. O documento é um relatório técnico que a IBM preparou para guiar os entusiastas na modularização das etapas.
- [Data Mining](./books-papers/AGGARWAL-Data_Mining.pdf). Esse livro tem uma pegada mais conceitual e matemática, mas a leitura dele vai consolidar os conceitos de KDD e explorar eles com mais profundidade. Não subestimar a preparação dos dados, 80% do trabalho se concentra nisso. Os capítulos importantes são 1 e 2. Capítulos importantes serão revisitados em tópicos futuros. 
- [Machine Learning](./books-papers/burkov.pdf). A essa altura machine learning já foi mencionado várias vezes, então nada melhor que uma leitura rápida para fixar. Capítulos 1, 4, 5, 6, 7. Aqui você pode revistar o AIMA, capítulo 19, para entender os fundamentos de ML.
- [Neural Networks](./books-papers/1999-Haykin.pdf). Aqui é importante entender a matemática dos modelos neurais, vai ajudar em melhorias futuras. Capítulos 1, 2, 3 e 4.
- [Deep Learning](./books-papers/CHOLLET-Deep_Learning_with_Python_2nd.pdf). Esse livro é o balanceamento perfeito entre teoria e prática, sem falar que o autor é ninguém mais que o criador da biblioteca Keras. Capítulos 1, 2, 3, 4, 5, 6 e 7. Aqui você pode revistar o AIMA, capítulo 21, para entender os fundamentos de DL. O capítulo 11, pode ser lido após o tópico de NLP.
- [Natural Language Processing](./books-papers/Livro_PLN.pdf). O Oraculo realiza a mineração de texto, logo entender PLN é fundamental. Os capítulos mais importantes desse livro são 1, 3, 4 e 5. Os capítulos 7 e 8 também são importantes, mas serão tratados com mais detalhes nas referências a seguir. Aqui você pode revistar o AIMA, capítulo 23 e 24, para entender os fundamentos de NLP e as técnicas avançadas.


# 3. Frameworks

- [Numpy](https://numpy.org/): manipulação de dados numéricos.
- [Pandas](https://pandas.pydata.org/): manipulação de dados tabulares.
- [Matplotlib](https://matplotlib.org/) e/ou [Plotly](https://plotly.com/): visualização da informação.
- [TensorFlow](https://www.tensorflow.org/): algoritmos de deep learning.
- [Keras](https://keras.io/): interface amigável para o TensorFlow.
- [NLTK](https://www.nltk.org/): processamento de linguagem natural clássica.
- [Spacy](https://spacy.io/): processamento de linguagem natural avançada. 
- [Qt](https://www.qt.io/): interfaces gráficas de desktop de rápida implementação.