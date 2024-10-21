**Reference:**idS9
**Citation:**Ging-Jehli, Nadja R., et al. “Characterizing Underlying Cognitive Components of ADHD Presentations and Co-Morbid Diagnoses: A Diffusion Decision Model Analysis.” Journal of Attention Disorders, vol. 26, no. 5, 2022, pp. 706–22, https://doi.org/10.1177/10870547211020087.


![ref1]![ref2]![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.003.png)

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.004.png)


**Characterizing Underlying Cognitive Components of ADHD Presentations and Co-morbid Diagnoses: A Diffusion Decision Model Analysis**

Journal of Attention Disorders 2022, Vol. 26(5) 706–722

© The Author(s) 2021 Article reuse guidelines:

[sagepub.com/journals-permissions](https://us.sagepub.com/en-us/journals-permissions) DOI: 10.1177/10870547211020087

[journals.sagepub.com/home/jad](https://journals.sagepub.com/home/jad)

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.005.png)



# **Nadja R. Ging-Jehli1![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.006.png), L. Eugene Arnold1, Michelle E. Roley-Roberts2, and Roger deBeus3**


### **Abstract**
**Objective:** To Explore whether subtypes and comorbidities of attention-deficit hyperactivity disorder (ADHD) induce distinct biases in cognitive components involved in information processing. **Method:** Performance on the Integrated Visual and Auditory Continuous Performance Test (IVA-CPT) was compared between 150 children (aged 7 to 10) with ADHD, grouped by DSM-5 presentation (ADHD-C, ADHD-I) or co-morbid diagnoses (anxiety, oppositional defiant disorder [ODD], both, neither), and 60 children without ADHD. Diffusion decision modeling decomposed performance into cognitive components. **Results:** Children with ADHD had poorer information integration than controls. Children with ADHD-C were more sensitive to changes in presentation modality (auditory/visual) than those with ADHD-I and controls. Above and beyond these results, children with ADHD+anxiety+ODD had larger increases in response biases when targets became frequent than children with ADHD-only or with ADHD and one comorbidity. **Conclusion:** ADHD presentations and comorbidities have distinct cognitive characteristics quantifiable using DDM and IVA-CPT. We discuss implications for tailored cognitive-behavioral therapy. *(J. of Att. Dis. 2022; 26(5) 706-722)*

### **Keywords**
diffusion decision model, ADHD, comorbidity, cognitive testing, computational psychiatry



# ![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.007.jpeg)**Introduction**
The Diagnostic and Statistical Manual of Mental Disorders (DSM-5; American Psychiatric Association [APA], 2013) distinguishes among three presentations of attention-deficit hyperactivity disorder (ADHD) based on whether the pre- dominant symptom is inattention (ADHD-I); hyperactivity- impulsivity (ADHD-H); or a combination of both, inattention and hyperactivity-impulsivity (ADHD-C). Moreover, chil- dren with ADHD frequently struggle not only with inatten- tion and/or hyperactivity-impulsivity, but also with symptoms of disruptive behavior disorders (oppositional-defiant, con- duct) and/or anxiety disorders (Avila et al., 2004; Nikolas et al., 2019). To date, little is known about how different DSM-5-defined presentations and co-morbid diagnoses influence underlying latent cognitive components of infor- mation processing (e.g., Avila et al., 2004; Nikolas et al., 2019).

Research using neurocognitive tests found that children with ADHD have slower mean reaction times (RTs) and/or accuracy than those without ADHD across a range of tasks such as those presumed to measure sustained attention (e.g.,

Baytunca et al., 2018; Huang-Pollock et al., 2012, 2020; Karalunas et al., 2018; Weigard et al., 2020), inhibitory con- trol (e.g., Baytunca et al., 2018; Epstein et al., 2011; Fosco et al., 2018; Huang-Pollock et al., 2017; Mowinckel et al., 2015) or working memory (e.g., Kawabe et al., 2018; Nigg et al., 2018; Stroux et al., 2016). Recently, Ging-Jehli et al. (2021) reviewed studies across a broad range of neurocog- nitive tests for ADHD and they found that most studies focused on differences between controls and ADHD and on specific ADHD populations (e.g., boys only or children without co-morbid diagnoses).

A few studies (e.g., Carr et al., 2010; Collings, 2003; O’Driscoll et al., 2005; Pritchard et al., 2008) have already examined differences among ADHD presentations. For

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.008.png)

1The Ohio State University, Columbus, USA 2Creighton University, Omaha, NE, USA 3University of North Carolina at Asheville, USA

**Corresponding Author:**

Nadja R. Ging-Jehli, Department of Psychology, The Ohio State University, 1835 Neil Avenue Mall, Columbus, OH 43210, USA. Email: <nadja@gingjehli.com>



instance, Carr et al. (2010) found that children with ADHD-I detected significantly more target letters in a stream of let- ters than those with ADHD-C though only if they were instructed to divide attention between two types of targets (i.e., type and color of target letters). When having to focus on responding to only the letter type, children with ADHD-I and ADHD-C were equally accurate. O’Driscoll et al. (2005) found similar results as Carr et al. (2010) in another task (an anti-saccade task in which children had to move their eyes either toward the position or toward the opposite position of visually presented target boxes). However, the aforementioned studies focused on summary statistics and on differences between ADHD presentations only, neglect- ing co-morbid diagnoses.

Research from Cognitive Psychology (e.g., Forstmann et al., 2016; Ratcliff & McKoon, 2008; Ratcliff et al., 2018) showed that RTs are the product of a decision-making pro- cess that consists of multiple cognitive components. Computational models, such as the diffusion decision model (DDM; Ratcliff, 1978), can be used to quantify and sepa- rately study each of these cognitive components. Therefore, such a computational modeling approach seems appealing to assess differences in distinct cognitive components among ADHD presentations and between children with dif- ferent comorbidities.

Understanding similarities and differences in specific cognitive processes among ADHD presentations and between comorbidities is important not only for diagnostic purposes but also for personalized medicine. For instances, studies found that comorbidities can moderate treatment response (Jensen et al., 2001; The MTA Cooperative Group, 1999). One-third of those diagnosed with ADHD are non- responders to the first stimulant tried, and up to 10% are non-responders to all medication (Adler et al., 2006; Arnold, 2000; Arnold et al, 1978; Pliszka, 1989; Swanson et al, 2001). If one identifies and quantifies those cognitive com- ponents that lead to deficits or biases in information pro- cessing, one can target those components in cognitive behavioral therapies.

## *Current Study*
The purpose of this study was to compare the underlying latent cognitive components between children without ADHD and those with DSM-5 ADHD presentations (analy- sis 1); and between children with ADHD who had different co-morbid diagnoses, statistically adjusting for differences in DSM-5 ADHD presentations (analysis 2).

