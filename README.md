# cimt-argument-concreteness-dataset

January 17, 2022 (corpus version 1.0)

About

This directory contains a dataset of public participation contributions annotated with argument concreteness. The dataset is part of the CIMT PartEval Corpus and is further described in the publication "A Corpus of German Citizen Contributions in Mobility Planning: Supporting Evaluation Through Multidimensional Classification", to be published in Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022).

This work is based on research in the project CIMT/Partizipationsnutzen, which is funded by the Federal Ministry of Education and Research as part of its Social-Ecological Research funding priority, funding no. 01UU1904. (for more information, visit https://www.cimt-hhu.de/en/)

----------

Content

Each of the folders (one per public participation process) contains the coded dataset and the corresponding terms of use.

The "concreteness"-csv-files contain one entry per unit with the following information.

unit_id: unique unit id

sentences: span of sentences that form the unit

code: annotation label (argument component)

coder1-coder5: concreteness annotation per coder

dataset: name of the dataset

document_id: document id


The "dataset"-csv-files contain one entry per unit with the following information.

id: unique sentence id

document_id: document id

sentence_nr: sentence number in document

content: textual content of sentence

code: annotation label (argument component)

title/text: denotes whether a sentence is taken from the title or the body text of a document

dataset: name of the dataset

url: original url of document (depending on the respective terms of use)

----------

Argument Concreteness Scheme

high concreteness: unit contains details that specify the what, how and where. Such specifications can be colour, surface, measurements, etc. (an example is "cycle paths often in poor condition, tarred surface torn up, bumpy due to roots, mostly only half width because overgrown").

intermediate concreteness: unit contains some specifications like location or descriptions of what exactly should be done, but leave some room for interpretation (e.g.: "new cycle lanes without interruptions" - the measure is described and somewhat detailed, but it is not clear how it should look exactly and where it should be located).

low concreteness: unit contains no information on location or specific measures, so that a variety of measures could be deducted (e.g.: "unfavorable traffic lights" - it does not become clear, what exactly the problem is, where it is and what should be done).

More detailed information can be found in the paper.

----------

Citation

If you use the dataset, please cite the following paper:

Julia Romberg, Laura Mark, and Tobias Escher. 2022. A Corpus of German Citizen Contributions in Mobility Planning: Supporting Evaluation Through Multidimensional Classification. In Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022), Marseille, France. European Language Resources Association (ELRA).

----------

License

The annotated data corpus is available under the Creative Commons CC BY-SA License (https://creativecommons.org/licenses/by-sa/4.0/).

----------

Contact Person

Julia Romberg, julia.romberg@hhu.de, https://www.cimt-hhu.de/en/team/romberg/
