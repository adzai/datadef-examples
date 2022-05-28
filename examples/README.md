## datadef examples

Example usages of datadef and the dtb module are in
the `examples` folder.

**Generate documentation**

`cd example-doc`

`scribble +m doc.scrbl`

`open doc.html`

**Run tests**

`raco test **.rkt`

**Run example server**

`cd examples`

`racket server.rkt`

Test with curl:

`curl localhost:7777/users`
