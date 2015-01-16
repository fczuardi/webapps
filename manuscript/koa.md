# koa

[Koa][1] é um framework web minimalista, pode ser encarado como uma evolução
do [Express][2], suas características principais são o tamanho/footprint
pequeno (não vem com nenhum middleware de fábrica) e a sintaxe simplificada baseada em [generators][3] (uma novidade do
[ES][4]6) que permite uma representação da pilha de middlewares de uma
maneira mais fácil de ler e acompanhar.

## mas o que é middleware?

Resumidamente, é uma função mediadora que neste contexto de frameworks
para servidores hhtp (koa, express, etc…) atua em algum ponto do ciclo de
vida de uma chamada http. É um intermediário que implementa funcionalidades
comuns e úteis que facilitam nossa vida trazendo produtividade por eliminar
a necessidade de reinventar a roda.

Alguns exemplos de funcionalidades que podem ser "empilhadas" em uma chamada
a uma url da sua aplicação:

- roteamento
- autenticação
- compressão
- cache
- e muitas outras, consulte a [lista de middlewares na wiki][5] ou busque por
["koa" no npm][6]


[1]: http://koajs.com/
[2]: http://expressjs.com/
[3]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*
[4]: http://en.wikipedia.org/wiki/ECMAScript "Ecma Script"
[5]: https://github.com/koajs/koa/wiki#middleware
[6]: https://www.npmjs.com/search?q=koa