We focused on the DSM-5 ADHD presentations “ADHD-I” and “ADHD-C” because research has shown that “ADHD-H” is rare after preschool years (Barkley, 2003; Milich et al., 2001). Moreover, we focused on study- ing the underlying latent cognitive components that together resemble information processing by using a specific version

of the Continuous Performance Test (CPT) - a common neurocognitive test for ADHD. The latent cognitive compo- nents were estimated by applying the DDM to the neuro- cognitive performance data. In the following sections, we first summarize literature on CPTs for ADHD that are closely related to this study. Then, we explain the DDM in more detail. We also highlight important differences of this study to previous DDM applications (to CPTs) in clinical research.

## *Continuous Performance Tests for ADHD*
The CPT is a commonly used instrument to study cognition in ADHD (Corbett & Constantine, 2006; Epstein et al., 2011; Hervey et al., 2006; Nichols & Waschbusch, 2004). In a CPT, a series of stimuli (e.g., letters, numbers) are pre- sented on a computer screen (or via headphones). Typically, one stimulus represents go trials while another stimulus represents no-go trials. Participants are asked to press a response key for go trials, and to *not* press the response key for no-go trials. RTs, omission, and commission errors serve as performance measures.

There are two types of CPTs, differing in frequency of go versus no-go trials (see for a review: Edwards et al., 2007). The performance from CPTs with frequent go trials are pre- sumed to elucidate cognitive concepts such as inhibitory control (e.g., Huang-Pollock et al., 2012; but see for cri- tiques also Ging-Jehli et al., 2021). In this type of CPT, chil- dren with ADHD often committed more errors (pressing the key when they should not or not pressing the key when they should) than those without ADHD, though evidence remains mixed (Huang-Pollock et al., 2012; Parsons et al., 2019; Sonuga-Barke et al., 2008). Moreover, Collings (2003) found differences among ADHD presentations such that children with ADHD-C conducted significantly more omis- sion errors than those with ADHD-I or those without ADHD. In contrast, other studies failed to find subtype- specific differences (see for a review: Ging-Jehli et al., 2021). The performance from CPTs with rare go trials are presumed to elucidate cognitive concepts such as sustained attention (Gordon, 1986; Robertson et al., 1997; but see for critiques also Ging-Jehli et al., 2021). In this type of CPT, children with ADHD often showed more (omission and commission) errors, slower mean RTs, and greater variabil- ity in RTs than those without ADHD (Hervey et al., 2006; Huang-Pollock et al., 2006; Sergeant et al., 1999). Moreover, Epstein et al. (2011) did not find differences among ADHD presentations, but all children with ADHD had significantly slower mean RTs and lower accuracy values than those without ADHD. In contrast, Egeland et al. (2009) found that children with ADHD-I had slower mean RTs than those with ADHD-C or without ADHD.

Distinguishing between the two types of CPTs is impor- tant because some have argued that ADHD-C is linked to




![ref1]![ref2]![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.009.png)


deficits in inhibition control, while ADHD-I is linked to deficits in sustained attention (e.g., Baeyens et al., 2006; Barkley, 1997; Houghton et al., 1999). Therefore, we would expect that CPTs with frequent go trials are particular sensi- tive to the characteristics of ADHD-C while CPTs with rare go trials are particular sensitive to the characteristics of ADHD-I. However, a thorough examination of this hypoth- esis is lacking because most CPTs involve *either* frequent go trials (Conners, 2002) *or* rare go trials (Gordon, 1986; Robertson et al., 1997) but rarely both. Moreover, Ging- Jehli et al. (2021) have recently pointed out that studies are hard to compare because of differences in: (i) sample char- acteristics; (ii) definition of ADHD presentations; and (iii) task specifics. Therefore, a task that includes both, blocks with rare go trials and blocks with frequent go trials, might provide information about the cognitive characteristics of ADHD presentations.

A CPT with multiple conditions might be useful for studying the association between latent cognitive compo- nents and different ADHD presentations and comorbidities. This is because understanding how children adapt to differ- ent task conditions (e.g., transitioning from blocks with fre- quent go trials to blocks with rare go trials) provides insights into their individual mechanisms of cognitive processing (we provide specific hypotheses in section: Previous DDM Applications To CPTs in ADHD Research). For this study, we used the Integrated Visual and Auditory Continuous Performance Test (IVA-CPT). We refer to the Method sec- tion for a detailed description of the IVA-CPT. Compared to the previously discussed CPTs, the IVA-CPT allows for an assessment of *both* auditory *and* visual attention on the same task and includes blocks of *both* frequent *and* rare go trials (Sandford & Turner, 2000).

## *The Diffusion Decision Model (DDM)*
Computational modeling applications such as those with the DDM (Ratcliff, 1978) have shown that test performance can be decomposed into underlying cognitive components (e.g., response cautiousness, quality of information integration, response bias) that can be studied separately and that each have established psychological interpretations (Forstmann et al., 2016; Huang-Pollock et al., 2017; Wiecki et al., 2015). The DDM has also been successfully applied to go/no-go tasks such as CPTs (e.g., Gomez et al., 2007; Huang-Pollock et al., 2017, 2020; Ratcliff et al., 2018).

Pursuing a DDM analysis is interesting because it allows one to understand which cognitive components differ among ADHD presentations and comorbidities. A DDM analysis is more sensitive for detecting cognitive differences between ADHD presentations and comorbidity because it considers the RT distribution (rather than only mean RTs), and simulta- neously accounts for correct and error responses from differ- ent experimental conditions (Hauser et al., 2016; Montague

et al., 2012). Therefore, a DDM analysis uses more informa- tion than conventional performance measures such as mean RTs or accuracy. Moreover, the DDM (Ratcliff, 1978) has successfully accounted for the performance in (neuro)cogni- tive testing from a broad range of clinical populations such as ADHD, autism, depression, anxiety, aphasia (Pe et al., 2013; Pirrone et al., 2015; White et al., 2010a, 2010b; Zeguers et al., 2011).

The DDM is based on the most dominant theory of how people make decisions (Forstmann et al., 2016). It is pre- sumed that decisions (such as those in laboratory settings) are a result of decision-making processes that have a start- ing point and that evolve by sequentially accumulating (noisy) evidence up to a specific criterion at which time a response is initiated. A graphical illustration of the model (Supplemental Figure S1), including a description, is pro- vided in the Supplemental Material. In the following para- graphs, we describe the main DDM parameters (*a, z/a, Ter, v, dc*) that represent the cognitive components of the deci- sion-making process.

*Boundary separation (a).* Boundary separation indexes a par- ticipant’s general tendency toward cautious versus hasty responses (Ratcliff & McKoon, 2008; Voss et al., 2004). Participants with more cautious response strategies (prefer- ring accurate over fast decisions) have larger boundary separations than participants with less cautious response strategies. Generally, a larger boundary separation results in slower but more accurate responses. Boundary separation varies by the introduction of different instructions (empha- sis of speed vs. accuracy; Mulder et al., 2010), reward for accurate responses (Voss et al., 2004), or difficult condi- tions (Schmitz & Voss, 2012).

