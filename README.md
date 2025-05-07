# Automations for Sales Opportunities

This repository contains both automations constructed to fulfill the objective of registering desired opportunities in sales. It was built using UiPath Studio, and requires usage of UiPath Orchestrator.

To execute, download .zip file and store locally. Then, use UiPath Studio to run each .xaml file, starting with <i>DownloadAndQueue.xaml</i>, to then end with <i>RegisterFormAndEmail.xaml</i>. Keep in mind: the <i>Get/Add Queue Items</i> activities require connections with Orchestrator, and the <i>Send Email</i> activity requires connection to an e-mail account.

Below are two images, each one representing a simplified flowchart explaining each step for each automation.

## 1st automation (<i>DownloadAndQueue.xaml</i>)
<img align="center" src="https://i.imgur.com/5rcI4eK.png" />

## 2nd automation (<i>RegisterFormAndEmail.xaml</i>)
<img align="center" src="https://i.imgur.com/3MVj0sx.png" />

## Video demonstration
<a href="https://vimeo.com/1082039569/a7ba8da2a8?share=copy">UiPath Live Demo of Sales Opportunities Automation - Luis Bernardo</a>
