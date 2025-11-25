# **DS200 – Lab 2**  
<p align="center" style="background-color: white; padding: 10px;">
  <a href="https://www.uit.edu.vn" target="_blank">
    <img src="media/uit.png" alt="VNUHCM - UIT Logo" style="background-color: white;">
  </a>
</p>

### **Lecture:** Nguyen Hieu Nghia  
### **Student:** Nguyen Vo Tien Loc – 22520792  

---

## **Overview**

Lab 2 of DS200 focuses on providing hands-on experience with **Apache Spark**, especially working with **Resilient Distributed Datasets (RDDs)** and using **PySpark** for large-scale distributed data processing. This lab aims to deepen students' understanding of how Spark executes computations in parallel, how RDD transformations and actions operate, and how to write effective Spark programs for manipulating, analyzing, and transforming data efficiently.

## **Questions list**
Question 1: Calculate the Average Rating and Total Number of Ratings for Each Movie

Question 2: Analyze Ratings by Genre

Question 3: Analyze Ratings by Gender

Question 4: Analyze Ratings by Age Group

Question 5: Analyze Ratings by Occupation of Users

Question 6: Analyze Ratings by Time

## **Guidance**

This github repository can be read by branch. Branch name bai1, bai2, bai3, bai4, bai5, bai6 stand for 6 questions in the lab. For each branch I setup Question*.ipynb for the solution.
```
git clone https://github.com/iseT1enLoc/LAB2_BIGDATA.git
```

Create virtual environment
```
python -m venv .venv
```

Enter the virtual environment:
```
source .venv/bin/activate
```

Install required package
```
pip install -r requirements.txt
```

If check the lab in local, please checkout to coresponding branch for verification:
```
// Branch name: bai1, bai2, bai3, bai4, bai5, bai6
git checkout bai1
```
## **Dataset**
Please adding data folder by contacting me via email locnvt.it@gmail.com.
Expected folder structure for each branch:

# Folder structure:
```
LAB2_BIGDATA/
├── .gitignore
├── .venv/
├── data/ #data files is store here
├── Question*.ipynb
├── readme.md
├── requirements.txt
```


Overall, Lab 2 strengthens students’ understanding of **distributed data processing** with Spark. Through practical exercises, students gain hands-on skills in:

- Creating and managing RDDs  
- Applying transformations and actions  
- Understanding Spark’s execution pipeline  
- Writing efficient PySpark programs  

This lab builds a strong foundation for upcoming topics such as **DataFrames**, **Spark SQL**, and **machine learning pipelines**, preparing students for more advanced data engineering and analytics tasks.