Functional Classes CSS
=================

Às vezes precisamos manipular características de elementos que já foram customizados pelo CSS. Normalmente quando manipulamos elementos com javascript, precisamos modificar diversas vezes as características básicas dos objetos no HTML. Vira e mexe você precisa esconder, fazer aparecer, transformar em bloco ou linha, retirar margens, paddings e etc… você pode fazer isso com Javascript ou com uma simples linha de CSS.

A ideia é que você tenha uma biblioteca de classes reutilizáveis. Se você já leu sobre [OOCSS](http://tableless.com.br/oocss-ou-css-do-jeito-certo/) você entende que a reutilização de código de forma controlada é ótimo para todo o projeto. Dessa forma é possível extender estruturas e controlar designs e layouts de forma mais uniforme e controlada. Eu costumo chamar isso de classes funcionais.

Essa classes tem uma única função: modificar uma determinada característica dos elementos. Pode ser que um elemento por padrão contenha um float ou um position. Quando ele foi criado, essa propriedade deve ter sido inserida por conta do ambiente inicial na qual ele seria utilizado. Mas agora essa mesma estrutura será reutilizada em diversos momentos no projeto. Pode ser que o float atrapalhe e você tenha que tirá-lo. Aí você utiliza as classes funcionais para te dar essa força.

Essa combinação de classes é necessária por que você vai reutilizar código HTML durante todo o seu projeto. Normalmente são pequenas modificações ESTRUTURAIS. Uso muito pouco classes funcionais para modificar características visuais de layout, por exemplo cores, backgrounds e etc. Apenas em projetos que necessitam ter modificações de templates ou skins. No exemplo acima apenas retiramos a margin-bottom e o border-bottom do elemento.