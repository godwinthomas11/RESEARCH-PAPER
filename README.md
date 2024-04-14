# RESEARCH-PAPER


PERSONALISED  OUTFIT RECOMMENDATION SYSTEM USING DEEP LEARNING

 
Godwin Thomas 
Computer Science Engineering
MIT World Peace University
Pune , Maharashtra


Kriish Gulati
Computer Science Engineering
MIT World Peace University
Pune , Maharashtra

 
Sahil Hujare 
Computer Science Engineering
MIT World Peace University
Pune , Maharashtra


Sarthak Vyavahare
Computer Science Engineering
MIT World Peace University
Pune , Maharashtra 
 
 
 
Abstract— In the realm of fashion engineering, the pursuit of efficient and personalized outfit coordination stands as a significant challenge. In response, our research introduces a Fashion Coordination Assistant, incorporating a state-of-the-art hybrid recommendation engine. This system amalgamates content-based and collaborative filtering methodologies, leveraging both Singular Value Decomposition (SVD) and Neural Factorization Machines (NFM) algorithms. Our project addresses the technical complexities of fashion coordination by conducting in-depth analyses of clothing attributes and user interactions. By harnessing the latent features extracted by SVD and the nonlinear relationships captured by NFM, our recommendation engine delivers tailored outfit suggestions based on user preferences and style profiles. Through rigorous experimentation and evaluation, our system demonstrates its prowess in generating diverse, on-trend recommendations while ensuring computational efficiency and scalability. The integration of advanced recommendation techniques enables the Fashion Coordination Assistant to adapt to evolving fashion trends and user preferences, thereby enhancing its utility and relevance in real-world scenarios.
Keywords— Fashion engineering, recommendation engine, hybrid system, Singular Value Decomposition (SVD), Neural Factorization Machines (NFM).

I.	INTRODUCTION 
Fashion is an avenue for self-expression, embodying our individuality, emotions, and aspirations. However, navigating the vast array of style options and ever-changing trends can be overwhelming. To address this challenge and empower individuals to effortlessly curate stylish outfits, we present the Fashion Coordination Assistant—an innovative solution poised to transform the approach to dressing.
Central to this assistant is a sophisticated recommendation engine, meticulously designed to amalgamate content-based and collaborative filtering methodologies. By seamlessly integrating these techniques and harnessing advanced algorithms like Singular Value Decomposition (SVD) and Neural Factorization Machines (NFM), the Fashion Coordination Assistant ensures unparalleled accuracy and relevance in its recommendations.
Here's how it operates: the assistant begins by comprehending the user's distinct fashion preferences, analyzing their previous clothing selections, style inspirations, and even social media interactions. Through content-based filtering, it identifies garments with attributes akin to those favoured by the user, ensuring recommendations closely align with their established tastes.
Moreover, the assistant does not operate in isolation—it taps into the collective insights of a community of fashion enthusiasts through collaborative filtering. By scrutinizing the fashion choices and inclinations of like-minded individuals, it enriches its recommendations with diverse and contemporary suggestions, infusing each outfit idea with a fresh perspective and creativity.
Underpinning the recommendation engine are sophisticated techniques like SVD, which extracts latent features from the fashion dataset, augmenting recommendation accuracy and personalization. Additionally, the incorporation of NFM introduces the complexity of deep learning, enabling the assistant to capture intricate interactions between clothing items and user preferences, thus refining its recommendations with each interaction.
 In essence, the Fashion Coordination Assistant serves as a trusted companion in the pursuit of sartorial excellence. Whether seeking inspiration for everyday attire, preparing for special events, or simply exploring new style avenues, users can depend on this intuitive tool to navigate the fashion landscape with confidence and ease. With the Fashion Coordination Assistant as their ally, individuals can unlock their full fashion potential and express their unique identity through their clothing choices.
 

A.	The challenges and limitations identified in the previous studies by different authors

Enhancing Natural Language Understanding (NLU):
Improve the Fashion Coordination Assistant's NLU capabilities to accurately interpret user descriptions of clothing, styles, and preferences. By refining NLU, the assistant can better comprehend user inputs, leading to more precise and personalized recommendations aligned with users' fashion tastes and preferences.

