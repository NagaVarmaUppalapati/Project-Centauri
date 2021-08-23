# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       | If User enters correct password - Checking the password | Data | Success - Program continues  | Success - Program continues | Scenario based |
|  H_02       | If User enters wrong password - Checking the password | Data | Fails - Program exit  | Fails - Program exit | Scenario based |

## Table no: Low level test plan

| **Test ID** | **H ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|----------|----------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       | H_01     | Add new DVD to store | Data | Add DVD | Add DVD | Requirement based |
|  L_02       | H_01     | Delete DVD from store | Data | Delete DVD | Delete DVD | Requirement based |
|  L_03       | H-01     | Search for specific DVD |  Data | Search DVD | Search DVD | Requirement based |
|  L_04       | H_01     | View the list of DVDs |  Data | View DVD | View DVD | Requirement based |
|  L_05       | H_01     | Edit DVD specific Information | Data | Edit DVD | Edit DVD | Requirement based |
|  L_06       | H_01     | User wants to exit | Data | Exit | Exit | Requirement based |