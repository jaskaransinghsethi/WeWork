-------------------------------------------------------------------WeWork.com----------------------------------------------------------------------------------------------------

## Project Title: WeWork.com

WeWork is a crowdsourcing platform for individuals to find work or post a job and find workers. 
WeWork has a coin-based system which allows you to pay an individual in coins for your work, and the balance can be replenished by working for someone else.

## Getting Started

WeWork is a web application which has its front end developed using HTML, CSS, Bootstrap and Javascript. 
Server code is developed using PHP and Database is designed using MySQL, later deployed on AWS RDS. 

### Prerequisites

1. XAMPP to run server and database(Using XAMPP admin) 
2. Web browser supporting Bootstrap CSS2 or higher version.
3. A 32 bit or higher operating system.
4. XAMPP can be downloaded installed from https://www.apachefriends.org/download.html 
5. Any web browser supporting CSS2 or higher can be installed. Please note that Javascript should be enabled.

### Installing

The development environment can be set up using following steps.

1. All the PHP files should be stored inside ../xampp/htdocs/wework
2. Start XAMPP Control panel.
3. In XAMPP control panel, start Apache and MySQL.

## Running the tests

1.Once the Apache and MySQL are running, provide the URL of the first page in the browser.
  For example: for the files stored under ../xampp/htdocs/wework, provide URL as localhost/wework/index.php
2.Go to Sign up and create new user.(Two users should be created in order to demonstrate employer and employee roles).
3.Once the users are created, login as one of the user considering it to be Employer.
4.For employer follow the below mentioned steps:-
	1. Login
	2. From Home page click on "Post Job" menu item.
	3. Post a new job providing relevant and required details.
	4. Submit and logout.
5. For Employee, Login from the second user and follow the below mentioned steps:-
	1. Login and click on the apply jobs from the list of available jobs.
	2. An employee can check the list of his/her "applied jobs".
6. Once the job is completed, Empployer can log in and go to "Posted Jobs"
7. For every completed job, employer can initiate payment by first setting status to finished and then clicking on the Pay button for the desired job from the list of jobs in "Posted Jobs".
8. Clicking on "Pay" button will redirect the employer to the payment page.
9. Confirm the provided detail and submit the form to confirm the payment.
10. If the payment is successfull, the application will redirect to a landing page.
11. User can either go back to the home page or can view his/her payment history.

##Built with

1. Notepad++
2. Sublime text 3
3. XAMPP
4. VSCode
5. Google Chrome

## Versioning

Version 1.0 Alpha
Functional website with MySQL Database
Release date: 04/20/2018
Develeoped by: Team wework.com

Version 1.1
- Bugs fixed
- Queries updated
- Added new pages
Release date:04/24/2018
Develeoped by: Team wework.com
Maintenance history: N/A


Version 1.2 Beta
- AWS2.php added to connect with AWS RDS server
- Payment features added
Release date:04/24/2018
Develeoped by: Team wework.com
Maintenance history: Fixed old bugs by Akshay Jagtap

Version 2.0 Deployment
- All pages functional
- AWS working successfully
Release date:04/24/2018
Develeoped by: Team wework.com
Maintenance history: N/A

## Authors

1.Akshay Kacharaj Jagtap
2.Bo Li
3.Jaskaran Singh
4.Khushboo Gupta
5.Malhar Ujawane
6.Manushi Manish Sheth
7.Nidhi Surya Prakash
8.Sakthi Priya Rajendran
9.Vaibhav Kumar



## License

MIT License

Copyright (c) 2018 Team WeWOrk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THIS SOFTWARE IS AN ACADEMIC PROJECT AND IS NOT ASSOCIATED WITH ANY OTHER COMPANY.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

* https://www.w3schools.com/
* Coursework by Edmund Yu
-----------------------------------------------------------------------End of Read Me---------------------------------------------------------------