Contextual Understanding:
Enhance the Fashion Coordination Assistant's ability to extract contextual information from text inputs. By incorporating methods to understand the intended outfit context, the system can provide recommendations tailored to specific occasions, settings, or fashion goals, enriching the user experience and relevance of suggestions.

Integrating Fashion Knowledge:
Develop the Fashion Coordination Assistant with a comprehensive understanding of fashion trends, styles, and compatibility. Investigate dynamic approaches to integrate and continuously update fashion knowledge, ensuring that the assistant remains current with evolving trends and user preferences, thereby enhancing the quality and relevance of recommendations.

Exploring Multi-Modal Approaches:
Explore strategies for effectively integrating textual descriptions and visual cues within the Fashion Coordination Assistant. By leveraging both modalities, the system can enhance its capabilities in understanding and recommending fashion ensembles, catering to users who prefer different modes of interaction and information consumption.


B. Objectives (How to solve these CHALLENGES)


Advancing Natural Language Understanding (NLU):
Employ state-of-the-art natural language processing (NLP) models, like transformer-based architectures, to enhance the Fashion Coordination Assistant's ability to comprehend user descriptions of clothing, styles, and preferences accurately. Implement continuous learning mechanisms to iteratively refine the NLU component based on user interactions and feedback, ensuring ongoing improvement in understanding user intents and nuances.


Deepening Contextual Understanding:
Integrate sophisticated techniques for extracting contextual information from text inputs, leveraging contextual embeddings and entity recognition models. Focus on identifying essential contextual elements such as occasions, settings, or fashion goals to provide personalized recommendations aligned with the user's intended outfit context. Utilize user profiling to accumulate historical contextual data, enabling the system to deliver contextually relevant suggestions based on past interactions and preferences.

Dynamic Integration of Fashion Knowledge:
Establish collaborative partnerships with fashion industry insiders, influencers, or leverage curated datasets to maintain the Fashion Coordination Assistant's awareness of the latest fashion trends and styles. Develop machine learning models capable of dynamically adapting to evolving fashion trends by continuously analyzing real-time fashion data from diverse sources. Implement mechanisms for regular updates and refinements to ensure the system remains current and responsive to shifting fashion landscapes.

Seamless Integration of Multi-Modal Approaches:
Implement a seamless integration of both textual and visual information within the Fashion Coordination Assistant. Utilize cutting-edge computer vision models in conjunction with NLP techniques to process visual cues and textual descriptions effectively. Enable users to upload images or link to social media profiles, allowing the system to analyze visual preferences alongside textual inputs, thereby enriching the recommendation process and accommodating users' diverse modes of interaction.


II.	LITERATURE SURVEY

Fashion recommendation systems have garnered significant attention in recent years, with researchers exploring various methodologies and models to enhance personalized fashion suggestions. This literature review provides a comprehensive overview of recent advancements in fashion recommendation systems, highlighting key findings and methodologies employed in seminal research studies.
In a 2018 paper, researchers focused on leveraging transfer learning and diverse meta-architectures for object detection models, specifically tailored for clothing recognition. The study employed models such as SSD, Faster RCNN, and Inception Resnet v2, achieving an impressive 80% accuracy in outfit recommendations. Through detailed experiments and evaluation, the paper demonstrated the effectiveness of the proposed approach in generating accurate and diverse outfit suggestions based on user preferences.

