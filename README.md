# INDIA-GENERAL-ELECTIONS-RESULT-ANALYSIS-2024
SQL PROJECT

## Project Overview
The **INDIA GENERAL ELECTIONS RESULT ANALYSIS 2024** project is a comprehensive analysis of the Indian General Election results for 2024. This project uses **SQL** to process, query, and derive insights from the election data, focusing on key trends, party performance, and voter behavior.

---

## Problem Statements
This project answers 15 key questions related to the election results:

1. **Total Seats:** What is the total number of seats available across the country?
2. **State-wise Total Seats:** What is the total number of seats available for elections in each state?
3. **NDA Total Seats:** How many seats were won by the NDA alliance?
4. **NDA Party Seats:** How many seats were won by each party in the NDA alliance?
5. **I.N.D.I.A. Total Seats:** How many seats were won by the I.N.D.I.A. alliance?
6. **I.N.D.I.A. Party Seats:** How many seats were won by each party in the I.N.D.I.A. alliance?
7. **Party Alliance Classification:** Add a new column in the `partywise_results` table to classify parties as **NDA**, **I.N.D.I.A**, or **OTHER**.
8. **Winning Alliance:** Which party alliance (NDA, I.N.D.I.A, OTHER) won the most seats across all states?
9. **Winning Candidate Details:** Retrieve the winning candidate's name, party name, total votes, and the margin of victory for a specific state and constituency.
10. **EVM vs Postal Votes:** Analyze the distribution of EVM votes vs postal votes for candidates in a specific constituency.
11. **State-wise Party Wins:** Which parties won the most seats in a state, and how many seats did each party win?
12. **Alliance-wise State Seats:** What is the total number of seats won by each alliance (NDA, I.N.D.I.A, OTHER) in each state?
13. **Top Candidates by EVM Votes:** Identify the candidates with the highest number of EVM votes in each constituency (Top 10).
14. **Winners and Runners-Up:** Identify the winner and runner-up for each constituency in a given state.
15. **Maharashtra Insights:** For the state of Maharashtra, determine the total seats, total candidates, total parties, total votes (including EVM and postal votes), and a breakdown of EVM and postal votes.

---

## Dataset Description
The project uses the following tables:

### 1. **`constituencywise_details`**
| Column Name      | Description                          |
|------------------|--------------------------------------|
| `S_No`           | Serial number of the record          |
| `Candidate`      | Name of the candidate                |
| `Party`          | Name of the candidate's party        |
| `EVM_Votes`      | Votes received through EVM           |
| `Postal_Votes`   | Votes received through postal ballots|
| `Total_Votes`    | Total votes received                 |
| `%_of_Votes`     | Percentage of votes received         |
| `Constituency_ID`| Unique ID for the constituency       |

### 2. **`statewise_results`**
| Column Name             | Description                          |
|-------------------------|--------------------------------------|
| `Constituency`          | Name of the constituency             |
| `Const_No`              | Constituency number                  |
| `Parliament_Constituency`| Name of the parliamentary constituency|
| `Leading_Candidate`     | Candidate leading in the constituency|
| `Trailing_Candidate`    | Candidate trailing in the constituency|
| `Margin`                | Vote margin between leading and trailing candidates|
| `Status`                | Status of the constituency result    |
| `State_ID`              | Unique ID of the state               |
| `State`                 | Name of the state                    |

### 3. **`constituencywise_results`**
| Column Name              | Description                          |
|--------------------------|--------------------------------------|
| `S_No`                   | Serial number of the record          |
| `Parliament_Constituency`| Name of the parliamentary constituency|
| `Constituency_Name`      | Name of the constituency             |
| `Winning_Candidate`      | Name of the winning candidate        |
| `Total_Votes`            | Total votes received in the constituency|
| `Margin`                 | Vote margin of the winning candidate |
| `Constituency_ID`        | Unique ID for the constituency       |
| `Party_ID`               | Unique ID of the winning party       |

### 4. **`partywise_results`**
| Column Name              | Description                          |
|--------------------------|--------------------------------------|
| `Party`                  | Name of the political party          |
| `Won`                    | Total seats won by the party         |
| `Party_ID`               | Unique ID of the party               |

### 5. **`states`**
| Column Name              | Description                          |
|--------------------------|--------------------------------------|
| `State_ID`               | Unique ID of the state               |
| `State`                  | Name of the state                    |

---

## Queries and Insights
The project uses a variety of SQL techniques, including:
- **Joins**: To connect data across multiple tables.
- **Aggregations**: To calculate totals, counts, and percentages.
- **Grouping**: For state-wise and alliance-wise summaries.
- **Subqueries**: To identify top candidates and winners/runners-up.
- **Table Updates**: Adding new fields for classification.

Each problem statement is addressed with detailed SQL queries in the project repository.

---

## Tech Stack
- **SQL Server**: For database management and querying.
- **SQL Queries**: Optimized for insights and performance.
- **GitHub**: To manage and share project files.

---

## Repository
Explore the complete project, including datasets and SQL queries, on GitHub:  
[**GitHub Repository**](https://github.com/prashantd2001/INDIA-GENERAL-ELECTIONS-RESULT-ANALYSIS-2024)

---

## Key Learnings
- Efficient use of SQL to analyze large datasets.
- Applying SQL techniques like joins, group by, and aggregations to derive meaningful insights.
- Understanding election dynamics and patterns through data.

---

## Contact
Feel free to connect with me on LinkedIn or share your feedback and suggestions! I look forward to hearing your thoughts. 🙌
LinkedIn Profile

