# [Essence](https://conjure.readthedocs.io/en/latest/essence.html) language package for [CodeMirror 6](https://codemirror.net/6/)

On [GitHub](https://github.com/stylpe/lang-essence) and [Replit](https://replit.com/@SuperMikal/codemirror-lang-essence)

From the abstract of the original [paper defining Essence](https://doi.org/10.1007/s10601-008-9047-y):

> Essence is a formal language for specifying combinatorial problems in a manner similar to natural rigorous specifications that use a mixture of natural language and discrete mathematics. Essence provides a high level of abstraction, much of which is the consequence of the provision of decision variables whose values can be combinatorial objects, such as tuples, sets, multisets, relations, partitions and functions. Essence also allows these combinatorial objects to be nested to arbitrary depth, providing for example sets of partitions, sets of sets of partitions, and so forth. Therefore, a problem that requires finding a complex combinatorial object can be specified directly by using a decision variable whose type is precisely that combinatorial object.

## TODO
(see the [language support example](https://codemirror.net/6/examples/lang-package/) for a more detailed tutorial):

 * [x] `git grep EXAMPLE` and replace all instances with your language name.

 * [ ] Rewrite the grammar in `src/syntax.grammar` to cover your language. See the [Lezer system guide](https://lezer.codemirror.net/docs/guide/#writing-a-grammar) for information on this file format.

 * [ ] Adjust the metadata in `src/index.ts` to work with your new grammar.

 * [ ] Adjust the grammar tests in `test/cases.txt`.

 * [ ] Build (`npm run prepare`) and test (`npm test`).

 * [x] Rewrite this readme file.

 * [ ] Optionally add a license.

 * [ ] Publish. If you want to use a `@codemirror/lang-...` package name, open an [issue](https://github.com/codemirror/codemirror.next/issues) to ask for npm publish rights for that name.