*Starting point bias (z/a).* Bias in starting point measures a participant’s a priori tendency toward go or no-go responses. Previous studies found a larger starting point bias (*z/a*) for ADHD compared to controls; particularly when interstimu- lus intervals were short rather than long (Huang-Pollock et al., 2016, 2012).

*Nondecision time (Ter).* Nondecision time represents the latency of processes outside the decision process such as task preparation, perceptual encoding of cue, and response execution (i.e., the latency from having reached a decision to pressing the response key associated with that decision). Nondecision time is longer by the introduction of task switches (Ging-Jehli & Ratcliff, 2020; Schmitz & Voss, 2012), by aging (Cohen-Gilbert et al., 2014; Ratcliff et al., 2006), and poor individual allocation of attention at the beginning of a trial (Nunez, 2015).

*Drift rate (v).* Drift rate represents the quality of integrating stimulus information. Larger drift rates represent faster and



more accurate responses, whereas lower drift rates represent slower and less accurate responses. Drift rates are lower in more difficult conditions than in easier conditions (Ratcliff & McKoon, 2008; Voss et al., 2004). Multiple studies found positive associations of drift rate with IQ and working mem- ory capacity (Ratcliff et al., 2010). Previous meta-analyses found lower drift rates for children and adults with ADHD as compared to children and adults without ADHD (Huang- Pollock et al., 2012; Mowinckel et al., 2015).

*Drift criterion (dc).* Drift criterion represents the context sen- sitivity of integrating stimulus information (e.g., Ratcliff & McKoon, 2008; Smith & Ratcliff, 2015). For instance, Smith and Ratcliff (2015) explained that changes in drift criterion measure biases in drift rates when stimulus types differ in reward rates or their relative frequency (see also: Starns et al., 2012; Kloosterman et al., 2018).

## *Previous DDM Applications to CPTs in ADHD Research*
Our study allowed us to address several limitations of past DDM applications in the field of ADHD research:

First, previous DDM applications consistently found that children with ADHD have impaired information pro- cessing (lower drift rates) than those without ADHD across a range of tasks (see for a detailed review: Ging-Jehli et al., 2021; see also Fosco et al., 2018; Huang-Pollock et al., 2017; 2020; Karalunas et al., 2018; Mowinckel et al., 2015; Nigg et al., 2018; Weigard et al., 2020). However, these studies did not account for different DSM-defined presenta- tions and co-morbid diagnoses.

Second, past model applications used neurocognitive tests that involved visual targets only. However, attention to auditory information seems important to many areas of functioning and learning. Most importantly, we predicted that different ADHD presentations show differences in auditory versus visual attention. Processing of auditory and visual information occurs in separate human brain areas (Arnott & Alain, 2011; Salo et al., 2013); and other clinical studies found that ADHD presentations differ in some of these brain areas (Fair et al., 2013; Loo et al., 2003). For instance, Fair et al. found that children with ADHD-C had, among others, atypical connectivity in the insular cortex. Functional brain imaging studies showed that the insular cortex is involved in directing particularly auditory atten- tion during cognitive tasks (e.g., Bamiou et al., 2003). Moreover, the timing and intensity of attention is more important for processing auditory rather than visual infor- mation because auditory information is temporally sequenced and of short duration (i.e., not allowing for “a second look”). To address the neglect of auditory data in previous reports, we used a Continuous Performance Test (CPT) that involved both visual and auditory targets.

Third, past DDM applications to CPTs included either blocks with frequent or rare go trials (see for a review: Ging-Jehli et al., 2021). However, based on the studies pre- viously discussed, it may be that cognitive processing of ADHD-C is particularly sensitive to blocks with frequent go trials, while cognitive processing of ADHD-I is particu- larly sensitive to blocks with rare go trials. The CPT that we used involved both blocks with frequent and rare go trials (targets).

# **Method**
## *Participants*
*ADHD sample.* One hundred fifty children<sup>1</sup> aged 7 to 10 had the baseline assessment in the International Collaborative ADHD Neurofeedback (ICAN; The Collaborative Neurofeed- back Group, 2020) randomized clinical trial (NCT02251743). Children were required to: meet DSM-5 ADHD diagnostic criteria for inattentive or combined presentation (APA, 2013) assessed with the Children’s Interview for Psychiatric Syn- dromes (Weller et al., 1999; see Instruments: ChIPS) and doc- toral clinician interview; have an IQ ≥80 assessed with the Wechsler Abbreviated Scale of Intelligence (WASI, Wechsler, 1999), have an electroencephalographic Theta/Beta-ratio (TBR<sup>2</sup>) ≥4.5 assessed with the Thought Technology ADHD Suite, and item mean ≥1.5 SD above norms on the Conners- 3rd rating scale (Conners, 2008) by both parent and teacher while off medication. As part of the baseline assessment, chil- dren performed the IVA-CPT without medication. Of the 150 children, 43 were taking medication, which they stopped for 5 days before assessment.

*Control sample.* Sixty children without ADHD (aged 7 to 10) participated in one visit to perform the IVA-CPT. The con- trols were required to meet the following inclusion criteria: absence of any DSM-5 psychiatric diagnoses, no head injury with loss of consciousness, and no current psychotherapy or physical or occupational therapy. Children were excluded if they were taking medication for seizures, mood, anxiety, or other DSM-5 disorders. Prospective participants were pre- screened for eligibility via telephone prior to coming to the visit. We additionally used the parent-rated Conners-3rd edi- tion rating scale to screen for undiagnosed ADHD and symptom severity of inattention and hyperactivity-impulsiv- ity (see Instruments: C-3:P). When analyzing the parents’ ratings on the C-3:P, we noticed that three controls had rat- ings of total ADHD symptoms above norms. We therefore excluded those three children from all analyses.

## *Instruments*
*Conners-3rd edition: Parent report long version (C-3:P; Con- ners, 2008).* The C-3:P was used to assess DSM-IV criteria



of ADHD symptoms and symptom severity. All parents completed the C-3:P and were asked to rate the frequency of child behaviors on a 4-point scale (0=not true at all, 1=just a little true, 2=pretty much true, 3=very much true). The questionnaire included 108 questions, with 21 items used to measure DSM-IV ADHD symptoms (10 items for inattention symptoms and 11 items for hyperactivity/ impulsivity symptoms). We used the T-scores of parent- rated inattention and hyperactivity-impulsivity (both DSM-5 scales) to test for differences between the ADHD sample and controls.

*Children’s interview for psychiatric syndromes -child (ChIPS) and*

