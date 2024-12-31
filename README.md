# INDIAN-GENERAL-ELECTION-2024-DATA-ANALYSIS-PROJECT
# ![image](https://github.com/user-attachments/assets/b9b8a641-4372-490d-89fa-8022adbb2a14)
# Overview: - 
This project involves an in-depth analysis of the 2024 India General Elections results using MSSQL and Excel. 
The aim is to extract insights about election results across different constituencies and states. 
The project addresses key business questions such as the distribution of seats won by political alliances, vote margins, and the performance of political parties.

# ER Diagram: -
# Objective: - 

•	Analyse the seats won by political alliances (NDA, I.N.D.I.A, OTHER).

•	Identify the top candidates based on EVM votes and the closest races.

•	Study content distribution based on geographic and demographic factors. 

•	Analyse party-wise and state-wise election outcomes.

## Business Problems and Solutions
--Total Seats


![image](https://github.com/user-attachments/assets/5335c307-71ab-415c-833f-ed2867c5f7dc)


Output


![image](https://github.com/user-attachments/assets/7f962036-f760-487a-bc5a-5c56b51c848f)


--What is the total number of seats available for elections in each state? 


![image](https://github.com/user-attachments/assets/676c82fd-d2bc-4b29-ae5a-36c86f8fb744)


 
Output

![image](https://github.com/user-attachments/assets/d36dba5f-f525-413b-9311-a478bfd988e3)


--Total Seats Won by NDA Alliance


![image](https://github.com/user-attachments/assets/004ed8ae-d96a-403c-9bb6-1940aa7d498d)

 
Output


![image](https://github.com/user-attachments/assets/b2a48ff4-4123-40a9-89cc-06d37d585202)

 

--Seats won by NDA Allience Parties


![image](https://github.com/user-attachments/assets/42faa46f-ad3f-4139-81e5-0798ee498357)


 
Output


![image](https://github.com/user-attachments/assets/db19e3ec-ef0b-46b0-8b6e-d9a26a31f82d)

 
--Total Seats Won by I.N.D.I.A. Allianz
India National Development Inclusive Allience (I.N.D.I.A.)


![image](https://github.com/user-attachments/assets/ef2cd4ca-2aac-45ed-a8c6-156659a3481f)


 
Output


![image](https://github.com/user-attachments/assets/362e50bc-a903-46c7-a7c4-e1f0567bd728)

 

-- Seats Won by I.N.D.I.A. Allianz Parties

 


![image](https://github.com/user-attachments/assets/ff5f597b-037a-40d1-874e-ae83a53db187)





Output

![image](https://github.com/user-attachments/assets/692e4971-1581-475c-8273-83cfa5910dc6)




--Add new column field in table partywise_results
--to get the Party Allianz as NDA, I.N.D.I.A and OTHER


![image](https://github.com/user-attachments/assets/b84b0d48-6d8f-423a-9218-681505440920)






-- For India Allianz


![image](https://github.com/user-attachments/assets/ac5be277-feb2-4d82-bea2-0d90d20bc9ad)


 
-- For NDA Allience


 ![image](https://github.com/user-attachments/assets/f8b68d02-d95b-4901-9d07-14c9a8a22e01)



-- For Others

 

![image](https://github.com/user-attachments/assets/2fd9c213-89a0-45af-a252-e3380bb3fda7)



-- Which party alliance 
-- (NDA, I.N.D.I.A, or OTHER) won the most seats across all states?


![image](https://github.com/user-attachments/assets/028de5a0-9d19-40ba-bf85-a70cd38cd3d0)


Output


 ![image](https://github.com/user-attachments/assets/a7005997-cac8-4793-a4a2-032f2a84ea50)



-- Winning candidate's name, their party name, total votes, 
-- and the margin of victory for a specific state and constituency?


![image](https://github.com/user-attachments/assets/acd60b06-d1bc-4718-a1f0-776a852ec8e9)


 
Output


![image](https://github.com/user-attachments/assets/0ef64dad-ef15-4f12-ac69-3dbcb1a218f8)

 
-- What is the distribution of EVM 
-- votes versus postal votes for candidates in a specific constituency?


![image](https://github.com/user-attachments/assets/3d79df66-7850-4cfe-8ff0-39c2850ffa02)

 
Output

![image](https://github.com/user-attachments/assets/7b4f3def-526a-4b8c-9094-03603dd3ba6c)

 

-- Which parties won the most seats in s State, 
-- and how many seats did each party win?


 ![image](https://github.com/user-attachments/assets/ff3734f4-9b22-4d56-aa3f-e84c7276225c)







Output

![image](https://github.com/user-attachments/assets/c11acc46-d9a1-43c5-9389-25862ecef472)



 

-- What is the total number of seats won by each party alliance (NDA, I.N.D.I.A, and OTHER) in each state for the India Elections 2024

 
![image](https://github.com/user-attachments/assets/43c7bed7-df62-4ba4-8d8d-423b17011219)



Output- 



![image](https://github.com/user-attachments/assets/567260c8-08e3-4a0c-8487-000a8e7ffa11)


 

-- Which candidate received the highest number of 
-- EVM votes in each constituency (Top 10)?


![image](https://github.com/user-attachments/assets/391e3ae1-8396-43bb-ba0f-69129f37bbcb)

 

Output-


![image](https://github.com/user-attachments/assets/0900581c-c374-4c9a-af04-b4cb45ad5e64)

 

-- Which candidate won and which candidate was 
-- the runner-up in each constituency of State for the 2024 elections?



![image](https://github.com/user-attachments/assets/2c42c169-549e-434d-b3fb-dfbd07d542ff)

 

Output:- 


![image](https://github.com/user-attachments/assets/6d5bcfc3-7da5-47dc-8154-b2af1a051f6b)

 



-- For the state of Maharashtra, 
-- what are the total number of seats, total number of candidates, 
-- total number of parties, total votes 
-- (including EVM and postal), and the breakdown of EVM and postal votes?



![image](https://github.com/user-attachments/assets/2e3d5c03-fa25-40f4-a4d7-8d16a4e27146)

 


Output:- 


![image](https://github.com/user-attachments/assets/405f8962-6f15-4126-a0dd-133766c949c1)





# Conclusion

This analysis offers an in-depth examination of the 2024 India General Elections, shedding light on political alliances, candidate performance, and regional voting patterns. Leveraging SQL-based techniques provides valuable insights for policymakers, political analysts, and researchers to better understand the intricate dynamics of Indian politics and electoral behaviors. Furthermore, it lays a foundation for forecasting future trends with improved accuracy.

 


