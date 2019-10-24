
**5. Selected projects and references (A brief description of the projects and stepping stones to the projects)  WORK IN THE MAKING**



TODO Write the project in details, List the research questions and plan the data processing

ALL: collect BibTex references in a .BIB file, begin writing the abstract/ poster sections. 
(define keywords, abstract, RQ, SOA, training data, results, future research)

30/10 : reading week (abstract writing week)


7/11: abstract writing? 
Jupyter notebook
Regular expression (reminder)

14/11 : send your abstract by Nov. 12th
Group 2 presents Treetagger
Jupyter notebooks : an appraisal






**1. Text generation with phonological constraints (Rap Machine)** <br/>
(Eitanite, Hind, Nelson) <br/>
(phonological, rhythmic pattern, text generation)

INSTRUCTIONS:
The pronouncing package and its youtube tutorial: generate poems with the pronouncing library / https://www.youtube.com/watch?v=W0pdPNh86H0
1 hour youtube video for reverse engineering : find how the functions do what they do,
extend functions from the demo
pr.rhymes("failings")
pr.rhyming_part(pr.phones)
logical values and test : do these words rhyme?


INSTRUCTIONS :  investigate the Carnegie Mellon university phonetic dictionary <br/>
http://www.speech.cs.cmu.edu/cgi-bin/cmudict <br/>
Look at stress patterns for words (and stress notation: 2, 1, 0) <br/>
Generate Heptasyllabic poems <br/>
Search for text-generation githubs, 
Eitanite : analyse one example of your training corpora (2pac?), detail the phonological/semantic patterns you observe, discuss how you may generate texts implenting these features.

Suggestions: 
check the Jabberwocky implementation
OULIPO RAP: use only certain vowels in your poem.


ASSIGNMENT : in class,  present the CMU dictionary as a resource and the corresponding libraries (CMU, pronouncing). (Nov 21st?)


**2. Two Projects in morphology investigating 18th century dictionaries**  <br/>
(Blanche, Dao , François, Preethi): 2 projects for 4 students <br/>

RQ1 : Can we use TreeTagger to analyse Buchanan and Walker : can we predict the words that have become obsolete?
Run Treetagger on Walker's data.

Did Walker define all the words he used in his dictionary?

RQ2 : Can we train Treetagger with 18th century data ?
Can Treetagger learn Walker's grammatical categories (ie "s." for substantives, both NN1 and NNS) 

INSTRUCTIONS: get the data and install Treetagger. Done
Extract pos, entries and definitions (senses) from Walker's dictionary.
Use Treetagger in learning mode . Find a lexicon for Treetagger. 

ASSIGNMENT : in class,  present the Penn Treebank as a tasget and Treetagger as a tool. (Nov. 14)

Next step: analyse Treetagger results : precision and recall of the PoS-tagger.
Next stage: use Linguistica to analyse Walker's corpus of definitions


**3. Project in text summarisation for literary texts** <br/>
(Claude, Guillaume)

INSTRUCTIONS : Read papers, Specify your research question. Specify the training data and the features that have been used to generate the summaries. List existing tools and previous research. Run existing programs with literary works you know and evaluate the resulats.



**4. A Pragmatic Approach to chatbots (Making sense with a chatbot?)**  <br/>
(Emma, Sawssen)

INSTRUCTIONS: Install the Eliza python (github), discuss the limitations
Investigate the Alice (AIML) robot, Sofia and other robots.
RQ: investigate the semantic and pragmatic aspects of the interaction with the chatbot.



