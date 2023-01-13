---
hide_hero: true
layout: page
hide_hero: true
show_sidebar: false
---

# Project Guideline

The course project is one of those great opportunities in which you can apply your newly learned skills towards real-life problems.
It offers you the chance to build a Deep Learning pipeline, tune and debug a machine learning model,
and experiment with one of the world’s most successful Computer Science approaches.
It is also responsible for a significant portion of your final grade.

We strongly suggest you do the project in a team. A team can have a maximum of two members and remember we will review each member’s contribution individually.
For the project topic, there are two options, you can either define the project based on our default topics or implement your own idea.
It is OK to use your thesis as the course project but keep in mind that you still need to match up our requirements such as writing a final report,
submitting the project proposal, and reporting the progress on the corresponding milestone.

Additionally, we have to make sure your idea is feasible and also in the scope of the course.
Thus before starting to work on your project, the proposal should be approved by us.

This document will guide you through milestones as well as their evaluation policy. Please read them carefully and reach us if you have any question.

## Proposal
No matter how you came with the project idea (whether it’s towards your Master/PhD thesis or one of the pre-defined topics), we need you to complete the proposal. It shows how well you have understood the problem and how well you have explored the problem space. We’ll review the proposal and inform you whether we think the scope of the project is too narrow or too wide.

1. **Title:** A statement to briefly explain the problem/task and a solution you’re going to propose. Example: “Grammatical error corrections using an augmented sequence to sequence model”.
2. **Problem definition:** Describe what problem you are going to solve. What goal(s) you’re trying to achieve. Why do you think it is important/challenging? Explain the inputs and outputs of your system in detail. Give us an example if applicable.
3. **Dataset:** A high-quality dataset is a critical prerequisite for deep learning. Please specify the dataset you will use, also include its size and license (if you want to evaluate your model on several datasets, go ahead and list all of them). If you need any preprocessing step, please describe it. Sometimes it is necessary to collect data yourself. Explain how you are going to do that and how you plan to label the collected data (if applicable).
4. **Evaluation metric:** This is a measurement of how well your model performed its desired task. It should be a well-defined, numerical, comparable, automatic evaluation metric (for example: F1-measure or BLEU score).
5. **Baseline method:** Describe a baseline method for solving this problem. Make it clear that you will implement it yourself, or will use a previously published score. Baseline is a trivial approach. The first idea that can be thought. You suggest an algorithm that should be better than the baseline at least. For example feeding a word with its neighbors is a baseline to name entity recognition task.

Your submission is first examined in terms of an accurate description of the required fields. It will also be judged on creativity in defining the problem and the quality of your write-up.

## Progress Report
Up until this point, you should have implemented a preliminary and simple version of your idea, this implementation doesn’t have to be fully optimized at this point, and it doesn’t have to contain all the features you want yet. You must report these items:

1. **Proposed algorithm**: Describe your proposed algorithm for solving the problem in detail, use a concrete example to show how your model and algorithm work. Your description must be precise and specific (what are your model’s inputs, outputs, variables, etc.).
2. **Results**: Report the experimental results of using this basic version of implementation and compare the results with the baseline methods. Descriptions should be quantitative (using tables, metrics, plots, etc.). Explain whether you were expecting these results or not.
3. **Improvement plan**: Explain your plan for improving the results in the future (e.g. you can look for the flaws in the proposed method, try to find a way to fix them, or you can simply search for a more advanced model than what you already have). Note that you must implement these suggestions and put them to use for the final version.

## Final Report

Your final report is the most important part of your project, and it must be comprehensive, precise, and clear. It demonstrates how well you understood the problem and the changes that you might face to solve such a problem. It also conveys your understanding of the course materials. Your report should contain the following parts.

1. **Abstract:** You should give a brief introduction of your problem and the solution that you have provided
2. **Introduction:** In this part, you should explain the problem or the task you want to solve and demonstrate the challenges that you may face during solving this problem.
3. **Related work/Background:** A concise explanation of two to three recent works that had proposed an approach to overcome or solve the problem. These works might have found a solution for different settings of this problem.
4. **Proposed method:** In this section, you must provide a comprehensive explanation of your final improved method to solve this problem. Some of the things that you should describe in the report are the following items:
    - Any kind of preprocessing or normalization (if you have used).
    - The architecture of the neural network that you have used. It is better to demonstrate this with a graph.
5. **Results:** At first, you should describe the dataset that you have used, and then, you must describe the experiments that you did and its results. It is better to test your proposed method in different settings and with various parameters.
6. **Discussion:** In this section, you will discuss your proposed method to solve the problem. Some of the questions that you might find useful to answer are:
Why is this specific type of Deep Neural Networks suitable for this task?
What are the benefits of your proposed model against other approaches?
7. **References:** You must cite all of the papers and codes that you have used in your project.

You will not be penalized if your system performs poorly, if you analyze the model output and explain why it failed which is much more important to us. Your report will be graded based on its quality. By quality, we mean how well you explained, expanded, and conveyed your problem and its challenges; how well you could persuade usage of a specific model for solving a particular task, your results and implementation, your writing quality, and your understanding of the problem and Deep Learning tools.

To have an estimate of how much and how well you should write this report please look at the [here](https://teias-courses.github.io/nlp99/projects).

**Note:** If you have used any paper or code in your project you must cite that paper/code, and you also must clarify your contribution to the code/paper.

### Template 

You should use [ACL* template](https://github.com/acl-org/acl-style-files) for your final report. You can use [Overleaf](https://www.overleaf.com/latex/templates/acl-2020-proceedings-template/zsrkcwjptpcd) to use this template and write your report.


## Presentation
