eux
===

Support transparency by providing other and improved means of search over a selected EU document corpus.

Corpus: Legal documents
-----------------------

The EU continuously publishes legal documents on [http://eur-lex.europa.eu](http://eur-lex.europa.eu),
including treaties, international agreements, legislation and more. There exists an simple and advanced
search form that provides multilingual full text access, as well as search by date, document identifiers,
type of act (decision, directive, ...).

Observations: There is still information contained in the documents, that would be interesting to
mine and to use for other kind of searches.

* Geographic relationships

    > show me all *international agreements* between the *EU* and the *Kingdom of Norway*

* Currency

    > show me all documents, that mention sums between EUR 10000 and EUR 20000

    Example from corpus:

    > she had won a prize of EUR 20 000. It was clear from

* A dependency graph and linkage of regulations

    > show me all *directives* that reference *Regulation No 44/2001*

    Or even more fine grained:

    > show me all *directives* that reference *Article 2 of Regulation No 44/2001*

    By applying a ranking algorithm (such as pagerank) to the dependency graph
    of regulations one could identify important documents within the corpus,
    or within parts of it.

* Named entity recognition

    The legal documents contain various names, that could be extracted via NER,
    such as *Brussels Convention*, *General Tizzano*, *Wien*, ...
    This derived information could be used to support search directly
    by recognizing an entity in the user query, such as:

    > show me all *documents* that involved *Oberlandesgericht Wien*

    or by using it as a base for other kind corpus clustering.

* Linked Data

    With the identification of names (NER), it is possible to link concepts
    or places with other data sources, that hold information about these
    resources, such as wikipedia/dbpedia, the factbook, geonames, ...

----

Advantages of the legal corpus:

Legal language is *relatively* regular compared to *average* text, in the sense
that references are expressed in a somewhat uniform notation.
Legal text might also display regularity in formulations:

> According to the ...

> This Agreement shall be without prejudice to other Agreements concerning

> The Parties shall cooperate in order to establish, insofar as possible

Corpus: Harmonised standards
----------------------------

Homepage: http://ec.europa.eu/enterprise/policies/european-standards/harmonised-standards/index_en.htm

The information that could be extracted from the standards corpus is similar
to the legal corpus. However, the subject matter might vary even more than in the
legal corpus.
