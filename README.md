# Power line Fault Detection and Analysis
Specifying the question

Electrical Fault Definition: Fault in electrical equipment or apparatus is defined as an imperfection in the electrical circuit due to which current is deflected from the intended path. In other words, fault is the abnormal condition of the electrical system which damages the electrical equipment and disturbs the normal flow of the electric current.

Types of Electrical Fault

There are two main types of electric fault:

Symmetrical - Symmetrical fault is one that affects each of the phases equally. Its occurence is rare and 5% of transmission-line faults are symmetrical.

Asymmetrical- Here, all the three phases are not affected equally unlike in symmetrical faults. Common types of asymmetric faults and their causes:

Single Phase to Ground Fault – It is also called a line-to-ground fault. It mainly occurs due to insulation breakdown between one of the phases and earth. Their chances of appearance in the power system are 70%.
Phase-to-Phase Fault – Such type of fault rarely occurs on the power system. It is also called Line-to-line fault. It occurs when two conductors are short circuited. Their chance of appearance is hardly 15% in the power system.
Two Phases to Ground Fault – In this type of fault breakdowns of insulation between two phases and earth occur. It is the most severe type of fault but rarely occurs in the power system. It is also called Line-to-line-to-ground fault (L-L-G). Their chance of occurrence is hardly 10%.
Phase to phase and Third Phase to Ground Fault – It is the combination of phase to phase and phase to phase to ground fault. Such types of fault occur due to the breakdown of insulation between two phases and simultaneous breakdown of insulation between the third phase and earth. The chance of such a type of fault is hardly 2% to 3%.
All the Three Phases to Ground Fault – It is the most severe type of the fault and very rarely occurs in the power system. It occurs due to a breakdown of insulation between all the phases as well as to the earth. Its chance of occurence is 2% to 3% in the power system.
Reason for faults

Possible causes of power line fault include:

Insulation failure or breakdown
Lighting
surge
Unbalanced current or voltage
Stability fall
Mechanical fault in transmission line
Over voltage
Temperature rise

Overall objective:
Detection and classify faulty power transmission lines based on the analysis of current and voltage

A good fault detection system provides an effective, reliable, fast and secure way of a relaying operation. The application of a pattern recognition technique could be useful in discriminating against faults or disturbances and healthy electrical power systems. This will enable the power system to remain in stable condition. 
The analysis  also enables us to differentiate among three phases which phase is experiencing a fault for quick resolution.

Specific objectives:

Which type of fault appears the most,is it line to line or line to ground?
How can we identify and mitigate the risks associated with power faults?
Which phase has the most fault?
What is most likely to cause fault?

Three Phase electric power
Three-phase electric power is a common method of alternating current electric power generation, transmission, and distribution. [1] It is a type of polyphase system and is the most common method used by electrical grids worldwide to transfer power. It is also used to power large motors and other heavy loads. A three-wire three-phase circuit is usually more economical than an equivalent two-wire single-phase circuit at the same line to ground voltage because it uses less conductor material to transmit a given amount of electrical power

In a three-phase system feeding a balanced and linear load, the sum of the instantaneous currents of the three conductors is zero. In other words, the current in each conductor is equal in magnitude to the sum of the currents in the other two, but with the opposite sign. The return path for the current in any phase conductor is the other two phase conductors

The machine learning models employed include:

Linear regression
Logistic regression
Decision trees
Random forest
Support Vector Machine
KNN
Naive bayes
Multi layer perceptron

Defining metrics of success

Defining the metrics for success This study will be considered a success if:

We get an accuracy score of at least 80% for our model
We are able to obtain better metrics to assess our model
We are able to plot auc curves and explain the results