*-parent (P-ChIPS; Weller et al.,1999).* The ChIPS/P-ChIPS is a structured diagnostic interview that was administered at baseline to the children in the ADHD sample to determine DSM-5-defined disorders. Comorbid diagnoses as well as ADHD presentations were taken from the ChIPS/P-ChIPS, which assessed for 20 DSM-IV psychiatric diagnoses (ADHD, ODD, CD, Substance Abuse, Specific Phobia, Social Phobia, Separation Anxiety Disorder, Generalized Anxiety Disorder, Obsessive-Compulsive Disorder, Stress Disorders [ASD/PTSD], Anorexia, Bulimia, Depression/ Dysthymia [MDD/DD], Mania/Hypomania, Enuresis, Encopresis, and Schizophrenia/Psychosis). Diagnoses of co-morbidities were given if either the child or parent endorsed criteria of the disorder. For ADHD, DSM-IV and DSM-5 criteria are identical for this age range except for a more liberal age of onset (before age 12) in DSM-5.

*Demographic questionnaire.* Parents of children with and without ADHD completed a demographic questionnaire that included questions such as the child’s sex, age, educa- tional setting, overall household income and primary care- giver’s education (Table 1). We used this questionnaire to test for socio-demographic differences between the ADHD sample and controls.

*Neurocognitive Testing (IVA-CPT 2nd edition; Sandford & Turner, 2002).* The Integrated Visual and Auditory Continuous Performance Test (IVA-CPT) is composed of 500 trials with an additional 10 warm-up and cool-down trials, respec- tively. On each trial, participants are presented with either the number “1” (go trial) or the number “2” (no-go trial). Participants are instructed to click the button of a computer mouse when the number “1” is presented (either visually or auditorily), but to refrain clicking any buttons when the number “2” is presented (either visually or auditorily). The IVA-CPT involves eight conditions, determined by: two block types (frequent vs. rare go trials), two trial types (go vs. no-go trials), and two modalities (visual vs. auditory tri- als). In blocks with frequent go trials, 84% of all trials are go trials. In blocks with rare go trials, 16% of all trials are go trials (for additional details see Supplemental Material).

The IVA-CPT was developed based on the DSM-IV-TR diagnostic criteria for ADHD (APA, 2000). It has made sig- nificant contributions to neuropsychological testing for sev- eral medical and psychological disorders for different age groups, including adults and children with ADHD (Corbett & Constantine, 2006; Moreno-García et al., 2015; Park et al., 2011; Tinius, 2003). However, different studies relied on different outcome measures with varying norms (mea- sures provided by test makers without reporting mean RTs and/or accuracy) and none of these previous IVA studies applied a DDM analysis, thus neglecting the study of under- lying cognitive components.

## *Procedure*
This research was approved by The Ohio State University's Institutional Review Board (IRB), and written informed consent and assent were obtained from parents and chil- dren. Participants were recruited through flyers posted in local community centers and elementary schools. Controls (and at least one of their parents) were invited to a one-time visit (1 hour). Parents completed questionnaires (Method section: Instrument), while their child performed the IVA- CPT on a computer in a separate room (accompanied by a research assistant). Instructions on the IVA-CPT were stan- dardized and integrated into the computerized test adminis- tration. All participants were reimbursed for participation regardless of performance.

## *Estimating DDM parameters*
*Model parametrization.* The IVA-CPT involves eight condi- tions (two block types × two trial types × two modalities) and we introduced: one value for boundary separation (*a*) for all conditions; eight drift rates; one for each trial type (go vs. no-go), modality (visual vs. auditory), and block type (frequent go vs. rare go); and four nondecision times; one for each modality and block type. We provide addi- tional explanation about model parametrization in the Sup- plemental Material and in the Supplemental Figures S2 and S3. The DDM additionally includes variability parameters (for explanations see Supplemental Material), but we focused our analysis on main parameters. All estimated model parameters can be found in the Supplemental Tables S1 and S2. **Model Fitting Procedure.** DDM parameter estimates were obtained by using a standard method (Huang-Pollock et al., 2020; Ratcliff & Tuerlinckx, 2002; Ratcliff et al., 2018) in which model parameters were adjusted to obtain a minimum value of chi-square. We explain in detail how the DDM was fit to the data of each participant in the Supplemental Material. **Goodness of Fit.** We assessed goodness of fit in different ways (as suggested by Ratcliff & Tuerlinckx, 2002; Ratcliff et al., 2018), dis- cussed in detail in the Supplemental Material. First, the


**Table 1.** Background Characteristics for the Diagnostic Groups.

||Control (*N*=57)|ADHD-I (*N*=51)|ADHD-C (*N*=99)|<p></p><p>Group comparisons</p>|
| :- | :- | :- | :- | :- |
|Mean (SD) age in years|9 (1)|8 (1)|9 (1)|Control vs. ADHD-C: ns|
|||||Control vs. ADHD-I: ns|
|||||ADHD-C vs. ADHD-I: ns|
|Number of females|26|13|22|Control vs. ADHD-C\*\*|
|||||Control vs. ADHD-I\*\*|
|||||ADHD-C vs. ADHD-I: ns|
|Co-morbid diagnoses<sup>a</sup>|||||
|Neither|0|21|23|Control vs. ADHD-C\*\*|
|ANX|0|12|16|Control vs. ADHD-I\*\*|
|ODD|0|7|30||
|Both|0|11|30|ADHD-C vs. ADHD-I\*|
|Mean (SD) *T*-scores on inattention|48 (6)|79 (8)|78 (8)|Control vs. ADHD-C\*\*|
|||||Control vs. ADHD-I\*\*|
|||||ADHD-C vs. ADHD-I: ns|
|Mean (SD) *T*-scores on hyperactivity-impulsivity|49 (7)|63 (11)|75 (12)|Control vs. ADHD-C\*\*|
|||||Control vs. ADHD-I\*\*|
|||||ADHD-C vs. ADHD-I\*\*|
|Child’s educational setting|||||
|Regular public school (*N*)|54|19|38|Control vs. ADHD-C\*\*|
|Regular public school with some special classes (*N*)|1|23|43||
|Regular private/parochial school (*N*)|2|1|5|Control vs. ADHD-I\*\*|
|Home school (*N*)|0|1|2||
|Charter school (*N*)|0|6|11|ADHD-C vs. ADHD-I: ns|
|Special school for children with developmental disabilities (*N*)|0|0|0||
|Primary caregiver’s education|||||
|High school/GED or less (*N*)|2|2|12|Control vs. ADHD-C: ns|
|Some college (*N*)|12|8|24||
|College (*N*)|21|20|39|Control vs. ADHD-I: ns|
|Advanced degree (*N*)|22|21|24|ADHD-C vs. ADHD-I: ns|
|Annual household income|||||
|Less than $23,850 (*N*)|2|4|9|Control vs. ADHD-C\*\*|
|$23,851-$50,000 (*N*)|5|8|21||
|$50,001-$100,000 (*N*)|13|22|41|Control vs. ADHD-I\*\*|
|More than $100,000 (*N*)|37|17|28|ADHD-C vs. ADHD-I: ns|

