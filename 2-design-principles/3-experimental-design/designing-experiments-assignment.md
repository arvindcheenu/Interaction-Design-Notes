# Experimental Design

## **Designing Experiments** Assignment

In this assignment, you will be giving advice to a team that is creating a new website. The design team has created a first prototype of a website for this specialization. Before fully implemented, they wanted to be able to get usability feedback on this early prototype. They decide to bring several participants into the lab.

### Review Criteria

Each of the questions in this assignment is worth 2 points. Answers will be graded for correctness.

### My Submission

1. **The team asks you whether they should videotape these participant sessions. What is your recommendation and why?**

   > If the team were to ask me, it depends on **whether you want the participant to be aware of it.** 
   >
   > This is because, by virtue of the **"Hawthorne effect"**- which refers to a reactive phenomenon in which individuals modify an aspect of their behavior in response to their awareness of being observed - the results of the participant sessions could become skewed and meaningless.
   >
   > However, if you choose to **not** notify the participants that they are being videotaped, doing so could expose some more empirical information about the participants’ reactions while using with the interface, like how their body language varies while navigating the website. 
   >
   > If in need for further information, I might also suggest **screen-recording** and **eye-gaze tracking** to give a better indication of a user's flow and navigation of the website, while revealing things that they themselves might not have noticed (i.e. the unreported cues) about their behavior.
   > 

2. **The first participant arrives. The facilitator briefs them by explaining, “I’d like to show you a new design that I’ve created. I’d like to see how well you perform with this design.” What are two problems with this introduction?**

   > In this scenario, the facilitator puts pressure on the participants here in a few ways, the first of which lies in suggesting that **the participants** **are the ones being tested** – “*...I’d like to see how well you perform with this design*”. They should understand instead that the study is not an assessment of their personal performance, but rather of the website’s ability to be used effectively.
   >
   > The facilitator is also creates a **“please the experimenter”** bias by **attaching themself to the object being tested** – *“I’d like to show you what I’ve created”*. This may result in the participants wanting to please the facilitator, not being as truly critical as is required to get useful responses.
   >
   > Additionally, the participants don’t know what the design is or what they are reviewing. This could be remedied however, if it’s specified further along the introduction.
   > 

3. **Rewrite this introduction to avoid those two problems.**

   > *“We’re going to show you a prototype for a new website design, and we would like to learn about how effective  and interacive the website is for students. Your participation is highly appreciated, as it will help us in creating better student experiences.”*
   >

4. **The experimenter continues, “I’d like to get a sense of what you’re thinking about as you go through this site. As you go through the following tasks, please think aloud. Whatever’s on your mind, share it vocally.” If the experimenter uses this think-aloud protocol, what should they not do?**

   > If the experimenter uses the think-aloud method, they should **avoid** asking the participant specific **questions** **while the participant uses the interface** as it would interrupt the participant's stream of thought, collating which could have evoked **well-thought-out feedback** from the participant. 
   >
   > If an interruption is inevitable, one should make sure that one **should not prompt the user for immediate feedback** as it may result in responses without insight.
   >
   > They should also take care to **not measure and compare task completion time**. This is because think-aloud adds to the duration at different rates depending on how much or how fast people talk. Doing so will unwittingly lead to **content bias based on its length**.
   >
   > 

5. **Usability feedback in hand, the development team creates two alternative home pages for the course. They want to see which one encourages more users to sign up. If they compare these two alternatives in a controlled experiment, what is the null hypothesis?**

   > In this case, the null hypothesis (H0) states that there is no significant difference between the two alternatives in the controlled experiment.
   >
   > 

6. **One team member suggests that all participants first see one design, and then all participants see the other design. What is a problem with this approach?**

   > The problem with  "**between-subjects design**" is that this approach introduces the possibility of **personal bias** into the experiment. Say we conduct the study and learn that there is a statistically significant difference between the results of A and B: *How can we be sure that this significance cannot be attributed to personal preference or personal technical knowledge?*
   >
   > 

7. **The team agrees with you. The developers propose a between-subjects design. Participants who sign up in the AM will be assigned the first condition, those that sign up in the PM will be assigned to the second. What is a problem with this approach?**

   > The problem with this approach is that the **assignment of participants is not random.** This means that the outcome of the study could more likely be a result of the way in which the participants signed up, which in turn might be a factor of their personal attributes. For example, participants who sign up in the morning could be from an evening college, while those signing up in the evening could be from the morning college. In this particular case, the approach would be biased based on their study routines.
   >
   > 

8. **What would you propose that the development team do instead?**

   >  As long as there are fewer than several hundred students, I would propose a within-subjects design so each participant uses each website. I would also propose the participants are all assigned a random condition. If conditions are tied to test times, this means the participants **should be assigned a random test time**.
   >
   > 

9. **One hundred participants are exposed to each condition. In Design A 36 participants sign up. In Design B 24 participants sign up. Consider what the chi-squared value is for each condition. Is the difference significant at the p < 0.05 level? To help you get started, the expected sign-up rate is 30% ((36+24)/200). You should also refer to critical values for the chi-squared variable.**

   >  **Expected** **signup**: ((36+24)/200) = **30%**, **30 participants**
   > **Expected** **non-signup**: (100-30)% = **70%**, **70 participants**
   >
   > **Condition A:**
   > **Observed** **signup**: (36/100) = **36%**
   > **χ2(*Signup*)**: (((36 – 30)^2)/30) = **1.2**
   > **χ2(*Non* *Signup*)**: (((64 – 70)^2/70) = **0.514**
   > **χ2(*A*)** = 1.2 + 0.514 **= 1.714**
   >
   > **Condition B:**
   > **Observed** **signup**: (24/100) = **24%**
   > **χ2(*Signup*)**: (((24 – 30)^2)/30) = **1.2**
   > **χ2(*Non* *Signup*)**: (((76 – 70)^2/70) = **0.514**
   > **χ2(*B*)** = 1.2 + 0.514 **= 1.714**
   >
   > **Chi Square: 1.714 + 1.714 = 3.428**
   > **Degrees of freedom (df) = 1** (*2 website options - 1*)
   >
   > Based on a critical chi-squared values table, this puts the **p-value at around .06.** This means that there is roughly a **6%** **chance** that **you would get these observed values** just by chance, or by some underlying distribution. With our **p-value threshold** at .05 or **5%,** there is **no statistically significant difference** **between the signup rate** for A and B here, and we **fail to reject H0** which states that there is **no statistical difference between the two alternatives.**
   > 

10. **Imagine that instead, 50 participants were exposed to each condition. In Design A, 18 sign up; in Design B, 12 sign up. The sign-up ratios are the same as in the previous question. Would the p-value increase, decrease, or stay the same, and why?**

    >  **As the sample size decreases, p-value increases as significance decreases**. A **larger number of participants would provide** **more certainty** that the observed difference between A and B did not happen due to some underlying distribution or external phenomena, such as the more technically-minded students signing up in the morning assuming the old study design. **A study with very few observations is far more likely to contain statistical ratio “anomalies”**; flipping a coin 5 times and getting 4 heads would be far less suspect (so higher p-value) than getting 400 heads when flipped 500 times, though the ratio remains constant.

