---
title: "Preference Design"
hero_image: "hero.jpg"
nometadata: true
notags: true
noshare: true
nocomments: true
---

## Introduction

Suppose an investigator is interested in conducting a clinical trial to assess the effect of medical versus surgical treatment for low back pain. In the traditional clinical trial design, participants would be randomized to the medical or surgical arm with the express purpose of estimating treatment efficacy. However, this traditional design ignores the potential impact that an individual’s preference for a particular treatment may play on the overall effectiveness. This impact may especially be of concern in this example where participants are not blinded to the treatment arm: medical versus surgical. The two-stage clinical trial design [1], where patients are first randomized to a choice arm versus a random arm, allows for estimation of the standard treatment effect as well as a selection effect and a preference effect. The selection effect is the effect on outcomes from the self-selection of individuals into a particular treatment [1,3]. For example, this effect would capture differences in pain score between those preferring the medical intervention versus those preferring the surgical intervention.  The preference effect measures the impact receiving the preferred treatment has on the outcome [1,3]. This effect would measure the difference in pain score between participants receiving their preferred treatments (e.g. prefer medical and receive medical or prefer surgical and receive surgical) and participants who do not receive their preferred treatment (e.g. prefer medical and receive surgical or prefer surgical and receive medical). From this two-stage design, the investigator is able to estimate how much the choice of a preferred treatment can impact the effectiveness of a given treatment.

<center>
![](/img/rucker-design.png)
</center>

## Designing a Trial

In order to design a two-stage clinical trial, you will need to answer a few important questions:

1.  What is the most important effect of interest?  Is it the treatment effect, the preference effect or the selection effect?

<div style="margin-left: 2em;">
Most often we are going to be interested in either the treatment effect or the preference effect.  However, it is possible to design the study for any or all of these effects.  In our example, since prior literature showed that freedom from low back pain was not significantly different between the two groups, we are focused on being able to detect a preference effect and thus will design our study with this as the primary effect of interest.
</div>

2.  What is the preference for one treatment over the other?

<div style="margin-left: 2em;">
In order to determine the preference for one treatment over another we do any of the following: rely on prior published literature; conduct a small pilot study and ask participants their preferences for one treatment over another; or make an educated guess based on clinical experience.  According to literature from a clinical trial of medical treatment versus surgical treatment for lower back pain [REF], 26% randomized to medical treatment eventually had surgery.  Therefore, we will use this information to estimate the preference for surgery to be 75% compared to 25% for medical intervention.
</div>

3.  What difference (effect size) do we want to be able to detect between the two groups?

<div style="margin-left: 2em;">
Ideally, we would want to determine a meaningful difference based on the scale of interest.  For example, a one point change on the pain scale may be meaningful and therefore, we would use that to help determine sample size for our study.  In order to determine the appropriate effect size, we can use the effect size calculate (see below), and we would need to know 4 estimates: (1) the mean pain score for the surgical intervention in the random arm; (2) the mean pain score for the medical intervention in the random arm; (3) the mean pain score for the surgical intervention in the choice arm; and (4) the mean pain score for the medical intervention in the choice arm. With this information, and the preference rate for one treatment over another, we can calculate the effect size.

However, if we are unsure about the effect size, we can always determine sample size based on standardized effect sizes.  In this case, we could use standards set out by XX [REF] for what is considered small, medium and large effects.
</div>

4.  What is the variability in our groups?

<div style="margin-left: 2em;">
In addition to knowing the effect size, we need to know something about the variability of the effect size.  Therefore, it is important to know how much variability we expect in our measure of pain score, and whether or not we expect this to be the same in the two treatment groups.

If a standard effect size is proposed, then the variability would be set at 1.
</div>

## Stratified Preference Designs

The above design assumes that the preference rate is constant across the entire population.  However, this may not be the case.  In some instances, there may be a variable that we would want to stratify the population based upon.  In the medical versus surgical trial, this may be age.  It may be that younger individuals would have a much higher preference for a surgical intervention compared to a medical intervention then older individuals.  Based on clinical experience, we may hypothesize that the surgical preference rate in the younger population would be 80%, whereas the surgical preference rate in the older population would 65%.  Under this scenario, we would want to implement a stratified design.

The stratified design is explored further in the [Stratified Design Page](../stratified-design).


