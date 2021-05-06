# Neuro-240-Final-Project
Final project for Neuro 240 (Spring 2021), focused on applying Machine Learning to automate transliteration of the Code of Hammurabi from hand-copy

Abstract:

This project focuses on using transfer learning to adapt existing machine learning architectures to the visual recognition of cuneiform characters
in the Code of Hammurabi (~1750 BCE). The focus will be on exploiting the underlying structural regularity of the cuneiform script in order to isolate
patterns of strokes, and then on categorizing the stroke layouts into character identifications. Through a combination of ML object-detection and algorithmic
segmentation and identification techniques, it is possible to generate stroke-based representations that are distinguished by a second network with high accuracy ($.99\%$);
further, given the inherent complexities and ambiguities of any written text, the specific details of hard-to-identify characters and/or sections might offer insight not only
into the text, but also into the applicability of AI to character or object recognition tasks more generally. Lastly, the design process for the overall workflow might offer
insights into the usefulness of AI in "small data" applications where the dataset on which the network is trained is relatively small; in this case, careful design can be used
to introduce context-specific inductive biases that optimize the training process and allow the network to make maximal use of a minimal training set.
