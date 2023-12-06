様々な数値計算法のpythonによるコードを載せています。
順次更新予定。

・ニュートン法 newton.py\n
ある数の平方根を求めます。平方根を求めたい数と初期値を入力するとステップごとの数の変化と最終的な解が与えられます。\n
収束判定はdeの値によるため、変更したい場合はコードの変更をしてください。

・最急降下法 gradient_descent.py\n
f(x,y)=a x^2 + b y^2 + c xy + d x + e y + f の係数a,b,c,d,e,fを入力すると、ステップごとの数の変化と最終的な最小値とその時の(x,y)が与えられます。\n
探索点更新の際の係数を一定のαにする場合と、進行するごとに変更するタイプの二つを用意しています。αを変えたい場合や、変更の仕方を変えたい場合はコードの変更を行ってください。
収束判定はdeの値によるため、変更したい場合はコードの変更をしてください。

・共役勾配法 conjugate_gradient_with_cholesky\n
Ax=bの線形システムを解くものです。ステップごとの数の変化と最終的な解が与えられます。\n
不完全コレスキー分解による前処理を行うものと、行わないものがあります。\n
線形システムの値を変更したい場合はコードを変更してください。\n
