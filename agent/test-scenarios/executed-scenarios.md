# Scenarios

## Scenario 1 | First iteration

### Step 1
**When** "I select the default option" "I want to choose a domain from certification"

**Then** "the assistent returns the 5 exam domains"

### Step 2
**When** "I choose a specific domain"

**Then** "It asks by a question type"

**When** "I choose a specific question type"
**Then** "It creates a question with right domain and question type"

### Step 3
**When** "I answer the question"

**Then** "It review my answer and give an explanation about the correct and incorrect options and give me the options for the next iteration"


## Scenario 2 | Second iteration

### Step 1
**When** "select option '1. Continue with another question of the same type'"

**Then** "It creates a question in the same domain but with different type from the previous user choice"

## Scenario 3 | Third iteration

### Step 1
**When** "select option '1. Continue with another question of the same type'"

**Then** "It creates a question in the same domain and stays with scenario 2 question type (it is different from that the user previously select but remain the same from scenario 2)"

## Scenario 4 | Fourth iteration
### Step 1
**When** "select option '1. Continue with another question of the same type'"

**Then** "It creates a question in the same domain and change the question type again"

## Scenario 5 | Fifth iteration
### Step 1
**When** "select option '1. Continue with another question of the same type'"

**Then** "It creates a question in the same domain and remain the question type again from fourth iteration"

## Scenario 6 | Sixth iteration
### Step 1
**When** "select option '1. Continue with another question of the same type'"

**Then** "It creates a question in the same domain and remain the question type again from fourth iteration"




## Scenario 5 | Changing the domain after a question
### Step 1
**When** "select option '3. Change the domain topic'"

**Then** "It list the domain options. The user select an option and next list the question types options to use select". **Note:** It is not updating the `QUESTION_DOMAIN` variable  


### Step 2
**When** "the user select a question type". **Note:** It is updating the `QUESTION_TYPE` variable successfully.  

**Then** "It creates a question in the wrong domain and right question type"





## Scenario 6 | Changing the domain after a question
### Step 1
**When** "select option '3. Change the domain topic'"

**Then** "It list the domain options. The user select an option and create a new question". **Note:** It is not updating the `QUESTION_DOMAIN` variable and update `QUESTION_TYPE` variable with the value selected for `QUESTION_DOMAIN`.





## Scenario 7 | When I ask a specific task statement, without passing in domain and questions menu, the assistent didn't save the right variables


## Scenario 8 | When I select a different type of question in the menu after a question, at third select the assistent is loosing the domain selected before.