# Justin_CER
CER Smart Meter Project by Irish Social Science Data Archive

#Notes on Documentation and Paper Reading

##Background


####[CER Customer Behavior Trial][dl], by ISSDA

[dl]: http://www.ucd.ie/issda/data/commissionforenergyregulationcer/#

1. *Electricity Customer Behaviour Trial*:
During 2009 and 2010, with over 5,000 Irish homes and businesses
![Elec Time](https://github.com/justinishere/Justin_CER/blob/master/markdown/time1.png)




2. *Gas Customer Behaviour Trial*:	During 2010 and 2011 with nearly 2,000 Irish homes.
![Gas Time](https://github.com/justinishere/Justin_CER/blob/master/markdown/time2.png)



--------

##Folders of 'CER Electricity March 2012'
#### Check out the 'Manifest' word file, *important*

#####(1)	Smart meter read data: 
* 6 zip files, each around 1 million records
* Units are 30 minute interval (in kW), then multiply 0.5 hour. Thus **all kwh records in the should be divieded by 2**

#####(2)	Pre and post trial residental surveys:
* Pre: about 100 questions, 4200 answer participants, ID_survey=IDmeter
* Post: about 120 questions, 3400 answer participants

#####(3)	Pre and post trial SME surveys:
* Pre: about 80 questions, 330 answer participants
* Post: about 120 questions, 288 answer participants


#####(4)	Allocation Excel file (.csv and .xlsx)
* a graph showing the details of tariff price added to .xlsx
* In the surveys we can also know which ID is control/treatment group, and what tariff+stimulus taken, **but this file is more accurate**






------------


##Folder of 'CER Gas October 2012'
#### Check out the 'Manifest' word file, *important*

#####(1)	Smart meter read data: 
* 78 Excel files, each 0.5 million records

#####(2)	Pre and post trial residental surveys:
* Pre: about 130 questions, 1360 answer participants
* Post: about 200 questions, 1200 answer participants
*  ***A quick view of survey questions: in the order of the file***
  * Segmentation: gender, age (7 groups), employment,social status(A,B,C1,C2,D,E,F), family members+children, rent/own
  * Attitude: if willing to change, if thinking this project important, etc.
  * Behavior: 
     - Q 470 how to heat home, 
     - Q 54192 and 47031 if they know the rates are changing
     - Q 54131 household change behavior or not
     - Q 5414 if bill, overall usage % changes, peak hour
     - Q 5419 tarrif
     - Q 5420 5-7pm factors
     - Q 6022 monitor
     - Q 6520 Statement
     - Q 6601 OLR


#####(3)	Allocation Excel file 
----------

##Folder of 'Documentation'
###1. cer09163: 
Talked in detail of Domestic ToU ***tarrif*** (A,B,C,D), weekend tarrif (W), and genertal perpose tarrif(A,B)
![tarrif small](https://github.com/justinishere/Justin_CER/blob/master/markdown/tarrif.png)
###2. cer11080: For Electric trial
* This file is the conclusion of cer11080(a), cer110080(b), cer11080(c). Cer11080(a) also has (a)(i) and (a)(ii). These files can all be Google found.
* The structure of cer11080: 
     * 2.0. Underlining technology: not something we care about
     * 3.0. CBT key findings: Eg. reduce overall electricity usage by 2.5% and peak usage by 8.8%; reducing peak usage with a peak shift of 11.3%; 82% of participants made some change to the way they use electricity due to the Trial with 74% stating major changes were made by their households
        * Family members, No. of children are important
        * Different tarrifs are not so effective, difference in stimulus is
        * **In the Excel of post survey we have a list of: OLR (58% recalled using), IHD, Statement 1, Statement 2(per month or bi-month; different from bill), Tarrif, stimulus**
     * 4.0. Cost-benefit analysis:  net present value (NPV) of the project in 2011    
![NPV](/Users/wangweizhi/Desktop/ISSDA-CER/markdown/npv.png)
     * 5.0. Future steps


###3. cer11080(a): 
####11080(a)(i): ***very important***, every detail of how the electric trial is designed, and how data analyzed. Begin reading from  *6.0. :Approach to Data Analysis* Some take aways- 

* Detect a minimum effect of a 2% change in usage over the whole sample of participants and between Tariff A and Tariff C. A change of 3% would be detected at the level of Tariffs B and D and the DSM stimuli and a reduction of 4% would be detected at a Tariffs A and C and at a cellular level. A 90% confidence level is applied to all tests conducted.

![Stimulus](https://github.com/justinishere/Justin_CER/blob/master/markdown/stimulus.png)


* Distribution of the data
![frequency](https://github.com/justinishere/Justin_CER/blob/master/markdown/frequen.png)
![mean](https://github.com/justinishere/Justin_CER/blob/master/markdown/mean.png)



* The way they show % change: Rt and Rc: (Page 60). They looked at Rt-Rc as the % decrease

![ratio](https://github.com/justinishere/Justin_CER/blob/master/markdown/ratio.png)

* P65-P93, Residental key results. For example, **based on the above defined ratio, we have the following % decrease**; also the segmentation results. After P94 is SME key results.

![% decrease](https://github.com/justinishere/Justin_CER/blob/master/markdown/decrease.png)
![segementation](https://github.com/justinishere/Justin_CER/blob/master/markdown/segment.png)





-----------------
####11080(a)(ii): More data-analysis method(P21~28)+ visualization, *important*
* A2.2 talks about the hypothesis test, 90% confidence level
* ***Missing data***: (zero usage being recorded). Specifically, data is missing for a single day of the study for 114 meters and for two days for 42 meters. **4225=4069+114+42**, and there should be around 700 meters missing all the records.

* P26 defined Night, Day, Peak time. P27 verification of sum. **P30 gives Tp test between ratios**  
![sum](https://github.com/justinishere/Justin_CER/blob/master/markdown/sum.png)
![t](https://github.com/justinishere/Justin_CER/blob/master/markdown/t.png)
![p](https://github.com/justinishere/Justin_CER/blob/master/markdown/p.png)
* The rest pages are detailed results of segementations, focus group, Pre and Post-survey analysis


###3. cer11180, cer11180a, cer11180b: For Gas trial
-------------------









