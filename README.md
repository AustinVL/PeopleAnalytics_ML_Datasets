# PeopleAnalytics_ML_Datasets

Hey everyone! This is going to be a repository for a few ML data sets you might interested in. I'll provide a little documentation here on each.

## heart.csv -- Predicting whether a patient has heart disease

This dataset contains information on a group of anonymous patients. Specifically, it has various pieces of biomedical information about them (see below) and whether or not they had heart disease (see [here](https://archive.ics.uci.edu/ml/datasets/heart+disease) for more information). The outcome was originally one of severity, but there's not really enough variation in the original data to predict all the different classes so it's easier to reduce heart disease to a binary outcome. Here's the data I've included:

* **age**: age of the patient, in years
* **sex**: equal to one if the patient was assigned male, zero if the patient was assigned female (it is unclear if they were going off gender identity or what biological sex the patient was categorized as at birth)
* **cp**: whether/what kind of chest pain the patient was complaining of (0 = no chest pain, 1 = typical angina, 2 = atypical angin, 3 = non-anginal) 
* **trestbps**: the patient's resting blood pressure
* **chol**: the patient's cholestoral level
* **fbs**: whether the patient exhibited high levels of (fasting) blood sugar
* **restecg**: whether the patient exhibited abnormal electrocardiogram (ecg) results **[THIS NEEDS CHANGING]**
* **thalach**: patient's maximum measured heart rate
* **target**: whether the patient was found to have heart disease

## america_divided.csv -- Predicting Americans' immigration attitudes and/or affective polarization

This is a dataset I collected through [Prolific](https://www.prolific.co/about) in early 2022. We asked a lot of questions about politics, party identification, and other matters. This is a set of variables that should be easy and interesting to work with. The sample is comprised entirely of residents of the (continental) U.S. who identified either as a Democrat or as a Republican, in about equal proportion. Here is the information provided:

* **partyID**: whether the participant identified as a strong Democrat (1), a "not strong" Democrat (2), a "not strong" Republican (3), or a strong Republican (4).
* **ideology**: where the participant identified on a 7-point political ideology scale from "Extremely conservative" (1) to "Extremely liberal" (7).
* **region**: whether the participant reported being from (raised in or identifies with) the midwestern (1), northeastern (2), southern (3), or western (4) United States (defined by self-reported state and the [official US census regions](https://en.wikipedia.org/wiki/List_of_regions_of_the_United_States#Census_Bureau-designated_regions_and_divisions)).
* **daca**: whether the participant reported supporting (1) or not supporting (0) the continuation of [DACA](https://en.wikipedia.org/wiki/Deferred_Action_for_Childhood_Arrivals)
* **ap**: the participant's reported level of affective polarization. Specifically, participants reported how warmly they felt towards their political ingroup and outgroup on a 1 (cold) to 100 (warm) scale, and the difference is measured such that higher scores mean participants reported more warm scores towards their political ingroup than their political outgroup.

## titanic.csv -- Predicting who survived the Titanic

This dataset contains information on a collection of passangers aboard [the infamous voyage of the ship The Titanic](https://en.wikipedia.org/wiki/Sinking_of_the_Titanic), including whether they survived the ship's skinking. It contains the following information on each passanger:

* **Survived**: whether the passanger survived the Titanic shipwreck
* **Pclass**: the passanger class of the passanger (1st class folks were rich, 3rd class folks were more poor, and 2nd class folks were in-between).
* **Name**: the name of the passanger
* **Male**: one if the passanger was male and zero if they were female
* **Age**: the age of the passanger in years
* **Siblings/Spouses Aboard**: the sum of the number of sibling and spouses of the passanger that were also aboard the ship.
* **Parents/Children Aboard**: the sum of the number of parents and children of the passanger that were also aboard the ship.
* **Fare**: the amount of money paid for the passanger's ticket for the ship
