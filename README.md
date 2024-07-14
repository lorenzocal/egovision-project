# Natural Language Queries in Egocentric Videos: from segment localization to natural language answers
This repository contains the code of the project "Natural Language Queries in Egocentric Videos" carried out as part of the 'Machine Learning and Deep Learning' course (Polytechnic of Turin, Data Science and Engineering, 2024).

The attached notebooks contain data preparation and training of VSLBase using Omnivore [1] and EgoVLP features [2], VSLNet using Omnivore [3] and EgoVLP features [4], VSLNet replacing the default BERT text encoder with GloVe using Omnivore [5] and EgoVLP features [6].

The extension notebook [7] takes the following files as input:

- data.txt : it contains the queries of the validation set together with the predictions made by VSLNet + EgoVLP features + BERT, the ground truths extracted from the validation .json and other relevant information.
- annotated_gt.txt : it contains the manually annotated textual ground truths for 50 NLQs.

Please note that due to problems with the AWS credentials request in the final stages of the project, which do not depend on us, it was not possible to fully regenerate the qualitative results in the extension notebook [7].
