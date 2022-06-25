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

![image](https://user-images.githubusercontent.com/68818979/172058147-0a82030b-7b52-49be-b71e-c5115911aff8.png)

where the total number of respondents that agreed or fully agreed with one AI Principle, in relation with the Total number of respondents, produces the Engagement index – a positive measure meaning that one Principle is being observed by that portion of respondents. 

![image](https://user-images.githubusercontent.com/68818979/172058172-719cefab-464d-4fb2-af95-86246bf0546a.png)

where at the other side of the scale, the total number of respondents that disagreed or fully disagreed with one AI Principle, in relation with the Total number of respondents, produced the Disengagement index – a negative measure meaning that one Principle is being neglected by that portion of respondents. 

To visualize this information a Likert bar was plot (Picture 1) meaning that as greater the bar at the right side of Likert scale as greater the Engagement index is and as greater the bar at the left side of the Likert scale as greater the Disengagement index is. Where you can see that Privacy is the major AI Concern being observed by respondents and Fairness is the last one AI Concern being addressed by respondents AI implementations.

![image](https://user-images.githubusercontent.com/68818979/172056662-cf1a8c10-03f3-452d-aac8-906a9875d6fa.png)
<font size="2">Figure 1 - AI Concerns Engagement according to respondents. Source: Research results</font>

A second analysis was about whether respondents perceive AI more as risk or more as opportunity at their department (of a company), at their professional field of occupation (or their profession) and about with their personal life aspects. Where you can see at Picture 2 that more than 93% of respondents perceive AI as an overall Opportunity for their Companies, their Occupation or Profession and their Individual or Personal life. 

![image](https://user-images.githubusercontent.com/68818979/172056776-2f12975b-e337-4e29-b698-b37bbe0c05f0.png)

<font size="2">Figure 2 – How is AI perceived at Companies, Professional and at Personal life. Source: Research results</font>

Pictures 3 and 4 describe some natural language processing analysis comparing answers to open questions for respondents more perceiving AI as a risk (Negativity bias) and respondents more perceiving AI as an opportunity (Positivity bias).

![image](https://user-images.githubusercontent.com/68818979/172056817-9390acd9-2c6a-460f-bedf-55b1757709c1.png)

<font size="2">Figure 3 – overall comments for the full respondents. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172056834-77e5c9b9-d972-48a9-855e-526cdfc2bbe5.png)

<font size="2">Figure 4 – comments for who’s classified its perceptions of AI utilization more as Risk (on left side) and who’s classified more as Opportunities (on right side). Source: Research results</font>

For your information, word cloud plots were made tokenizing words following these restrictions: minimal frequency equal two, removed unnecessary words in Portuguese and English, all words in lower case, no white spaces, no punctuation, and no numbers. No stemming was done to contribute with a better clarity of the readers.

Third aspect was to compare respondents’ self-assessment answers into the Responsible AI assessments defined by the European Parliament Regulation Council [ERPC] (European Parliament, 2021); and the National Institution for Transforming India [NITIA] (NITIA, 2021).

Figure 5 shows self-assessment results using a Miller scale bar plot, visualizing the information showing when one Category of unacceptable AI according ERPC is being avoid.

![image](https://user-images.githubusercontent.com/68818979/172056852-7452c195-c696-4815-ba10-a37d8ade8dfb.png)
<font size="2">Picture 5 – Respondents’ adoption rate of categories of unacceptable utilization of AI system according to the ERPC. Left side of avoiders is preferably. Source: Research results</font>

Besides of unacceptable categories of utilization of AI systems, respondents made a self-assessment of their engagement index about ERPC Categories of Requirements for High-Risk AI systems. In alphabetic order, the categories are bellow, with Picture 6 showing the respondent’s engagement index:

-	Classification of the trustworthiness of natural personal based on their social behavior with social scoring leading to detrimental or unfavorable treatment of certain natural persons or whole groups,
-	Exploration of vulnerabilities of specific vulnerable groups, like children or disabled persons, to materially distort their behavior in a manner that is likely to cause them or another person psychological or physical harm,
-	Manipulation of persons through subliminal techniques beyond their consciousness,
-	Use of real time remote biometric identification system in publicly accessible spaces for the purpose of law enforcement,
-	Violation of fundamental rights.

![image](https://user-images.githubusercontent.com/68818979/172056872-23b6dd01-57ef-4b1b-a27f-fa85e753cb66.png)
<font size="2">Figure 6 – Respondent’s adoption rate, of ERPC categories of requirements or obligations to be observed by High-Risk AI systems or to whose providers. Source: Research results</font>

After ERPC questionnaire, respondents were presented to the NITI recommendations of 8 practices to be adopted for better AI systems. Being the practices respectively: 1) Problem Definition and Scoping; 2) Data Collection; 3) Data Labelling; 4) Model Selection; 5) Model Training; 6) Model Evaluation; 7) Model Deployment and 8) Ongoing Monitoring.

