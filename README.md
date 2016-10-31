# wordAttributes

This is a repository of documents and encoding snippets, a basis for a feature request submitted to the TEI Technical Council concerning new inline attributes of the element `<w>`. We are aiming for minimally the trio of `@lemma`, `@pos` (for part-of-speech) and `@reg` (for the normalized form in e.g. historical corpora), with `@msd` (for morphosyntactic description) being a welcome fourth. Because five is perfect (as uncontroversially evidenced by many of our hands, feet, as well as umami), we can also, following the example of the Perseus project, add a `@head` attribute that can be used for simple word-grammar (~ relational grammar) dependency graphs. 

The overall principle invoked here is the well-known KISS (for "keep it simple, scholar, or else you will end up alone in your armchair, while many corpus linguists adopt other annotation formats"). At no point is it claimed that these suffice for comprehensive lexical/structural description in a world with a zillion taggers and umpteen popular linguistic theories. However, sometimes (quite often, in fact) these provide are just the right amount of information for just the right cost (and time) of processing. The trick is to keep this as a sort of "corpus TEI Simple" for those who require only these simple means or else they move to other formats to get them. And, at the same time, to make sure that these means of description are aligned with the robust apparatus that the TEI offers, featuring e.g. standoff annotation and/or feature-structure matrices.

The deliverable should be, minimally, 
* a set of definitions to be included in the source of the TEI Guidelines
* the prose to accompany those definitions in the text of the appropriate chapter
* short examples of use (for the documentation)
* possibly "[Exemplars](https://github.com/TEIC/TEI/tree/dev/P5/Exemplars)" (more robust examples that can also act as a test suite)

Because we are assuming here simple cases with a single set of features for each `<w>`, it is not clear if it is worth to also suggest an attribute for the certainty score.
