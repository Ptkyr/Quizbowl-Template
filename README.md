# Quizbowl-Template
This is a template for writing Quizbowl packets.

The main features are the `tossup` and `bonus` environments which automatically number themselves (and will not split across pages), and the various answerline commands. Unfortunately it is impossible to design commands to make all possible answer lines easier to type up, but the more common patterns have been covered. You will likely have to manually format a lot of stuff.

There is also optional support for explicit powers: if the `powers` package option is set to true, tossup text will be bold until `\powmark` is used in the tossup.

Two examples with ([code](./powerexample.tex), [pdf](./powerexample.pdf)) and without ([code](./example.tex), [pdf](./example.pdf)) powers are provided.

Formatting based off of 2022 ACF Nationals, other than the header (which can easily be changed).
