# Netflix Recommendation System

<p align='center'>
  <a href="#"><img src="https://user-images.githubusercontent.com/96771321/214456292-ef421cff-a59f-46a1-9411-fef980ee6814.gif" width="400"></a>
</p>


### INTRODUCTION
The content-based recommender system is highly based on the similarity calculation among items. The similarity or closeness of items is measured based on the similarity in the content or features of those items. The important features used in this project are:

- DIRECTOR
- CAST
- COUNTRY
- GENRES
- TYPE

---

### IMAGES

#### System Diagram
![Netflix Recommendation System](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Netflix%20Recommendation%20System.jpg)

#### Missing Values Analysis
![Missing Values](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Missing%20Values%20Percentage%20per%20Column.png)

#### Distribution of Shows by Type
![Distribution of Shows](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Distribution%20of%20Shows%20by%20Type.png)

#### Distribution of Movies and TV Shows by Age Rating
![Age Rating Distribution](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Distribution%20of%20Movies%20and%20TV%20Shows%20by%20Age%20Rating.png)

#### Top 10 Countries with the Highest Number of Content
![Top 10 Countries](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Top%2010%20Countries%20with%20the%20Highest%20Number%20of%20Content.png)

#### Directors and Actors
- **Top Directors in All Countries**  
![Directors All Countries](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%2010%20Directors%20with%20the%20Highest%20Number%20of%20Movies%20in%20All%20Country.png)

- **Top Directors from the United States**  
![Directors US](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%2010%20Directors%20from%20the%20United%20States%20with%20the%20Highest%20Number%20of%20Movies.png)

- **Top Directors from Indonesia**  
![Directors Indonesia](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%2010%20Directors%20from%20Indonesia%20with%20the%20Highest%20Number%20of%20Movies.png)

- **Top Actors in All Countries**  
![Actors All Countries](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%20Actors%20with%20the%20Highest%20Number%20of%20Movies%20in%20All%20Country.png)

- **Top Actors from the U.S.**  
![Actors US](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%2010%20Actors%20from%20the%20U.S.%20with%20the%20Highest%20Number%20of%20Movies.png)

- **Top Actors from Indonesia**  
![Actors Indonesia](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%20Actors%20from%20Indonesia%20with%20the%20Highest%20Number%20of%20Movies.png)

---

### GENRE ANALYSIS

#### Genre Correlation Heatmap
![Genre Correlation](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Genre%20Correlation%20Heatmap.png)

#### Genre Correlation Heatmap (Non-Redundant)
![Genre Correlation Non-Redundant](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/Genre%20Correlation%20Heatmap%20(Non-redundant).png)

---

### NETWORK ANALYSIS

#### NetworkX Representation
![NetworkX Graph](https://github.com/hijirdella/Netflix-Recommendation-System/blob/b7a744c1d8318692443832029abcd25c9cd2433e/Picture/NetworkX.png)

#### Top Recommendation for Ocean's Twelve
![Top Recommendation for Ocean's Twelve](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Picture/Top%20Recommendation%20(Ocean's%20Twelve).png)

#### Top Recommendation for Stranger Things
![Top Recommendation for Stranger Things](https://github.com/hijirdella/Netflix-Recommendation-System/blob/45251caac2f04ab250427bae95cf75afa55421ba/Picture/Top%20Recommendation%20(Stranger%20Things).png)

---

### MODEL EVALUATION SUMMARY

| **Model**               | **Metric**                | **Value**               |
|--------------------------|---------------------------|-------------------------|
| **KNN**                 | Accuracy                 | 1.00                |
| **Decision Tree**        | Accuracy                 | 0.8638                 |
| **Logistic Regression**  | Accuracy                 | 0.3990                 |
| **Random Forest**        | Accuracy                 | 0.8383                 |
| **Naive Bayes**          | Davies-Bouldin Index     | 1.310                  |
| **K-Means Clustering**   | Davies-Bouldin Index     | 1.451                  |

---

### SUMMARY
- **KNN** achieved the highest accuracy (100%) and is highly effective for recommendation purposes.
- **Decision Tree** also performs well, with accuracy exceeding 86%.
- **Random Forest** offers a strong balance between precision and interpretability.
- **Logistic Regression**, while not as accurate, provides insights into feature significance.
- **Naive Bayes** and **K-Means Clustering** are evaluated using Davies-Bouldin Index, indicating good cluster separation and structure.
- Visualization of genres, actors, and directors highlights content trends and preferences by country.

---

### LINKS

- [Python Code](https://github.com/hijirdella/Netflix-Recommendation-System/blob/05b9407d022de22ca94d07bb965fed4ac9bf39a6/Netflix_Recommendation_System.ipynb)
- [LinkedIn Profile](https://www.linkedin.com/in/hijirdella/)
- Email: [hijirdw@gmail.com](mailto:hijirdw@gmail.com)
