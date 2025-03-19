🎥 Movie Recommendation System

### COMPANY: **CODTECH IT SOLUTIONS**  
### NAME: **P. Nitish**  
### Intern ID: **CT08UJT**  
### DOMAIN: **JAVA**  
### DURATION: **4 WEEKS**  
### MENTOR: **NEELA SANTOSH**  

---

## 📚 Project Overview
The **Movie Recommendation System** processes user-item interaction data (such as movie ratings) to recommend movies to users. The system leverages:

- ✅ **Item-based Collaborative Filtering:** Suggests items based on similarities between movies.  
- ✅ **Tanimoto Coefficient Similarity:** Used to calculate similarity between items.  
- ✅ **Movie Title Mapping:** Maps movie IDs to titles for better result interpretation.

---

## 🛠️ Technologies Used
- **Apache Mahout:** Collaborative filtering framework.  
- **Java:** Primary language for implementation.  
- **CSV:** Stores movie data (ratings and information).

---

## 🚀 Setup Instructions

### 1. Clone the Repository
To get started, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/movierecommendator.git
cd movierecommendator
```

---

### 2. Add Required Libraries

Download and place the necessary `.jar` files into the `lib/` directory:

- **Apache Mahout Core**  
- **Guava**  
- **SLF4J**  

Make sure the following JAR files are present in the `lib/` folder:

```
/lib
├── commons-math3-3.2.jar
├── guava-15.0.jar
├── mahout-core-0.8.jar
├── mahout-integration-0.8.jar
├── mahout-math-0.8.jar
├── slf4j-api-1.7.5.jar
└── slf4j-nop-1.7.5.jar
```

---

### 3. Compile the Project
Navigate to the project root and compile the Java files:

```bash
javac -cp "lib/*" -d bin src/com/predictionmarketing/convert/MovieDataConvert.java src/com/predictionmarketing/itemrecommend/ItemRecommend.java
```

✅ Compiled `.class` files will be placed in the `bin/` directory.

---

### 4. Run the Data Conversion
Run the `MovieDataConvert` class to convert the dataset (`u.data`) into CSV format (`movies.csv`):

```bash
java -cp "bin;lib/*" com.predictionmarketing.convert.MovieDataConvert
```

---

### 5. Run the Recommendation Engine
After data conversion, run the recommendation engine to generate recommendations:

```bash
java -cp "bin;lib/*" com.predictionmarketing.itemrecommend.ItemRecommend
```

---

## 📊 Output

The system will generate movie recommendations with similarity scores and display them in the terminal.

---

## 📸 Sample Output

```
Recommended Movies for User 1:
1. The Matrix (1999) - Similarity: 0.92
2. Pulp Fiction (1994) - Similarity: 0.89
3. Fight Club (1999) - Similarity: 0.87
```

---

🎉 **Enjoy building your Movie Recommendation System!** 🎉

---