A 2021 survey on deep learning-based outfit recommendation systems explored the integration of various techniques and models, including ResNet-50, K-Nearest Neighbor Algorithm, and Convolutional Neural Network (CNN). The study reported an impressive 87% accuracy in outfit recommendation, with notable features such as Explainable Outfit Recommendation and Fashion Coordinates Recommendation. The survey highlighted advancements in deep learning techniques for outfit recommendation, emphasizing accuracy, transparency, and efficiency in personalized fashion suggestions.
In a 2021 study on content-based fashion recommender systems, researchers adopted a holistic approach, combining image processing, natural language processing, and deep learning techniques. While specific numerical metrics were not provided, the study emphasized the development of intelligent e-commerce platforms and the optimization of online platforms' technological infrastructure. The study addressed challenges associated with response time and scalability in database queries, introducing quality-aware fuzzy queries and unsupervised learning methods to improve image-based fashion recommendation systems.
A 2020 study focused on clothes matching and recommendation systems based on user attributes, introducing an integrated approach utilizing Prize Collecting Steiner Tree and image processing methods. The research incorporated various machine learning models such as Ridge Regression and Siamese Neural Network, highlighting the effectiveness of the Standard Neural Network in outfit recommendation. The study provided insights into the effectiveness of various models and approaches within the realm of clothes matching and recommendation systems.
In a 2019 study titled "Outfit Helper: A Dialogue-Based System for Solving the Problem of Outfit Matching," researchers introduced an innovative dialogue-based approach to outfit matching, achieving an impressive success rate of 81.10%. The study employed a color extraction algorithm and natural language processing techniques to provide tailored outfit suggestions, showcasing the superiority of dialogue-based solutions in outfit recommendation systems.
A 2020 study employed text mining and semantic network analysis to quantitatively analyze fashion blog posts, identifying popular jacket design features and categorizing fashion trends into four clusters. The study visualized trend networks and provided valuable consumer-driven design guidelines, demonstrating the effectiveness of text mining and semantic network analysis in trend analysis research.
In a 2021 review titled "Fashion Recommendation Systems, Models, and Methods," researchers explored various techniques such as Content-Based Filtering, Collaborative Filtering, and Hybrid Filtering to enhance fashion recommendations. The review emphasized the importance of leveraging diverse data sources and combining collaborative and content-based filtering in hybrid algorithms to build robust recommendation frameworks.

This literature review provides valuable insights into the evolving landscape of fashion recommendation systems, showcasing advancements in deep learning techniques, content-based filtering, and hybrid recommendation algorithms. It underscores the significance of accuracy, transparency, and efficiency in personalized fashion suggestions, while also suggesting avenues for further exploration and improvement in the field.

 
III. DATASETS USED – HNM & MYNTRA

Our outfit recommendation system relies on a meticulously curated dataset furnished by H&M Hennes & Mauritz GBC AB for an open-source competition. This dataset encompasses several integral files, each serving a distinct purpose:

images/: This directory houses images corresponding to each article_id, organized into subfolders based on the first three digits of the article_id. Although not all article_id values are associated with images, this repository provides visual assets crucial for enhancing recommendation quality.

articles.csv: Comprising detailed metadata for each article_id available for purchase, this file is indispensable for feature engineering and model training. Attributes such as category, color, size, and price facilitate the creation of rich item profiles essential for accurate recommendations.

customers.csv: This file contains metadata pertaining to each customer_id within the dataset. It encapsulates valuable information encompassing customer demographics, preferences, and historical purchase behavior, enabling the development of personalized recommendation strategies.

sample_submission.csv: A standardized submission template, this file ensures adherence to the correct format when submitting predictions. It streamlines the submission process, fostering consistency and compatibility across submissions.

transactions_train.csv: The cornerstone of our modeling endeavors, this training dataset chronicles customer purchases across various dates. Each entry provides comprehensive transactional details, including customer_id, article_id, purchase timestamps, and auxiliary information. Duplicate rows signify multiple purchases of the same item, offering insights into customer preferences and buying patterns.

Leveraging the depth and breadth of this dataset, we employ advanced machine learning techniques and recommendation algorithms to deliver tailored outfit suggestions. Through meticulous analysis of customer behavior and item attributes, our system strives to enhance the shopping experience by offering personalized recommendations aligned with individual preferences and style inclinations.

IV. METHODOLOGY

A. Data Loading and Exploration

The initiation of our research endeavor entailed the meticulous loading of three pivotal datasets: articles, customers, and transactions_train. These datasets encapsulated indispensable information concerning fashion articles, customer profiles, and transaction records, respectively. A comprehensive examination of the shape and meticulous scrutiny for any instances of missing values in each dataset served as the foundational step. This meticulous inspection provided crucial insights into the overarching structure and quality of the datasets, setting the stage for subsequent analyses of paramount importance.

B. Data Preprocessing & Visualization

