# 1. Course OUTLINE

This basic initiation to natural language processing (and mining of linguistic data) covers the following points :

**1. JB (NB):  python for dummies (Sept 19)** 
Basic notions (loops) and commands to understand python 

Assignment : with your classmate : install the CMU library, install Latex (create your own overleaf account). 

**2. NB (JB) : Linguistics/NLP for dummies (Sept. 26)** 
From sound to meaning, basic terms and available linguistic programs
-> outline the project and the learning curve  
 Describe available tools for automatic analysis of linguistic data
  [Phonetic conversion (and text to speech)](https://tophonetics.com/)\\
  [French parsing on line](http://5.135.166.30/send2UDPIPE.html)\\
  [English parsing, Part-of-speech tagging, Stanford's suite of tools:](http://corenlp.run/)\\


**32. JB : Using Latex and templates for papers (Oct 3)**
the architecture of a scientific paper (stylesheet as textual structure)\\
LAteX for posters and presentations, etc.\\


**4. JB  The art of writing a conference abstract, finding references on Google Scholar, storing them with Zotero/Mendeley in Bibtex format (Oct. 10).**
Assignment: create an overleaf abstract, search models for abstracts for conferences. <br/>
Assignment : prepare a template for an [LREC2020 paper](https://lrec2020.lrec-conf.org/en/)


**5. NB (JB): : case study 1.  the Carnagie Mellon university phonetic dictionary (Oct 17) **
the basics of morphophonology : main concepts, open access databases
Assignment : recode with IPA symbols, a few regex scripts for data wrangling 


**6 JB (NB) the CMU dictionary and related python libraries (Oct 24)**
[library pronouncing](https://pronouncing.readthedocs.io/en/latest/tutorial.html)
data cleaning  and data wrangling on the CMU (regex) <br/>
setting up your own github and post your first scripts <br/>


**7. NB (JB) Creating a dataset : out of the CMU dictionary (Nov 7)** 
Regular expressions (regex) : find all the words ending in -ic, -ation, 
Assignment : find all the words with the KIT vowel. 


**8. JB:  writing your first Jupyter notebook (Nov 14)**
Assignment : submitting your abstract / read existing notebooks on 18th century dictionaries <br/>

**9. NB: Buchanan dictionary : suffix extraction and the Linguistica tool and library (Nov 21)**
[Examples with Buchanan's dictionary:](https://nbviewer.jupyter.org/urls/gitlab.huma-num.fr/mshs-poitiers/forellis/dicodiachro/raw/master/Buchanan_eng.ipynb?flush_cache=true) <br/>
[Comparison between Buchanan and Walker:](https://nbviewer.jupyter.org/urls/gitlab.huma-num.fr/mshs-poitiers/forellis/dicodiachro/raw/master/Buchanan-Walker_Exploration-Syneresis.ipynb?flush_cache=true) <br/>

Assignment: read the Goldsmisth et al. paper \\
Install the [linguistica library](https://pypi.org/project/linguistica/) <br/>

**10. JB:  Python library linguistica (Nov 28)**
http://linguistica-uchicago.github.io/lxa5/
data : case study 2: the Brown corpus and the Linguistica library (Goldsmith 2015) : the unsupervised learning of morphological stems and inflectional paradigms

NB : Computational approaches to linguistics: Lu 2014  (Treetagger and PoS-tagging) low level annotation : Pos-tagging 
Assignment : do Part of speech annotation for 18th century dictionaries \\

**11:  JB the spaCy library: parsing data (Dec 5)** 
[SpaCy](https://spacy.io/)

**12. NB: Using Spacy annotation to isolate zero relatives (Dec 12)** 
Estimate precision and recall of a script for a given linguistic structure: <br/> 
[script](https://github.com/kimgerdes/SUD/blob/master/tools/searchRelatives.py) \
From the CONNLL format to Arborator visualisations : https://arborator.ilpga.fr/q.cgi \


ALTERNATE 12. Designing a poster (overleaf)
January : poster session at Descartes


**POSTER SESSION : January 17th, 9h30-12h30**
- information about MAs (Paris 5 / Paris 7)
- MA students from the master in Machine Learning for Data Science 

**Second semester** 
Scikit-learn: Machine Learning in Python (Pedregosa et al. 2011): the basics

Motivated students will submit a collective paper.
