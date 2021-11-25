## Introduction

The term ATM stands for automated teller machine. It is an electronic device that is used by only bank customers to process account transactions. The users access their accounts through a special type of plastic card that is encoded with user information on a magnetic strip.

## 4W's and 1'H

Who:ATM Machine's can be used by anyone with ATM card. Anyone with a credit card or debit card can access cash at ATMs.

What:Automated teller machines (ATMs) are electronic banking outlets that allow people to complete transactions without going into a branch of their bank.

When:It is a self-service outlet that you can use to withdraw money, check balance or even transfer funds. Different banks provide their ATM services by installing cash machines in different parts of the country.

Where:ATMs can be placed at any location but are most often placed near or inside banks, shopping centers/malls, airports, railway stations, metro stations, grocery stores, petrol/gas stations, restaurants, and other locations. 
An automated teller machine (ATM) is an electronic banking outlet that allows customers to complete basic transactions without the aid of a branch representative or teller. Anyone with a credit card or debit card can access cash at most ATMs.

How:This program can be executed in a system which has Linux or Windows operating system.


## SWOT ANALYSIS

Strengths: Withdraw cash at any time or in urgent without the help of bank. It ensures privacy to the customers.

Weakness: The initial amount of the application is fixed and cant be changed by user.

Opportunities: Oppertunity to serve whole world with this application.Saves time by not going to bank for transactions.

Threats: Insufficient network security.Insufficient peripheral security.Improper configuration of systems or devices.

## High Level Requirements

|**ID**|**Description**|**Category**|**Status**|
| :-: | :-: | :-: | :-: |
|HR01|User shall be able to choose one of the options|Technical|IMPLEMENTED|
|HR02|User shall be able to choose check balance amount|Technical|IMPLEMENTED|
|HR03|User shall be able to choose deposit money|Technical|IMPLEMENTED|
|HR04|User shall be able to choose withdraw money|Technical|IMPLEMENTED|
|HR05|User shall be able to exit the application|Technical|IMPLEMENTED|

## Low level Requirements

|**ID**|**Description**|**HLR ID**|**Status (Implemented/Future)**|
| :-: | :-: | :-: | :-: |
|LR01|User must choose one of the options |HR01|IMPLEMENTED|
|LR02|User can choose to check the available balance in the bank account|HR02|IMPLEMENTED|
|LR03|User can choose to deposit amount into the bank account|HR03|IMPLEMENTED|
|LR04|User can choose to withdraw amount from the bank account|HR04|IMPLEMENTED|
|LR05|The user can exit the application if he/she checked balance, deposit money or withdrawed money|HR05|IMPLEMENTED|

# TEST PLAN

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |tested to choose one of the option below| 1,2,3,4 | SUCCESS|SUCCESS|Technical |
|  H_02       |tested to check the available balance in the account| 1 |SUCCESS|SUCCESS|Technical   |
|  H_03       |tested to deposit money to the bank account| 2000| 17000 | SUCCESS |Technical |
|  H_04       |tested to withdraw money fron the bank account|5000|10000|  SUCCESS |Technical |

## Table no: Low level test plan

| **Test ID** | **HLT ID** |**Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       | H_01|Tested to choose one of the option as input| 1,2,3,4 |SUCCESS|SUCCESS |Technical |
|  L_02       | H_02|Tested on check the availabile balance in the account|  1 |SUCCESS|SUCCESS |Technical |
|  L_03       | H_03, H_04 |Tested on deposit money option and withdraw money option|  2,3  |SUCCESS|SUCCESS|Technical |


## Output Images:


