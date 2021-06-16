# Climate Change and Sustainability Communication in the U.S. Democratic Party

# Table of contents
1. [Introduction](#introduction) (exam.nr: 2)
2. [Netnography](#netnography)
    1. [Methodology](#methodology)
    2. [Analysis](#analysis) 
    3. [Limitations and further research](#limitations)
3. [Advanced social data science 2](#asds2)
    1. [Motivation](#motivation)
    2. [Applied Methods](#appmethods)
      1. [Computer-assisted classifier of climate tweets](#classifier)
      2. [hSBM topic modelling](#hsbm)
      3. [Part of speech tagging (POS-T)](#pos)
    3. [Discussion of preprocessing and analytical choices](#disasds)
    4. [Results](#resultsasds)
    5. [Conclusion](#conasds)
    6. [Discussion of alternative methods](#altmethodsasds)
5. [Manual & automated networks](#networks)
    1. [Manual network](#manual)
    2. [Automated network](#automated) 
6. [Content analysis](#content)
    1. [Method](#methodcontent)
    2. [Findings](#findingscontent) 
    3. [Limitations](#limcontent)
7. [Qualitative & quantitative approach](#qualquant)
    1. [Qualitative & quantitative interplay](#interplay)
    2. [Advanced social data science 2 contribution](#asds2cont) 
    3. [Quality criteria](#quality)
8. [Discussion & conclusion](#conclusion)
9. [References](#ref)
## Introduction <a name="introduction"></a>

Inter-party divide in the Democratic party is usually based on ideological differences (Vargas, 2018). This ideological fracture is characterised by the moderate and progressive wing of the party. Although sharing some of the same goals, the moderate Democrats tend to favour slow, incremental change, whereas the progressive Democrats distinguish themselves as activists advocating for populist policies such as Medicare For All (Vargas, 2018). The conflict between the two wings of the Democratic party was highlighted by the Green New Deal solution proposed by U.S. Representative Alexandria Ocasio-Cortez and U.S. Senator Markey (Vargas, 2018). The Green New Deal is the first comprehensive proposal to combine climate change mitigation and the elimination of economic inequality (Galvin & Healy, 2020). The majority of progressive Democrats, such as Senator Bernie Sanders, support and have signed the Green New Deal proposal, whereas some moderates, such as Representative Diane Feinstein, are more critical of it (King, 2021). This inter-party difference in how Democrats tackle and approach climate change is what this paper wishes to explore further. We want to explore how the progressive and moderate Democrats frame and approach climate change and sustainability on social media, focusing on Twitter, Facebook, and their official websites.

We decided to approach this topic using agenda setting theory. Agenda setting theory refers to media’s selection and portrayal of certain issues, which leads people to perceive those issues as more important than others and aids in their interpretation of those issues (Wu & Coleman, 2009) . There are two levels of the theory: the first level concerns the amount of coverage of a certain issue, whereas the second level concerns how the issue is portrayed. Previous research investigating political communication and agenda setting usually analyse traditional media, such as news articles and political speeches (ibid.). However, there is a push toward analysing social media communication instead, but there is lack of research in this area (Jungherr, 2016). The need to analyse social media communications stems in the rise of politicians' use of social media, where they can communicate with the public, as well as engage with political opponents (Gilardi et al., 2021). 
 
 We wish to add to the literature of analysing political communication on social media, through the lense of agenda setting theory. However, the aim of our paper is to explore the communication patterns of the two Democratic wings, i.e.,  the moderates and progressives, not to investigate what influence they have on the public's perception of topic importance and its interpretation, which is why we will use agenda setting as merely a lense for our work. We will focus on the two levels of agenda setting. Namely, what they post regarding environmental sustainability, as well as how they frame these posts. The difference in this study and the majority of literature related to agenda setting is that we will have an open-ended question focusing on the patterns emerging, rather than a set hypothesis concerning the differences in communication between the factions (Gilardi et al., 2021). As we will employ a variety of quantitative and qualitative analyses, we seek a broad research focus, especially since the digital ethnographic work underpinning our study prioritises inductive exploration (Kozinets, 2019). Our inquiry focuses on the communication of over 200 politicians on two social media platforms, which broadens the scope of the research, rather than focusing on specific individuals or just one platform. Based on this, our research question is:

 
<em> RQ: How do progressive and moderate U.S Democrats approach the topic of climate change and sustainability on social media?</em>
 
Our research design will include netnographic work, network analyses, and a content analysis. The data in the analysis was gathered from Twitter and Facebook, and the netnography was complemented with data from official government websites. We delineate two wings of the Democratic Party, the moderates and the progressives, by examining the two largest congressional coalitions that relate to the two factions, the New Democrats and the Congressional Progressive Caucus (Thomsen, 2018). In the rest of this paper, the term moderates will refer to the members of the New Democrats, and the term progressives will refer to the members of the Congressional Progressive Caucus. Data for the automated network analysis and content analysis was gathered using the Tweepy-API. The actor set included all 110 members of the New Democrats and all 91 members of the Congressional Progressive Caucus, all of which currently hold office. The members were either U.S. Senators or Representatives. We chose to collect tweets from the politicians' feeds. Due to a limitation of the Tweepy-API, we only gathered the 3,200 most recent tweets from each of the politicians in our defined actor set. This limitation means that politicians who tweet more often have a shorter timeline than politicians who tweet less often in our dataset. The Twitter data were gathered on 8-11 May 2021. The Twitter data for the progressives contains 286,668 tweets, and the dataset for the moderates contains 322,512 tweets.

The netnographic section will follow our immersion journal where we followed the top 20 politicians from the progressive and moderate wing on Facebook, Twitter, and their official websites on posts regarding climate change and sustainability. A manual network, which demonstrates how the Democrats relate to other actors when discussing climate change and sustainability, will be included. We will then conduct an automated network analysis to explore the relations between the two wings, based on Twitter mentions. In our content analysis, we will create a PCA model to investigate the placement of politicians' climate agendas in relation to one another.



## Netnography <a name="netnography"></a>
Netnography

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/table1.PNG)

### Methodology <a name="methodology"></a>
To investigate how moderate and progressive U.S. Democrats discuss climate change and environmental sustainability on social media, we have conducted a netnography that attempts to uncover the main themes highlighted by the two coalitions. Netnography refers to a type of online ethnography that involves an immersive and iterative exploration of online data, with an emphasis on inspecting data from social media networks and other digital interactive platforms (Kozinets, 2019). Kozinets explains that while the traditional ethnography often necessitates researcher participation in the field site, typically culminating in a fieldnote journal that details these in-person activities, netnography asks the researcher to approach the online space as a data site. In these virtual environments, an immersion journal replaces conventional fieldnotes and serves as a medium in which the researcher can record data, interpret data, and engage in reflexivity in relation to these operations. This immersive dimension motivates us to use the netnographic method in our research, as it guides rich, inductive qualitative exploration of online data, providing the deep cultural understanding that ethnography prioritises. Furthermore, recent research has shown the benefits of using netnography to access a more robust interpretation of quantitative material (Blok et al., 2021), inspiring us to employ the method in our quali-quantitative study. 

In line with our research objectives, we have selected 10 Democrats from each coalition that have the largest following on Twitter. We chose to track the officials with the largest following based on the assumption that their posts reach larger audiences than their peers, which may facilitate their ability to set the public agenda (Gilardi et al., 2021). Additionally, retrieving this subsample from the original sample of 201 congressional Democrats allows for closer inspection of the site, which affords more opportunity to discover the "deep data" Kozinets (2019) describes—data that is detailed, resonant, and provides insight into larger patterns outside its scope. For these 20 officials, we have surveyed their Twitter and Facebook profiles, platforms we have chosen due to their wide use in U.S. politics as well as their potential agenda-setting capabilities (Skogerbro & Krumsvik, 2015). To collect data from these networks, two research members examined the politicians' feeds, focusing on posts that appeared to discuss the environment and sustainability. Since we did not demarcate keywords before data collection, we used our knowledge of the climate change rhetoric employed in U.S. politics to guide our initial exploration. In a spreadsheet immersion journal, we recorded the text and images of the environment-related posts, which totaled to 123 Tweets (56 from progressives and 67 from moderates) and 29 Facebook posts (18 from progressives and 67 from moderates). The earliest and latest posts were created on 12 December 2019 and 25 May 2021, respectively. We analysed these posts with the help of environmental policy information one research member inspected from the politicians' government websites, which assisted in contextualising the social media data. 

Our immersion journal not only served as a place to organise data we collected from the Web but also acted as a diary in which we reflected on our personal thoughts related to the material, attempted to reconcile our theoretical framework with the data site, and most importantly informed our overall data collection and analysis. As Kozinets (2019) explains, netnographers should use the immersion journal to "assess what [they] are looking for, where to find it, and to what it is connected" (p. 287). Thus, these writings enhanced our knowledge of the data site, which helped in revealing new keywords we considered in further data collection. We also used the immersion journal to code data, breaking down the posts into chunks and assigning labels to them. One member coded the moderate posts, another the progressive posts, and the third coded both wings' posts and the government sites. After the initial coding, we combined these codes into higher-order pattern codes, which we then analysed and employed throughout our study. 


### Analysis <a name="analysis"></a>
We do not aim to strictly compare the moderates and progressives in our netnographic analysis, as our research question seeks to understand how each faction addresses climate change and sustainability on social media, irrespective of its counterpart. Therefore, in our analysis we will highlight themes we detected from our data, though this discussion is not exhaustive of all patterns found. 

<em> Progressives: A rhetoric of intersectionality </em>

Progressive Democrats make connections between climate change and sustainability and issues pertaining to social justice, a term referring to a justice that promotes an equitable and diverse society, with consideration of marginalised communities (Bhugra, 2016). For example, in a tweet discussing a hardship faced by a community in her jurisdiction, Congresswoman Rashida Tlaib frames the climate discussion around racial inequality and corporate malpractice (Figure 1). Here, she notes how a corporate entity, Stellantis North America, participates in behaviours that pollute neighbourhoods. According to Tlaib, this pollution acts as a manifestation of the environmental racism encountered by people living in these communities. Attributing responsibility to the business in regards to environmental degradation and underscoring its consequences in terms of racial inequality draws our attention to Crenshaw's (1989) elaboration on intersectionality, which refers to the interdependent nature of social categorisations and its contribution to systems of discrimination. In this example, the social categories of race (i.e., "the environmental racism they face") and class (i.e., "residents in the [Stellantis North America] impact zone," a poor area in her jurisdiction that dwarfs in power compared to corporate interests) interrelate and act as frames in which the reader might understand the outcome of the company's unsustainable practices—a maintenance of racism and classism. We coded posts such as these as containing a number of themes, including "environmental injustice," "environmental racism," and "environment degradation and immigration," and combined them into the pattern code "intersectionality of climate and social justice."

(Add Figure 1: Congresswoman Rashida Tlaib tweets about climate)

<em> Moderates: Innovation and securing the U.S. economy </em>

When discussing climate change and sustainability on social media, moderate Democrats outline how innovation in the energy industry not only assists in combating environmental degradation but may also help improve the country's economy. A few codes associated with this rhetoric include, "energy innovation," "electric vehicles," and "economic opportunity," which were collated into the pattern code "economic opportunity in sustainability." This theme refers to the practice of framing the fight against climate change in terms of the economic prosperity the country may experience if society places value on sustainable innovation. A Facebook post by U.S. Senator Mark Warner serves as an example of this framing (Figure 2). Here, Warner suggests that developing wind energy, a practice meant to stymie climate change, assists in modernising his state's economy by creating "green" jobs. The senator even mentions the BlueGreen Alliance, a lobbying group that argues for an economically responsible solution to climate change. Many moderates appear to make this type of connection, echoing the analysis of Noel (2016), which states that centrist Democrats prioritise the nation's economy and business ventures over other political issues. 

(Figure 2: Senator Mark Warner discusses sustainable innovation on Facebook)

### Limitations and further research <a name="limitations"></a>
Two main limitations characterise our netnography. First, our analysis of the two wings implies homogeneity within groups, meaning that the progressives think alike and the moderates think alike. While our grappling with the data hints that members within groups post similarly, we concur that this may not be the case. After all, our netnography investigates the social media of 20 politicians, a fraction of the larger sample. Future research should expand this sample size or randomly select members of each coalition to analyse, which would possibly afford more diversity in viewpoints. Second, aside from the initial organisation of our data collection strategy, we lacked a systematic approach to collecting tweets and Facebook posts when exploring the data site, which can be seen by the incongruent dates of the posts we recorded. Since we did not demarcate a timeframe to guide our examination of the site, we recorded posts written in 2019, 2020, and 2021, without consideration of how time may influence climate change and sustainability rhetoric. However, we note that content written across all three years share similar themes, which means this limitation might not have harmed our study's analytic potential. Future research should demarcate a timeframe to examine how the political climate at a given time in history potentially influences climate change rhetoric.

(Add Table 1: Examples of immersion journal codes and pattern codes for moderates and progressives)

## Advanced Social Data Science 2 <a name="asds2"></a>
ASDS2

### Motivation <a name="motivation"></a>
This is a sub paragraph, formatted in heading 3 style

### Applied methods <a name="appmethods"></a>
This is a sub paragraph, formatted in heading 3 style

#### Computer-Assisted classifier of climate tweets <a name="classifier"></a>
This is a sub-sub paragraph, formatted in heading 3 style

#### hSBM topic modelling <a name="hsbm"></a>
This is a sub-sub paragraph, formatted in heading 3 style

#### Part of speech tagging (POST-T) <a name="pos"></a>
This is a sub-sub paragraph, formatted in heading 3 style

## Discussion of preprocessing and analytical choices <a name="disasds"></a>
The second paragraph text

## Results <a name="resultsasds"></a>
The second paragraph text

## Conclusion <a name="conasds"></a>
The second paragraph text

## Discussion of alternative methods <a name="altmethodsasds"></a>
The second paragraph text

## Manual & automated networks <a name="networks"></a>
The second paragraph text

### Manual network <a name="manual"></a>
This is a sub paragraph, formatted in heading 3 style

### Automated network <a name="automated"></a>
This is a sub paragraph, formatted in heading 3 style

## Content analysis <a name="content"></a>
The second paragraph text

### Method <a name="methodcontent"></a>
This is a sub paragraph, formatted in heading 3 style

### Findings <a name="findingscontent"></a>
This is a sub paragraph, formatted in heading 3 style

### Limitations <a name="limcontent"></a>
This is a sub paragraph, formatted in heading 3 style

## Qualitative & quantitative approach <a name="qualquant"></a>
The second paragraph text

### Qualitative & quantitative interplay <a name="interplay"></a>
This is a sub paragraph, formatted in heading 3 style

### Advanced social data science 2 contribution <a name="asds2cont"></a>
This is a sub paragraph, formatted in heading 3 style

### Quality criteria <a name="quality"></a>
This is a sub paragraph, formatted in heading 3 style

## Discussion & conclusion <a name="conclusion"></a>
The second paragraph text

## References <a name="ref"></a>
