# Courses@SIB_course_nextflow_Nov_2021

## Title

Reproducible research and data analysis using Nextflow pipelines
<br>
Course page: ...

## About the course

This slow-paced hands-on course is designed for absolute beginners who want to start using [Nextflow](https://www.nextflow.io) to achieve reproducibility of data analysis. 


### Outline

The 4-half-day Nextflow course will train participants to build Nextflow pipelines and run them with [Singularity](https://sylabs.io/singularity/)  containers.

It is designed to provide trainees with short and frequent hands-on sessions, while keeping theoretical sessions to a minimum.

The course will be fully virtual via the [Zoom](https://zoom.us/) platform.

Trainees will work in a dedicated [AWS environment](https://en.wikipedia.org/wiki/AWS).


### Learning objectives

* Locate and fetch Docker/Singularity images from dedicated repositories.
* Execute/Run a Docker/Singularity container from the command line.
* Locate and fetch Nextflow pipelines from dedicated repositories.
* Execute/Run a Nextflow pipeline.
* Describe and explain Nextflow's basic concepts.
* Test and modify a Nextflow pipeline.
* Implement short blocks of code into a Nextflow pipeline.
* Develop a Nextflow pipeline from scratch.
* Run a pipeline in diverse computational environments (local, HPC, cloud).
* Share a pipeline.

### Prerequisite / technical requirements

Being comfortable working with the CLI (command-line interface) in a Linux-based environment.
Knowledge of containers is not mandatory; however, this SIB course (https://www.sib.swiss/training/course/20211014_DOCK) can be advised to take. 

Practitioners will need to connect during the course to a remove server via the "ssh" protocotol. You can learn about it [here](https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work)

Those who follow the course should be able to use a command-line/screen-oriented text editor (such as nano or vi/vim, which are already available in the server) or to be able to use an editor able to connect remotely. For sake of information, below the basics of "nano":
https://wiki.gentoo.org/wiki/Nano/Basics_Guide

Having a [GitHub account](https://github.com/join) accounts is recommended. 

## Dates, time, location

* Dates: November 15-18, 2021

* Time: 13:00-17:30
  * Afternoon coffee break: 15:00-15:30

* Location: virtual, via Zoom.

## Program

### Day 1: Introduction to Nextflow and Linux containers

* 13:00-13:30 Getting started, became familiar with the working environment.
* 13:30-14:30 Talk by Cedric Notredame, CRG.
* 14:30-15:00 Introduction to Docker and Singularity containers.
* 15:00-15:30 Break
* 15:30-16:30 Docker hub and other repositories. Find existing containers. Run a Singularity container (interactively). 
* 16:30-17:30 Nexflow: introduction, installation, run a simple pipeline. 
* 
* 
* find existing pipelines. Run/troubleshoot an existing pipeline. 

### Day 2: Fetch, understand, run, and modify a Nexflow pipeline

* 13:00-14:30 Nexflow basic concepts. Processes and channels. Understand Nextflow main files (main.nf and config files).
* 14:30-15:00 Breakout rooms: run a pipeline.
* 15:00-15:30 Break
* 15:30-16:30 T.
* 16:30-17:30 Modify and run a Nextflow pipeline.

### Day 3: Write/modify and run a pipeline 

* 13:00-14:00 Hands-on: Modify and run a Nextflow pipeline.
* 14:00-15:00 Write Nextflow pipeline from scratch.
* 15:00-15:30 Break
* 15:30-16:30 Run Nextflow with containers.
* 16:30-17:30 Choose either Docker or Singularity.

### Day 4: Build and share a pipeline

* 13:00-14:00 Hands-on: build from scratch and run a Nextflow pipeline.
* 14:00-15:00 (continue hands-on?).
* 15:00-15:30 Break
* 15:30-16:30 Run Nextflow on a computing cluster (e.g. HPC). Definition of computing requirements and queues. Profiles.
* 16:30-17:30 Share Nextflow pipelines and good practices.



## Acknowledgements

* [Bookdown](https://bookdown.org/). The publication system for our course pages.
* [ELIXIR Workshop Hackathon](https://github.com/vibbits/containers-workflow-hackathon). Joined initiative with other colleagues to exchange materials for courses and approaches for courses like this.