The engagement index to each of the NITI’s pack of practices are depicted on Pictures 7 until 14.

![image](https://user-images.githubusercontent.com/68818979/172057129-a8f2ab16-351a-4b75-8cbc-6571e5404ad0.png)

<font size="2">Figure 7 – Respondent’s adoption rate, of NITI recommend practices for Problem Definition and Scoping of AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057144-fb613334-e8b3-4dac-8c77-301de24c4c32.png)

<font size="2">Figure 8 – Respondent’s adoption rate, of NITI recommended practices for Data Collections of AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057156-9b40cd38-1c57-482a-a633-e87422f53c32.png)

<font size="2">Figure 9 – Respondent’s adoption rate, of NITI recommended practices for Data Labeling of AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057167-07251742-c667-4482-b044-b5864288f889.png)

<font size="2">Figure 10 - Respondent’s adoption rate, of NITI recommended practices for Model Selection of AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057178-0a07091c-e79e-46a0-888b-a321afbf2bce.png)

<font size="2">Figure 11 – Respondent’s adoption rate, of NITI recommended practices for Model Training of AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057186-534becab-3607-4b80-9878-3eb64c0fa9d4.png)

<font size="2">Figure 12 – Respondent’s adoption rate, of NITI recommended practices for Model Evaluation for AI Systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057201-bfd9ea55-479e-4a7e-84d0-5d02eb85fbd3.png)

<font size="2">Figure 13 – Respondent’s adoption rate, of NITI recommended practices for Model Deployment for AI systems. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172057213-eb1b83c6-3b73-49ae-a279-7a3e3bad11de.png)

<font size="2">Figure 14 – Respondent’s adoption rate, of NITI recommended practices for Ongoing Monitoring of AI systems. Source: Research results</font>

Demographic data of research respondents is disclosed on Appendix III.

### Conclusions

From the point of view of the research answers, ***top 4 concern's*** they are most engaged are Privacy by design, the Safety and the Ethical aspects, and the Data Protection of the AI Solutions. 6,7% of respondents consider AI exclusively as a risk for their Companies, Occupation or Life what denotes a ***very positive perception*** about the AI opportunities. ***80%*** of respondents stated they are aware of and are avoiding The EPRC categories of unacceptable use of AI – what is really a quite good number. Yet ***61,5%*** of respondents on average - a number with margin to be enhanced, are positively engaged with the ERPC categories of Requirements for High-Risk AI Systems as well as ***67%*** of respondents are positively engaged with NITI recommended practices for sponsoring AI Systems – again an opportunity to enhance to a greater coverage of practices. In summary, based on these numbers is possible to say that ***a quite extensive background of responsible AI utilization principles are being transformed in laws in an incredible speed last 5 years and the respondents are supposedly early adopting future regulations closer to be enforced, positioned at the third quartile of the engagement index (61,5% and 67%). This denotes that companies and professionals investing on the AI field are aware of the worldwide of regulations forming just ahead of us, already implementing some of the practices with margin for increasing controls for a Responsible AI utilization***.

