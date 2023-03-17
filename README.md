# car_damage_detector_case_study
You are working as an ML engineer for an e-commerce company Carsdepo.com, which provides an online marketplace for the purchase and sale of used/new cars.

The company was founded in 2016 as an online platform to buy and sell used/new cars. The company offers end-to-end transactions, where it provides a smooth transition of ownership from the sellers to the buyers at the best rates. It sells more than 1 million cars worldwide annually and is considered one of the top three companies in the Asian market. 

While expanding operations internationally into several countries, it noticed that the market for used cars trumps over the new cars. However, this is a complicated problem to solve, as buyers want to be assured of the money they invest while buying. 

 

When a used car is listed, its worth must be effectively determined based on various features. A car can suffer from different types of damages, impacting its original shape and form, and this heavily impacts its resale value.
Therefore, when a used car is bought or sold, its actual market value must be known. Also, It is often impossible to manually inspect every part of a car, as this can be quite labour intensive.

In light of this, the company wants to build an automated damage-detection system that can detect any type of damage in cars. This solution can help determine the true resale value of a car. Based on what you learnt in the previous modules, you must understand the root problem that the company is trying to solve and build an ML system that provides an effective solution.

 

 

Let’s take a look at the problem statement:
The company wants to provide an effective pricing strategy for any listing of used cars. Earlier, this problem was solved by a manual inspection conducted by a representative, who would inspect every feature of a used car. This solution was effective, as the representative considered every factor affecting the resale value (especially the damage); however, this solution is not scalable, as the company is growing.

 

Using the millions of images of used cars the company has collected over the years, you must build an object-detection model that can detect the presence of any damage in cars. 

Among the various types of damage, the model should be able to detect two: scratches and dents. It should return “None” if no damage is detected. The product team will use these results to map the resale value of a car based on the type of damage detected.

![image](https://user-images.githubusercontent.com/43085686/225815282-5ec0ad72-693d-4c0e-9710-b6029a2b7e03.png)

Note: You have a large repository of images, where the count of each damage is almost equal. However, some of the images are not yet labelled.

You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. The framework should also be able to train if additional annotations are available later. 

 

 

The solution approach should be able to answer the following questions:
Q1. System design: Based on the above information, describe the KPI that the business should track. 

 

Q2. System design: Your company has decided to build an MLOps system. What advantages would you get from building an MLOps system rather than a simple model? 

 

Q3. System design: You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. For this problem, create an ML system design (diagram) 
(Note: The MLOps tools you want to use are up to your judgement. You can use open-source tools, managed service tools or a hybrid. 
You can use draw.io or any other convenient tool to create the architecture. You can refer to the segment link for <insert segment link> the architecture created in the customer churn case study.
You can upload the design/diagram as an image in the PDF.)

 

Q4. System design: After creating the architecture, please specify your reason for choosing the specific tools you chose for the use case. 

(Note: The MLOps tools you want to use are up to your judgement. You can use open-source tools, or managed service tools or a hybrid.)

 

Q5. Workflow of the solution: 
You must specify the steps that should be taken to build such a system end to end. 
The steps should mention the tools used in each of the components and how they are connected with one another to solve the problem.
Broadly the workflow should include the following:

Data and model experimentation
Automation of data pipeline
Automation of training pipeline
Automation of inference pipeline
Continuous monitoring pipeline
 

The workflow should also explain the actions to be taken under the following conditions:
After you deployed the model, you noticed that there was a sudden increase in the drift due to the poor lighting in the image taken.

What component/pipeline will be triggered if there is any drift detected? What if the drift detected is beyond an acceptable threshold?
What component/pipeline will be triggered if you have additional annotated data?

In the table below, you can find the evaluation rubrics for the assignment.

![image](https://user-images.githubusercontent.com/43085686/225815436-c8f41921-0b38-44fb-8674-1941101a020a.png)

All the deliverables should be combined and submitted as a single .pdf file.

