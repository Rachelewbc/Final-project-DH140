For my final project, I conducted a network visualization analysis based on the memoirs of a Buddhist scholar named Ruth Strout McCandless. The memoir, titled "Kangetsu: Memoirs of Ruth Strout McCandless, April 1944," is housed in box 2, folder 2 of the McCandless (Ruth S.) Collection on Nyogen Senzaki at UCLA's Charles E. Young Research Library Special Collections (https://oac.cdlib.org/findaid/ark:/13030/c8wh2vs5/).

### Topic and Questions of Interest

1. **How are individuals connected within the network centered around Ruth McCandless?**
2. **What are the predominant professional groups and their interactions within this network?**
3. **How does the proximity and co-occurrence of names in the text correlate with actual relationships and interactions?**
4. **What cultural and intellectual trends are reflected through the connections and interactions documented in Ruth McCandless's memoir?**

The study aims to provide insights into the significance of Ruth McCandless's role in connecting diverse groups, particularly within the realms of Zen Buddhism, Indian philosophy, and the creative industry. It also seeks to highlight broader cultural and intellectual trends of the mid-20th century by examining the network's structure and the individuals' professional and social ties.

### Process of Creating the Network Analysis

1. **Entity Recognition:** I used the English transformer pipeline in Spacy to identify named entities within the memoir text.
2. **Standardizing Names:** I created an Excel sheet with all variations of names in one column and the full names of characters in another to ensure consistency.
3. **Text Preparation:** The memoir's text was converted into PDF format. I then deleted all unnecessary punctuation and line breaks and replaced all variations of names with their full names.
4. **Node and Edge Table Creation:** I created a node and edge table to represent the connections between characters in the text. This data was used to construct a network visualization of the recognized individuals.
5. **Categorization:** Finally, I categorized the individuals into different colors based on their areas of expertise to provide additional insights into their roles and relationships.

Maintained by Rachel Han

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Rachelewbc/Final-project-DH140/main)