### Where to go from here

Aiming to contribute to you about how to attend all this sort of regulations, my recommendation is that value doesn’t magically comes from data just applying a ‘tier’ of AI – what is something that someone would like of having. Instead, for whose that are engaged onto the AI and Machine Learning [ML] world will recognizes their selves day by day routine of ML Operations as something closer to this flow of activities.

![image](https://user-images.githubusercontent.com/68818979/172060724-e76c41c0-875a-4c21-ae5c-5235cca6df0a.png)

Business problems are understood, data is Scoped and understood where to Source from, after this data is Collected, and have their Quality assured – a small group of tasks that takes a lot of time to do.

Then Data Science steps can walk through Exploratory Data Analysis, data Cleansing, Normalization and Dimensionality reduction techniques – when necessary, Models to represent the problem we are solving are Selected, Trained and had their Hyperparameters Tunned for looking the balance between over and under fit with the reality, balance between bias – to much specific to training data and variance – to incorrectly predicting. 

To reach out the best solution models are Evaluated, Compared, sometimes Learning can be Transferred and/or Reinforced, and sometimes a sort of models can be Ensembled for a best solution, that maybe, it can be such complex that it will requires resources to be explainable the AI, like Local Interpretable Model-Agnostic Explanations [LIME] and Shapley Additive exPlanations [SHAP], to bring lights on automated decisions. 

Well after this long Journey you are ready to start! 

Yes, now you can start to Deploy your AI to operation, then you start to Monitor its performance and maybe their Flaw, somehow you Retrain your model when it is Drifting from the reality, and maybe you either Retired your model. 

Ok, then you are asking where the Responsible AI Principles are, well, they spans multiple aspects of your AI development process, like this way:

![image](https://user-images.githubusercontent.com/68818979/172060763-594b90cd-2c48-45bf-8ae9-da2293ac6437.png)

And giving you straight forward guidance on how to implement all these Principles by means of internal controls and routines, you have that:

![image](https://user-images.githubusercontent.com/68818979/172060770-46f246b3-e4af-4a8b-baa8-0cca933fc9a3.png)


### References 

Zhang, L. 2020. Initiatives in AI Governance. Available at: https://static1.squarespace.com/static/5ef0b24bc96ec4739e7275d3/t/5fb58df18fbd7f2b94b5b5cd/1605733874729/SRI+1+-+Initiatives+in+AI+Governance.pdf. Access in: 25 Sep. 2021.

Comisión “Desafíos del Futuro, Ciencia, Tecnologia e Innovación”. 2019. Inteligencia Artificial para Chile. Available at: https://www.inria.cl/sites/default/files/2020-04/Propuesta%20Estrategia%20IA%20Chile_1.pdf. Access in: 25 Sep. 2021.  

European Parliament. 2021. Harmonized rules on Artificial Intelligence (Artificial Intelligence Act). Available at: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52021PC0206. Access in: 16 Oct. 2021.

Executive Office of the President. 2019. Maintaining American Leadership in Artificial Intelligence. Available at: https://www.federalregister.gov/documents/2019/02/14/2019-02544/maintaining-american-leadership-in-artificial-intelligence. Access in: 30 Oct. 2021.

Expert Group on Architecture for AI Principles to be Practice. 2021. AI Governance in Japan. Available at: https://www.meti.go.jp/press/2020/01/20210115003/20210115003-3.pdf. Access in: 30 Oct. 2021.

Ministério da Ciência e Tecnologia e Inovações [MCTI]. 2021. Estratégia Brasileira de Inteligência Artificial – EBIA. Available at: https://www.gov.br/mcti/pt-br/acompanhe-o-mcti/transformacaodigital/inteligencia-artificial. Access in: 25 Sep. 2021. 

Ministry of Economic Affairs and Climate. 2019. Strategic Action Plan for Artificial Intelligence. Available at: https://www.rijksoverheid.nl/ministeries/ministerie-van-economische-zaken-en-klimaat/documenten/beleidsnotas/2019/10/08/strategisch-actieplan-voor-artificiele-intelligentie. Access in: 09 Oct. 2021.

National Institution for Transforming India [NITIA]. 2021. Responsible AI #AIFORALL Approach Document for India. Available at: https://www.niti.gov.in/sites/default/files/2021-02/Responsible-AI-22022021.pdf. Access in: 11 Oct. 2021.

North Atlantic Treaty Organization [NATO]. 2021. Summary of the NATO Artificial Intelligence Strategy. Available at: https://www.nato.int/cps/en/natohq/official_texts_187617.htm. Access in: 31 October 2021.

Organization for Economic Co-operation and Development [OECD]. Recommendation of the Council on Artificial Intelligence. 2019. Available at: https://legalinstruments.oecd.org/en/instruments/OECD-LEGAL-0449. Access in: 21 Oct. 2021.

Personal Data Protection Commission [PDPC]. 2019. Artificial Intelligence Governance Framework 2nd edition. Available at: https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgmodelaigovframework2.pdf. Access in: 30 Oct. 2021.

Secretary of State for Digital, Culture, Media and Sport by Command of Her Majesty. 2021. National AI Strategy. Available at: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/1020402/National_AI_Strategy_-_PDF_version.pdf. Access in: 30 Oct. 2021.

The German Federal Government. 2020. Artificial Intelligence Strategy. Available at: https://www.ki-strategie-deutschland.de/files/downloads/Fortschreibung_KI-Strategie_engl.pdf. Access in: 16 Oct. 2021.

The State Council. 2017. New Generation Artificial Intelligence development plan. Available at: http://www.gov.cn/zhengce/content/2017-07/20/content_5211996.htm. Access in: 16 Oct. 2021.

UAE Government. 2017. UAE Strategy for Artificial Intelligence. Available at: https://u.ae/en/about-the-uae/strategies-initiatives-and-awards/federal-governments-strategies-and-plans/uae-strategy-for-artificial-intelligence. Access in: 16 Oct. 2021.

United Nations Educational, Scientific and Cultural Organization [UNESCO]. 2020. Recommendation on the Ethics of Artificial Intelligence. Available at: https://unesdoc.unesco.org/ark:/48223/pf0000373434. Access in: 27 Nov. 2021.

World Economic Forum [WEF]. 2019. AI Governance: A Holistic Approach to Implement Ethics into AI. Available at: https://www.weforum.org/whitepapers/ai-governance-a-holistic-approach-to-implement-ethics-into-ai. Access in: 21 Oct. 2021.

These were the countries and international organisms studied.

![image](https://user-images.githubusercontent.com/68818979/172497276-b19b858a-84ba-4b1c-89e4-f1155474d065.png)

### Appendixes
 
Additional content related to the research with detailed data supporting the information shared during the above sessions. 


***Appendix I – INTERNATIONAL LANDSCAPE of RESPONSIBLE AI PRINCIPLES***

Bellow table depicts 17 references of Responsible AI regulation being proposed worldwide by 13 Countries and four international organisms globally distributed from east to west, from Americas to Asia passing by the European Union.

| Country  | Is a Regulation | Describes the COM? | Gives Future Vision? | Describes a TOM? | Is a Strategic Plan? | Has a Self-Assessment? | 
|--------- | --------------- | ------------------ | -------------------- | ---------------- | -------------------- | ---------------------- |
| Belgium  |  | Yes |  |  |  |  | 
| Brazil   | Yes | Yes |  |  | Yes |  | 
| Chile    |  | Yes |  |  | Yes |  |
| China    |  |  | Yes | Yes | Yes |  |
| Dubai    |  |  |  |  | Yes |  |
| Euro     | Yes |  | Yes | Yes | Yes | Yes |
| Germany  |  |  |  |  | Yes |  |
| India    |  |  | Yes |  | Yes | Yes |
| Japan    |  |  | Yes |  | Yes |  |
| Singapore |  |  | Yes |  | Yes | Yes |
| The Netherlands |  | Yes | Yes |  | Yes |  |
| The United Kindgon |  |  | Yes |  | Yes |  |
| The United States of America | Yes |  |  |  | Yes |  |
| NATO     |  |  |  |  | Yes |  |
| OECD     |  |  |  |  | Yes |  |
| UNESCO   |  |  | Yes |  |  |  |
| WEF      |  |  | Yes |  |  |  |

<font size="2">Table 1 - Countries and International organisms publicizing Responsible AI Principles strategic plans. Source: original research results. Notes: COM is Current Operating Model, is the actual situation. TOM is Target Operating Model, is the future state desired. NATO states for North Atlantic Treaty Organization. OECD states for Organisation for Economic Co-operation and Development. WEF states for World Economic Forum. Source references are available at the References session.
</font>

The infographic bellow visually shows the number of publications addressing Responsible AI Principles in the recent years, with increasing number of new countries stating their principles.

![image](https://user-images.githubusercontent.com/68818979/172059762-f6cb9074-555b-443a-9640-b70d43dfab02.png)

<font size="2">Figure 15 – infographic with countries and organisms’ publications last 5 years. Source: Research results</font>

Compiling this list of above 17 publications of 13 countries and four international organisms, an ordered list of Responsible AI Principles was possible to be obtained, resulting on a graph showing the common sense between these places, the topmost concern, and the lesser common principles that received citation by these countries strategies to address a Responsible AI utilization.

![image](https://user-images.githubusercontent.com/68818979/172059822-ee8b1f75-0b2f-44bb-a296-57fec2332c34.png)

<font size="2">Figure 16 – Responsible AI Principles supported by each of the countries. Source: Research results</font>

And compiling the number of Responsible AI Principles that were cited by each Country and International Organism we have this ordered list.


***Appendix II – Research questionnaire***

Based onto the curated data gathered from the 17 countries publications about Responsible AI between 2017 and 2021, one questionnaire was draw aiming to gather demography data and the engagement and disengagement indexes related to major AI principles. Questionnaire sessions and questions are shown at the link bellow.

<a href="(https://drive.google.com/file/d/1AyJ_XohCjrR64XC0At25r_Ig8q1r7DYh/view?usp=sharing)">Questionnaire</a>

***Appendix III – Demographic data***

Respondents’ demographic data – with no personal data attached to.

![image](https://user-images.githubusercontent.com/68818979/172059949-64980a57-7331-41be-ad77-4fd18f1c7cb8.png)

<font size="2">Figure 17 – respondent’s demographic data by Economic Sectors (A), Market Segment (B), Roles (C) and Department (D). Source: Research results</font>

In relation to the country where the respondent company is head-quartered, this is the geographical distribution, based on each country’s capital geolocation.

![image](https://user-images.githubusercontent.com/68818979/172059980-bfe177f4-376b-47e5-9531-95bb889add1c.png)

<font size="2">Figure 18 – geolocation of country’s capital of where are the respondent’s companies headquartered. Image source: produced using R tool and the tmap library. Source: Research results</font>

![image](https://user-images.githubusercontent.com/68818979/172060006-dc586d8e-3244-4820-9494-f673da8a1c31.png)

<font size="2">Figure 19 – Country of the headquarter of respondent’s organizations. Source: Research results</font>

Supporting the conclusions – at the body of the text, these three graphs depicted together demonstrates that the major portion of respondents are positively engaged with the Responsible AI principles, all of them positioned at least onto the third quartile of respective graphs, comparing both with the same scale, from 0 (zero) to 100% of engagement index.

![image](https://user-images.githubusercontent.com/68818979/172060027-99d4df75-b55e-4cfa-b121-10d6be55b610.png)

<font size="2">Figure 20 – Major engagement indexes supporting RAI principles, the Requirements for high-risk AI systems and the NITI practices. Source: Research results</font>



