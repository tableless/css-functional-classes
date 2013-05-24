Functional Classes CSS
=================

Às vezes precisamos manipular elementos que já foram estilizados pelo CSS ou precisamos usar javascript para modificar diversas vezes as características básicas desses elementos. Vira e mexe você precisa esconder, fazer aparecer, transformar em bloco ou linha, retirar margens, paddings e etc… as classes funcionais podem te ajudar nesse trabalho dinâmico, ou manualmente, inserindo as classes direto no HTML para ajudar na construção de estruturas.

A ideia é que você tenha uma biblioteca de classes reutilizáveis. Se você já leu sobre [OOCSS](http://tableless.com.br/oocss-ou-css-do-jeito-certo/) você entende que a reutilização de código de forma controlada é ótimo para todo o projeto. Dessa forma é possível estender estruturas e controlar designs e layouts de forma mais uniforme e controlada.

Essas classes tem uma única função: modificar uma determinada característica no elemento aplicado. Suponha que você tenha um elemento por padrão comalguma propriedade como um float ou um position. Quando este elemento foi criado, essas propriedades podem ter sido inseridas por conta do cenário inicial na qual ele seria utilizado. Mas agora esse elemento deverá ser reutilizado em diversos momentos no projeto, posicionando-o de forma diferente, por exemplo. Nesse ponto, com a mudança de uma classe, você consegue fazer o elemento se adaptar ao cenário desejado.

Essa combinação pode ser muito útil para a reutilização do código HTML durante todo o seu projeto. Normalmente são pequenas modificações ESTRUTURAIS. Usa-se muito pouco as classes funcionais para modificar características visuais de layout (lembra a separação por camadas?), por exemplo cores, backgrounds e etc.