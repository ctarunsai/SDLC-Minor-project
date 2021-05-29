# Library Management System

The main objective of the proposed system is to record every transaction in computerised system so that the problem such as record file missing won’t happen.
To design a user-friendly graphical user interface (UI) which suits the user to save the cost and time.

<!-- Build | Code Quality | Unity | [Git Inspector](using github.io option)
------|----------|-------|--------------
[![C/C++ CI](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/c-cpp.yml) | [![Static Cppcheck](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/cppcheck.yml) [![Dynamic Valgrind](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/dynamic-code-quality.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/dynamic-code-quality.yml) [![Code Coverage](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/coverage.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/coverage.yml) | [![Unity - Unit Testing](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/unity.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/unity.yml) | [![Git Inspector](https://github.com/Sanchana-2k/LTTS_C_MiniProject/actions/workflows/gitinspector.yml/badge.svg)](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/b805d43e91e40f65639270e74d421be9d544b0ab/.github/workflows/gitinspector.yml) -->


## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF No. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
`15` | Tarun Chitta  | Admin Module, Dashboards, DB    | Nil     | Dashboards   | 5   | YES    
`30` | M K Chaitanya | User Module | Dashboards | User module fixes | 6 | YES
   

## Challenges Faced and How Was It Overcome

1. If the DB connection is lost in between add, update commands then the DB loses consistency -> We used Transactions of SQL in order to maintain (ACID properties)
2. New DB connections are created in between page navigation -> We are passing DB connection, cursor to next page during navigation

## Learning Resources
1. [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [markdownBasics](https://guides.github.com/features/mastering-markdown/)
3. [git inspector](https://github.com/ejwa/gitinspector.git)
4. [github workflow](https://docs.github.com/en/actions/learn-github-action)

## Credits

1. Reference requirements and architecture and test plan - [Manjari_AP](https://github.com/256152/Mini_Project_1_April_2021.git)
2. Reference for High Level Requirements and Low Level Requirements Table - [arc-arnob](https://github.com/arc-arnob/LnT_Mini_Project.git)

