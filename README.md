# Project: [Wizard Ordering](https://d1b10bmlvqabco.cloudfront.net/attach/j5vqc3j229b6u7/hzpndq5jv06214/j9lmr5b0mnxk/170_Project.pdf)

## Description

You are at another wizard party hosted by Prasad and Sanjam. As usual, wizards are shy about discussing
their age. From conversations at the party, you are only given information in the following form: some
wizard’s age is not between the ages of two other wizards. Since wizard parties are also notoriously long
(an entire month!), you decide to use your time at the party to write a solver and figure out the true ordering
of wizards by their ages.

## FAQ

How to run the solver?
```
1. Open the project using IntelliJ IDEA.

    a. Start IntelliJ IDEA.

    b. Click "Open".

    c. Select the root directory of this project.

2. Ensure all dependencies are correctly set up.

    a. Go to File > Project Structure > Project Settings > Libraries.

    b. Make sure "guava", "javalib", and "sat4j" have been added. If any library is missing, add them by clicking the '+' sign, followed by Java, and select the corresponding folder inside the "./lib/*" subdirectory.
    There is no need to build the libraries used in this project. The corresponding .jar files are already included.

3. The Phase II input files are located in "./src/resources/phase2_inputs/inputsXX/" where XX = 20, 35 or 50 depending on the number of wizards.
Their corresponding output files are located in "./src/resources/phase2_outputs/".

4. The staff input files are located in "./src/resources/Staff_Inputs/". The corresponding outputs are located in "./src/resources/Staff_outputs/".

5. To run the program on all the files we've solved so far, simply run the main method located in "./src/main/java/com/wizardordering/WizardOrdering.java".
The expected running time of the largest file we've solved "staff_180.in" is around ~100 minutes, thus expect the program to take up to two hours to run all the files up
to the aforementioned one.
If you need to run a particular staff input, please follow comments in the main method.

```

## Libraries Used

* [Google Guava](https://github.com/google/guava) - Used for their bi-directional mapping.
* [Princeton's Algorithms Library](https://github.com/kevin-wayne/algs4) - Used for post-processing methods (Directed Graphs and Topological Sorting).
* [SAT4J Solver](https://gitlab.ow2.org/sat4j/sat4j) - SAT Solver used to solve our reduction from Wizard Ordering to 3-SAT.

## Authors
* [Kyung Geun Kim](https://github.com/kyung4952)
* [Yoon Kim](https://github.com/ynnkim)
* [Denny Hung](https://github.com/d3nnyhl)

## Acknowledgements
* Course: CS 170 Fall 2017 Efficient Algorithms and Intractable Problems
* Professors Prasad Raghavendra and Sanjam Garg, and the course staff.
* Google's Guava team for developing Guava
* Professors Joshua Hug, Robert Sedgewick, and Kevin Wayne for making the Princeton library accessible.
* SAT4J development team. Check their work [here](http://www.sat4j.org/)