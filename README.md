# Climate Change and Sustainability Communication in the U.S. Democratic Party

# Table of contents
1. [Introduction](#introduction) (exam.nr: 30)
2. [Netnography](#netnography) 
    1. [Methodology](#methodology) (exam.nr: 32)
    2. [Analysis](#analysis) (exam.nr: 8)
    3. [Limitations and further research](#limitations) (exam.nr: 30)
3. [Advanced social data science 2](#asds2) 
    1. [Motivation](#motivation) (exam.nr: 19)
    2. [Applied Methods](#appmethods) (exam.nr: 2)
    3. [Discussion of preprocessing and analytical choices](#disasds) (exam.nr: 30)
    4. [Results](#resultsasds) (exam.nr: 19)
    5. [Conclusion](#conasds) (exam.nr: 2)
    6. [Discussion of alternative methods](#altmethodsasds) (exam.nr: 30)
5. [Manual & automated networks (Back to Digital Methods)](#networks) (exam.nr: 8)
    1. [Manual network](#manual) (exam.nr: 32)
    2. [Automated network](#automated)  (exam.nr: 30)
6. [Content analysis](#content) 
    1. [Methodology](#methodcontent) (exam.nr: 8)
    2. [Analysis](#findingscontent) (exam.nr: 30)
    3. [Limitations and further research](#limcontent) (exam.nr: 32)
7. [Qualitative & quantitative approach](#qualquant) 
    1. [Qualitative and quantitative interplay](#qual_quant) (exam.nr: 8)
    2. [ASDS 2 contribution](#asds_cont) (exam.nr: 30)
9. [Conclusion](#conclusion) (exam.nr: 32)
10. [References](#ref) 
11. [Appendices](#append) 
    1. [Appendix A](#appa) 
    2. [Appendix B](#appb) 
    3. [Appendix C](#appc) 


## Introduction <a name="introduction"></a>

Inter-party divide in the Democratic Party is usually based on ideological differences (Vargas, 2018). This ideological fracture is characterised by the moderate and progressive wings of the party. Although sharing some of the same goals, the moderate Democrats tend to favour slow, incremental change, whereas the progressive Democrats distinguish themselves as activists advocating for populist policies such as Medicare For All (Vargas, 2018). The conflict between the two wings of the Democratic Party was highlighted by the Green New Deal solution proposed by U.S. Representative Alexandria Ocasio-Cortez and U.S. Senator Markey (Vargas, 2018). The Green New Deal is the first comprehensive proposal to combine climate change mitigation and the elimination of economic inequality (Galvin & Healy, 2020). The majority of progressive Democrats, such as Senator Bernie Sanders, support and have signed the Green New Deal proposal, whereas some moderates, such as Representative Diane Feinstein, are more critical of it (King, 2021). This inter-party difference in how Democrats tackle and approach climate change is what this paper wishes to explore further. We want to explore how the progressive and moderate Democrats frame and approach climate change and sustainability on social media, focusing on Twitter, Facebook, and their official websites.

We decided to approach this topic using agenda setting theory. Agenda setting theory refers to media???s selection and portrayal of certain issues, which leads people to perceive those issues as more important than others and aids in their interpretation of those issues (Wu & Coleman, 2009). There are two levels of the theory: the first level concerns the amount of coverage of a certain issue, whereas the second level concerns how the issue is portrayed. Previous research investigating political communication and agenda setting usually analyse traditional media, such as news articles and political speeches (<em>ibid</em>). However, there is a push toward analysing social media communication instead, but there is lack of research in this area (Jungherr, 2016). The need to analyse social media communications stems in the rise of politicians' use of social media, where they can communicate with the public, as well as engage with political opponents (Gilardi et al., 2021). 
 
 We wish to add to the literature of analysing political communication on social media, through the lense of agenda setting theory. However, the aim of our paper is to explore the communication patterns of the two Democratic wings, i.e.,  the moderates and progressives, not to investigate what influence they have on the public's perception of topic importance and its interpretation, which is why we will use agenda setting as merely a lense for our work. We will focus on the two levels of agenda setting. Namely, what they post regarding environmental sustainability, as well as how they frame these posts. The difference in this study and the majority of literature related to agenda setting is that we will have an open-ended question focusing on the patterns emerging, rather than a set hypothesis concerning the differences in communication between the factions (Gilardi et al., 2021).
 
 As we will employ a variety of quantitative and qualitative analyses, we seek a broad research focus, especially since the digital ethnographic work underpinning our study prioritises inductive exploration (Kozinets, 2019). Our inquiry focuses on the communication of over 200 politicians on two social media platforms, which broadens the scope of the research, rather than focusing on specific individuals or just one platform. Based on this, our research question is:

 
<em> RQ: How do progressive and moderate U.S Democrats approach the topic of climate change and sustainability on social media?</em>
 
Our research design will include netnographic work, network analyses, and a content analysis. The data in the analysis was gathered from Twitter and Facebook. We delineate two wings of the Democratic Party, the moderates and the progressives, by examining the two largest congressional coalitions that relate to the two factions, the New Democrats and the Congressional Progressive Caucus (Thomsen, 2018). In the rest of this paper, the term <em>moderates</em> will refer to the members of the New Democrats, and the term <em>progressives</em> will refer to the members of the Congressional Progressive Caucus. Data for the automated network analysis and content analysis was gathered using the Tweepy-API. The actor set included all 110 members of the New Democrats and all 91 members of the Congressional Progressive Caucus, all of which currently hold office. The members were either U.S. Senators or Representatives. We chose to collect tweets from the politicians' feeds. Due to a limitation of the Tweepy-API, we only gathered the 3,200 most recent tweets from each of the politicians in our defined actor set. The Twitter data were gathered on 8-11 May 2021. The Twitter data for the progressives contains 286,668 tweets, and the dataset for the moderates contains 322,512 tweets.

The netnographic section will follow our immersion journal where we followed the top 20 politicians from the progressive and moderate wing on Facebook, Twitter, and their official websites on posts regarding climate change and sustainability. A manual network, which demonstrates how the Democrats relate to other actors when discussing climate change and sustainability, will be included. We will then conduct an automated network analysis to explore the relations between the two wings, based on Twitter mentions. In our content analysis, we will create a PCA model to investigate the placement of politicians' climate agendas in relation to one another.



## Netnography <a name="netnography"></a>

### Methodology <a name="methodology"></a>
To investigate how moderate and progressive U.S. Democrats discuss climate change and environmental sustainability on social media, we have conducted a netnography that attempts to uncover the main themes highlighted by the two coalitions. Netnography refers to a type of online ethnography that involves an immersive and iterative exploration of online data, with an emphasis on inspecting data from social media networks and other digital interactive platforms (Kozinets, 2019). Kozinets explains that while the traditional ethnography often necessitates researcher participation in the field site, typically culminating in a fieldnote journal that details these in-person activities, netnography asks the researcher to approach the online space as a data site. In these virtual environments, an immersion journal replaces conventional fieldnotes and serves as a medium in which the researcher can record data, interpret data, and engage in reflexivity in relation to these operations. This immersive dimension motivates us to use the netnographic method in our research, as it guides rich, inductive qualitative exploration of online data, providing the deep cultural understanding that ethnography prioritises. Furthermore, recent research has shown the benefits of using netnography to access a more robust interpretation of quantitative material (Blok et al., 2021), inspiring us to employ the method in our quali-quantitative study. 

In line with our research objectives, we have selected 10 Democrats from each coalition that have the largest following on Twitter. We chose to track the officials with the largest following based on the assumption that their posts reach larger audiences than their peers, which may facilitate their ability to set the public agenda (Gilardi et al., 2021). Additionally, retrieving this subsample from the original sample of 201 congressional Democrats allows for closer inspection of the site, which affords more opportunity to discover the "deep data" Kozinets (2019) describes???data that is detailed, resonant, and provides insight into larger patterns outside its scope. For these 20 officials, we have surveyed their Twitter and Facebook profiles, platforms we have chosen due to their wide use in U.S. politics as well as their potential agenda-setting capabilities (Skogerbro & Krumsvik, 2015). To collect data from these networks, two research members examined the politicians' feeds, focusing on posts that appeared to discuss the environment and sustainability. Since we did not demarcate keywords before data collection, we used our knowledge of the climate change rhetoric employed in U.S. politics to guide our initial exploration. In a spreadsheet immersion journal, we recorded the text and images of the environment-related posts, which totaled to 123 Tweets (56 from progressives and 67 from moderates) and 29 Facebook posts (18 from progressives and 67 from moderates). The earliest and latest posts were created on 12 December 2019 and 25 May 2021, respectively. We analysed these posts with the help of environmental policy information one research member inspected from the politicians' government websites, which assisted in contextualising the social media data. 

Our immersion journal not only served as a place to organise data we collected from the Web but also acted as a diary in which we reflected on our personal thoughts related to the material, attempted to reconcile our theoretical framework with the data site, and most importantly informed our overall data collection and analysis. As Kozinets (2019) explains, netnographers should use the immersion journal to "assess what [they] are looking for, where to find it, and to what it is connected" (p. 287). Thus, these writings enhanced our knowledge of the data site, which helped in revealing new keywords we considered in further data collection. We also used the immersion journal to code data, breaking down the posts into chunks and assigning labels to them. One member coded the moderate posts, another the progressive posts, and the third coded both wings' posts and the government sites. After the initial coding, we combined these codes into higher-order pattern codes, which we then analysed and employed throughout our study. 


### Analysis <a name="analysis"></a>
We do not aim to strictly compare the moderates and progressives in our netnographic analysis, as our research question seeks to understand how each faction addresses climate change and sustainability on social media, irrespective of its counterpart. Therefore, in our analysis we will highlight themes we detected from our data, though this discussion is not exhaustive of all patterns found. 

<em> Progressives: A rhetoric of intersectionality </em>

Progressive Democrats make connections between climate change and sustainability and issues pertaining to social justice, a term referring to a justice that promotes an equitable and diverse society, with consideration of marginalised communities (Bhugra, 2016). For example, in a tweet discussing a hardship faced by a community in her jurisdiction, Congresswoman Rashida Tlaib frames the climate discussion around racial inequality and corporate malpractice (Figure 1). Here, she notes how a corporate entity, Stellantis North America, participates in behaviours that pollute neighbourhoods. According to Tlaib, this pollution acts as a manifestation of the environmental racism encountered by people living in these communities. Attributing responsibility to the business in regards to environmental degradation and underscoring its consequences in terms of racial inequality draws our attention to Crenshaw's (1989) elaboration on intersectionality, which refers to the interdependent nature of social categorisations and its contribution to systems of discrimination. In this example, the social categories of race (i.e., "the environmental racism they face") and class (i.e., "residents in the [Stellantis North America] impact zone," a poor area in her jurisdiction that dwarfs in power compared to corporate interests) interrelate and act as frames in which the reader might understand the outcome of the company's unsustainable practices???a maintenance of racism and classism. We coded posts such as these as containing a number of themes, including "environmental injustice," "environmental racism," and "environment degradation and immigration," and combined them into the pattern code "intersectionality of climate and social justice."

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Figure%201.PNG)

<em> Moderates: Innovation and securing the U.S. economy </em>

When discussing climate change and sustainability on social media, moderate Democrats outline how innovation in the energy industry not only assists in combating environmental degradation but may also help improve the country's economy. A few codes associated with this rhetoric include, "energy innovation," "electric vehicles," and "economic opportunity," which were collated into the pattern code "economic opportunity in sustainability." This theme refers to the practice of framing the fight against climate change in terms of the economic prosperity the country may experience if society places value on sustainable innovation. A Facebook post by U.S. Senator Mark Warner serves as an example of this framing (Figure 2). Here, Warner suggests that developing wind energy, a practice meant to stymie climate change, assists in modernising his state's economy by creating "green" jobs. The senator even mentions the BlueGreen Alliance, a lobbying group that argues for an economically responsible solution to climate change. Many moderates appear to make this type of connection, echoing the analysis of Noel (2016), which states that centrist Democrats prioritise the nation's economy and business ventures over other political issues. 

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Figure%202.PNG)

### Limitations and further research <a name="limitations"></a>
Two main limitations characterise our netnography. First, our analysis of the two wings implies homogeneity within groups, meaning that the progressives think alike and the moderates think alike. While our grappling with the data hints that members within groups post similarly, we concur that this may not be the case. After all, our netnography investigates the social media of 20 politicians, a fraction of the larger sample. Future research should expand this sample size or randomly select members of each coalition to analyse, which would possibly afford more diversity in viewpoints. Second, aside from the initial organisation of our data collection strategy, we lacked a systematic approach to collecting tweets and Facebook posts when exploring the data site, which can be seen by the incongruent dates of the posts we recorded. Since we did not demarcate a timeframe to guide our examination of the site, we recorded posts written in 2019, 2020, and 2021, without consideration of how time may influence climate change and sustainability rhetoric. However, we note that content written across all three years share similar themes. Future research should demarcate a timeframe to examine how the political climate at a given time in history potentially influences climate change rhetoric. Some examples of codes and pattern codes we found interesting can be found in Table 1.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/table1.PNG)

## Advanced Social Data Science 2 <a name="asds2"></a>

### Motivation <a name="motivation"></a>
For our project, we focus on how different wings of the U.S. Democratic Party approach issues of climate change and sustainability. We delineate two wings of the Democratic Party, the moderates and the progressives, by examining the two largest congressional coalitions that relate to the two factions, the New Democrats and the Congressional Progressive Caucus. We aim to investigate how progressives and moderates approach environmental sustainability on Twitter through the lens of agenda setting. This motivates us to pose the following research question: 

<em> RQ: How do progressive and moderate U.S Democrats approach the topic of climate change and sustainability on Twitter? </em>

The agenda setting theory refers to the selection and portrayal of certain issues in the media, leading people to perceive those issues as more important than others and assisting in their interpretations (Wu & Coleman, 2009). There are two levels of the theory: the first level concerns the amount of coverage of a certain issue, and the second level concerns how the issue is portrayed (<em>ibid.</em>). We apply the algorithm developed by (King et al., 2017) to classify climate tweets in our dataset. Thereafter, we implement the hierarchical stochastic block model (hSBM) to explore the first level of agenda setting, i.e., what topics are present in the politicians' tweets, and the amount of coverage of these topics from the progressives and moderates. We argue that the wording used by Democrats when tweeting about climate change and sustainability acts as frames in how they want people to understand climate change and sustainability. Therefore, we will explore the second level of agenda setting by using Part of speech tagging (POS-T) to investigate the wording used in the climate tweets. 

### Applied methods <a name="appmethods"></a>

<em> Computer-assisted classifier of climate tweets </em>

Our initial sample consists of more than 600,000 tweets. We train a classifier to detect tweets with "climate" content in our large corpus. Previous studies have exemplified that choosing a set of keywords for document collection is a near-impossible task for humans to perform. As a result, ad hoc keyword selection performed by humans is usually biased and highly unreliable (King et al., 2017). Therefore, we have chosen to implement King et al.'s algorithm for computer-assisted keyword suggestions. The implementation of the algorithm can be described in the following way: a reference set, R, is defined narrowly using selected keywords from our immersion journal, which we discussed in the netnographic part of our paper. We included all tweets including the following words Q_s: {"greennewdeal," "gnd," "climate," "climatecrisis"} in our reference set. A total of 8,525 tweets were included in our reference set. We define the search set, S,  as all other tweets in our corpus. The goal with the classifier is to identify a target set, T, within the search set (T ??? S), containing documents with new examples of the concept in question. The algorithm ranks keywords from the search set by the likely relations to the concept represented by the reference set. By human input, we create Q_t, which is intended to retrieve T from S (<em>ibid.</em>). [Appendix A](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/README.md#appendix-a-) describes the implementation of the keyword algorithm in detail. We classified 11,655 tweets in total as containing climate content.  

<em> hSBM topic modelling </em>

In order to examine the topics and the coverage of these topics in the climate-related tweets of the Democrats, we use the hSBM for topic detection. This model represents the text corpus as a bipartite network consisting of words and documents. By implementing community-detection methods, we are able to detect the relevant topics in the text corpus by examining the hierarchical clusters of documents. In this analysis, we base our findings on the document groups formed at level one in the hSBM hierarchy. Previous studies have demonstrated that the hSBM model outperforms an LDA model in terms of model selection and topic accuracy (Gerlach et al., 2018). Further description of the hSBM topic model can be found in [Appendix B](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/README.md#appendix-b-). 

<em> Part of speech tagging (POS-T) </em>

We use POS-T to explore how climate change and sustainability are portrayed in the politicians' tweets. This method assigns a label to all tokens in the text corpus, indicating the words' grammatical categories. This method thereby allows us to investigate the politicians' choice of wording in the climate tweets (Meftah et al., 2018 ).

### Discussion of preprocessing and analytical choices <a name="disasds"></a>
In the following analysis, we use tweets of Democratic politicians as data. The dataset thereby consists of unstructured information, and initial preprocessing is required to obtain an applicable dataset for analysis. As the inferences of a study can be greatly sensitive to the preprocessing applied, all preprocessing decisions must be well considered (Denny & Spirling, 2018). 

In our preprocessing, we have implemented the following steps. All letters in the text corpus have been lowercased to prevent distinguishing identical words due to capitalization. Furthermore, all punctuation, separators, and numbers have been removed from the text corpus, as we have deemed these characters less critical for our analysis. Next, we have chosen to lemmatize the text corpus, enabling us to group words by their lemma. Finally, we have removed stopwords as these words usually convey little information. Finally, we have decided to remove the domain-specific terms: "RT," "via," "@mentions," and URLs. These are removed from the text-corpus in order to isolate the actual text in the tweets. This analytical choice implies that we cannot distinguish between re-tweets and original tweets, a choice we feel comfortable making as politicians often retweet posts they agree with (Guerrero-Sole, 2018). Words from re-tweets are thereby included in both the topic model and the speech tagging.

The classifier we implemented to designate climate tweets incorporates a combination of unsupervised and supervised approaches. The classifier uses an automated approach, but the interpretation of the output, i.e., which keywords to use, is based on our immersion with the topic from our netnographic work. In this way, we overcome the limitation of the quality of the training corpus from a supervised approach, as well as the interpretation issues often associated with an unsupervised approach (Chaovalit & Zhou, 2005). We have removed all prominent climate words, such as "climate," "climate chang," and "environment," from the analysis of the climate dataset. These commonly used climate words were present in most tweets and consequently did not convey great meaning. 


### Results <a name="resultsasds"></a>
We evaluate the classifier in two different ways starting with a qualitative review of the suggested keywords followed by an evaluation on both the recall and the precision. Table 2 lists the top 25 most predictive keywords for the target (T) and the non-target (S/T)  set. The table is a result of a single run of the algorithm without human input.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Table%202.PNG)

It appears that most of the target keywords are closely related to the concept of interest, sustainability and climate change. Few of the words are related but not specific enough to be included as a keyword for document retrieval. For example, if we were to include "change," we risk including too many unrelated tweets in our climate dataset. The non-target set consists of keywords that are not clearly related to climate, such as "covid" and "women." 
For the second evaluation of our classifier, we inspect the recall and precision of grouped keywords. The target set keyword list should ideally perform well on both recall and precision, whereas the non-target keyword list should perform poorly on the same measures. Figure 3 depicts the cumulative recall and precision for the first 17 keywords in the target and non-target list.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Figure%203.PNG)

Figure 3 shows that recall and precision for the target set are larger than the non-target set. The algorithm thereby successfully separates the two lists. The increasing trend of the cumulative recall indicates the need for human input, as the recall always will increase as the number of keywords added increases. The steep dive for the target set precision after two keywords added suggests that the third keyword, "chang," significantly worsens the precision. As earlier described, this is due to the general use of this word. This word should therefore not be included in the final search query for document retrieval. We included the tweets containing the tokens, Q_(r,t): {"greennewdeal," "gnd," "environment," "climate," ???climatecrisi,??? ???climatechang,??? ???earthday,??? ???actonclim,??? ???climateactionnow???} in our dataset.  

From the hSBM topic model, 19 different document communities were identified at level 1 of the hierarchical clustering. Each of these communities represent a subtopic of the climate agenda, and the tweets within each community are connected by the words used in the tweets. Table 3 shows the top five most frequently used words within each document community. We assign topics to the document communities based on the most frequently used words and by investigating the content of a subsample of the tweets within each community. Based on findings from our immersion journal (see [Netnography](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/README.md#netnography-)), we chose to merge some of the document communities in order to simplify the interpretation of topics present in tweets from moderates and progressives. The merging of the document communities is described in [Appendix C](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/README.md#appendix-c-). The communities range in size from 38 (0.3 % of all climate tweets) to 1.087 (9.3 % of all climate tweets). Community 12, 16, and 19 will be excluded from the further topic analysis, as these include tweets mainly consisting of emojis, generational security, and school/work environment, which are seemingly unrelated to our study. 

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/table%203.PNG)

Table 4 depicts the topic distribution for moderates and progressives based on document communities from hSBM topic modeling. The table does not show large differences between the two wings in the topics discussed on Twitter. The most raised topics by the democratic politicians are climate initiatives implemented by the Trump administration and intersectionality between climate and social justice. In line with our findings from the immersion journal, we find that the progressives have a stronger focus on injustices than the moderates. On the other hand, the moderates are more inclined to raise topics of how the U.S. economy could improve if it were to invest more in green energy and other sustainable innovations and a stronger focus on the local impacts of climate change.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Table%204.PNG)

Table 5 indicates that the moderates and the progressive use similar wording when tweeting about climate change and sustainability. Only a few differences in the choice of wording appear when comparing the most used nouns, adjectives, and verbs.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Tabel%205.PNG)

The moderates use the nouns economy, energy, and job more frequently than the progressives, and the progressives use the nouns justice, time, and people more frequently than the moderates. This backs up previous findings from the hSBM model that the topic of investments in green innovation is more present in tweets from moderates. In contrast, intersectionality (see [Netnography](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/README.md#netnography-)) is a topic that is more present in tweets from progressives. Looking at the adjectives used by the progressives and the moderates, only a few words differ. The word ???bold??? is more used by the progressives and calls for rather drastic and immediate changes. This stands in great contrast to the word "future," which is more commonly used by progressives. The use of verbs does not differ between the moderate and the progressive Democrats. 

### Conclusion <a name="conasds"></a>
For our project, we centered our analysis on how the progressive and moderate politicians of the U.S. Democratic Party approach climate change and sustainability on Twitter. We analyzed their portrayal and selection of climate issues on social media using the frame point of agenda setting. 
First, we trained a human-led, computer-assisted classifier to detect tweets with climate content in our large unstructured text corpus. We based our further analysis on this climate dataset. We investigate the first level of agenda setting by implementing an hSBM topic model to uncover the sub-topics of the climate tweets and the coverage of these topics by the two democratic wings. Concerns with the climate policy implemented by former president Trump is the most frequently covered topic on the Democratic politicians' Twitter timelines. Furthermore, we uncover that moderate Democrats are more prone to cover the benefits of investments in sustainable innovations and the local impacts of climate change on their Twitter profile. Progressives, on the other hand, are more likely to cover intersectionality between climate and social justice. The second level of agenda setting concerns how the democratic politicians portray climate change and sustainability issues on their Twitter accounts. Implementing POS-T, we uncover that the wording used by the progressive and moderate Democrats does not differ substantially. Both wings of the party refer to climate change as a threat to the planet which requires immediate action.

### Discussion of alternative methods <a name="altmethodsasds"></a>
Instead of investigating the second level of agenda setting, which refers to the portrayal of climate change and sustainability issues, we could have opted to do the Part Of Speech Tagging on selected politicians' tweets. Looking at individuals' use of words instead of the caucus' aggregated use of words could have provided us with more diverse findings, as writing style might depend on something different than caucus affiliation. However, this analysis would require a large number of observations for each politician, and the data collected for this project would not be sufficient. Another possibility for detecting the writing styles of politicians from the Democratic Party could be to implement a stylometry-based approach to a vector space model following the course of action presented in the study by Gomez-Adorno et al. (2018). This model requires longer text inputs, so merging the tweets for each politician or including text from the politician's official webpage would be necessary. Another interesting research question connected to the second level of agenda setting would be to investigate whether the writing style of the politicians depends on the online platform. 


## Manual & automated networks (back to Digital Methods) <a name="networks"></a>
The data in our immersion journal provides us the opportunity to approach our research question from a relational dimension. Kozinets (2019) notes that meanings do not exist as "static categories . . . [but] in specific relations and interactions" (p. 300), which motivates us to examine how moderates and progressives communicate about climate change and sustainability in relation to other actors across platforms. Here, we have used two methods to examine this network. 

### Manual network <a name="manual"></a>
<em>Methodology</em>

The data we collected in the immersion journal, including tweets and Facebook posts, served as the data used for the manual network. We decided to incorporate both platforms into the manual network analysis as we thought it important to broaden our network to include more than one context in hopes of understanding interdependencies between platforms (Lai et al., 2019). While coding themes for the netnography, we noted when the politicians discussed, mentioned, retweeted, or tagged other actors, as well as the name of the referred-to actor and the platform on which the interaction took place. While we only included actors within the coalitions for our automated network analysis, we wanted our manual analysis to expand this network by incorporating all human actors the politicians referred to in their climate-related posts. This inclusion demonstrates our commitment to the type of "thickness" Decuypere (2020) argues is important for relational research, a property that demands an examination of a variety of actors. We created two networks, one for the progressives and another for the moderates. Further elaboration on sampling, data collection strategy, and other methodological choices can be found in the netnography.

<em>Analysis</em>

Decuypere (2020) outlines a series of dimensions researchers may use when analysing networks, some of which we shall employ in our analyses. Many regions of the network belonging to the progressives are relatively dense, meaning that actors are highly interconnected in the network. This implies that to mobilise conversation related to climate change and environmental sustainability on social media, progressives often refer to each other and other actors. Connecting to the netnographic analysis, this pattern has parallels with the principle of intersectionality, as it appears that progressives shine light on many people from diverse backgrounds. An interesting element of the moderate network is that Presidents Donald Trump and Joe Biden act as prominent centers of the network, with many moderates linking to both actors. This means that the presidents hold positions of authority in the network (ibid.), potentially playing large roles in how moderates discuss climate change and environmental sustainability on the two platforms. The manual network can be seen in Figure 4.

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/figure%204.jpg)

<em>Limitations and further research</em>

Since we based the manual network analysis on our immersion journal, we examined a small number of politicians and only a fraction of their tweets related to climate change. For our netnography, this small sample did not prove much of an issue as it allowed us to uncover deep data; however, Decuypere (2020) highlights the importance of "thickness" in network research. Following fewer actors would have enabled us to more closely follow their posts, which may have assisted in making more connections between the politicians and other actors, including non-humans, an actor type our study mostly lacks. Future research could follow fewer actors to obtain this thickness and complement the observational social media data with other media???such as press releases and news articles???to gauge how different media types influence relations, a feat Lai et al. (2019) note as important in studying networks.

### Automated network <a name="automated"></a>
<em>Methodology</em>

The automated visual network analysis was conducted on the mentions among Democrats in the data regarding environmental sustainability. We did this by training a computer-assisted classifier for keyword suggestions (King et al., 2017), with reference to keywords we found in our immersion journal, as defined in ASDS2. The dataset was 11,655 tweets in total. Before gathering the climate tweet sample, we pre-processed the tweets by lowercasing all text to prevent distinguishing words due to capitalisations, as well as removing punctuation and separators. We then removed domain-specific terms: "RT," "via," "@mentions," and URLs. These are removed from the text-corpus in order to isolate the actual text in the tweets. Furthermore, we removed stop-words as they convey limited information and lemmatized the words with NLTK???s WordNetLemmatizer to group the same word with different tenses together to analyse it as a single item. The final climate dataset is what the automated network was based on. 

Firstly, the data was structured to only include mentions of members part of the two wings. Secondly, we counted the amount of times each actor was mentioned by the other actors, and this was represented by the node size, i.e., the larger the node, the more mentions.
Edge size thickness represents how often the actors have referred to each other. Aligned with Decuypere (2020), we employed a ForceAtlas2 algorithm to our network in Gephi. ForceAtlas2 works by attributing repulsive forces to nodes and attractive force to edges until it reaches a point that guarantees the best balance of forces (Decuypere, 2020). By applying this algorithm, connected nodes are linked closer to each other, which helps visualize the network. 

We believe inspecting mentions allows for more of an open conversation about topics compared to retweets, as one can write whatever they want in a mention. Furthermore, a previous study comparing a retweet and mention network on U.S. political communication on Twitter found that mention networks offered a more heterogeneous cluster of users compared to re-weets, where more users interacted with users of opposite political alignment (Conover et al., 2011). Therefore, a mention network made sense as we want to explore the communication between the factions.

<em>Analysis</em>

We applied a modularity statistic on our network using Gephi, which found a rather low modularity (0.456 out of 1). A high modularity score indicates that the actors formed distinct network structures (Yuan et al., 2019), which was not apparent in our network. This relationship may be attributed to our actors expressing similar views regarding climate change and sustainability. When analysing the network further, we refer back to our immersion journal in order to compare it to our relational data, so that we not only visualize but can also narrate the network (Decuypere, 2020). One key finding was that the edge size was thicker for progressives as compared to moderates, suggesting stronger ties among progressives. Referring back to our immersion journal, this is inline with what we found regarding how often our actors referred to each other in tweets. The largest node size was for Representatives Raul Grijalva and Donald McEachin, who are both very immersed in the climate debate. Interestingly, these two actors are from different wings, suggesting that some members of each faction intermingle to a large extent. In general, the network has a high density among all actors, and there is no distinct clustering between the two wings, which may be because the politicians are all from the same party. 

![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Figure%206.png)
**Figure 5:** Twitter mention network of the progressives and moderates

<em>Limitations and further research </em>

One shortcoming was that we only followed 20 of the politicians in the immersion journal and could not refer back to the journal on all the politicians that were a part of the automated network. Still, we could use the immersion journal to assist us in understanding general trends in how the wings discuss climate change and sustainability. Another shortcoming, and something to be explored in future research, is the use of one network over a long period of time. By making multiple networks, we can see how the connections evolve over time (Decuypere, 2020). This could be especially interesting as one could follow the Green New Deal debate, until the time the bill is passed or not, and see how the connections change with time. A single-platform analysis has the limitation of not being able to compare the findings in one medium to another (Venturini et al., 2018). In the manual network, we did cross-platform analysis, and this would also be interesting to do in the automated network, to see if there are similar trends on a larger scale.

## Content analysis <a name="content"></a>

### Methodology <a name="methodcontent"></a>
For the content analysis of the study, we have decided to conduct a principal component analysis (PCA) based on actor-word relations. PCA is a method that works by reducing the number of variables, while maintaining the majority of important information. The main task of the PCA is to simplify our model features into fewer components, to visualize the patterns in our Twitter data in an easier manner (Lever, Krzywinski, & Altman, 2017). We chose to focus on socio-symbolic constellations, as a mean of stressing the importance of actors and symbols and how they are relative to each other (Fuhse et al., 2020). In this framework, social relations consist of using the same symbols, which is useful in our study as we wish to see how the Democrats relate to each other based on words used in their climate tweets.

 The sample used for our PCA analysis included the 20 politicians we followed in our immersion journal. This was because we want to refer back to our immersion journal to qualify the quantitative findings we see from the analysis. By referring the findings back to our immersion journal, we are increasing our confidence in interpreting the results (Blok et al., 2021). The climate dataset previously defined in the automated analysis was used for the PCA analysis, focusing on only the 20 politicians from the immersion journal. Inline with Blok et al. (2021), we use the symbolic frames as emerging from the joint constellation of social and symbolic relations, i.e., the distance of the actors and Twitter term usage, instead of focusing on cultural-symbolic relations. The first step of the PCA was to count the amount of times each word appears in a tweet, before getting the tweet-frequency of each word, i.e., how many tweets the word appears in. We set our threshold to be 5 for the tweet-frequency step, i.e., dropping any words that appear less than five times. Further, we calculated the co-occurrence tweet-frequency and scaled it with the actual frequency to give less weight to infrequent co-occurrences. We then standardized the frequency of each word, to have zero variance across the actor set, by using StandardScaler from the Sci-kit Learn library. For our PCA, we will visualize these actor-word relations; the axes will represent the standardized score that positions the actors, and the word placement relates to the corresponding loading (Blok et al., 2021).

We decided to plot the local relations, with words most associated with keywords that we added (Fuhse et al., 2020). Our keywords were based on words we commonly found in the climate tweets in our immersion journal. In total we had nine keywords: (???greennewdeal,??? ???gnd,??? ???environment,??? ???climate,??? ???climatecrisi,??? ???climatechang,??? ???earthday,??? ???actonclim,??? ???climateactionnow???). We tried plenty of different keywords, and found that these were most representative of the material in our immersion journal from the 20 politicians. We plot the local association of the words related to the keywords, and the local constellation of actors associated with these words. 

### Analysis <a name="findingscontent"></a>

By looking at the left-hand side of the graph (Figure 6), we can see a cluster of words such as national, world, bold, as well as progressive Democrats Alexandria Ocacio-Cortez, Bernie Sanders, and Jerry Nadler. Inline with the netnographic work, this ties in with the pattern code "climate change requires transformative actions" of the progressive wing. On the most right-hand side we see words such as project, mitigation, subcommittee as well as moderate Democrats Mark Warner, Senator Cantwell, but also progressive Democrat Ted Lieu. This is inline with the pattern codes ???economic opportunity in sustainability??? and "incremental changes" that the moderates expressed from our netnographic work. In our immersion journal, Ted Lieu, a progressive Democrat, expressed his climate views more inline with the moderate Democrats, which would explain his position. It should be pointed out that Maxine Waters, a progressive Democrat, has been placed far to the right. This could be explained as she barely tweets about the climate, in total we recorded one tweet of hers that was related to climate. Joe Machin, who we found to be the most conservative Democrat based on his tweets and Facebook posts in the immersion journal, is placed close to carbon and company, and far away from the other politicians. Although somewhat inline with the theme ???economic opportunity in sustainability," the word Republican is also positioned here, which could explain his disconnectedness, as he is expressing more similar views to the Republican Party. In the middle of the PCA, we have both progressive and moderate Democrats placed, not particularly close to any of the word clusters. As all our actors are from the Democratic Party, they might not express clear differences when it comes to environmental sustainability, as party loyalty is often considered important in U.S. politics (Lindst??dt & Vander Wielen, 2013). 

 ![IMAGE](https://github.com/natalijaglisovic/SDS-Exam-Group-5/blob/main/images/Figure%206.PNG)

### Limitations and further research  <a name="limcontent"></a>
One limitation of our study is that our graph accounted for around 19% of variance, which is low in comparison to previous research on socio-symbolic constellations (Fuhse et al., 2020; Block et al., 2021). The lower the variance, the higher the information loss, thus there is a lot more to the actors and their word relations than what we can interpret from the graph. Another shortcoming was focusing on only 20 politicians instead of all the Democrats in our Twitter dataset, so that the PCA would be representative of all the members in the two coalitions. As explained, we wanted to refer back to our immersion journal to qualify our findings, so for future work, one should explore the entire sample of actors gathered in the tweets in the immersion journal as well to have as representative findings as possible. Further, this PCA was conducted only on tweets, for future studies it would be interesting to apply other social media platforms, to be able to compare if the communication differs across platforms. Also, it would be interesting to apply this PCA to political speeches, as Fuhse et al. (2020) did, to see if there are similar patterns in this media.

## Qualitative & quantitative approach <a name="qualquant"></a>

### Qualitative and quantitative interplay <a name="qual_quant"></a>

With the increasing use and potential of big data and analytical methods, it is important to not forget interpretation in research (Couldry, 2014). In order to address this, our paper used a combination of both qualitative and quantitative methods. The networks allowed us to see how actors related to each other. The PCA further showed how these actors related to each other, based on their usage of words in regards to environmental sustainability and climate change. The ForceAtlas2 algorithm, which we applied to our automated network, works by finding the most optimal way of cutting a network into smaller components, to find explorative patterns (Munk, 2019). In one way, this is used as a sense-making tool for us that allowed us to explore the relationships produced in the graph by narrowing in on the actors. However, in order to get a better grasp of why the actors are related, our netnographic findings offered a better explanation. As we explored all the findings in our networks and our PCA, we constantly referred back to our immersion journal to make sense of it. Further, if our immersion journal could not explain the relationship, we decided not to analyse it further (Blok et al., 2021). This is the reason for focusing on the 20 politicians we followed in our immersion journal, as we argue that if we cannot refer back to the immersion journal, we cannot fully comprehend the findings. 

As Munk (2019) proposed, qualitative and quantitative methods can be used as a complementary to each other. Our networks and PCA can prompt questions such as, ???How come X and Y are related???? or ???Why do X and Y both use these terms in regards to environmental sustainability????. However, in order to answer these questions, further work is needed. Munk (2019) went to the location to conduct interviews to collect deep data to answer these questions. In our case, we used novel digital methods and followed actors for months across platforms in an immersion journal to refer back to the relationship and communication patterns found there. An example was that we found that Joe Manchin in our PCA used very different words in regards to environmental sustainability, and was placed far from the rest of the Democrats. Without our immersion journal, we could not explain this result. 


###  ASDS 2 contribution <a name="asds_cont"></a>

The ASDS 2 part contributed to our paper as it provided us with a better overall understanding of the entire sample. In the digital methods section, all parts except the automated network focused on the 20 politicians in our immersion journal, giving us a limited, but in depth, understanding of the progressives and moderates. However, in the ASDS2 part, we conducted a hSBM topic model on the entire sample to get a sense of what topics were talked about in regards to environmental sustainability and climate change. Speech-tagging was used to make sense of how topics were talked about. Here, we could explore overall differences between moderates and progressives, and see if these findings were inline with the smaller sample from the digital methods section. Interestingly, our hSBM topic model showed that the topics differed between moderates and progressives in similar ways that we found in the immersion journal. The speech-tagging further showed differences in communication and framing choices, which were also inline with our netnographic work. It is also important to mention, that the netnographic work done in digital methods supported the work in ASDS2 equally as well, as we had an easier time making sense of the findings and referring back to our previous work.

## Conclusion <a name="conclusion"></a>
In this study, we explored how two factions of the U.S. Democratic Party, the moderates and progressives, approach issues related to climate change and sustainability on social media. We kept our research question broad as the goal of this paper was not to engage in hypothesis testing but to understand general patterns. We wanted to explore the "hows" and the "whys," which in this case was possible by the integration of quantitative methods to find patterns and qualitative methods to help interpret these findings. By employing agenda setting theory in our interpretation of the results, we can highlight a few conclusions. Progressives often pair their climate change posts with topics related to social justice and use themes that evoke a need for transformative, bold action in their framing of the issue. Interactivity characterises these discussions, in which progressives frequently refer to one another and a diverse set of actors when posting about climate. Moderates often couple discussion of climate change and sustainability with topics pertaining to sustainable innovation and frame these posts in terms of economic prosperity, implying that the nation can overcome climate change and simultaneously grow its economy. References to Presidents Biden and Trump often appear in these posts, perhaps acting as heuristics for how members of this coalition want the public to understand their positions on climate change. Future research should continue with the quali-quantitative tradition and use our immersion journal and findings to explore other issues in tension between moderate and progressive Democrats, such as health care and foreign policy. For instance, performing a thematic content analysis on social media posts related to Medicare For All???informed by categories discussed in our immersion journal???in combination with a sentiment analysis that inspects sentiments expressed in these posts could shine light on how the wings may differ in other issue fields. 

## References <a name="ref"></a>
Bhugra, D. (2016). Social discrimination and social justice. <em>International Review of Psychiatry, 28</em>(4), 336 - 341. 

Blok et al. (2021). Inter-risk framing contests: the politics of issue attention among Scandinavian climate NGOs during the coronavirus pandemic. Unpublished manuscript. 
 
Chaovalit, P., & Zhou, L. (2005). Movie review mining: a comparison between supervised and unsupervised classification approaches.<em>HICSS???05: Proceedings of 38th Annual Hawaiian International Conference on System Sciences, 4</em>(4), 1 - 9. 
 
Conover, M. D., Ratkiewicz. J, Francisco, M., Goncalves, B., Flammini, A., Menczer, F. (2011). Political polarization on Twitter. <em>Fifth International AAAI Conference on Weblogs and Social Media, 5</em>(1), 89 - 96. 

Crenshaw, K. (1989). Demarginalizing the Intersection of Race and Sex: A Black Feminist Critique of Antidiscrimination Doctrine, Feminist Theory and Antiracist Politics, <em>University of Chicago Legal Forum, 1989</em>(8). 

Denny, M. J., & Spirling, A. (2018). Text preprocessing for unsupervised learning: Why it matters, when it misleads, and what to do about it. <em>Political Analysis, 26</em>(2), 168-189.
 
Fuhse, J., Stuhler, O., Riebling, J., & Martin, J. L. (2020). Relating social and symbolic relations in quantitative text analysis. A study of parliamentary discourse in the Weimar republic. <em>Poetics, 78</em>, 101363.
 
Galvin,R., & Healy, N. (2020). The Green New Deal in the United States: What it is and how to pay for it. <em>Energy Research & Social Science, 67</em>, 1 ??? 9.
 
Gerlach, M., Peixoto, T. & Altmann, E. (2018). A network approach to topic models. <em>Science Advances, 4</em> (7)

Gilardi, F., Gessler, T., Kubli, M., & M??ller, S. (2021). Social media and political agenda setting. <em>Political Communication</em>, 1 ??? 22.

Gomez-Adorno, H., Rios, G. Duran, J.P., Sidorov, G. (2018). Stylometry-based Approach for Detecting Writing Style Changes in Literary Text. <em>Computacio y Sistemas</em>, 22(1)

Guerrero-Solio, F. (2018). Interactive behavior in political discussion on twitter: Politicians, media, and citizen???s patterns of interaction in the 2015 and 2016 electoral campaigns in spain. <em>Social Media + Society, 4</em>(4), 1 - 16. 
 
Halford, S., & Savage, M. (2017). Speaking sociologically with big data: symphonic social science and the future for big data research. <em>Sociology, 51</em>(6), 1132 ??? 1148.

Jungherr, A. (2016). Twitter use in election campaigns: A systematic literature review, <em>Journal of Information & Technology, 13</em>(1), 72 ??? 91.

King, G., Lam, P. & Roberts, M. (2017). Computer-Assisted Keyword and Document Set Discovery from Unstructured Text. <em>American Journal of Political Science, 61</em>(3)

King, L. (2021). Green New Deal too ambitious for some Democrats, even those who say Congress must ???do something???. USA Today. https://eu.usatoday.com/story/news/politics/2019/03/07/green-new-deal-not-all-democrats-board-ambitious-climate-plan/3032887002/

Koziner, R. V. (2019). Netnography: The essential guide to qualitative social media research. London: Sage.

Lai, S. S., Pagh, J., & Zeng, F. H. (2019). Tracing Communicative Patterns: A comparative ethnography across platforms, media and contexts, <em>NordiCom Review, 40</em>(1), 141 - 157. 

Lindst??dt, R., & Vander Wielen, R. J. (2013). Dynamic Elite Partisanship: Party Loyalty and Agenda Setting in the US House. <em>British Journal of Political Science, 44</em>(4), 741 - 772. 
 
Meftah, S. Semmar, N. & Sadat, F. (2018). A Neural Network Model for Part-Of-Speech Tagging of Social Media Texts, <em>European Language Resources Association</em>, L18-1446 

Munk, A. K. (2019). Four styles of quali-quantitative analysis. Making sense of the new nordic food movement on the web. <em>Nordicom Review, 40</em>(1), 159 ??? 176.

Noel, H. (2016). Ideological factions in the republican and democratic parties.<em>Annals of the American Academy of Political and Social Science, 667</em>(1), 166???188.

Skogerb??, E., & Krumsvik, A. H. (2015). Newspapers, Facebook and Twitter. <em>Journalism Practice, 9</em>(3), 350 - 366. 

Vargas, M. (2018). ???Agents of change???: the progressive democratic diffusion across U.S. house and state legislative elections in 2018. University of California Santa Cruz: Dean???s and Chancellor???s Research Award.
 
Wu, D., & Coleman, R. (2009). Advancing agenda-setting theory: The comparative strength and new contingent conditions of the two levels of agenda-setting effects. <em>Journalism & Mass Communication Quarterly, 86</em>(4), 775 ??? 789.
 
Yuan, E., Feng, M., & Liu, X. (2019). The r/evolution of civic engagement: an exploratory network analysis of the Facebook group occupy Chicago. <em>Information, Communication & Society, 22</em>(2), 267 - 285. 

## Appendices <a name="append"></a>

### Appendix A <a name="appa"></a>
Appendix A 
This appendix will briefly overview the specific steps implemented to classify Tweets containing green transition content.

**1. Define a reference set R and search set S**

We defined R as tweets including one or more of the following words, Q_r: {'greennewdeal', 'gnd', ', 'climate', 'climatecrisis', 'climatechange', 'actonclimte', 'climateactionnow'}. A total of 10,525 tweets was included in our reference set. We defined S as all other tweets in our sampled corpus, and S, thereby, includes 531.310 tweets in total. 

**2. Using classifiers to partition all documents in S into either the target set, T, or its complement, (S\T).**

**(a)** First, we define a training set by drawing a random sample from R and S. We repeated this step using different random sub-settings to increase the diversity of Keyword candidates. 

**(b)** We fitted the Naive Bayes and Logit classifiers to the training set using each tweet's actual membership in R or S as the outcome variable. We use the preprocessed text of the documents and available metadata (such as date of tweet creation, democratic wing membership, etc. ) as predictors.

**(c)** After fitting the classifiers, we use the estimated parameters to calculate the predicted probability of S being a member of R for all documents in S. The intention is that the algorithm learns from the mistakes that these classifiers make when placing high probabilities of S being in R. 

**(d)** We then aggregate the predicted probabilities of R membership from S into a single score. In this analysis, we used two different classifiers to obtain different "opinions" about the set placement of individual documents. Different classifiers pick up on different aspects of the climate concept and therefore highlight different keywords to choose from. We aggregate the probabilities across classifiers by taking the maximum probability across the classifiers as the membership score. We then use this score to group documents into T and (S\T)

**3. Find keywords that best classify documents into either T or (S\T), as follows:**

**(a)** We generate a set of potential keywords by mining S for all words that occur in more than five tweets.

**(b)** We then decide whether each keyword characterizes T or (S\T) better by comparing the proportion of tweets containing the keyword in T and (S\T).

**(c)** We rank keywords according to how well they discriminate between T and (S\T). We do this using a statistical likelihood score (see King et al., 2017)

**4. The keywords are presented in lists, and we choose words of interest for building a document retrieval query.**

Our climate dataset includes the following tokens, Q_(r,t): {'greennewdeal', 'gnd', 'environment', 'climate', 'climatecrisi', 'climatechang','earthday', 'actonclim', 'climateactionnow'} 

### Appendix B <a name="appb"></a>
Appendix B: 

Using a hSBM model gives a new framework to detect topics in unstructured text. By representing the word-document matrix as a bipartite network, inferring topics becomes a problem of inferring communities. The hSBM is a nonparametric approach that uncovers thematic structures in unstructured text and automatically determines the number of topics based on both words and documents. 

The network structure can be described via a graph consisting of a set of nodes (N) that are connected by edges (E).  In the hSBM  model, each node is assumed to have a fixed community membership (C), which is determined by the probability of an edge existing to other nodes. In this use case, each node represents a tweet, and each edge represents a word from the tweets. Thus, the documents are grouped in a community if there is a high probability that the tweets contain the same words. A more elaborate method examination can be found in "A network approach to topic models" (Gerlach et al., 2018).

### Appendix C <a name="appc"></a>
Community 1 and community 3 contain tweets on how the US economy can improve through investments in green energy and sustainable solutions. 

Community 2 contains tweets concerning legislation proposals such as the Green New Deal and the Clean Air Act and international agreements such as the Paris agreement.

Community 4, 8, and 9 include tweets protesting about climate initiatives implemented by the Trump administration.

Community 5 includes tweets that links public health issues to emission/pollution. 

Community 6 includes tweets connecting climate change to natural phenomena such as hurricanes, wildfires,  droughts, ice melting, etc. 

Community 7 and 10 call for urgency and describe climate change as the top thread to the planet. 

Community 11 and 15 contains tweets concerned about the local environment.  Community 11 mainly includes tweets about conservation and recreation of nature, whereas community  15 contains tweets about local pollution

Community 14 and community 17 contains tweets concerned with environmental injustice. Tweets from community 14 often link to other inequities as well, such as gender and racial injustice. Community 17 looks at environmental injustices between local communities/neighborhoods in the US.

Community 12 and Community 19 seem to catch topics that are not necessarily related to green transitions, such as home, school, and work environments. 

