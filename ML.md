[Layers](Layers)
[Metrix](Metrix)
batch size = размер пакетов фотографий, 1 batch = 1 градиентный спуск

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

Loss function -> необходима для того, чтобы измерять и минимизировать ошибки модели, направлять процесс оптимизации параметров, регулировать сложность модели и оценивать её производительность.

standart derivation

optimizer

normalization

Gradient

Regulization


640 фотографий, batch size = 64, 100 пакетов будет и значит 100 градиентных спусков



вне гласное правило batch size % 4 = 0 

batch size маленткий -> мало эпох
batch size большой -> много эпох

## Beginer

AI courses [Click](https://www.deeplearning.ai)
LLM [Click](https://www.youtube.com/@AndrejKarpathy/videos)
Layers types [Click](https://www.youtube.com/watch?v=DApk93qmHBE&list=PL-z9LMshkhjTqqOL15PwjndUetcgVhT2b)

## Intermediate

PyTorch, Real-Time segmentation/classification [Click](https://www.youtube.com/@Koldim2001/videos)

## Advanced

. . .
