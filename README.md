# student-performance-analysis
Student Performance Analysis using Python, Pandas, and Matplotlib. Includes data cleaning, exploratory data analysis, correlation analysis, and visualizations of student academic performance.

#  Titanic Dataset Analysis
### Data Science with Python Internship – Task 2 | Maincrafts Technology

---

##  Objective
Analyze the Titanic dataset to discover survival patterns based on gender, passenger class, and age group using Python.

---

##  Dataset
- **Source:** [Kaggle – Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Size:** 891 passengers × 15 columns
- **Key columns:** Survived, Pclass, Sex, Age, Fare, Embarked

---

##  Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python | Programming language |
| Pandas | Data cleaning & analysis |
| Seaborn | Data visualization |
| Matplotlib | Data visualization |
| Google Colab | Development environment |

---

##  What I Did
1. Loaded and explored the Titanic dataset
2. Cleaned missing values:
   - `Age` → filled with median
   - `Embarked` → filled with mode
   - `Deck` → dropped (77% missing)
3. Analyzed survival patterns
4. Built visualizations

---

##  Questions Answered

### Q1: Who survived more — Males or Females?
| Gender | Survival Rate |
|--------|--------------|
| Female | 74%  |
| Male | 19%  |

>  Females were nearly 4x more likely to survive due to the "women first" evacuation rule.

### Q2: Did Passenger Class affect survival?
| Class | Survival Rate |
|-------|--------------|
| 1st Class | 63%  |
| 2nd Class | 47% |
| 3rd Class | 24%  |

>  1st class cabins were closer to the lifeboats on upper decks.

### Q3: What was the survival rate by age group?
| Age Group | Survival Rate |
|-----------|--------------|
| Children (0–12) | 58%  |
| Teens (13–18) | 43% |
| Young Adults (19–35) | 35% |
| Middle-Aged (36–60) | 40% |
| Seniors (61+) | 23%  |

>  Children were prioritized during evacuation.

---

##  Visualizations
- Bar chart – Survival rate by gender
- Bar chart – Survival rate by passenger class
- Histogram – Distribution of passenger ages

---

##  Conclusion
Three factors heavily influenced survival on the Titanic:
1. **Gender** – Females survived far more than males
2. **Class** – Wealthier passengers had better access to lifeboats
3. **Age** – Younger passengers, especially children, were prioritized

---
