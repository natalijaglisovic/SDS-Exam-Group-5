# Climate Change and Sustainability Communication in the U.S. Democratic Party

# Table of contents
1. [Introduction](#introduction)
2. [Netnography](#netnography)
    1. [Methodology](#methodology)
    2. [Analysis](#analysis) 
    3. [Limitations and further research](#limitations)
3. [Advanced Social Data Science 2](#asds2)
    1. [Motivation](#motivation)
    2. [Applied Methods](#appmethods)
      1. [Computer-Assisted Classifier of Climate Tweets](#classifier)
      2. [hSBM Topic Modelling](#hsbm)
      3. [Part of Speech Tagging (POS-T)](#pos)
    3. [Discussion of Preprocessing and Analytical Choices](#disasds)
    4. [Results](#resultsasds)
    5. [Conclusion](#conasds)
    6. [Discussion of Alternative Methods](#altmethodsasds)
5. [Manual & Automated Networks](#networks)
    1. [Manual Network](#manual)
    2. [Automated Network](#automated) 
6. [Content Analysis](#content)
    1. [Method](#methodcontent)
    2. [Findings](#findingscontent) 
    3. [Limitations](#limcontent)
7. [Qualitative & Quantitative Approach](#qualquant)
    1. [Qualitative & Quantitative Interplay](#interplay)
    2. [Advanced Social Data Science 2 Contribution](#asds2cont) 
    3. [Quality Criteria](#quality)
8. [Discussion & Conclusion](#conclusion)

## Introduction <a name="introduction"></a>

Inter-party divide in the Democratic party are usually based on ideological differences (Vargas, 2018). This ideological fracture is characterised by the moderate and progressive wing of the party. Although sharing the same goals, the moderate Democrats tend to favour slow, incremental change, whereas the progressive Democrats distinguish themselves as activists advocating for populist policies such as Medicare For All (Vargas, 2018). The conflict between the two wings of the Democratic party was highlighted by The Green New Deal solution proposed by Alexandria Ocasio-Cortez and Senator Markey (Vargas, 2018). The Green New Deal is the first comprehensive proposal to combine climate change mitigation and the elimination of economic inequality (Galvin & Healy, 2020). The majority of progressive Democrats, such as Bernie Sanders, support and have signed the Green New Deal proposal, whereas some moderates, such as Diane Feinstein, were more critical of it (King, 2021). This inter-party difference in how Democrats tackle and approach climate change is what this paper wishes to explore further. We want to explore how the progressive and moderate Democrats frame and approach climate change and sustainability on social media, focusing on Twitter, Facebook and their official websites.

We decided to approach this topic from the frame of agenda setting theory. Agenda setting theory refers to media’s portrayal and selection of certain issues, which leads people to perceive those issues as more important than others (Wu & Coleman, 2009). There are two levels of the theory: the first level concerns the amount of coverage of a certain issue, whereas second-level concerns how the issue is portrayed (Wu & Coleman, 2009). Previous research investigating political communication and agenda-setting theory usually analyses traditional media, such as news articles and political speeches (Wu & Coleman, 2009). However, there is a push towards analysing social media communication instead, but there is a lack of a common body of evidence (Jungherr, 2016). The need to analyse social media communications stems in the rise of politician’s use of social media, where they can communicate with the public, as well as engage with political opponents (Gilardi, Gessler, Kubli & Müller, 2021). 
 
We wish to add to the literature of analysing political communication on social media, through the lense of agenda-setting theory. However, the aim of our paper is to explore the communication patterns of the two democratic wings, i.e. moderate and progressive, not to investigate what influence it has on the public's perception of topic importance, which is why we will use agenda-setting as merely a lense for our work. We will focus on the two levels of agenda setting. Namely, what they tweet about regarding environmental sustainability, as well as how they phrase their opinions. The difference in this and most other literature, is that we will have an open ended question focusing on the patterns emerging, rather than a set hypothesis concerning the differences in communication (Gilardi, Gessler, Kubli & Müller, 2021). 

A broad rather than narrow approach is preferred in netnographic work (Kozinet, 2019). Our inquiry focuses on the communication of over 200 politicians on two social media platforms, which broadens the scope of the research, rather than focusing on specific individuals or specific platforms. Based on this, our research question is:
 
<em>How do progressive and moderate U.S Democrats approach the topic of climate change and sustainability on social media?<em>.
 
Our research design will include netnographic work, network analyses, and a content analysis. The data in the analysis was gathered from Twitter and Facebook, and the netnography was complemented with data from official government websites. We delineate two wings of the Democratic Party, the moderates and the progressives, by examining the two largest congressional coalitions that relate to the two factions, the New Democrats and the Congressional Progressive Caucus. In the rest of this paper, the term moderates will refer to the members of the New Democrats, and the term progressives will refer to the members of the Congressional Progressive Caucus. Data for the network analysis and content analysis was gathered using the Tweepy-API. The actor set included 110 active members from The New Democrats, as well as 91 active members of the Congressional Progressive Caucus, that were all US. Senators and Representatives. To ensure that the topics and the wording reflect the two democratic wings, we chose to collect tweets from the politicians' social media timelines. Due to a limitation of the Tweepy-API, we only gathered the 3,200 most recent tweets from each of the politicians in our defined actor set. This limitation implies that politicians who tweet more often have a shorter timeline than politicians who tweet less often in our dataset. The Twitter data were gathered on 8 May 2021. The Twitter data for the progressive contains 286,668 tweets, and the dataset for the moderated contains 322,512 tweets. The netnographic section will follow our immersion journal where we followed the top 20 politicians from the progressive and moderate wing on Facebook, Twitter, and their official websites on posts regarding climate change and sustainability. A manual network, which demonstrates how the democrats relate to each other based on topics, will be included. We will then conduct an automated network analysis to explore the relations between the two wings, based on Twitter mentions. In our content analysis, a PCA model will be conducted on the politicians from the immersion journal to investigate the placement of politician’s climate-agenda in relation to each other.


## Netnography <a name="netnography"></a>
Netnography

### Methodology <a name="methodology"></a>
This is a sub paragraph, formatted in heading 3 style

### Analysis <a name="analysis"></a>
This is a sub paragraph, formatted in heading 3 style

### Limitations and further research <a name="limitations"></a>
This is a sub paragraph, formatted in heading 3 style

## Advanced Social Data Science 2 <a name="asds2"></a>
ASDS2

### Motivation <a name="motivation"></a>
This is a sub paragraph, formatted in heading 3 style

### Applied Methods <a name="appmethods"></a>
This is a sub paragraph, formatted in heading 3 style

#### Computer-Assisted Classifier of Climate Tweets <a name="classifier"></a>
This is a sub-sub paragraph, formatted in heading 3 style

#### hSBM Topic Modelling <a name="hsbm"></a>
This is a sub-sub paragraph, formatted in heading 3 style

#### Part of Speech Tagging (POST-T) <a name="pos"></a>
This is a sub-sub paragraph, formatted in heading 3 style

## Discussion of Preprocessing and Analytical Choices <a name="disasds"></a>
The second paragraph text

## Results <a name="resultsasds"></a>
The second paragraph text

## Conclusion <a name="conasds"></a>
The second paragraph text

## Discussion of Alternative Methods <a name="altmethodsasds"></a>
The second paragraph text

## Manual & Automated Networks <a name="networks"></a>
The second paragraph text

### Manual Network <a name="manual"></a>
This is a sub paragraph, formatted in heading 3 style

### Automated Network <a name="automated"></a>
This is a sub paragraph, formatted in heading 3 style

## Content Analysis <a name="content"></a>
The second paragraph text

### Method <a name="methodcontent"></a>
This is a sub paragraph, formatted in heading 3 style

### Findings <a name="findingscontent"></a>
This is a sub paragraph, formatted in heading 3 style

### Limitations <a name="limcontent"></a>
This is a sub paragraph, formatted in heading 3 style

## Qualitative & Quantitative Approach <a name="qualquant"></a>
The second paragraph text

### Qualitative & Quantitative Interplay <a name="interplay"></a>
This is a sub paragraph, formatted in heading 3 style

### Advanced Social Data Science 2 Contribution <a name="asds2cont"></a>
This is a sub paragraph, formatted in heading 3 style

### Quality Criteria <a name="quality"></a>
This is a sub paragraph, formatted in heading 3 style

## Discussion & Conclusion <a name="conclusion"></a>
The second paragraph text