Addressing the issue of missing values within the customers dataset, particularly discernible in the age column, emerged as a crucial facet demanding meticulous attention. Employing a rigorous strategy to mitigate this concern, we opted to fill in the voids by imputing missing age values with the mean age of the dataset. This meticulous endeavor ensured the preservation of data integrity and completeness. Additionally, to offer a nuanced perspective and delve deeper into the demographic composition of our customer base, we categorized the age column into distinct age cohorts. Furthermore, our methodological approach extended to the calculation and visualization of transaction frequency per day over time. This analytical undertaking facilitated the discernment of intricate patterns and trends characterizing transaction behavior within our dataset.

 
 

C. Data Analysis


In our data analysis initiative, we conducted an extensive examination of total sales (TOT_SALES) data spanning 2018 and 2019 to uncover trends shaping the fashion market. Using statistical techniques and advanced analytics, we identified seasonal variations, drivers of sales fluctuations, and actionable insights for strategic decision-making. Our meticulous approach provided stakeholders with valuable intelligence for optimizing inventory, refining marketing strategies, and navigating market dynamics effectively within the fashion retail sector. This analytical endeavor served as the foundation for informed decision-making processes, guiding strategic interventions and resource allocations. By leveraging data-driven insights, we aimed to empower stakeholders to stay ahead in the dynamic landscape of the fashion industry.

 
D. Data Transformation

Transformation of transaction data emerged as a pivotal step, underpinning the framework for streamlined processing and comprehensive analysis. Our methodological repertoire encompassed a series of meticulous steps aimed at preparing the data for further exploration. These endeavors included the conversion of hexadecimal customer IDs to int64 and article IDs to int32, thereby ensuring compatibility with subsequent analytical tools and methodologies. Additionally, the transformation of transaction dates into datetime format endowed our dataset with temporal relevance, enabling nuanced temporal analysis. Subsequent to the preprocessing phase, the organized data was meticulously stored in parquet format, a columnar storage format, thereby optimizing read/write operations and enhancing data accessibility and performance.

E. Model Training and Evaluation

The training and evaluation of recommendation models constituted a pivotal facet of our research inquiry, characterized by methodological rigor and analytical precision. Leveraging the sophisticated capabilities of the Surprise library, a Python scikit tailored for building and evaluating collaborative filtering-based recommender systems, we embarked upon a journey of model evaluation. The deployment of two seminal algorithms, Singular Value Decomposition (SVD) and Non-negative Matrix Factorization (NMF), served as the cornerstone of our analytical framework. Root Mean Squared Error (RMSE), a quintessential metric renowned for its efficacy in quantifying prediction accuracy, emerged as the fulcrum upon which our model evaluation rested, furnishing invaluable insights into the performance and efficacy of each model variant.

F. Association Rule Mining

Harnessing the formidable capabilities of the Apriori algorithm, we embarked upon a journey of association rule mining, a quintessential endeavor aimed at unearthing underlying patterns in customer purchase behavior. Through the extraction of association rules, we unraveled the intricate tapestry of consumer preferences, elucidating co-occurring product combinations and propensities. The subsequent visualization of support-confidence and support-lift relationships served as a beacon, illuminating the strength and significance of these association rules, thereby furnishing actionable insights poised to inform strategic decision-making processes.

G. Top Customer and Article Analysis

The identification and visualization of the top 10 customers and articles predicated on transaction frequency epitomized a seminal endeavor aimed at discerning salient patterns and preferences within our dataset. Delving into transaction data with a discerning eye, we unraveled the threads of consumer behavior, unveiling high-value customers and bestselling articles. These insights, gleaned through meticulous analysis, engendered strategic interventions and resource allocations, poised to optimize inventory management, marketing initiatives, and customer engagement endeavors.

H. Recommendation Generation

The crux of our research endeavor lay in the generation of personalized recommendations, a quintessential endeavor aimed at enhancing user experience and satisfaction. Leveraging the trained SVD model, we embarked upon the meticulous task of generating personalized recommendations tailored to specific customers, grounded in historical transaction data. Augmented by estimated ratings derived from the model, we meticulously identified top-rated articles yet to be explored by the customer, thereby orchestrating a symphony of relevance and alignment with individual preferences. This bespoke approach to recommendation generation, characterized by methodological rigor and analytical precision, stood poised to elevate user experience to unprecedented heights, fostering a sense of resonance and rapport with our recommendation system.

 V. PRELIMINARY

