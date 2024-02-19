# build_your_copilot_hackathon
Repository with code and materials for the hackathon for developing your own copilot. 

## Introduction
Creating your own add-in/extension to Visual Studio Code is a good way of customazing a workflow for a software developer. We can develop an own code generation tool or a test tool. 

Generative AI and ChatGPT have taken software engineering with storm. They provide a lot of promises and they can help in many ways, maybe so many that we need to understand it better. We can use these models to generate test cases, we can use them to write text and we can use them to summarize text. The generally available tools like ChatGPT, Github CoPilot, GitLab CoPilot, Code Whisperer and Tabnine are already very good, but they are trained on data that is publicly available in open repositories. 

The goal of this Hackathon is to learn how to develop own extension to Visual Studio Code based on generative AI. We learn how to use publicly available models from HuggingFace as part of a software development workflow for code generation and code summarization. 

## Tasks
In this Hackathon, we learn how to integrate JavaScript/TypeScript extension framework with generative AI models. We start with a simple technology where we embed the Python code in JavaScript. If time permits, we can learn how to design a web service (and a container) to make the solution more portable and robust. 

The task can be adjusted based on the interest in the following directions:
1)	Instead of developing an add-in -> learn how to train an own model 
2)	Creating a web service (and/or) a container that can provide code completion from existing models (e.g., CodeParrot) – for this, you need to read the following chapter: https://1drv.ms/b/s!Avcq_JfcNezZhpscaH8QSnAMrjI4Rw?e=iFHfUU 

## Preparations
To get the most out of the Hackathon, you should prepare for the following: 
1.	Before the Hackathon
* Find yourself a team of 2-3 colleagues.
* Download and install Visual Studio Code (https://code.visualstudio.com).
* Read the following chapter: B19548_13.pdf
* Download the reference code for the add-in development: https://github.com/miroslawstaron/machine_learning_best_practices/tree/main/chapter_13 
  * This task requires installing node.js, so please read the chapter and install the dependencies needed
* Make sure that you can download models from HuggingFace, e.g.: https://huggingface.co/roberta-base 
3.	During the Hackathon
* Create an add-in with the CodeParrot model
  * Improve on the existing skeleton code, for example: 	
    * add a stop condition (e.g., do not generate more code than the end of the function)
    * add a skeleton code to generate test cases instead of completing the code
* Create an add-in with the model that summarizes the code, e.g. CodeT5
 * Modify the code to generate summaries for code documentation (e.g., comments)
 * Modify the code to generate summaries for pull requests based on the selected code (e.g., based on the template for your company/product/team)
* Optional: Create a web-service
 * Follow the chapter https://1drv.ms/b/s!Avcq_JfcNezZhpscaH8QSnAMrjI4Rw?e=iFHfUU
 * Modify the code available here: https://github.com/miroslawstaron/machine_learning_best_practices/tree/main/chapter_16/predictor to use the CodeBert model
3.	After the Hackathon
* Improve on the quality of the solution to make it work for your team
* Present it for your colleagues

## During the day
