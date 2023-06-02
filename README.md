# MCQ-generator-
To generate MCQ by given Text

The main objective of this project is to simplify the laborious process of examining complex details of a textual  in order to produce Multiple Choice Questions (MCQs) for various quizzes.

This project aims to simplify the challenging task of carefully examining the small details in a written piece. Its ultimate objective is to generate top-quality MCQs with four options, using Natural Language Processing. 

It takes the input in the form of a text then when clicked on button it creats MCQs and then we can see them in next prompt by clicking show button.

Youtube Link :
https://youtu.be/pieTg8YxcGM


# This Python code helps generate multiple-choice questions (MCQs) from a given text article. Here's a simple explanation of how it works:

The code reads the text and extracts important keywords using a technique called Python Keyword Extraction (PKE). These keywords are crucial for creating the questions.

The text is divided into individual sentences so that we can focus on sentences related to the keywords.

The code finds sentences that contain the keywords and creates a map connecting each keyword to its related sentences. This makes it easier to find the right sentences when generating questions.

Next, the code determines the meaning of each keyword in its specific sentence. It uses a resource called WordNet to find the correct sense of the word, which is important for creating good distractors (wrong answer options).

Distractors are generated for each keyword. Distractors are words that are similar to the keyword but incorrect in the given context. The code uses WordNet to find related words and also makes use of an external resource called ConceptNet if WordNet doesn't provide enough distractors.

The distractors are mapped to their respective keywords, creating a list of options for each question.

Finally, the code constructs MCQs by replacing the keywords in sentences with blanks. The options for each question consist of the keyword itself (correct option) and randomly selected distractors.

The generated MCQs are saved to a file named "mcqs.txt" for later use.

## GUI
The main window is created with a full-screen size and a title.

A text box is displayed where the user can enter or paste the text for which they want to generate MCQs.

There is a "Text to MCQ" button. When clicked, it retrieves the text from the text box and passes it to the main code for MCQ generatio

After the MCQ generation process is completed, a label is displayed below the button, indicating that the execution was successful. The user is instructed to click on the "Show generated MCQ" button.

The "Show generated MCQ" button loads the generated MCQs from the "mcqs.txt" file (if it exists) and displays the content in a text area below the button. If the file is not found, an appropriate message is displayed.

The text area displays the generated MCQs, allowing the user to view and copy the questions.

The GUI window remains open until the user closes it or exits the application.

This code makes it easier to create MCQs from a text article, which can be helpful for educational purposes or creating assessments.