*Note.* Group comparisons for age and *T*-scores are based on contrast tests. Group comparisons for number of females, co-morbid diagnoses, child’s educational setting, primary caregiver’s education, and annual household income are based on chi-square tests. Numbers in brackets refer to SD. ns=nonsignificant.

aComorbidity group classification based on ChIPS (see Instruments): neither=neither anxiety disorders nor disruptive behavior disorders; ANX=anxiety disorders only; ODD=oppositional defiant disorders only; Both=ANX and ODD. *T*-scores on parent-rated inattention (AN) and hyperactivity-impulsivity (AH) (both are DSM-5 scales).

\*p < .05; \*\**p* < .01 (p values after correction for multiple tests).


Supplemental Table S3 shows the mean chi-square good- ness of fit values and the degrees of freedom. All the chi- square values were below the critical chi-square values, which suggests that the model fit the data well. Moreover, the fits are quite reasonable compared to previous studies that applied the DDM to other CPTs (e.g., Gomez et al., 2007; Ratcliff et al., 2018). Second, Supplemental Figure S4 illustrates plots of model predictions against data for

response proportions (i.e., accuracy) and the 0.1, 0.5, and

0\.9 quantile RTs for each condition and for each participant. Supplemental Figure S4 further demonstrates that the model fit the data well. **Alternative Model Analyses.** We also provide in the Supplemental Material the results of an alter- native model (a model with a more flexible model parame- terization) which provided poorer fits than the model introduced in the main manuscript.



## *Statistical Analysis*
We used a DDM analysis to compare the cognitive compo- nents between children without ADHD and those with DSM-5 ADHD presentations<sup>3</sup> (analysis 1); and between chil- dren with ADHD and different comorbidities (analysis 2).

We concentrated our analysis on four DDM parameters: *z/a, Ter, v, and dc* (we present all model parameters for each participant group in the Supplemental Material). In the

Introduction, we explained that our focus lay on examining how cognitive processing changes across modality (visual vs. auditory) and block type (frequent vs. rare go trials). Therefore, we averaged the drift rates for go trials and no-go trials for each block type and each modality.<sup>4</sup> This resulted in four drift rates and the larger the drift rate, the better (i.e., faster and more accurate) is the processing of the stimulus. Hence, in line with past research discussed in the Introduction, we refer to *drift rates* as *efficiency of the infor- mation integration process*. In the Introduction, we also explained that changes in drift criteria (*dc*) refers to biases in drift rates across blocks due to differences in target fre- quency (e.g., proportion of go vs. no-go trials; see: Smith & Ratcliff, 2015). Therefore, we calculated drift biases (see for further discussions: Kloosterman et al., 2018; Starns et al., 2012) by taking the difference between drift rates for no-go trials<sup>5</sup> and those for go trials for each block type and for each modality. This resulted into four drift biases (*cv*) and the larger the drift bias (deviation from zero), the more is stimulus processing dependent on the type of trial (go vs. no-go). If drift rates for go trials and no-go trials are approx- imately equally large, then this could suggest good stimulus disrimination irrespective of the stimulus type (given that drift rates are large). Hence, in line with past research dis- cussed in the Introduction, we refer to *drift bias* as *context sensitivity, the sensitivity of the information integration pro- cess to stimulus type* (*go vs. no-go*).

*For analysis 1.* We conducted two separate ANOVAs since different model parameters were kept fixed across different conditions (Method section: Model parametrization). In all ANOVAs, participant group was the between-subject fac- tor. In the first ANOVA, we tested for group-specific differ- ences in starting point bias (*z/a*). The block type (frequent vs. rare go trials) presented the within-subject factor. In the second mixed ANOVA, we tested for group-specific differ- ences in nondecision time (*Ter*), drift rate (*v*), and drift bias (*cv*). The block type and the modality (auditory vs. visual trials) presented the within-subject factors. Since hypothe- sis tests were repeatedly conducted, respective Bonferroni corrections were incorporated into all the analyses. We also used contrast tests to further examine group-specific differ- ences in main model parameters. We will specify these con- trast tests in the forthcoming sections when we introduce the results.

*For analysis 2.* We included all children with ADHD (*N*=150) and assigned them to one of four comorbidity groups based on their CHIPS/CHIPS-P diagnosis: *neither, anxiety only, oppositional defiant disorder (ODD) only*, or *both*. Table 1 shows the number of children in each comorbidity group sorted by the DSM-5 presentations ADHD-I and ADHD-C. We accounted for the effects of DSM-5 presentations in the comorbidity analysis (including it as a covariate into our analysis) since the number of DSM-5-defined presentations varied among comorbidity groups.

# **Results**
## *Sample Characteristics*
Sample characteristics are provided in Table 1. Both ADHD groups had significantly higher inattention and hyperactiv- ity-impulsivity T-scores than the controls. The two ADHD groups had similar inattention *T*-scores, but the ADHD-I group had significantly lower hyperactivity-impulsivity *T*-scores than the ADHD-C group. The controls included more girls than either ADHD group. ADHD-I and ADHD-C groups did not differ in gender composition. Comorbid diagnoses varied as a function of DSM-5 presentation. Compared to controls, children with ADHD were more likely to attend special classes or a charter school. Moreover, controls were more likely to come from upper income households than children with ADHD. There were no dif- ferences in primary caregiver’s education between children with ADHD and controls.

## *Differences between DSM-5-defined ADHD Presentations and Controls*
We analyzed differences in cognitive components between controls (*N*=57) and children with ADHD who were sub- grouped into either ADHD-C (*N*=99) or ADHD-I (*N*=51) based on DSM-5 presentation. We included sex, child’s educational setting, and annual household income as covari- ates into our analysis due to differences between controls and ADHD groups. Table 2 shows the model parameter val- ues (and corresponding test statistics) for each diagnostic group (controls, ADHD-C, ADHD-I). The Supplemental Figure S3 shows the entire RT distributions for correct and error responses across all conditions and for each of the three diagnostic groups (controls, ADHD-C, ADHD-I). We also provide additional analyses of conventional perfor- mance measures (e.g., mean RTs for correct and error responses, omission errors, commission errors) in the Supplemental Table S4.

