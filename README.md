## Project Title: Analysis of Coursera Courses Dataset

---

### **Project Description**
This project involved analyzing a dataset scraped from the Coursera platform to explore various patterns and trends in online learning. The dataset consisted of 890 records across six features: `course_title`, `course_organization`, `course_certificate_type`, `course_rating`, `course_difficulty`, and `course_students_enrolled`. This analysis aimed to uncover insights into course popularity, enrollment patterns, course difficulty, ratings, and other features associated with online learning trends.

### **Objective**
The main objectives of the project were:
1. To understand the popularity of courses across different organizations and topics on Coursera.
2. To examine the relationship between course difficulty levels, certifications offered, and enrollment trends.
3. To analyze enrollment data and course ratings to gauge student preferences.

### **Methodology**
1. **Data Cleaning**: Verified data types, checked for missing values, and ensured data consistency.
2. **Descriptive Analysis**: Used summary statistics to understand the distribution of `course_rating` and `course_students_enrolled`.
3. **Exploratory Data Analysis (EDA)**: Created visualizations to explore the dataset’s categorical and numerical variables.
4. **Trend Analysis**: Investigated trends in course enrollments, certificate types, difficulty levels, and ratings.

### **Tools & Technologies**
- **Python**: Primary programming language for data manipulation and analysis.
- **Pandas**: For data cleaning, transformation, and basic statistical analysis.
- **Matplotlib and Seaborn**: For data visualization to explore and communicate insights.
- **Jupyter Notebook**: For coding, documentation, and visual output.

### **Insights**
1. **Popularity by Organization**: Certain universities, such as the University of Michigan and the University of Pennsylvania, dominated course offerings on Coursera.
2. **Enrollment Patterns by Course Difficulty**: Beginner-level courses were the most popular, followed by mixed-level courses, indicating a preference among users for introductory and flexible learning paths.
3. **Certificate Type Trends**: Standard "Course" certificates accounted for the majority of enrollments, with over 50 million students enrolled, followed by “Specializations.”
4. **Ratings vs. Enrollments**: Courses with high enrollments generally had high ratings, suggesting that course popularity could be tied to user satisfaction.

### **Challenges & Solutions**
1. **Challenge**: Handling an imbalanced dataset in terms of enrollment distributions.
   - **Solution**: Used logarithmic scaling for visualizations involving enrollment counts, ensuring readability and comparability.
   
2. **Challenge**: Identifying meaningful insights from sparse categories, such as “Professional Certificate” types, which had fewer courses.
   - **Solution**: Focused on aggregated views rather than individual data points to analyze trends within each certificate type.

### **Recommendations**
1. **Curated Learning Paths**: Coursera could create curated paths, integrating beginner and intermediate levels to improve student retention and progression.
2. **Expand Professional Certificates**: The interest in "Professional Certificates" suggests potential for expansion, especially in high-demand fields.
3. **Optimize High-Rated Courses for Marketing**: Highly rated and popular courses can be highlighted in marketing to attract more enrollments.

---
Note: I have also attached the .ipynb file to this repository. You can also check the full jupyter notebook report [here](https://github.com/bayoxx/learning_management_system/blob/main/coursera__task.pdf)
