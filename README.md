\# HR Employee Onboarding Automation



\## Overview

This project automates the employee onboarding process using UiPath. 

The automation processes employee data and performs onboarding tasks automatically.



\## Technology

\- UiPath Studio

\- REFramework

\- Excel integration

\- Queue processing



\## Project Structure

Main.xaml – Entry point of the automation.



Framework – Contains REFramework workflows:

\- InitAllSettings.xaml

\- GetTransactionData.xaml

\- Process.xaml



Data – Contains configuration files such as Config.xlsx.



\## Automation Flow

1\. Read configuration from Excel.

2\. Initialize required applications.

3\. Retrieve employee onboarding data.

4\. Process employee onboarding tasks.

5\. Update transaction status.



\## Exception Handling

The automation uses the REFramework for:

\- Business exceptions

\- System exceptions

\- Retry mechanisms





\## Architecture



This automation uses UiPath REFramework.



States in the workflow:



Initialization

Loads configuration and prepares applications.



Get Transaction Data

Retrieves employee onboarding data.



Process Transaction

Processes each employee onboarding record.



End Process

Closes applications and ends the process.



\## Author

Amma Somuah-Ansong