*Tendency toward premature decisions (z/a).* Table 2 shows that the three diagnostic groups did not differ in their tendency toward premature decisions (*z/a*). All children (controls,


**Table 2.** Means, Standard Deviations, and ANCOVA Statistics for Main Model Parameters for Diagnostic Groups.

![ref1]

Control (*N*=57)	ADHD-I (*N*=51)	ADHD-C (*N*=99)	ANCOVA

|Variable|*M*|*SD*||*M*|*SD*||*M*|*SD*|Effect|*F* ratio|*p*|*df*	c2|
| :- | :-: | :- | :- | :-: | :- | :- | :-: | :- | :-: | -: | :- | :- |
|*z bias*<sup>a</sup>|**0.49**|**0.02**||**0.49**|**0.02**||**0.50**|**0.01**|G|0\.412|.663|2	0.004|
|FreqGo|0\.54|0\.03||0\.52|0\.03||0\.55|0\.02|GxB|0\.662|.517|2	0.007|
|RareGo|0\.44|0\.02||0\.45|0\.02||0\.46|0\.02|||||

||||||||||||
| :- | :- | :- | :- | :- | :- | :-: | :- | :- | :-: | :- |

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.010.png)![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.011.png)a
||||||||||||
| :- | :-: | :- | :-: | :-: | :-: | :-: | :-: | -: | :-: | :-: |
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||


![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.012.png)*er*

|FreqGo,vis|0\.34|0\.01|0\.35|0\.01|0\.35|0\.01|GxB|0\.022|0\.978|2|0\.000|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | -: | :-: | -: |
|FreqGo,aud|0\.43|0\.02|0\.46|0\.02|0\.47|0\.01|GxM|0\.199|0\.820|2|0\.002|
|RareGo,vis|0\.38|0\.03|0\.41|0\.03|0\.43|0\.02|GxBxM|1\.842|0\.161|2|0\.018|
|RareGo,aud|0\.50|0\.02|0\.50|0\.02|0\.50|0\.02||||||









*v*








