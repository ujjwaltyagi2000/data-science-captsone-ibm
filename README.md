# IBM Data Science Capstone Project - SpaceX

## Introduction

In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

This capstone project course will give you a taste of what data scientists go through in real life when working with real datasets. You will assume the role of a Data Scientist working for a startup intending to compete with SpaceX, and in the process follow the Data Science methodology involving data collection, data wrangling, exploratory data analysis, data visualization, model development, model evaluation, and reporting your results to stakeholders. You are tasked with predicting if the first stage of the SpaceX Falcon 9 rocket will land successfully.

## Commercial Space Age Overview:

The commercial space age is booming, with companies making space travel affordable for everyone. Notable players include:

- Virgin Galactic providing suborbital spaceflights.
- Rocket Lab serving as a small satellite provider.
- Blue Origin manufacturing sub-orbital and orbital reusable rockets.
- SpaceX, perhaps the most successful, achieving milestones like sending spacecraft to the International Space Station, establishing Starlink for satellite internet access, and conducting manned space missions.

## SpaceX's Cost Advantage:

SpaceX's notable cost advantage lies in the affordability of its rocket launches. For instance, a Falcon 9 rocket launch is priced at $62 million on SpaceX's website, significantly lower than competitors' costs exceeding $165 million. A key factor contributing to this cost-effectiveness is SpaceX's ability to reuse the first stage of its rockets.

## Understanding Falcon 9:

To comprehend the scale of SpaceX's Falcon 9, we'll refer to diagrams by Forest Katsch, a 3D artist and software engineer at zlsadesign.com. The Falcon 9 comprises multiple stages:

1. Payload Enclosed in Fairings: The cargo is enclosed in fairings.

![alt text](img\image.png)

2. Second Stage: Assists in bringing the payload to orbit.

![alt text](img\image-1.png)

3. First Stage: Performs the majority of the work and is notably larger than the second stage.

![alt text](img\image-2.png)

## First Stage Reusability:

SpaceX's distinctive feature is the ability to recover the first stage, a substantial and costly component. However, it's essential to note that sometimes the first stage may not land successfully due to various reasons, including mission parameters. Occasionally, SpaceX may choose not to recover the first stage based on payload, orbit, or customer requirements.

## Capstone Project:

In this capstone project, the objective is to determine the price of each launch by collecting information about SpaceX and creating informative dashboards for a team. Additionally, I'll delve into predicting whether SpaceX will reuse the first stage, not through rocket science, but by training a machine learning model using publicly available information.
