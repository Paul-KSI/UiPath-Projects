# UiPath Projects Repository

Welcome to the **UiPath Projects Repository**! This repository contains a wide range of automation projects built using **UiPath Studio**, showcasing various use cases such as **web scraping**, **email automation**, **invoice processing**, **sentiment analysis**, and much more. These projects are designed to demonstrate the capabilities of UiPath and help you get hands-on experience with different automation workflows.

This repository is organized in a way that allows you to easily access and explore each project. Each project contains its own set of workflows, configurations, and dependencies, and most projects are accompanied by a folder containing the necessary files to run them.

### **Important Note:**
- This repository **will not be updated** in the future. The current contents reflect the full set of experiments available for download and usage.

---

## Project Structure

The repository is organized into different folders, each representing a specific UiPath automation project. Here's how it is structured:

### **Folder Breakdown:**

1. **Project Folders**: Each project folder contains the relevant **.xaml** workflow files, along with configuration files (like `project.json`) and required dependencies (like **.dll** or **.nupkg** files).
   
2. **Auxiliary Files**: Most of the projects use external files (like Excel files, PDFs, or datasets). These are stored in the `Auxiliary_Files` folder within each project directory. The data files are referenced using **relative paths**, so the projects should work seamlessly when the folder structure is maintained.

3. **Zip Files**: All the projects are available in compressed formats within the [**`Zip Files`**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/Zip%20Files) folder. This allows you to quickly download any individual project or even the entire collection of projects.

4. **Download All Experiments**: There is a compressed file available that contains all the experiments in a single file for quick access. This can be downloaded in multiple formats (e.g., `.zip`, `.rar`, `.tar`, `.7z`).

---

## Execution Instructions

To run any of the projects, follow these steps:

1. **Open UiPath Studio**:
   - If you don't have UiPath Studio installed, you can download and install it from the official UiPath website.
   
2. **Select Your Project**:
   - Navigate to the project folder you wish to run. For example, if you want to run the **BMI Automation** project, go to the folder `BMI Automation`.
   
3. **Load the Project**:
   - Inside the folder, locate the **`project.json`** file.
   - Open UiPath Studio and choose **File > Open**.
   - Locate and select the `project.json` file to load the automation project into UiPath Studio.

4. **Run the Workflow**:
   - Once the project is loaded in UiPath Studio, you can click **Run** to start executing the workflow.

5. **Troubleshooting**:
   - If you encounter errors, make sure all dependencies are installed, and the paths to the **Auxiliary_Files** folder are correctly referenced.

---

## Projects Overview

The following is a list of all the projects available in this repository, along with descriptions of each project. You can click on each project name to access the project folder directly.

| Project Name | Description | Download Link |
|--------------|-------------|---------------|
| [**AssetsINorchestrator**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/AssetsINorchestrator) | A simple trial project that demonstrates how to use assets in UiPath Orchestrator. This project shows how to store and retrieve configuration data during automation workflows. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/AssetsINorchestrator.zip) |
| [**AttendedAutomationTrigger1**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/AttendedAutomationTrigger1) | A sample automation project using an attended trigger. Based on UiPath's templates, this project shows how attended processes work. Outputs include playful text files like "Done something instead of nothing." | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/AttendedAutomationTrigger1.zip) |
| [**AttendedAutomationTrigger2**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/AttendedAutomationTrigger2) | A variation of AttendedAutomationTrigger1 with added enhancements. Outputs include messages such as "If you don't know anything, at least learn from the one who is going ahead." | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/AttendedAutomationTrigger2.zip) |
| [**BMI Automation**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/BMI%20Automation) | Automates the calculation of Body Mass Index (BMI). This project uses Excel and a BMI web page, alongside UiPath's recording features. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/BMI%20Automation.zip) |
| [**DynamicWebScrapingAJAX**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/DynamicWebScrapingAJAX) | Web scraping of YouTube Shorts metadata, including name, likes, views, and upload date. Includes auto-scrolling to capture more data. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/DynamicWebScrapingAJAX.zip) |
| [**EcommerceWebscraping**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/EcommerceWebscraping) | Scrapes product data from a dummy e-commerce website, demonstrating basic web scraping techniques. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/EcommerceWebscraping.zip) |
| [**ExceptionalHandling**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/ExceptionalHandling) | Demonstrates best practices for exception handling in UiPath. This project showcases how to handle errors gracefully to ensure smooth workflow execution. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/ExceptionalHandling.zip) |
| [**GmailAutomation**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/GmailAutomation) | Automates Gmail interactions including generating email bodies using LLM, sending emails, logging unread emails, reading specific emails, and downloading email attachments. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/GmailAutomation.zip) |
| [**InvoiceAutomation**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/InvoiceAutomation) | Automates the extraction and validation of invoice data. Scrapes invoice dates, checks for inconsistencies, and sends an email to the respective auditor if an error is found. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/InvoiceAutomation.zip) |
| [**QueuesInOrchestrator**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/QueuesInOrchestrator) | A simple trial project using queues in UiPath Orchestrator. Demonstrates managing automation tasks using Orchestrator's queue functionality. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/QueuesInOrchestrator.zip) |
| [**SentimentalAnalysisDocumentUnderstanding**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/SentimentalAnalysisDocumentUnderstanding) | Analyzes shopping product reviews using sentiment analysis. Scrapes reviews, creates a dataset, and labels them based on sentiment (positive/negative). | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/SentimentalAnalysisDocumentUnderstanding.zip) |
| [**SimpleWorkflow**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/SimpleWorkflow) | A simple demonstration of basic UiPath functionalities. This project serves as a starting point for new users to get familiar with UiPath Studio. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/SimpleWorkflow.zip) |
| [**feeConcessionBot**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/feeConcessionBot) | Automates the fee concession process for educational institutions using Excel and if-else conditions. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/feeConcessionBot.zip) |
| [**pdf Automation**](https://github.com/Paul-KSI/UiPath-Projects/tree/main/pdf%20Automation) | Automates handling of PDF documents. Scrapes data from invoices and sales reports, and merges multiple PDFs into a single file. | [Download](https://github.com/Paul-KSI/UiPath-Projects/raw/main/Zip%20Files/pdf%20Automation.zip) |

---

## Download All Experiments

For those who want to download all the projects at once, you can choose the compressed file in your preferred format from the options below:

- [**All_experiment.zip**](https://github.com/Paul-KSI/UiPath-Projects/raw/main/All_experiment.zip)
- [**All_experiment.rar**](https://github.com/Paul-KSI/UiPath-Projects/raw/main/All_experiment.rar)
- [**All_experiment.7z**](https://github.com/Paul-KSI/UiPath-Projects/raw/main/All_experiment.7z)
- [**All_experiment.tar**](https://github.com/Paul-KSI/UiPath-Projects/raw/main/All_experiment.tar)

Click any of the links above to start downloading the full set of experiments.

---

## Contributing

We welcome contributions! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

---

## License

This repository is available under the **MIT License**. You can freely use, modify, and distribute the code in this repository for personal and commercial purposes.

---

Feel free to reach out if you need help, have questions, or would like to share your feedback. Happy automating with UiPath!