*Note.* ANCOVA=analysis of variance (controlling for differences in sex, educational setting, and annual household income); presented *p*-values are not Bonferroni-corrected. For *z* bias, we applied one ANOVA with block type as within-subject variable, therefore: Bonferroni adjusted significance level equals to 0.025 (i.e., 0.05/2 conditions). For *Ter, v*, and *cv*, we applied one ANOVA with block type and modality as within-subject variable, therefore: Bonferroni adjusted significance level equals to 0.004 (i.e., 0.05/[3 parameters×4 conditions]). Significant effects are highlighted in bold. G=diagnostic groups; B=block type; M=modality. *z* bias=*z*/*a* bias in starting point; *Ter*=nondecision time; *v*=drift rate represents the average drift rates for go and no- go trials (i.e., absolute values of drift rates for no-go trials, see footnote 3 in the main text). Supplemental Table S1 illustrates the individual drift rates for go and no-go trials; *cv*=drift rates for no-go trials (absolute values, see footnote 3 in the main text) minus drift rates for go trials.

aValues averaged over block type and modality.

bContrast tests: control versus ADHD-I: *t*(204)=3.67\*\*; control versus ADHD-C: *t*(204)=5.87\*\*.

cADHD-I versus ADHD-C: *t*(204)=1.56.


ADHD-C, ADHD-I) showed a significantly greater ten- dency toward premature decisions (*z/a*: bias toward go- responses) in blocks with frequent go trials than blocks with rare go trials (Table 2).

*Deficits in task preparation and response execution (Ter).* Chil- dren with either ADHD-C or ADHD-I were slower in task preparation and response execution (*Ter*) than controls, but this difference was not statistically significant (Table 2).

*Efficiency of processes involved in information integration*

*(v).* The controls were significantly more efficient in infor- mation integration (larger *v*) than children with ADHD-C or ADHD-I (Table 2). Children with ADHD-C were nominally less efficient in information integration (lower *v*) than chil- dren with ADHD-I, but this difference was not statistically significant (Table 2).

*Context sensitivity of processes involved in information integration (cv).* We found a significant diagnostic group × modality interaction (Table 2). Figure 1A illustrates that children with ADHD-C were more sensitive to changes in presentation

modality (auditory vs. visual) than children with ADHD-I and controls (i.e., larger changes in *cv* between auditory and visual trials).

We also found a significant diagnostic group × modality

× block type interaction (Table 2). Figure 1B and C illustrate larger group differences for blocks with frequent go trials (Figure 1B) than for blocks with rare go trials (Figure 1C). For blocks with frequent go trials, we found an interesting rela- tionship: For auditory trials, children with both ADHD-I and ADHD-C had significantly larger *cv* than controls (control vs. ADHD-C; *t*[204]=-2.39, *p=*.018; control vs. ADHD-I; *t*[204]*=*-2.71, *p=*.007; ADHD-C vs. ADHD-I: *t*[204]*=*0.06,

*p=*.955). For visual trials, children with ADHD-C had signifi- cantly smaller *cv* than controls and children with ADHD-I (ADHD-C vs. control; *t*[204]*=*2.56, *p=*.011; ADHD-C vs. ADHD-I; *t*[204]*=*2.48, *p=*.014; control vs. ADHD-I: *t*[204]*=*-

0\.15, *p=*.884). Hence, presenting information visually in a context with frequent targets helped children with ADHD-C in integrating information. In contrast, children with ADHD-I did not show any sensitivity to changes in presentation modal- ity (i.e., equally large *cv* for auditory and visual trials). Rather, children with ADHD-I seemed to respond predominantly


![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.013.png)

**Figure 1.** (A) Drift biases *cv* (drift rate for go trials minus drift rate for no-go trials [absolute values; see footnote 3 in main text]) for each modality (auditory vs. visual) averaged over block type (frequent go trials vs. rare go trials). Drift bias cv represents context sensitivity of processes involved with information integration (with *cv* equal to zero representing the optimal level). Vertical lines represent the error bars (+/− 1 SE). ADHD-C was most context sensitive (largest difference in *cv* between auditory and visual trials) compared to ADHD-I and controls. For auditory trials: control had significantly smaller cv than ADHD-C; *t*(204)=−2.51, *p*=.013 and ADHD-I; *t*(204)=−2.33, *p*=.021. The difference between ADHD-C and ADHD-I was not significant; *t*(204)=0.18, *p*=.855. For visual trials: control had significantly larger cv than ADHD-C; *t*(204)=2.27, *p*=.024. The difference between ADHD-C and ADHD-I was not

significant; *t*(204)=1.80, *p*=.073. The difference between control and ADHD-I was also not significant; *t*(204)=0.35, *p*=.729. Figure 1. (B and C) drift biases *cv* for each modality, block type, and diagnostic groups. Vertical lines represent the error bars (+/− 1 SE). Positive *cv* means that go trials had higher (faster and more accurate) drift rate than no-go trials; negative *cv* means no-go trials had higher

drift rate than go trials. For visual trials from the blocks with frequent go trials: ADHD-C had significantly smaller cv than control;

*t*(204)=2.56, *p*=.011 and ADHD-I; *t*(204)=2.48, *p*=.014. The difference between control and ADHD-I was not significant; *t*(204)=−0.15, *p*=.884. For the blocks with rare go trials: there were no statistically significant group differences; all *p*>.227.For auditory trials from

the blocks with frequent go trials: control had significantly smaller *cv* than ADHD-C; *t*(204)=−2.39, *p*=.018 and ADHD-I; *t*(204)=−2.71, *p*=.007. The difference between ADHD-C and ADHD-I was not significant; *t*(204)=0.06, *p*=.955. For the blocks with rare go trials: differences between diagnostic groups did not reach statistical significance; all *p*>.284.


“go” to most trials (i.e., large positive *cv* indicating a large drift rate for go trials and a low drift rate for no-go trials).

Comparing how *cv* changed across block types showed another interesting relationship: For blocks with frequent go trials (presumed to tax inhibitory control), processes involved in integrating *auditory* information were most sen- sitive, while in blocks with rare go trials (presumed to tax sustained attention), processes involved in integrating *visual* information were most sensitive.
## *Differences between Comorbidity Groups and Controls*
We tested for comorbidity-specific cognitive differences among children with ADHD, above and beyond the effects of DSM-5 presentations discussed before (Method section: Statistical Analysis 2). Table 3 shows the model parameter values (and corresponding test statistics) for each comorbid- ity group (neither, anxiety only, ODD only, both). We also provide additional analyses of conventional performance


**Table 3.** Means, Standard Deviations, and ANCOVA Statistics for Main Model Parameters for Comorbidity Groups.

![ref1]

Neither (*N*=44)	ANX (*N*=28)	ODD (*N*=37)	Both (*N*=41)	ANCOVA

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.014.png)![ref3]![ref3]![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.016.png)![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.017.png)

Variable	*M	SD	M	SD	M	SD	M	SD*	Effect	*F* ratio	*p	df*	c2







||||||||||||||
| :- | :-: | -: | :-: | -: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||

![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.018.png)*er*

















*v*








*Note. C*omorbidity group classification: Neither=neither anxiety disorders nor disruptive behavior disorders, ANX=anxiety disorders only; ODD=oppositional defiant disorders only, Both=ANX and ODD. ANCOVA=analysis of variance (controlling for differences in DSM-5-defined presentations. We did not find any significant ADHD presentations by comorbidity interactions.); C=comorbidity group; B=block type; M=modality. *z* bias=bias in starting point; *Ter*=nondecision time; *v*=drift rate represents the average drift rates for go and no-go trials (i.e., absolute values of drift rates for no-go trials, see footnote 3 in the main text). Supplemental Table S1 illustrates the individual drift rates for go and no-go trials; *cv*=drift rates for

no-go trials (absolute values, see footnote 3 in the main text) minus drift rates for go trials.

aValues averaged over block type and modality; Presented *p*-values are not Bonferroni-corrected. For *z* bias, we applied one ANOVA with block type as within-subject variable, therefore: Bonferroni adjusted significance level equals to 0.025 (i.e., 0.05/2 conditions). For *Ter, v*, and cv, we applied one ANOVA with block type and modality as within-subject variable, therefore: Bonferroni adjusted significance level equals to 0.004 (i.e., 0.05/[3 param- eters×4 conditions]). Significant effects are highlighted in bold.

1Contrast tests (with Bonferroni adjustments) for changes in model parameters across block types. Group comparisons: 1. neither vs. anxiety only (for *z: t*[146]=0.07; for *z bias: t*[146]=−0.07). 2. neither vs. ODD only (for *z: t*[146]=−0.66; for *z bias: t*[146]=−0.79). 3. neither vs. both (for *z: t*[146]=−3.27; for *z bias: t*[146]=−3.16). 4. anxiety only vs. ODD only (for *z: t*[146]=−0.65; for *z bias: t*[146]=−0.63). 5. anxiety only vs. both (for *z: t*[146]=−2.96; for *z bias: t*[146]=−2.72). 6. ODD only vs. both (for *z: t*[146]=−2.48; for *z bias: t*[146]=−2.25).


measures (e.g., mean RTs for correct and error responses, omission errors, commission errors) in the Supplemental Table S5.

*Tendency toward premature decisions (z/a).* Table 3 shows that the four comorbidity groups differed in their tendency toward premature decisions (*z/a*; significant block type × comorbidity group interaction). Figure 2 illustrates that all four comorbidity groups showed increased tendency toward premature decisions (*z/a*: bias toward go-responses) in blocks with frequent go trials compared to blocks with rare go trials. However, the ADHD group with both co-morbid anxiety and ODD (group: *both)* had a significantly larger tendency toward premature decisions than the other three comorbidity groups (Table 3).

*Deficits in task preparation and response execution (Ter).* Table 3 illustrates that the four comorbidity groups were similarly fast in task preparation and response execution (*T*er).

*Efficiency (v) and context sensitivity (cv) of processes involved in information integration.* The four comorbidity groups showed similar efficiency in information integration (*v*) as well as context sensitivity information integration to go ver- sus no-go stimuli (*cv*).

# **Discussion**
This is the first study to examine clinical associations of distinct cognitive components with DSM-5-defined ADHD presentations (analysis 1) and comorbidity groups (analysis 2) using a computational modeling approach (i.e., DDM).

Our results suggest important differences in specific cognitive components among ADHD presentations and between children with different comorbidities. These find- ings provide insights regarding heterogeneity of cognitive characteristics among children with ADHD (Kofler et al., 2017; Nigg et al., 2005). Specifically, examining differ- ences between controls and ADHD presentations, we found




![](Aspose.Words.ae5ce956-2cef-4dd0-8a71-d2f69a05cc3a.019.png)

**Figure 2.** Starting point bias (*z/a*) for each block type and comorbidity group (neither, anxiety disorders only [ANX-only], oppositional defiant disorder only [ODD-only], both).

Black bars=starting point bias for blocks with frequent go trials minus starting point bias for blocks with rare go trials. Vertical lines represent the error bars (+/− 1 SE).


that controls had, on average, a significantly better quality of information integration (larger *v*) than children with ADHD-C or -I. This means that controls had faster and more accurate processing than those with ADHD for both visual and auditory stimuli. Previous studies that used other CPTs (with visual trials only) and that often focused on children with ADHD-C are consistent with our finding (Huang-Pollock et al., 2017, 2012; Mowinckel, et al., 2015). We extend past research by using the IVA-CPT (with both auditory and visual trials) and finding a significant diagnostic group × modality interaction. Specifically, chil- dren with ADHD-C were more sensitive than those with ADHD-I and controls to whether stimuli were auditory or visual (Figure 1A: larger changes in *cv*). These results could be important for educational strategies regarding the most useful modality for presentation of educational materials: in a context with frequent targets (go stimuli), presenting them visually rather than auditorily helped particularly children with ADHD-C to achieve faster and more accurate process- ing. One may speculate that a context with frequent target stimuli is more engaging, but also more demanding, and presenting material visually rather than auditorily helped children with ADHD-C to integrate information better (per- haps by allowing them to “take a second look”). However, further studies are needed to assess to which extent these

results generalize.

In a context with rare target stimuli, presenting informa- tion auditorily rather than visually helped children with both ADHD-C and ADHD-I to achieve faster and more accurate processing. This conclusion is evidenced by smaller drift

biases (decreased sensitivity of information integration to go vs. no-go stimuli, suggesting robust information integration) for auditory than visual trials and similar drift rates (effi- ciency of information integration) for auditory and visual trials. One may speculate that a context with rare target stim- uli is more boring and presenting material auditorily rather than visually helped children with ADHD to stay on the task (with all *v* being higher compared to those of the blocks with frequent go trials). Conversely, perhaps the rarity of go stim- uli in the blocks with rare go trials makes the go stimuli “stick out” and appear novel/interesting. However, further studies are needed to assess to what extent these results generalize.

A few studies examined the cognitive characteristics of DSM-defined ADHD presentations in other CPTs (with fewer conditions than the IVA-CPT), but without a DDM analysis. Their results remained mixed (e.g., Collings, 2003; Epstein et al., 2011). For instance, Collings (2003) administered a CPT to children with ADHD-C, ADHD-I, and controls. He found that ADHD-C made significantly more omission errors than ADHD-I and controls. In con- trast to the results found by Collings (2003), Epstein et al. (2011) did not find significant differences between DSM- defined ADHD presentations; neither in the number of omission and commission errors nor in the mean RTs. Both studies relied on a CPT with only visual trials and with only blocks of rare go trials. We also did not find any significant differences between DSM-defined ADHD presentations for blocks with rare go trials; a result further consistent with Lin et al. (2017)’s findings discussed in the Introduction. However, for blocks with frequent go trials, we did find that DSM-defined ADHD presentations significantly differed in their ability to respond to auditory relative to visual trials (as reflected by the previously discussed finding that ADHD-C, more so than ADHD-I, processed auditory stim- uli slower and less accurately than visual stimuli). *Our find- ings highlight the importance of cognitive tests with multiple conditions because our results show that clinical associa- tions appear when we examine how cognitive components change across conditions.*

Accounting for different co-morbid disorders (above and beyond DSM-5 ADHD presentations), we found that doubly comorbid children with ADHD (with both ODD and anxiety disorders) showed a significantly increased tendency toward premature responses (larger *z/a*) for blocks with frequent go trials (relative to blocks with rare go trials) than children with ADHD and anxiety only, ODD only, or no co-morbid disor- der. This finding highlights the confounding effect of “comor- bidity load,” suggesting additional biases in cognitive processing with double comorbidity. One may speculate that the larger shifts in starting point bias (*z/a*) due to transitions between block types in children with ADHD and double comorbidity highlights their tendency to overly adjust prior expectations (about what follows next) in response to



contextual changes. Overly adjusting expectations can be a blessing in some contexts, but a curse in other contexts, and raising awareness of such biases in an individual’s decision- making process could be an important target of cognitive behavioral therapy (CBT). Specifically, our results suggest that treatments are needed that help children with both ODD and anxiety disorders to overcome response biases, avoiding making premature conclusions. One might speculate that a synergism of anxiety and oppositional-defiant tendencies could lead to a cognitive stance like “I expect them to try to fool me, but I’m on guard and will outsmart them by adjusting my responses when they try to trap me with a change of rules.” Strengths of this study include the large sample of chil- dren with ADHD and the application of a cognitive task that involves multiple conditions. However, limitations include the administration of only one cognitive task. Future studies could administer a battery of cognitive tasks and apply a hierarchical DDM analysis to those tasks to examine the generalizability of DDM results to other tasks. Moreover, the clinical sample in this study did not include other fre- quent co-morbidities associated with ADHD, such as autism spectrum disorder, and thus is not representative of the whole child mental health clinical population. Some of our findings are restricted to children who had a diagnosis of ADHD and who had an electroencephalographic TBR of at least 4.5 (see for details Method section: Participants). Seventy-seven percent of all prospective participants Meeting DSM-5 ADHD criteria met the TBR inclusion cri- terion. While our results provide insights into the cognitive characteristics of different DSM-5 defined presentations and comorbidities, the question remains how fine-grained a subgroup analysis should be. The more specific and smaller the subgroups, the larger the risk that results are not gener- alizable. In this study, the children with ADHD had co-mor- bid anxiety disorders and/or oppositional defiant disorders which led to a relatively small subgrouping (i.e., four comorbidity groups: ADHD+anxiety, ADHD+ODD, ADHD+anxiety+ODD, or ADHD-only). In a sample with a larger variety of co-morbid diagnoses, one sensitive approach could be to group comorbid diagnoses into exter- nalizing and internalizing disorders. Finally, we focused our analysis on differences between DSM-defined presenta- tions and co-morbid diagnoses. Future studies should also focus on a dimensional perspective of ADHD by examining how DDM model parameters relate to symptom severity of inattention and hyperactivity-impulsivity (see for further discussions: Coghill & Sonuga-Barke, 2012; Ging-Jehli

et al., 2021; Salum et al., 2014).

## *Conclusion*
Our results suggest that neurocognitive testing, in conjunc- tion with computational models, can be used to index differ- ent cognitive patterns distinguishing ADHD presentations

from controls and from each other and distinguishing comorbidity effects. Moreover, we showed that a CPT with multiple conditions, in conjunction with a computational modeling analysis, adds important insights by helping to characterize and quantify biases in distinct cognitive com- ponents. Identification of the underlying latent cognitive components of different ADHD presentations and co-mor- bid diagnoses could help to select and design treatments tailored to the needs of different individuals with ADHD.

### **Acknowledgments**
N.R. Ging-Jehli thanks SNSF for support of her graduate studies. She also thanks: Russ Childers for insightful discussions; Roger Sandford for the neurocognitive tests; Roger Ratcliff for providing access to modeling; Catherine Panchyshyn, Rachel Bergman, Arielle Cottrell, Alex Lingel, Madeline Thomas, Shea Connor for invaluable help with data collection.

### **Declaration of Conflicting Interests**
The author(s) declared the following potential conflicts of interest with respect to the research, authorship, and/or publication of this article: N.R. Ging-Jehli received research funding from SNSF and neurocognitive tests from testmakers. L.E. Arnold received research funding from Curemark, Forest, Lilly, Neuropharm, Novartis, Noven, Shire, Supernus, Roche, and YoungLiving (as well as NIH and Autism Speaks), has consulted with Gowlings, Neuropharm, Organon, Pfizer, Sigma Tau, Shire, Tris Pharma, and Waypoint, and been on advisory boards for Arbor, Ironshore, Novartis, Noven, Otsuka, Pfizer, Roche, Seaside Therapeutics, Sigma Tau, Shire. M.E. Roley-Roberts has no potential conflict of interest pertaining to this Journal's submission. R. deBeus received research funding from NIMH; he is on the Board of Directors for the International Society for Neurofeedback and Research and has a clinic in NC where he performs neurofeedback and other clinical services.

