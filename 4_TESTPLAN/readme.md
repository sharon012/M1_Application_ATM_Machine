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
