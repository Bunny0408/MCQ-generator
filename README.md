# MCQ-generator-
To generate MCQ by given Text

The main objective of this project is to simplify the laborious process of examining complex details of a textual article in order to produce Multiple Choice Questions (MCQs) for various quizzes.

This project aims to simplify the challenging task of carefully examining the small details in a written piece. Its ultimate objective is to generate top-quality MCQs with four options, using Natural Language Processing. 


## How it works 
It takes the input in the form of a text then when clicked on button it creats MCQs and then we can see them in next prompt by clicking show button.




It use the PKE (Python Keyword Extraction) library to extract important words (keywords) from the text. 
Split the text article into individual sentences to facilitate mapping of sentences to keywords.
Map the sentences that contain the keywords to their respective keywords.
Determine the sense of each keyword in its context using WordNet.
Generate distractors (alternative options) for each keyword based on WordNet's hypernym and hyponym relationships.
If WordNet fails to provide distractors, use the ConceptNet API to obtain additional distractors.
Map the generated distractors to their respective keywords.
Present the MCQs in a readable format, replacing the keywords with blanks and providing multiple options.
The code generates MCQs by replacing keywords in the original sentences with blanks and offering the keywords along with their distractors as options. The options are shuffled randomly to ensure variation.

