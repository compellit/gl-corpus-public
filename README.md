# gl-corpus-public

TEI versions created at the [COMPEL](https://compellit.github.io) project for **public domain sources only**.

The project schema is at the following location: [schema](https://github.com/compellit/corpus-schema/blob/main/out/compel-schema.rng).

The poems bear the following prosodic information, obtained automatically with NLP-based tools developed in the project:

- Metrical tagging, obtained with [GAMA](https://github.com/compellit/gama-sym)
- Enjambment, following the typology and method in Haider et al. (forthcoming). See `encodingDesc` for a description. Labeling is done with a fine-tuned BERT model for sentence-pair classification. Models yet unreleased.
- Rhyme scheme, with letter-based notation. The tool is yet unreleased.
- Stanza types. The inventory can be seen in the [schema](https://github.com/compellit/corpus-schema/blob/main/out/compel-schema.rng) and the tool is yet unreleased. 

An `encodingDesc` in the TEI header gives more details.

A user interface giving access to the tools is deployed at http://prf2.org/galapagos/