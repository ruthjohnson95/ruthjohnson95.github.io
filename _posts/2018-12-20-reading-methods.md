---
title: '7 Tips for making presentations'
date: 2018-12-04
permalink: /posts/2018/10/prsentation-tips/
tags:
  - grad-school
  - education
excerpt: ""
---


When I was interviewing for PhD programs, I asked one of the PIs I was chatting with, "What's the best piece of advice you can give for upcoming graduate students." He said, "Read as many papers as you can". I'm not going to go into why this piece of advice is important, because I think it speaks for itself. However, when you're first starting out as a grad student, this is way easier said than done. 

I remember, and I'm sure many can relate, that reading papers can take hours-- reading paragraph many times over, staring blankly at equations, ready to call it quits after barely scraping the surface of the Methods section. 

In particular, I find myself reading many bioinformatics methods papers, specifically many in the realm of computational/statistical genetics papers. When I read these papers, I follow a certain structure of thought. 

*This is not how I'd personally do a 'deep dive' for a paper, but more of a 'staying up to date' on the literature or skimming type of approach 

This is a template for approaching a paper. When I can fill in each part of this template, I feel can efficiently summarize what I've learned. 

- Introduction references 	
	- references of references (recursion)
	- Review paper 
- Math References:
	- Probabalistic inference: Kevin Murhpy 
	- Bayesian: Gelman 
	- Intro Stats: Penn State notes 
	- Matrix "stuff": Matrix cookbook 
	- Notes from this class 


## Biological problem statement

The heart of every bioinformatics method is to solve a biological problem. The first step is to identify exactly which biological problem a method is trying to either solve or address. I like to define the biological problem at this step, as in fine-grain resolution as possible. The Introduction will often set the landscape for the biological problem and explicilty lay out the contributions of a particular method. 

The key biological problem is to quantify the amount of genetic overlap between two complex traits by estimating the shared proportion of causal SNPs. Note that we're being specific by identifying the problem as idenitfying the shared proportion, rather than just leaving it at looking at genetic overlap which is more high-level. 

## Statistical problem statement

The foundation of these methods are rooted in statistics, mathematics, and computer science, and oftentimes methods seek to solve or improve upon a problem with a new statistical approach, a faster algorithm, etc. The second step is to identify what the statistical problem the paper is trying to solve. For example, are they trying to use a more complex model, performing maximum likelihood, doing causal inference? And there can be multiple parts to this.

Our statistical problem focuses on describing the genetic architecture between a pair of traits with a full Bayesian generative model and performing inference 


- Statistical problem statement (Methods)
- Inputs
- Outputs
- Model assumptions
- Inference assumptions 
- Speed (opt) (often tied with assumptions of inference)
- Discussion (skim)
- How does this meet the bottom line of biology (100 foot overview)
- How is this related to what I do...? 
- Math:
	- Is this here for completeness? 
	- Deep dive if I need to answer an above question. 
	- This gets easier, I promise. 

	
Where to find papers: 
