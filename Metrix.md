Precision -> сколько из всего выбраного является истино позитивным
$$  \require{enclose} \begin{array}{c} 
Precision = \cfrac{TP}{TP + FP}

\end{array} $$

Recall -> сколько выбрано нужных элементов из всех нужных элементов
$$  \require{enclose} \begin{array}{c} 
Recall = \cfrac{TP}{TP + FN}

\end{array} $$

F-мера -> среднее гармоническое precision и recall она стримится к нулю если Precision или Recall стремится к нулю. Возможно рассчитать F-меру придав различный вес точности и полноте, если вы осознанно отдаете приоритет одной из этих метрик при разработке алгоритма.
$$  \require{enclose} \begin{array}{c} 

F = 2\cfrac{Precision \times Recall}{Precision + Recall}

\end{array} $$
<center> <span style="color: gray;">*среднее гармоническое precision и recall*</span> </center>

$$  \require{enclose} \begin{array}{c} 

F = (\beta^2 + 1) \cfrac{Precision \times Recall}{\beta^2Precision + Recall}

\end{array} $$
<center> <span style="color: gray;">*среднее гармоническое с приоритетом*</span> </center>

Accuracy -> точность угадывания правильных ответов среди всех угадааных 
$$  \require{enclose} \begin{array}{c} 

Accuracy = \cfrac{TP + TN}{TP + TN + FP + FN}

\end{array} $$

Loss function -> необходима для того, чтобы измерять и минимизировать ошибки модели, направлять процесс оптимизации параметров, регулировать сложность модели и оценивать её производительность. Существует множество видов функции потерь [Loss](Loss)

standart derivation

optimizer

normalization

Gradient

Regulization