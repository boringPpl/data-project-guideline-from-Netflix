# Project guideline: How to approach a data science project the "Netflix" way?

> "Data science is such a nebulous term. To some, it means data analytics; to some it is synonymous to machine learning; others think there is a data engineering flavor to it. The wide spectrum of possible responsibilities and the nuanced differences across companies or even teams within the same company make the identity evasive. You literally have to speak to a data scientist in company X to understand how company X sees data science. This guidline is inspired by a Netflix talk with a focus on the structure of a data science projects."
> 
> Credit goes to Boringppl contributor - Hui Zhu from her article ["Curious About How To Be A Data Scientist? Hear From A Netflix Data Scientist"](https://towardsdatascience.com/a-peek-into-a-netflix-data-scientists-day-66bf3dacabb9)

## Preparation
- Bounce ideas, vote
- Confirm the time frame to complete the projects 
- Break down into milestones and objectives
- Gather resources

## Execution
### Step 1: Start with understanding the business questions:
- [ ] What is the business need?
- [ ] What are we trying to do/ measure/ predict?
- [ ] Who will be using this prediction or model?
- [ ] What is a good proof of concept?
- [ ] What is our metric of success?
- [ ] Who is responsible for validation?
- [ ] What is the time frame?
- [ ] What other teams are involved?

### Step 2: Make a technical plan
- [ ] What data do we have available? How clean is it?
- [ ] What techniques have others used to solve problems like this?
- [ ] What tools should we use to do the data engineering, modeling, and productionalization?
- [ ] What error metric are we optimizing?
- [ ] If there are several possible techniques, which are the most promising

### Step 3: Create a proof of concept 
> - Iterate/validate until you succeed or decide it can’t be done
> - Communicate results back to stakeholders

- [ ] Create a proof of concept/ iterate/ validate:
    - SQL to get/ manipulate data (provided in clean, usable tables by data engineers)
    - Prototyping typically done in Juputer Notebook (Python) with standard ML packages
        - Scikit learn
        - XGBoost
        - Keras
        - Pandas
    - Early results often passed back and forth with stakeholders vis spreadsheets and documents
    - Debuggings/ modeling suggestions from discussions and presentations to other data scientists
    - Early visualization is not fancy: Plots in Python or a basic Tableau dashboard
        - Matplotlib
        - Seaborn

### Step 4: Productionalize the model
### Step 5: Communication and problem solving