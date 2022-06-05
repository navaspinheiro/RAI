## Responsible AI

This is for the results of an USP (University of São Paulo) ESALQ essay for the MBA Data Science and Analytics, elaborated by Roberto NAVAS Pinheiro in 2021, with orientation of Dr. Gabrielle Maria Romeiro Lombardi.

***Responsible AI  - laws and governance to assure ethical, fairness and transparent AI Business implementation***. This was the theme of the essay and I hope you will learn from it and apply sucessfully onto your own AI implementation.

### Abstract

This research is to address concerns of actual Artificial Intelligence AI utilization. How responsible are the AI solution being nowadays? Started in the 50s the AI study field was triggered to develop computational resources to learn, to think and to act like humans. A long period of lower development occurred till a confluence of factors like performance, communications, data, and algorithms had contributed to speed up AI research. Nowadays many AI cases are getting more and more adoption worldwide while countries, companies and humans are being worried when AI has irresponsible utilization. Countries and international organisms are paving the road to a common ground of Responsible AI Principles to be seem like standards. This research wants to explore how far and neglecting or how closer and aware about this Responsible AI Principles some companies are on their AI Business implementations. Participants were benefited of curated documents collected by the researcher while this one was benefited of looking for hypothesis confirmation based on respondent’s data. A questionnaire was build based onto the common ground of 17 countries and international organisms Responsible AI Principles. Respondents had their personal identifiable data kept anonymous while answering the questions.

### Introduction

Artificial Intelligence [AI] origins reassemble to the 50s at Dartmouth conference with objectives and key results that coined the term “artificial intelligence”. After a period known as “AI Winter”, where no hardware was capable to process algorithms accordingly, a convergence of conditions like hardware with more performance, broader connectivity, data being everywhere collected, all short of things producing data and connected and algorithms enhancements then, a lot of enhancement was reached out.

Analyzing current AI applications nowadays available between Common, Cool and Ethical dilemmas AI cases, we can have that:

Very ***Common*** applications of near AI (AI of a specific field): a) Waze, Uber & Ifood are samples of geo localization and regression problems successfully implemented and highly used; b) Gmail anti-Spam successfully implemented classification methods to clean our ‘inboxes’ from undesired content; c) translators of several types like Siri and Alexa are extending Natural Language Processing [NLP] capabilities; d) feed recommendation algorithms like that used by trademarks Facebook, LinkedIn, Google, YouTube, Pinterest, NETFLIX plus 'n' others are continuously benefiting their sponsors; e) fraud detection with less false positives cases are a tremendous success. Just to name a few.

***Cool*** AI applications: a) autonomous vehicles can drive for you and free your time while commuting; b) Alexa and Siri can listen and talk with you and free your hands; c) face recognition can sign in you autonomously on mobiles; d) computers can see, listen, talk, read and write for you; d) computers are successfully competing against human games' champions like in Chess and Go; e) Internet of the Things [IOT] can help you control house, companies, industries, the health and the agri-business effortless; f) decisions are taken at the speed of light for Asset Management trades, Credit Approval and Resume scrutiny between others.

Ethical ***dilemmas*** and gray frontiers with dangerous AI applications: a) who is responsible when an autonomous vehicle takes a wrong decision, crashes and kill a person? The car, the human 'passenger' not steering, the algorithm, the company, which company in a chain of integrated services; b) is your privacy being protected or used as an asset? With or without your consent; c) are you concerned when you are recognized in public spaces without being noticed; d) are you ok of being profiled in regarding the places you go, the likes you do, the searches you make, the topics you are interested in, the purchases you do; e) what your feeling would be if you are automatically classified with an early warning signal or rejected or unauthorized for something you’ve applied for because of your personal or worst your sensitive data like age, race, sexual, health, political and religion aspects; f) was it you already negatively impacted by bias on an algorithm (race, gender, age, geolocation)? By the other hands, was it you benefited by a biased decision; g) are you in control of the things (mobile, appliances, cars, assistants) around you or is the opposite; h) are you controlling the algorithms you use or is the opposite; i) are you aware of the algorithms you are interacting with (chat bots, virtual assistants) and taking decisions together you; j) commute to home via an autonomous car, automatically entering you home by means of face recognition and automatically starting to heating up your bathroom is a pleasant scenario of use case of integration between Computer Vision [CV] and IOT isn't it? But, and about if you are fired by a Lethal Autonomous Weapon [LAW] (another IOT case) that recognizes your face in a public space (another CV case) and cross and match your face against a terrorists database as a matter of a false positive event with no human supervision?

