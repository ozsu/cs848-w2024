# CS 848 (Winter 2024)
# Disaggregated and Heterogeneous Computing Platform for Graph Processing

+ **Instructor:** [M. Tamer Özsu](https://cs.uwaterloo.ca/~tozsu/)
+ **Seminar Room:** DC 2568
+ **Seminar Time:** Thursday 1:30pm-4:30pm

## Overview
For many years, the preferred parallel data management architecture was shared-nothing where multiple compute units, each of which consist of CPU+Memory+Storage, are connected by a network. The shared-nothing architecture performs parallel computation, usually, through explicit messaging. The shared-nothing architecture has been reflected in cloud data centres in the form of a rack-and-blade design, where each blade contains some compute elements, some memory, usually some storage, and perhaps some accelerators tightly connected and multiple blades are mounted on a rack. This _converged_ data centre architecture is now starting to experience difficulties in adequately serving emerging big data applications with highly varying application require-ments. An important expectation of cloud computing is to provide elasticity to accommodate these extreme application needs, but only when they arise. However,  converged data centre architecture is stressed in providing this elasticity and usually over-provisions (i.e., allocates at the beginning of the computation task the maximum resources that may be needed at some point) resulting in low resource utilization. Most data centres have moved to shared-storage solutions by the deployment of SANs that are connected to compute units through high-speed networks. This is called _disaggregated storage_. More recent work has focused on also disaggregating memory, where a bank of memory units are accessible by the compute units over very high speed and low lantency networks. This is called _disaggregated memory_. The combination of both to achieve a fully disaggregated platform architecutre has not yet been studied extensively.

At the same time, there is significant interest in using hardware accelerators for data management. Most of the work has focused on GPUs, but there is interest in the use of FPGAs as well. Many are single machine solutions, but parallel environments and CPU-GPU combinations have also been investigated. There is some work on using FPGAs in data management systems and some on CPU-FPGA combinations. There is no work that considers a heterogeneous CPU-GPU-FPGA platform.  With the increasing role of data management in AI and ML workloads, hardware accelerators will be increasingly important. Current platforms directly connect these accelerators to the compute units, but they can be disaggregated in the same way storage and memory are. 

The purpose of this seminar is to study and debate the design issues of a _disaggregated and heterogeneous computing platform_ (DHCP) and its impact on data management. The design space is quite large, so when more focus is needed by fixing specific workloads, the concentration will be on graph processing.

The course is based on weekly paper readings and student presentations, discussions, and a term project. 

## Course Logistics

+ Weeks 1 and 2: I will be presenting some background material to set the stage. There are background reading materials for this section and I expect you to read them and be prepared to discuss (see below for details).

+ Week 3: Prof. Samer Al-Kiswany and his student will be presenting their work on RDMA. We will then have a discussion on CXL.

+ Weeks 4-11: These weeks, we will spend the class time in paper presentations and discussions. Each week will be two paper presentation and discussions.

+ Weeks 12-13: Brief project presentations (see below)

+ Discussions will be over Piazza. Please go [here and add yourself](https://piazza.com/uwaterloo.ca/winter2024/cs848) to the class.


## Workload Breakdown (Tentative and might change depending on class size)
+ Presentation: 15%
    + Each student will present one paper in class, critique it, and answer questions from the class. The presentation should be about 25-40 minutes.
        + If the class size is small, we will have two presentations per student, in which case I will increase the presentation percentage to 20%.
    + See [these guidelines](Presentation.md) for preparing your presentation.
    + Submit the presentation slides by 7pm on the Wednesday prior to your presentation. See below for submission of presentation slides.
    + See the schedule below that we will fill as we go through the term.
+ Paper Reviews: 20%
    + All students will read the two papers that will be presented each week, and will write a review of the papers. You do not need to write a review of the paper you are presenting.
    + Submit the reviews by 7pm on Wednesday before the lecture. See below for submission of your reviews.
    + Each review should be no longer than 1000 words -- that is about 2 pages in 12pt font.
    + I don't care which tool you use, but please make it single column, single-spaced, 12 pt, normal margins (1 in).
    + See [these guidelines](Reviews.md) for writing the reviews.
+ Class participation: 15%
    + Participation in the discussions in class.
    + Since this is a seminar course, this discussion is very important. The expectation is that everyone in class will participate.
+ Project: 50%
    + Done in groups of two.
    + Each group needs to find a topic to research and write a report.
    + See [these guidelines](Project.md) for further details
    + If the class size is small and each student presents two papers, the project percentage will drop to 45%.


## Weekly Schedule
See the [schedule](Schedule.md). Please note that we might adjust it as needed depending on class size.

## Submission of Course material
* I have set up a dropbox folder for you to drop things; [drop everything here](https://www.dropbox.com/request/qHrYhkK8ZwiTbbPCMUiH).
* Everything should be submitted in PDF format.
* Please name your files as follows: &lt;week_no&gt;-&lt;last_name&gt;-&lt;type&gt;&lt;number&gt;.pdf where &lt;type&gt; is either "review" is for paper reviews or "slides" is for presentation slides when it is your turn; &lt;number&gt; is the paper number.

## Administrative Issues 

Please review the materials concerning [academic integrity](https://uwaterloo.ca/library/research-supports/academic-integrity/graduate-academic-integrity-module) and [academic honesty](https://uwaterloo.ca/academic-integrity/integrity-students).


