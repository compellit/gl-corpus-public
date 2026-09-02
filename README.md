# gl-corpus-public
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22251987.svg)](https://doi.org/10.5281/zenodo.22251987)



TEI versions created at the [COMPEL](https://compellit.github.io) project, based on sources allowing redistribution.

The poems bear the following prosodic information, obtained automatically with the GALAPAGOS toolkit (Galician Automatic Poetry Analysis System), which consists of NLP-based tools developed in the project:

- Metrical scansion. The module for this is released as [GAMA](https://github.com/compellit/gama-sym).
- Enjambment, following the typology and method in Haider et al. (forthcoming). See `encodingDesc` for a description. Labeling is done with a fine-tuned BERT model for sentence-pair classification. Models yet unreleased.
- Rhyme scheme, with letter-based notation. The tool is yet unreleased.
- Stanza types. The typology is listed in the rule titled "Stanza type inventory" in the [schema](https://github.com/compellit/corpus-schema/blob/main/compel-schema.odd). The tool is yet unreleased. 

An `encodingDesc` in the TEI header gives more details.

The project ODD is at the following location: [schema](https://github.com/compellit/corpus-schema/blob/main/compel-schema.odd).

A user interface giving access to the tools is deployed at https://prf2.org/galapagos/.

## Citation

Ruiz Fabo, P., Alonso Pérez, A., Moreau, P. (2026). COMPEL Public Corpus: Galician 19th-Century Poetry. CiTIUS - USC.