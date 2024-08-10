# SkillStream: A Cource Recommendation System
<p>Aiming to connect you with the right courses through intelligent recommendations.</p>

<h3>Udemy Cource Recommender:</h3>
<p>SkillStream is a course recommendation system built using Udemy course data. This project demonstrates the entire process of creating a recommendation system, from data collection to model building. Here’s a simple breakdown of how it works:

<b>Data Collection:</b> we start by gathering data from Udemy, which includes various course details like titles, descriptions, and ratings.

<b>Data Preparation:</b> The raw data is cleaned and organized. We prepare the data by selecting relevant features (like course titles) that will help in making accurate recommendations.

<b>Feature Engineering:</b> To recommend similar courses, we focus on course titles. We use tokenization to break down titles into individual words or tokens.

<b>Vectorization:</b> Using TF-IDF Vectorization (Term Frequency-Inverse Document Frequency) from scikit-learn, we convert the course titles into numerical vectors. This helps in capturing the importance of each word in the context of the entire dataset.

<b>Similarity Calculation:</b> We calculate the similarity between course titles using Cosine Similarity. This measures how closely related two course titles are based on their vector representations.

<b>Recommendation Generation:</b> Based on the calculated similarities, the system can recommend courses similar to the one you're interested in.

SkillStream showcases how a recommendation system is built, demonstrating each step clearly to help you understand how data can be transformed into useful insights for course recommendations.

</p>