Facing these dilemmas, 17 countries or international organisms are building regulations to drive a Responsible AI utilization besides of including comprehensive strategies to be a dominant country on AI. China lunched its AI strategy in July 2017 (The State Council, 2017) a very comprehensive and broad countrywide and multiple aspects and industries strategy with goals to be a dominant country on AI theme in a short period of time and, with a low number of six, of the Responsible AI principles being recognized in their plans and statements. After this China's event, 16 other countries or international organisms like Organization for Economic Co-operation and Development [OECD], United Nations Educational, Scientific and Cultural [UNESCO], World Economic Forum [WEF] and more recently also North Atlantic Treaty Organization [NATO], published their documents stating the importance of countries and private companies to adopt a greater portion of Responsible AI aspects. While China and Dubai lunched their AI strategies in 2017 (UAE Government, 2017), last recent years (2019 and 2021) experienced an increased number of countries stating their strategies and regulations, six countries or international organisms in 2019 and nine countries or international organisms in 2021, some of the countries (The USA, Singapore, Japan and Brazil) with more than one of their publications. Most recent publications (from October 2021) are from NATO and Brazil, bringing lights about the Military utilization of AI by NATO countries and a proposal for a Brazil law about AI regulation being legislated – Brazil law is encompassing 26 Responsible AI Principles (MCTI, 2021). Most documents are Strategic Plans for driving the country's development of AI, China and Euro documents describes a Target Operating Model [TOM] about its future vision and three of them (European Union, India and Singapore) bring together a self-assessment to help countries and private organizations to draw its own plans for AI utilization in accordance with a common ground of Responsible AI principles.

The Responsible AI principles presented by more than half (50%) the countries or international organisms documents are: 100% Safety; 94% Privacy and Transparency; 88% Security; 82% Ethics and no-Bias; 76% Fairness and Accountability; 71% Robustness; 65% Protection, Explainability and Human-centered; 59% Human-rights and Responsibility; 53% Trustworthy and Well-being.

To search for how closer and aware or how far and neglecting the Responsible AI principles some companies are on their AI use cases, this research was designed for.

### Material and Methods

The research was structured in three moments: 1st the regulations for 17 countries or international organisms about Responsible AI utilization were curated by the researcher and first analysis were produced resulting on tables and graphs on Appendix I; 2nd a questionnaire was designed and publicized within the researcher’s network of contacts inviting they to be contributors, this questionnaire is described on Appendix II; 3rd the collected answers were analyzed using R language for data wrangling and exploratory data analysis showing by means of a set of graphs how engaged or disengaged the respondents are in relation with the common ground principles starting to be globally accepted – by means of legal enforcement, about Responsible Artificial Intelligence, a summary of the answers is described on Appendix III. Engagement index was calculated using R programming library called likert, which automatically produced bar blot graphs with standard scale of colors from brown (representing high disengagement) to green (representing high engagement).

Closed questions were object of qualitative measures and answers to open and free text questions had their natural language processed by means of word clouds, separating comments of positive and negative respondent’s perceptions about opportunities and risks of AI utilization, using R programming libraries tidytext and wordcloud. 

Attention was giving to protect the privacy of respondents, input of data at the main questionnaire, used to collect data related to Responsible AI awareness, with no personal data on it, this way data privacy was protected by design.

### Results and Discussion

China is the last country in the group of 17 stating controls for Responsible AI, with only 6 Principles entitled onto their country documents about AI strategies. Brazil is at the other side of the table listing 26 Responsible AI principles into their law being voted in 2021. Security of the AI solutions is the major Principle listed by all the countries and international organisms with no exception (100% of the cases), closer followed by principles of Privacy by Design aspects and Transparency in 94% of the cases. Last five years shows numbers of international laws rocking from two publications in 2017 to nine publications in 2021 (350% of increase) showing how hot this topic is worldwide (from seven distinct geographies) and some countries like Japan and Brazil doing publications twice in 2021. 

