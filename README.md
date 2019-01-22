# ReAdTeX
My Mathematics LaTeX macros and shortcuts

# Manifesto

(La)TeX is a technical typesetting tool and Turing-complete language used by mathematicians (and others!) to type their work. I think the Turing-completeness should be leveraged to the advantage of writers. In programming languages, an important feature of any language is its "readability," or how quickly can readers intuit the intention and functioning of the code. To the unititiated, (La)TeX can be difficult to parse and, to the experienced, has many readability shortfalls.

Specifically, and for good reasons, in (La)TeX, typeset symbols are named after what the symbols are, such as "\cup" for a set union symbol or "\rightarrow" for an arrow pointing right, typically shorthanded by mathematicians to "\to". Such shorthands make code more readable. Contrast `f: X \rightarrow Y` to `f: X \to Y`. The latter reads more like how a mathematician would refer to the typeset result in English. Thus, I think there are benefits to extending such ideas further, even at the sake of taking slightly longer to type. For instance, I propose `A \cup B \cap C` should be long-handed to `A \union B \intersect C`. While it takes slightly longer to type, the benefits are 3 fold.

1. The *intent* of the typist is more clear. It is easy to mistype `\cap` for `\cup`. This reduces typos.
1. Parsing the TeX code is much faster for a human reader.
1. A standard set of commands makes it easier for readers to change conventions to their tastes.

Many such long-hands will be added here, along with typical convenience functions that I use in my LaTeX documents. Many of these ideas are inspired by my work on ghseeli/grad-school-notes. After using this system with collaborators and on my own, I believe it offers many merits worth the slight time disadvantages that come with typing a few extra characters here or there.
