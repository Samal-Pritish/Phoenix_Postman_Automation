# API Automation Framework (Postman + GitHub Actions)

## Overview
This project is a demonstration of API automation framework where test cases are created and maintained in **Postman** collections. The tests are executed from the command line using **Newman**, with detailed HTML reports generated through **newman-reporter-htmlextra**. The framework is integrated with **GitHub Actions** to enable automated test execution as part of the CI/CD pipeline. 

Github Action will automatically execute the collection whenever there is a **pull_request** or **Push** event on the main branch. We can also execute the project manually using **workflow_dispatch**. The project runs on scheduled time using **cron** job.

Once execution completes a execution report will be generated, archieved and available under **artifact** section. The execution report is also deployed into **github-pages** and can be viewed under the URL:
https://samal-pritish.github.io/Phoenix_Postman_Automation/

After execution completes a mail will be triggered to different stake holders using **GMAIL SMTP**.




