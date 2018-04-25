The ScriptBase Corpus

#####

If you use this data, please cite the following paper:
Philip John Gorinski and Mirella Lapata (2015). Movie Script Summarization as Graph-based Scene Extraction. In Proceedings of NAACL-HLT 2015, Denver, Colorado, USA.

#####

The ScriptBase Corpus is split in two parts:
    ScriptBase-alpha: The first crawl of movie scripts
    ScriptBase-J: Additional meta data from Jinni

#####

ScriptBase-alpha can be found in the scriptbase_alpha folder.
It contains the following data for 1,276 movies:
    * script.htm / script.html  - in cases where the script was crawled from a web-page in HTML format
    * script.txt                - plain-text version of the movie script
    * wiki.html                 - the movie's Wikipedia[1] page (2014 dump)
    * imdb.html                 - the movie's main IMDB[2] page (2014 dump)
    * keywords.html             - the movie's IMDB keywords page
    * credits.html              - the movie's IMDB credits page
    * summary.html              - the movie's IMDB summaries page
    * synopsis.html             - the movie's IMDB synopsis page
    * taglines.html             - the movie's IMDB taglines page
    * processed/imdb_meta       - meta data extracted from IMDB
    * processed/logTag.txt      - the movie's log line(s) and tag line(s), if it has any
    * processed/wikiplot.txt    - plain-text version of Wikipedia's plot section for the movie
    * processed/summaries/      - folder containing plain-text versions of the movie's IMDB summaries (if any)

#####

ScriptBase-J can be found in the scriptbase_jinni folder.
It contains the following additional data for 917 movies:
    * jinni.html                    - the movie's Jinni[3] page (2015 dump)
    * processed/script_clean.txt    - plain-text version of the movie script, manually corrected for inconsistencies
    * processed/script.xml          - XML version of the movie script, with various automatic annotations
    * processed/profile.txt         - Jinni's movie profile in plain-text format
    * processed/genes.txt           - all Jinni genes (attribute-value pairs) for the movie

#####

[1] https://en.wikipedia.org/
[2] https://www.imdb.com/
[3] http://www.jinni.com/
