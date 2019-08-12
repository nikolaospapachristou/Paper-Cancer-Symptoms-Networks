## Appendix C

This is the Appendix C of the application of Bayesian Networks (BNs) on cancer symptoms. If you are viewing this from github you can find its html form in the following link.
* [https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)

The following **list of interactive Bayesian Networks**, ran on the same set of cancer symptom data. The **complete dataset** consisted of 38 different symptoms collected from 1328 cancer patients. Inside this dataset, there were 295 male and 1033 female cancer patients. There were, also, 958 cancer patients below the age of 65 and 370 cancer patients above the age of 65.  

The networks were created by the **symptom dimension of occurrence**. The **size of nodes** represent the prevalence of each symptom in our dataset, among the 1328 cancer patients. The **width of the edges** are proportional to the strength that symptoms connect with each other, based on the conditional probabilities identified with the BN algorithm.

By **clicking on a node** you can see its markov blanket, meaning the specific symptom with its parents and children. You can see the same markov blanket by selecting a symptom in the **menu on the left**.

You can **move each node** in the diagram by click and drag. To **deselect** it click on the white space of the diagram. To **restart the diagram** refresh the page.

**A.** In the list below you will find the application and comprarison of Grow-Shrink, Hill Climbing, Max-Min Hill Climbing BN algorithms on the complete dataset of cancer patients (n=1328):

 * [SF1] [All cancer patients (n=1328), Grow-Shrink, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSmod1.html)
 * [SF2] [All cancer patients (n=1328), Grow-Shrink, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSmod2.html)
 * [SF3] [All cancer patients (n=1328), Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/HCmod1.html)
 * [SF4] [All cancer patients (n=1328), Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/HCmod2.html)
 * [SF5] [All cancer patients (n=1328), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MMHCmod1.html)
 * [SF6] [All cancer patients (n=1328), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MMHCmod2.html)
 * [SF7] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSHCmod1.html)
 * [SF8] [Cancer symptoms' network differences between the Grow-Shrink and Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSHCmod2.html)
 * [SF9] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSMMHCmod1.html)
 * [SF10] [Cancer symptoms' network differences between the Grow-Shrink and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/GSMMHCmod2.html)
 * [SF11] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, 0.85 threshold (Sachs et al., 2005), all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/HCMMHCmod1.html)
 * [SF12] [Cancer symptoms' network differences between the Hill Climbing and Max-Min Hill Climbing models, optimal threshold according to Scurati & Nagarajan, 2013, all cancer patients (n=1328)](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/HCMMHCmod2.html)

**B.** In the list below you will find, as a case study, the application of BNs on 4 different subgroups of cancer patients based on their and age (i.e., male vs female, < 65 versus > 65 years of age), **without the symptom clusters (i.e., communities)** identified in the Papachristou et al. 2019. [1]
 * [SF13] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Agebelow65MMHCmod1.html)
 * [SF14] [Cancer patients with age below 65 (n=958), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Agebelow65MMHCmod2.html)
* [SF15] [Cancer patients with age below 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF16] [Cancer patients with age below 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF17] [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Ageabove65MMHCmod1.html) 
 * [SF18] [Cancer patients with age above 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Ageabove65MMHCmod2.html) 
 * [SF19] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Agemod1.html) 
 * [SF20] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/Agemod2.html)  
 * [SF21] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/) 
 * [SF22] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/) 
* [SF23] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=958) and below the age of 65 (n=370, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/) 
 * [SF24] [Cancer symptoms' network differences between cancer patients below the age of 65 (n=370, bootstrapped sampling) and above the age of 65 (n=370), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/) 
 * [SF25] [Male cancer patients (n=295), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MenMMHCmod1.html) 
 * [SF26] [Male cancer patients (n=295), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MenMMHCmod2.html) 
 * [SF27] [Female cancer patients (n=1033), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/WomenMMHCmod1.html)
 * [SF28] [Female cancer patients (n=1033), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/WomenMMHCmod2.html) 
 * [SF29] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF30] [Female cancer patients (n=295, bootstrapped sampling), Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/) 
* [SF31] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MenWomenmod1.html)
 * [SF32] [Cancer symptoms' network differences between male (n=295) and female (n=1033) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/MenWomenmod2.html)
 * [SF33] [Cancer symptoms' network differences between male (n=295) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF34] [Cancer symptoms' network differences between male (n=295) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF35] [Cancer symptoms' network differences between female (n=1033) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, 0.85 threshold. Sachs et al., 2005](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
 * [SF36] [Cancer symptoms' network differences between male (n=1033) and female (n=295, bootstrapped sampling) cancer patients, Max-Min Hill Climbing, optimal threshold according to Scurati & Nagarajan, 2013](https://nikolaospapachristou.github.io/Paper-Cancer-Symptoms-Networks/)
