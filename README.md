This open source project serves two purposes.

1. Collection and evaluation of a Question Answering dataset to improve existing QA/search methods - **COVID-QA**
2. Question matching capabilities: Provide trustworthy answers to questions about COVID-19 via NLP - **outdated**

# FAQ matching

**Update 17th June, 2020**: As the pandemic is thankfully slowing down and other information sources have catched up, we decided to take our hosted API and UI offline. We will keep the repository here as an inspiration for other projects and to share the COVID-QA dataset.

### :zap: Problem

- People have many questions about COVID-19
- Answers are scattered on different websites
- Finding the right answers takes a lot of time
- Trustworthiness of answers is hard to judge
- Many answers get outdated soon

### :bulb: Idea

- Aggregate FAQs and texts from trustworthy data sources (WHO, CDC ...)
- Provide a UI where people can ask questions
- Use NLP to match incoming questions of users with meaningful answers
- Users can provide feedback about answers to improve the NLP model and flag outdated or wrong answers
- Display most common queries without good answers to guide data collection and model improvements
