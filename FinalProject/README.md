# JAPAN2020

## Motivation
Social media has become a high potential platform for cybercriminals to conduct their phishing attacks. The amount of one's personal information available to the public is tremendous and could be used against you. With the help of AI, Spear-phishing messages, which used to be well-researched and tailored to each target attacks, can now be automated by cybercriminals. 

Through this project, I also wanted to demonstrate the risk of AI and how these tools could be misused against human.

## Overview
This model will produce spear phishing tweets that mimic the writing style of other tweets (rather than literature or research paper writing style) and include a keyword that match the target interest.

This project is used for educational and penetration testing purpose only.

## Project Details

### Dataset
As a few-shot attempt, I will fine-tune the pre-trained T5 model with 8 phishing messages.

### Model description
Text-to-text transfer transformer (T5) is a recently released encoder-decoder model that solvư NLP problems with a text-to-text approach. This is where text is used as both an input and an output for solving all types of tasks. This was introduced in the recent paper, *Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer* ([paper](https://arxiv.org/pdf/1910.10683.pdf)). 

The fine tuning process is done by using the Huggingface library.

### Output
A short message prompting the target to click on the attached link

### Future works:
Include profile scraping for keyword extraction
Add more ways for spear-phishing (LinkedIn, Emails, text messages,...)

## Assistance
This project was completed with a great help from the instructors and TAs at CoderSchool, especially anh Quan Tran

## References
https://towardsdatascience.com/poor-mans-gpt-3-few-shot-text-generation-with-t5-transformer-51f1b01f843e