Regarding these top Artificial Intelligence concerns being addressed by multiple governs, laws and regulatory sandboxes, companies are adopting this on distinct levels. Using the Likert scale of 5 possible answers, the researcher calculated two indexes. 

![image](https://user-images.githubusercontent.com/68818979/172056616-5f05d224-4a0c-4024-9ea2-aad43962e45a.png)

where the total number of respondents that agreed or fully agreed with one AI Principle, in relation with the Total number of respondents, produces the Engagement index – a positive measure meaning that one Principle is being observed by that portion of respondents. 

![image](https://user-images.githubusercontent.com/68818979/172056647-90b26950-72d9-4ee3-9eff-b5a6cb6310c0.png)

where at the other side of the scale, the total number of respondents that disagreed or fully disagreed with one AI Principle, in relation with the Total number of respondents, produced the Disengagement index – a negative measure meaning that one Principle is being neglected by that portion of respondents. 

To visualize this information a Likert bar was plot (Picture 1) meaning that as greater the bar at the right side of Likert scale as greater the Engagement index is and as greater the bar at the left side of the Likert scale as greater the Disengagement index is. Where you can see that Privacy is the major AI Concern being observed by respondents and Fairness is the last one AI Concern being addressed by respondents AI implementations.

![image](https://user-images.githubusercontent.com/68818979/172056662-cf1a8c10-03f3-452d-aac8-906a9875d6fa.png)
Picture 1 - AI Concerns Engagement according to respondents

A second analysis was about whether respondents perceive AI more as risk or more as opportunity at their department (of a company), at their professional field of occupation (or their profession) and about with their personal life aspects. Where you can see at Picture 2 that more than 93% of respondents perceive AI as an overall Opportunity for their Companies, their Occupation or Profession and their Individual or Personal life. 

![image](https://user-images.githubusercontent.com/68818979/172056776-2f12975b-e337-4e29-b698-b37bbe0c05f0.png)

Picture 2 – How is AI perceived at Companies, Professional and at Personal life

Pictures 3 and 4 describe some natural language processing analysis comparing answers to open questions for respondents more perceiving AI as a risk (Negativity bias) and respondents more perceiving AI as an opportunity (Positivity bias).

![image](https://user-images.githubusercontent.com/68818979/172056817-9390acd9-2c6a-460f-bedf-55b1757709c1.png)

Picture 3 – overall comments for the full respondents

![image](https://user-images.githubusercontent.com/68818979/172056834-77e5c9b9-d972-48a9-855e-526cdfc2bbe5.png)

Picture 4 – comments for who’s classified its perceptions of AI utilization more as Risk (on left side) and who’s classified more as Opportunities (on right side)

For your information, word cloud plots were made tokenizing words following these restrictions: minimal frequency equal two, removed unnecessary words in Portuguese and English, all words in lower case, no white spaces, no punctuation, and no numbers. No stemming was done to contribute with a better clarity of the readers.

Third aspect was to compare respondents’ self-assessment answers into the Responsible AI assessments defined by the European Parliament Regulation Council [ERPC] (European Parliament, 2021); and the National Institution for Transforming India [NITIA] (NITIA, 2021).

Picture 5 shows self-assessment results using a Miller scale bar plot, visualizing the information showing when one Category of unacceptable AI according ERPC is being avoid.

![image](https://user-images.githubusercontent.com/68818979/172056852-7452c195-c696-4815-ba10-a37d8ade8dfb.png)
Picture 5 – Respondents’ adoption rate of categories of unacceptable utilization of AI system according to the ERPC. Left side of avoiders is preferably

Besides of unacceptable categories of utilization of AI systems, respondents made a self-assessment of their engagement index about ERPC Categories of Requirements for High-Risk AI systems. In alphabetic order, the categories are bellow, with Picture 6 showing the respondent’s engagement index:

-	Classification of the trustworthiness of natural personal based on their social behavior with social scoring leading to detrimental or unfavorable treatment of certain natural persons or whole groups,
-	Exploration of vulnerabilities of specific vulnerable groups, like children or disabled persons, to materially distort their behavior in a manner that is likely to cause them or another person psychological or physical harm,
-	Manipulation of persons through subliminal techniques beyond their consciousness,
-	Use of real time remote biometric identification system in publicly accessible spaces for the purpose of law enforcement,
-	Violation of fundamental rights.

![image](https://user-images.githubusercontent.com/68818979/172056872-23b6dd01-57ef-4b1b-a27f-fa85e753cb66.png)
Picture 6 – Respondent’s adoption rate, of ERPC categories of requirements or obligations to be observed by High-Risk AI systems or to whose providers

After ERPC questionnaire, respondents were presented to the NITI recommendations of 8 practices to be adopted for better AI systems. Being the practices respectively: 1) Problem Definition and Scoping; 2) Data Collection; 3) Data Labelling; 4) Model Selection; 5) Model Training; 6) Model Evaluation; 7) Model Deployment and 8) Ongoing Monitoring.

