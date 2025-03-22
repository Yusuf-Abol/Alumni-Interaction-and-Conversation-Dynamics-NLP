
# Alumni Interaction and Conversation Dynamics

## **Overview**  
This Natural Language Processing (NLP) project took a dive into chat engagement dynamics within the University of Ilorin’s Class of 2018 Statistics alumni group. By applying Latent Dirichlet Allocation (LDA) for topic modeling and network analysis, I uncovered communication patterns, topic distributions, and member interactions.


## **Dataset**  
The dataset was sourced from 'Certified Statistician' WhatsApp group consisting of **3,091 messages** with the following breakdown:  
- **Average message length**: 28.14 characters  
- **Media messages**: 343  
- **Emojis used**: 1,040  
- **Links shared**: 33

## **Challenges**
          
   - **Privacy and Ethical Considerations.** Analyzing WhatsApp conversations involves accessing potentially sensitive personal data. To address this, I ensure the anonymization of alumni phone numbers and any other identifying details, safeguarding privacy while maintaining ethical standards throughout the analysis process.

   - **Informal Language.** WhatsApp conversations often include slang, emojis, and informal language, which can complicate sentiment analysis.

   - **Data Noise.** WhatsApp conversations contain excessive noise, such as irrelevant content, off-topic discussions, or incomplete sentences, which can complicate the sentiment analysis process. Cleaning the data and filtering out irrelevant content is essential to obtaining meaningful insights.

## **Methodology**  
1. **Data Preprocessing**  
   - Cleaning and structuring raw chat data  
   - Tokenization and stopword removal  
   - Feature extraction (e.g., message types, emoji counts, link frequency)  

2. **Topic Modeling (LDA)**  
   - Optimized hyperparameters using Bayesian optimization  
   - Extracted key discussion themes  
   - Identified dominant topics and unique conversation threads  

3. **Network Analysis**  
   - Mapped participant interactions  
   - Identified highly active members and community structure  
   - Analyzed engagement levels and isolated nodes

---

## **Key Findings**  
- The conversation is predominantly **faith-based**, with topics such as *Blessings & Devotion*, *Religious Messages*, and *Encouragement & Celebration*.  
- **Topic 4** stands out as a distinct cluster, representing *birthday celebrations, well-wishing, and encouragement messages*.  
- The **most active participants**, `@STA14_1` and `@STA14_6`, form the core of the network, with `@STA14_1` having the highest connectivity.  
- Several participants exhibit minimal engagement, with messages that are either **occasional replies or isolated posts**.  

## **Technologies Used**  
- **Python** (for data preprocessing, LDA, and network analysis)  
- **Gensim** (for topic modeling)  
- **NetworkX** (for social network analysis)  
- **Matplotlib, Seaborn, Plotly Express, and pyLDAvis** (for data visualization)  

## **Future Work**  
- Expanding the dataset to capture **long-term engagement trends**  
- Applying **sentiment analysis** to understand emotional tones within topics  
- Investigating **time-based engagement patterns**  

## **Contributors**  
- **Yusuf Abolarinwa** – Research & Analysis  

## **License**  
This project is licensed under the **MIT License**.  
