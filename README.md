# Kujenga_Project_Nesredien
Analysis of the impact of mock exam scores on national exam results.

📖 Project Overview 
This project investigates whether Mock Exam scores significantly predict National Exam results. We analyze the relationship using correlation and regression models, considering two scenarios: 
    1.	Including students with zero Mock Exam averages. 
    2.	Excluding students with zero Mock Exam averages. 

📂 Dataset – 
    •	Period: Exam cycle (1st–6th) – 
    •	Mock_Exam Average: Average score computed from number of mock exams taken by the students.
    •	Exit_Exam Result: Final score in the national exam 
    •	Pass/Fail: Derived variable (Pass if National_Result ≥ 50, Fail otherwise) 
    •	Dataset file: “Mock Exam Vs Exit Exam.csv” 

📝 Research Question & Hypothesis 
   •	Version A – Including Zero Mock Scores
      o	Research Question: Do Mock Exam scores, including cases where students did not participate (score = 0), significantly predict National Exam results? 
      o	Hypothesis: Mock Exam scores, even when some students score zero, have a significant positive impact on National Exam results. 
   •	Version B – Excluding Zero Mock Scores
      o	Research Question: Among students who took the Mock Exam, do their scores significantly predict National Exam results?
      o	Hypothesis: For students who participated in the Mock Exam, higher scores have a significant positive impact on National Exam results. 
