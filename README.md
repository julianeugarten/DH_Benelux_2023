# DH Benelux 2023
This repo contains an anonoymized version of the MythFic Metadata dataset. The set contains metadata for all 5.154 works of fanfiction written in English in the fandom 'Ancient Greek Religion and Lore' that were marked completed in December 2022. Popularity metrics ( comments, kudos, bookmarks and hits) were accurate as of that date but are, of course, constantly increasing.  The repo also contains a Jupyter Notebook of code that was used to analyze the metadata, and the resulting tally of  the frequency of relationship-types and violence-categories.

**The metadata fields are:**  

title - The work’s title.  

author - an identifier consisting of the word author plus an author-specific number.  

rating - Options: Not Rated, General Audiences, Teen and Up Audiences, Mature, Explicit.  

category - Options: F/F, F/M, Gen, M/M, Multi, Other. 413 stories are not tagged with any category.  

fandom - all stories were selected for the tag Ancient Greek Religion and Lore, but many are tagged with multiple fandoms.  

relationship - tags naming two or more characters involved in a relationship within the story. A slash indicates a romantic or sexual relationship, while an ampersand indicates friendship or social interaction. 1.244 stories are not tagged with any relationship.   

character - tags listing the characters present or mentioned in the story. 293 stories are not tagged with any characters.  

additional tags - these tags can contain all sorts of information about the story, including themes, plot elements, content warnings or the author’s reflections. 616 stories are not tagged with any additional tags.  

language - in this corpus, all works are in English.  

published - date of initial publication.  

status - in this corpus, all works are ‘Completed.’ AO3 also enables authors to label works in progress, but these were excluded in the data collection. Note: AO3 began in 2009, but stories can be backdated.  

status date - in this corpus, status date reflects the date that the work was marked ‘Completed.’  

words - number of words in the work. 60 stories have a wordcount of zero. These are probably other fanworks such as art.  

chapters - number of chapters in the work.  

comments - number of comments left by readers. 1.585 stories received no comments.  

kudos - number of Kudos (similar to ‘Likes’ on Facebook) left by readers. 122 stories received no Kudos.  

bookmarks - number of readers who bookmarked the story. 1.162 stories were never bookmarked.  

hits - number of page views. It is difficult to determine whether hits align with the number of readers, because there is no way to ascertain whether someone who viewed a page truly read it. Only one story received zero hits.  



**Jupyter Notebook for analyzing MythFic Metadata**  

The notebook walks you through the steps taken to count and visualize the frequency of relationship categories in the metadata. It also identifies the 500 most frequently used additional tags, which were used to generate the violence-categories. Finally, the code counts the occurrence of the violence categories and transforms these counts into data that were input in SPSS.  

**tally.csv**    

Tally.csv contains a tally of the occurrence of relationships-categories and violence-categories per story. This can be uploaded into SPSS for further statistical analysis of results.