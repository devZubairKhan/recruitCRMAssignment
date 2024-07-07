# recruitCRMAssignment

This repository contains Performance Test scripts, test data for careers module and Test execution results.

Test scenario document and test results and observations document are added in .xls format

Test scenarios are designed to execute for 15 minutes duration with a maximum load of 10 users as the application under load is a dummy application for training purpose and is unable to handle high load.

In absence of any APM tool, the analysis provided in the results and observation files is a preliminary observation. Further drill down into a detailed analysis would only be possible with a proper APM tool.

Steps to run the scripts;
1. Create assignments folder within the bin folder of the JMeter.
2. Place the .jmx files of each module in the folder along with careers_host.csv (will be used in careers modules jmeter script) file in the same location
3. Te result files with .jtl extension will be saved in the same assignments folder.

