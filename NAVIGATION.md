#  PLUMED Masterclass 21.7: Optimizing PLUMED performances

This lesson was given as part of the PLUMED masterclass series in 2021.  It includes:

* A video that explain the theory covered and a second video which shows you how the exercises should be completed.
* A series of exercises that you should try to complete yourself.
* Some supplementary python notebooks that provide further background information on the exercise.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplmentary resources that you may find useful when completing the exercise. 

This lesson was the seventh masterclass in the 2021 series.  You will likely be able to complete the exercise without completing all the exercises in the first six masterclasses in the series.  However, you will need to install plumed and gromacs so that you can run in MPI (installing PLUMED and gromacs is covered in the 5th masterclass).  You will also be working on optimising performance in metadyanmics simulations. This method was introduced in the fourth masterclass in the series.

```mermaid
flowchart TB;
  A[Metadynamics] -.-> C[Lecture I] 
  B[MPI installation] -.-> C
  C ==> D[Instructions];
  D ==> E[Lecture II];
  D --> F[exercise 1 solution];
  D --> G[exercise 2 solution];
  click A "ref1" "This lesson teaches you how to run metadynamics simulations. In this exercise you complete a series of exercise to improve the performance of metadynamics simulations.";
  click B "ref2" "This lesson teaches you how to run simulations with multiple replicas. You do not need to know how to run simulations with multiple replicas to complete the exercises on optimising the performance of PLUMED. You may like to consult this lesson, however, as it shows you how to install PLUMED and gromacs with MPI.  You will need parallel versions of these two codes to complete the exercises in this lesson.";
  click C "video1" "A lecture that was given on April 26th 2021 as part of the plumed masterclass series that introduces you to the exercises in this lesson";
  click D "INSTRUCTIONS.md" "The instructions for the exercises";
  click E "video2" "A lecture that was given on May 3rd 2021 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson";
  click F "notebooks/Exercise1.ipynb" "A set of solutions for the first exercise in the instructions";
  click G "notebooks/Exercise2.ipynb" "A set of solutions for the second exercise in the instructions";
```