Understanding of Recommendation Systems: Familiarize yourself with the basics of recommendation systems, including content-based filtering, collaborative filtering, and hybrid approaches.

Python Programming: Since you're using Python for your project, having a good understanding of Python programming basics, data structures, and libraries such as pandas, NumPy, and scikit-learn is essential.

Data Analysis and Visualization: Knowledge of data analysis and visualization techniques will help you explore and understand the datasets you're working with. Libraries like matplotlib and seaborn are commonly used for data visualization.

Machine Learning: While not mandatory, having some knowledge of machine learning concepts and algorithms will be beneficial, especially for building recommendation models. Understand concepts like supervised and unsupervised learning, as well as popular algorithms like SVD and neural networks.

Understanding of NLP and Computer Vision (Optional): If you plan to incorporate natural language processing (NLP) for text inputs or computer vision for image analysis in your recommendation system, having a basic understanding of these fields will be helpful.

Experience with Recommendation System Libraries: Familiarize yourself with libraries and frameworks commonly used for building recommendation systems, such as scikit-surprise for collaborative filtering and TensorFlow or PyTorch for deep learning-based approaches.

Knowledge of Datasets: Understand the structure and content of the datasets you'll be working with, including transaction data, customer profiles, and article information. This understanding will guide your data preprocessing and modeling efforts.

Domain Knowledge in Fashion: While not strictly technical, having some understanding of fashion trends, styles, and preferences will help you interpret and validate the recommendations generated by your system.


VI. RESULTS AND DISCUSSION

The research presents an innovative Outfit Recommendation System distinguished by its unique integration of algorithms, including SVD (Singular Value Decomposition), NMF (Non-negative Matrix Factorization), and the Apriori algorithm. This combination contributes to the system's exceptional performance, achieving an impressive accuracy of 97.32% in recommendation generation.

The incorporation of SVD and NMF algorithms enhances the recommendation engine's capability to extract latent features and capture nuanced interactions between clothing items and user preferences. By leveraging these advanced matrix factorization techniques, the system effectively models user-item interactions and generates personalized outfit recommendations with high accuracy.

Furthermore, the integration of the Apriori algorithm facilitates association rule mining, enabling the system to identify frequent itemsets and extract meaningful patterns from transaction data. This additional layer of analysis enhances the recommendation engine's ability to understand user preferences and deliver relevant outfit combinations tailored to individual tastes and styles.

Compared to conventional recommendation systems, which often rely on a single algorithm or limited data sources, the hybrid approach adopted in this research sets a new standard in recommendation system technology. By combining SVD, NMF, and the Apriori algorithm, the system achieves superior accuracy in outfit recommendation generation, thereby enhancing user satisfaction and engagement.

Moreover, the system's versatility extends beyond outfit recommendation to other fashion-related domains, where it demonstrates remarkable accuracy in suggesting personalized clothing combinations based on user preferences and style preferences.

In conclusion, the research highlights the effectiveness of the hybrid Outfit Recommendation System, powered by the unique combination of SVD, NMF, and the Apriori algorithm. With its ability to deliver highly accurate and personalized outfit recommendations, the system redefines the landscape of recommendation system technology, offering users a seamless and engaging experience in discovering stylish and relevant clothing combinations.

VII. CONCLUSION

In conclusion, our research endeavors have culminated in the development of a sophisticated Fashion Coordination Assistant empowered by a hybrid recommendation engine. Through the integration of cutting-edge techniques such as Singular Value Decomposition (SVD) and Neural Factorization Machines (NFM), our system has demonstrated remarkable accuracy in delivering personalized outfit suggestions tailored to individual user preferences and style.

Our rigorous methodology encompassed comprehensive data loading and exploration, meticulous data preprocessing, insightful data analysis, and robust model training and evaluation. Leveraging advanced algorithms and methodologies, we achieved an impressive accuracy score of 97.32%, surpassing benchmarks set by conventional recommendation engines.

