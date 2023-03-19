# UmrahPerformanceScript
Performance Test Script for umrah.eg/home Site
This repository contains the JMeter script used to perform performance testing on the umrah.eg/home website. The script sends HTTP requests to two pages on the website using ten concurrent users and is executed twice to simulate load.

Prerequisites
Apache JMeter 5.4 or later installed on your machine.
Internet connectivity to connect to the umrah.eg/home website.
Instructions
Clone this repository to your local machine using the following command:
bash
Copy code
git clone https://github.com/<your-github-username>/umrah-performance-test.git
Open JMeter and import the umrah-performance-test.jmx file located in the jmeter directory of the cloned repository.
Modify the HTTP Request samplers in the script to use the desired pages on the umrah.eg/home website.
Run the test script by clicking the "Play" button or by using the command line.
The results of the test will be displayed in JMeter's "Summary Report" and "Graph Results" listeners.
Test Details
The performance test script sends a total of 40 HTTP requests to the umrah.eg/home website using ten concurrent users. The script is executed twice to simulate load. The test duration and ramp-up time can be modified in the JMeter script as needed.

License
This project is licensed under the MIT License - see the LICENSE file for details.
