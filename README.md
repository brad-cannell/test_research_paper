# This is a test research paper written in RStudio

I would love to be able to write my papers directly in RStudio. It may have the following advantages:    
* Automatically make updates to results and figures, which would be great   
* Could do versioning in Github   
    - Google Docs have built-in versioning, but Word docs do not.   
    - Many of my collaborators can't use Google Docs.    

# Process

Here's what I'm thinking the process might look like:    
* Write in RStudio papers directly in RStudio   
    - May want to knit to Word or may want to use something like the officer package.   
    - Automatically make updates to results and figures, which would be great.   
* Do versioning in Github (of the Rmd file).     
* Use BibTeX file for citations/references - these can easily be exported from Paperpile.   
    - Yes, you lose the automatic insertion that you get with Google Docs, but the efficiency gains in the rest of the process may be worth it.   
    - You still get to use Paperpile for managing and marking up PDFs and references.   
    - Many of my collaborators can’t use Google Docs anyway.   
    - Other citation managers that my collaborators use can generate bibtex files that they can share with me.   
* Send to collaborators.   
* They send back track changes.   
* I will make edits.   
* Then I should be able to cut and paste those edits back into the Rmd file. I need to test this, but I think git is smart enough to be able to highlight only the lines that changed — even if you cut and paste an entire paragraph. Even if it can’t, it’s not the end of the world.

I'm going to simulate this process in this repository. I'm especially curious to test the versioning stuff.

* I still want to try creating a document using officer.