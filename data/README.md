# Data

We use three massive datasets to create our model - the web of science dataset (with research papers published in the US, from 2010-2016), the Open Syllabus Project, and the Burning Glass Job Demands dataset. As the total dataset is massive (over 250 GB), we do not host the full data online. This folder contains a metadata folder that maps different geographic regions to the research institutions in them, as well as the population information used for scaling. The sample data folder contains a sample of the syllabus data.

The notebooks folder contains a meta data folder that includes cleaning code as well as basic validation of the texts.

## Some notes on the Open Syllabus Project:

In their FAQ, OSP mention that they believe that their dataset includes 5-10\% of the Anglophone curricular universe over the last 10 years. They also mention that the dataset focuses on assigned texts: syllabi which have clear assigned texts represent a bit over 50\% (though this varies by institution) of the collection. A closer look at some of the syllabi suggests that they are not necessarily representative of actual teaching conducted at the universities, which can be seen in the figures below - some departments might have majority of all of their syllabi available online, others only a few, and many might not be represented at all. Since the syllabi represented might not give the complete picture, we must be very careful when drawing strong conclusions. While it was not done in this analysis, one option to mitigate for the syllabi representation is weighting the syllabi based on the subject so as to account for the imbalance; another ideal source to have would be the actual break-up of the number of courses taught by discipline for each of the universities.

![University of Chicago Open Syllabus](https://github.com/bhargavvader/knowledge-economy-diversity/blob/main/images/uchicago%20open%20syllabi.png)


![Harvard University Open Syllabus](https://github.com/bhargavvader/knowledge-economy-diversity/blob/main/images/harvard%20open%20syllabi.png)