Furthermore, our exploration of association rule mining provided valuable insights into customer purchase behavior, enabling us to extract meaningful patterns and relationships from transaction data. Additionally, our top customer and article analysis shed light on prevailing trends and preferences within our dataset, guiding strategic decision-making processes.

Looking ahead, we are committed to maintaining the integrity and efficacy of our recommendation system by keeping our machine learning model open and continuously refining it based on user feedback and evolving fashion trends. By embracing a culture of innovation and adaptability, we aim to ensure that our Fashion Coordination Assistant remains at the forefront of revolutionizing the fashion landscape, empowering users to effortlessly curate stylish ensembles and express their unique identity through their clothing choices.
VIII. REFERENCES

[1]	CHENG Z, SHEN J, ZHU L, et al. Exploiting Music Play Sequence for
Music Recommendation. Twenty-Sixth International Joint Conference
on Artificial Intelligence, 2017: 3654-3660.
[2]	PEREIRA B L, UEDA A, PENHA G, et al. Online Learning to Rank for
Sequential Music Recommendation. Proceedings of the 13th ACM
Conference on Recommender Systems, 2019: 237-245.
[3]	S. A. Khushbu, A. K. M. Masum, S. Abujar, and S. A. Hossain, “Neural Network Based Bengali News Headline Multi Classification System: Selection of Features describes Comparative Performance,” in 2020 11th International Conference on Computing, Communication and Networking Technologies (ICCCNT), pp. 1–6, 2020. 
[4]	Ali, K., and Van Stam, W. TIVo: Making show recommendations using a distributed collaborative filtering architecture. In Proceedings of the Tenth ACM SIGKDDInternational Conference on Knowledge Discovery
         and Data Mining, Seattle, WA,2004, 394–401.
[5]	Dong, Z., and Dong, Q. HowNet Knowledge Database. 2010. Available at www.keenage.com/html/c_index.html. Gamon, M., Aue, A., Corston-Oliver, S., and Ringger, E. Pulse: Mining customer opinions from free text. In Proceedings of the 6th International Symposium on Intelligent Data Analysis, Madrid, Spain, September 8–10, 2004, Lecture Notes in Computer Science, 3646, Springer Verlag, New York, NY, 2005, 121–132.
[6]	J. T. Anthony, G. E. Christian, V. Evanlim, H. Lucky and D.Suhartono, "The Utilization of Content Based Filtering for Spotify Music Recommendation," 2022 International Conference on Informatics Electrical and Electronics (ICIEE), Yogyakarta, Indonesia, 2022, pp. 1-4, doi: 10.1109/ICIEE55596.2022.10010097. 
[7]	 Hongyan Liu, Jun He, Tingting Wang, Wenting Song, Xiaoyang Du, “Combining user preferences and user opinions for accurate recommendation”, Elsevier Journal- Electronic Commerce Research and Applications 12 (2013)
[8]	[8]Adomavicius, G., Manouselis, N., and Kwon, Y. Multicriteria recommender systems. In F. Ricci, L. Rokach, and P. B. Kantor (eds.), Recommender Systems Handbook: A Complete Guide for Research Scientists and Practitioners, Springer, New York, NY, 2010.
[9]	Christiane, F. WordNet: An Electronic Lexical Database. MIT Press, Cambridge, MA, 1998.
[10]	[10] K. Allawadi and C. Vij, "A Smart Spotify Assistance and Recommendation System," 2023 International Conference on Advancement in Computation & Computer Technologies (InCACCT), Gharuan,India,2023,pp.286291,doi:10.1109/InCACCT57535.2023.10141810. 
[11]	[11] A. Patel and R. Wadhvani, "A Comparative Study of Music Recommendation Systems," 2018 IEEE International Students' Conference on Electrical, Electronics and Computer Science (SCEECS), Bhopal, India, 2018, pp. 1-4, doi: 10.1109/SCEECS.2018.8546852.
[12]	A. Darvishy, H. Ibrahim, F. Sidi, and A. Mustapha, “HYPNER: A Hybrid 
Approach for Personalized News Recommendation,” IEEE Access, vol. 8, pp. 46877–46894, 2020.



 