The engagement index to each of the NITI’s pack of practices are depicted on Pictures 7 until 14.

![image](https://user-images.githubusercontent.com/68818979/172057129-a8f2ab16-351a-4b75-8cbc-6571e5404ad0.png)

Picture 7 – Respondent’s adoption rate, of NITI recommend practices for Problem Definition and Scoping of AI systems

![image](https://user-images.githubusercontent.com/68818979/172057144-fb613334-e8b3-4dac-8c77-301de24c4c32.png)

Picture 8 – Respondent’s adoption rate, of NITI recommended practices for Data Collections of AI systems

![image](https://user-images.githubusercontent.com/68818979/172057156-9b40cd38-1c57-482a-a633-e87422f53c32.png)

Picture 9 – Respondent’s adoption rate, of NITI recommended practices for Data Labeling of AI systems

![image](https://user-images.githubusercontent.com/68818979/172057167-07251742-c667-4482-b044-b5864288f889.png)

Picture 10 - Respondent’s adoption rate, of NITI recommended practices for Model Selection of AI systems

![image](https://user-images.githubusercontent.com/68818979/172057178-0a07091c-e79e-46a0-888b-a321afbf2bce.png)

Picture 11 – Respondent’s adoption rate, of NITI recommended practices for Model Training of AI systems

![image](https://user-images.githubusercontent.com/68818979/172057186-534becab-3607-4b80-9878-3eb64c0fa9d4.png)

Picture 12 – Respondent’s adoption rate, of NITI recommended practices for Model Evaluation for AI Systems

![image](https://user-images.githubusercontent.com/68818979/172057201-bfd9ea55-479e-4a7e-84d0-5d02eb85fbd3.png)

Picture 13 – Respondent’s adoption rate, of NITI recommended practices for Model Deployment for AI systems

![image](https://user-images.githubusercontent.com/68818979/172057213-eb1b83c6-3b73-49ae-a279-7a3e3bad11de.png)

<font size="2">Picture 14 – Respondent’s adoption rate, of NITI recommended practices for Ongoing Monitoring of AI systems</font>

Demographic data of research respondents is disclosed on Appendix III.

### Conclusions

From the point of view of the research answers, top 4 concerns they are most engaged are Privacy by design, the Safety and the Ethical aspects, and the Data Protection of the AI Solutions. 6,7% of respondents consider AI exclusively as a risk for their Companies, Occupation or Life what denotes a very positive perception about the AI opportunities. 80% of respondents stated they are aware of and are avoiding The EPRC categories of unacceptable use of AI – what is really a quite good number. Yet 61,5% of respondents on average - a number with margin to be enhanced, are positively engaged with the ERPC categories of Requirements for High-Risk AI Systems as well as 67% of respondents are positively engaged with NITI recommended practices for sponsoring AI Systems – again an opportunity to enhance to a greater coverage of practices. In summary, based on these numbers is possible to say that a quite extensive background of responsible AI utilization principles are being transformed in laws in an incredible speed last 5 years and the respondents are supposedly early adopting future regulations closer to be enforced, positioned at the third quartile of the engagement index (61,5% and 67%). This denotes that companies and professional investing on the AI field are aware of the worldwide of regulations forming just ahead of us, already implementing some of the practices with margin for increasing controls for a Responsible AI utilization.

 <font size="1"> This is my text number1</font> 

 <font size="2"> This is my text number 2 </font>
 
 <font size="3"> This is my text number 3</font> 
 
 <font size="4"> This is my text number 4</font> 
 
 <font size="5"> This is my text number 5</font> 
 
 <font size="6"> This is my text number 6</font>
 
