# How to use
Go to the `Types` folder first to find the question type you want to delve into, The `Type` page will always list all questions, algorithms and skills used. When join into a specific algorithm or skill, caveats will be listed.

The order is `Type` -> `Algorithms` / `Skills` / `Language` -> `Caveats`

# Section Introduction

This project is organized into five distinct sections:

1. **Types**:
   - Represents the category of a question. Links of all questions under this type will be provided.
   - While some question types have a strong correlation with specific algorithms (e.g., dynamic programming), others might fall under the same type but require different skills or algorithms.
   - Questions are grouped by their `Type` label. Relevant algorithm or skill URLs associated with these questions will be provided. Where possible, these URLs should link to the current repository.
   - Note: Some questions might be labeled with multiple `Types`. All such labels should be taken into account.

2. **Algorithms/Skills**:
   - Provides a brief overview of specific algorithms or skills.
   - Directs readers to the associated README file in the respective question's directory for comprehensive details and use cases.
   - If there are caveats or language-specific skills under a certain algorithm or skill, links to the `Caveats` or `Languages` sections will be provided.

3. **Caveats**:
   - Briefly documents various caveats.
   - A link to the specific README file of a question for detailed insights will be provided.

4. **Languages**:
   - Highlights language-specific techniques or skills.
   - Associated URLs will direct readers to detailed discussions in the specific README file of a question.



# TODO
1. A Algorithm_Intelligence should be integrated into the backend console to extract folder and file paths of given github url automatically.
2. Each Algorithm Questions repo should follow a certain format, having `src` folder under the root directory. So, this Algorithm Intelligence could extract questions title from these Algorithm Questions Repository. Each question should have a `labels.md` file to labelize questions and read by the Algorithm_Intelligence.
3. The Algorithm_Intelligence will read 
   1. questions titles, 
   2. questions labels
   3. questions github url
   4. labels - has content fields
   5. questions origin
   6. readme url for labels explanation
   and store all these info into the database
4. When open the Algorithm console frontend, it display:
   1. Labels
   2. Questions with Labels
5. Algorithm Insight will summarize all labels but no need to list questions here, no need to bind to the labels readme either (??). The Algorithm_Intelligence shows labels content url.
6. For a label document, it should record the url of the summary in Algorithm_Insights as well as the content url of each questions. When the user click on a label, the label page first show the summary and then list all questions with this label, if the question has the readme for this label, the label icon will have a red edge.
