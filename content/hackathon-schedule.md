---
title: "Hackathon Schedule"
date: 2018-06-12T15:33:52-04:00
anchor: "hackathon-schedule"
weight: 4
---

## Goal
Analyze and compare available methods for matching morphological signatures across different experiments or across data sets from different labs.

## Problem and challenges
Imagine two different institutions collaborating in a research study: Lab A and Lab B. These two labs want to create image-based profiles of genes and compounds. Each lab profiles a different set of perturbations, including positive and negative controls, plus other perturbations of interest to each lab. They then want to compare the effect of all perturbations across the experiments run in both labs. How can they achieve this, given that there may be differences in the experiment conditions?

The CytoData 2018 Challenge is to come up with methodologies to match image-based profiles across datasets. Participants will be provided with image-based profiles coming from different sources and having overlapping perturbations. As the profiles come from different sources, the signature embeddings may have implicit biases reflecting differences in microscope equipment, batch effects, experimental conditions, and even cell lines. We assume that these differences are irrelevant to the underlying biological process, and should not dominate the observed signal.

Participants of the CytoData 2018 Challenge will team up with other fellow scientists to improve cross-dataset signature recall. Their goal is to refine, normalize and transform image-based features using machine learning or statistical approaches to remove the effect of experimental artifacts. Successful methodologies will accurately cluster the data in holdout sets. An effective solution to this problem will help make image-based profiling workflows more robust and reusable at a large scale.

## Challenge format

**Before the challenge: From now until Sept 21, 2018**

Participants will be invited to contribute ideas towards a solution, in the form of methods, relevant literature, and other relevant material. Participants are encouraged to engage in a conversation to understand other’s ideas, point out potential problems and solutions, and post comments and other ideas.

This will be moderated through a GitHub repository, with readme files, contributors, issues and other software development practices.

**During the challenge: Sep 24 and 25, 2018**

The challenge will start with a description of the problem and a presentation of the datasets available for research. A summary of methodologies proposed before the challenge will be presented too. Teams will be formed after preliminary discussions and Q&A sessions. The data and other resources will be released when the teams are organized to start hacking.

Amazon Web Services virtual machines available for participants to run experiments. Also, example code to load data, run baseline experiments and evaluate performance will be provided to get partipants up to speed.

At the end of the two-day challenge, a holdout set will be released to participants to match image-based signatures in the sets provided before. This will be evaluated automatically to identify the team that can match signature across datasets more accurately than the baselines and other teams. 

The winning team will take a home a prize sponsored by Nvidia. 

**After the challenge: From Sep 26, 2018 onwards**

All the data generated during the challenge will be potentially useful to compare and analyze different strategies for solving the cross dataset matching problem. Interested participants can refine their approaches after the competition and contribute with their results in a collaborative paper written jointly with the challenge organizers and other participants.

