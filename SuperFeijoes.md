# Super Feijoes

Omar é fã de shows de mágica, ele já foi em tantos que conhece todos os truques. Porém ele sempre se perde quando o mágico resolve fazer o truque dos feijões, no qual ele coloca um feijão embaixo de um dos quatro copos e os embaralha para perguntar à plateia onde o feijão foi parar. 

Por isso ele resolveu pedir sua ajuda pra criar um programa que dado a posição inicial do feijão e todas as trocas realizadas, diga em qual copo o feijão está no final do truque.

### Entrada :
Na primeira linha seguirão quatro inteiros, <img src="/tex/9b4d3d40ed3821f6448f28262c17452b.svg?invert_in_darkmode&sanitize=true" align=middle width=21.14384744999999pt height=22.465723500000017pt/>, <img src="/tex/7eef4793074d0a551e3525b3ed939b88.svg?invert_in_darkmode&sanitize=true" align=middle width=21.14384744999999pt height=22.465723500000017pt/>, <img src="/tex/558fe189a024544b44b192f8fb9b6cd9.svg?invert_in_darkmode&sanitize=true" align=middle width=21.14384744999999pt height=22.465723500000017pt/> e <img src="/tex/30bcfc530b6a9d251e4ad8e01ef75b68.svg?invert_in_darkmode&sanitize=true" align=middle width=21.14384744999999pt height=22.465723500000017pt/> separados por um espaço. O valor <img src="/tex/d103603c39d6c39459c8b588df204c83.svg?invert_in_darkmode&sanitize=true" align=middle width=48.72470459999999pt height=22.465723500000017pt/> indica que o feijão estava no copo na posição <img src="/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/>, e <img src="/tex/e1e0773d381a0e0ec88b4ba769e52046.svg?invert_in_darkmode&sanitize=true" align=middle width=48.72470459999999pt height=22.465723500000017pt/> indica que o <img src="/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/>-ésimo copo esta vazio. 

Em seguida, segue um número <img src="/tex/f9c4988898e7f532b9f826a75014ed3c.svg?invert_in_darkmode&sanitize=true" align=middle width=14.99998994999999pt height=22.465723500000017pt/>, o número de trocas realizadas. As próximas <img src="/tex/022a4317e28b2e323d4ba16298524c9e.svg?invert_in_darkmode&sanitize=true" align=middle width=81.30117269999998pt height=26.76175259999998pt/> linhas contêm dois inteiros <img src="/tex/3e384b223dce750e6c98aa501355f00b.svg?invert_in_darkmode&sanitize=true" align=middle width=20.679527549999985pt height=21.68300969999999pt/>, <img src="/tex/5d205a948d20e2734c1f4a087304e795.svg?invert_in_darkmode&sanitize=true" align=middle width=80.95320749999999pt height=21.68300969999999pt/> representando que o <img src="/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/>-ésimo copo foi trocado de lugar com o <img src="/tex/36b5afebdba34564d884d347484ac0c7.svg?invert_in_darkmode&sanitize=true" align=middle width=7.710416999999989pt height=21.68300969999999pt/>-ésimo copo.
Haverá sempre exatamente um copo com o feijão.

### Saida
Baseando-se nas trocas feitas, imprima um número <img src="/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/>, indicando que ao final das trocas o feijão estará no <img src="/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/>-ésimo copo. Haverá sempre exatamente um copo com o feijão.

| Exemplo de entrada | Exemplo de saída |
|--|--|
| 0 0 0 1 | 1 |
| 7 |
| 4 3 |
| 3 3 |
| 3 2 |
| 3 2 |
| 1 2 |
| 2 3 |
| 1 2 |
