# 533-project-group4
This package is a **recruitment system** where allows admins from companies to manage jobs and candidates and job-seekers to search and apply jobs.
## sub-package1 : system
### module1 : menu
* init : 2 companies, 2 admins and 5 jobseekers has been bulit in for testing
* signup : users input accountnumber and password to creat a account as long as other details like year of experience and specialty
* login : users input accountnumber and password which have to be matched with each other
* search_company : check the inputing company exists or not
* **start** : go to signup or login first, then for admins or jobseekers, we can here invoke all functions in their own modules
### module2 : company
* get_candidate_details : show all details of the applicants
* get_len_ap : show the total number of applicants
* sort_by_mark : Sort all candidates who were scored yet were not hired or rejected

