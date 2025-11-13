# **Mentora – AI-Powered Learning & Skill Development Platform**

This repository contains **Mentora**, my final project for the Data Science & Machine Learning Bootcamp.  
Mentora is a data-driven platform designed to help learners develop professional skills through personalized recommendations, structured skill tracking, and analytics.

---

## **Overview**

Mentora was created to explore how data, learning models, and analytics can support scalable and equitable learning experiences in organisations.

This project combines:

- **Python** for data generation, SQL execution, and validation  
- **SQL / Supabase** for database schema, security policies, and stored logic  
- **Tableau** for interactive analytics  
- **Figma** for the learner-facing prototype  

The platform models how learners progress, how content supports skill growth, and how organizations can track learning outcomes.

---

## **Core Features**

### **Learner Skill Mapping**
Tracks skills and proficiency levels for each learner.

### **Content Recommendation Logic**
Suggests learning content based on skill gaps and engagement history.

### **Engagement Tracking**
Logs learner interactions with trainings, articles, and videos to identify learning patterns.

### **Learning Analytics Dashboard**
Tableau dashboard showing:

- Skill distributions  
- Learning type usage  
- Top learners and top content  
- Content consumption trends  

### **Secure Data Architecture**
Supabase database with anonymized learner IDs and Row-Level Security enforcement.

---

## **Data Model**

Main tables:

- **learners**  
- **skills**  
- **content**  
- **learning_types**  
- **learner_skills**  
- **engagements**

A normalized relational schema connects learners, their skills, and the content they consume.

---

## **Tech Stack**

- **Python** — data generation, analysis, SQL execution  
- **SQL / Supabase** — schema design, RLS policies  
- **Tableau** — dashboards for learner analytics  
- **Figma** — UX prototype of the platform  

---

## **Project Structure**

```
Mentora_Final_Project/
├── data/
├── sql/
├── python/
├── tableau/
├── figma/
└── README.md
```

---

## **Future Improvements**

- Add a Streamlit or FastAPI interface  
- Develop a similarity-based recommendation model  
- Extend dashboards with team-level learning insights  

---

## **Author**

**Bruno Aro**  
GitHub: https://github.com/bruno-aro  
Portfolio: https://bruno-aro.github.io  
