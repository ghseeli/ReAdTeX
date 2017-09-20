# ReAdTeX
My LaTeX macros and shortcuts

# Manifesto

(La)TeX is a technical typesetting tool and Turing-complete language and this fact should be leveraged to the advantage of writers. In programming languages, an important feature of any language is its "readability," or how quickly can readers intuit the intention and functioning of the code. To the unititiated, (La)TeX can be difficult to parse and, to the experienced, has many readability shortfalls.

Specifically, and for good reasons, in (La)TeX, typeset symbols are named after what the symbols are, such as "\cup" for a set union symbol or "\rightarrow" for an arrow pointing right, typically shorthanded by mathematicians to "\to". Such shorthands make code more readable. Contrast `f: X \rightarrow Y` to `f: X \to Y`. The latter reads more like how a mathematician would refer to the typeset result in English. Thus, I think there are benefits to extending such ideas further, even at the sake of taking slightly longer to type. For instance, I propose `A \cup B \cap C` should be long-handed to `A \union B \intersect C`. While it takes slightly longer to type, the benefits are 2 fold.

1. The *intent* of the typist is more clear. It is easy to mistype `\cap` for `\cup`. This reduces typos.
  Parsing the TeX code is much faster.
