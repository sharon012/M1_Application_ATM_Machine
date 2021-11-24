# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |tested to choose one of the option below| 1,2,3,4 | SUCCESS|SUCCESS|Technical |
|  H_02       |tested to check the avilable balance in the account| 1 |SUCCESS|SUCCESS|Technical   |
|  H_03       |tested to deposit money to the bank account| 2000| 17000 | 17000 |Technical |
|  H_04       |tested to withdraw money fron the bank account|5000|10000|Technical |


## Table no: Low level test plan

| **Test ID** | **HLT ID** |**Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       | H_01, H_02, H_03|Tested on functions which accept two matrices as input|  matrix1, matrix2, n |SUCCESS|SUCCESS |Technical |
|  L_02       | H_04, H_05, H_06|Tested on functions which accept single matrix as input|  matrix1, n |SUCCESS|SUCCESS |Technical |
|  L_03       | H_07, H_08 |Tested on function which returns an integer value|  3  |-1|-1|Technical |
