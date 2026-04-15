# thesis
### file structure
|---analysis.rmd\
|---choosing-nouns.ipynb\
|---data\
&emsp;&emsp;|---(candidates.txt)\
&emsp;&emsp;|---(full-raw-output.csv)\
&emsp;&emsp;|---(glove.300d.txt)\
&emsp;&emsp;|---(output.csv)\
&emsp;&emsp;|---results.json\
&emsp;&emsp;|---(sims.csv)\
|---experiment.html\
|---process-results.ipynb\
|---README.md\
|---zisc\
&emsp;&emsp;|---chosen-pared.txt\
&emsp;&emsp;|---glove-check.ipynb\
&emsp;&emsp;|---chosen-synsets.txt

### file descriptions
* analysis.rmd: statistical analysis of experiment results
* choosing-nouns.ipynb: filters wordnet nouns to create candidate list for the study
    -->output: data/candidates.txt
* data/candidates.txt: details candidate synsets fulfilling restrictions outlines in choosing-nouns.ipynb
* data/glove.300d.txt: need to download [here](https://nlp.stanford.edu/projects/glove/)
* data/full-raw-output.csv: results.json in csv format, with participant ids added
* data/output.csv: nicely skimmed down version of full-raw-output.csv with relevant columns, typos corrected, glove similarities added
* results.json: file of downloaded experiment responses
* data/sims.csv: same content as output.csv but with more similarity comparisons added
* experiment.html
* process-results.ipynb
    -->output: full-raw-output.csv, output.csv, sims.csv
* zisc/chosen-pared.txt: final 6 handpicked candidates
* zisc/glove-check.ipynb: checking for variance in glove similarity among final candidates and their related words
* zisc/chosen-synsets.txt: candidates.txt filtered to chosen candidates


TODO: download glove.300d.txt to data folder