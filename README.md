# Reanalysis of Kirsch's 23-08-27 survey

## 1 Summary

Steve Kirsch ran a survey on # of COVID infections [off his substack](https://kirschsubstack.com/p/how-many-times-have-you-had-covid). Steve then [published his analysis](https://kirschsubstack.com/p/vaccinated-people-are-over-2x-more) and [made the full dataset available](https://airtable.com/appcRtVQP2AblbiWD/shrfWf7WyJsXS8cxV/tblTbdsvLJWU0dIWu).

Steve claims the vaxxed were over 2X more likely to get COVID than the unvaxxed. He claims risk of hospitalization is the same regardless of vax. He said 
>The CDC lied, people died. If you disagree, please post your row-level data survey results.

I think the CDC lied and people died too, and am happy to disagree with his other conclutions with his own "row-level" data survey results. I use his own data set and anecdotes from the particicants to show [anecdotes often paint a more accurate picture than gamed suveys.](https://x.com/stkirsch/status/1722150927883514103)

## 2 Anecdotes
## 2.1 Testing

What does “have you had COVID” mean? 

As 1538 puts it:
>I cannot answer the 'how many times have I had COVID?' question meaningfully, as (a) the symptoms that 'define' it are too subjective and overlap with 'flu/colds too much, so I do not know how accurately to distinguish it and (b) the PCR/LFD tests have no scientific basis for them.  I had one period of illness Dec 2019 which had some unusual symptoms and 3 or 4 other cold-type illnesses which I cannot tell were 'COVID' or not.

I cannot speak to the accuracy or lack thereof for the PCR/LFD.

578:
>How would anyone KNOW they had covid? 1) the PCR test is bogus, as Kerry Mullis made clear before his untimely death; 2) after reading/watching Dr. Samantha and Mark Bailey's and colleagues work, one must conclude there are no viruses--or alternatively refute them. 

61 is a little aggravating. 
>I show I have covid antibodies but I never tested positive or ever felt sick like I had covid.  So I must have had it at some point, but never was aware I ever had it.

That sure sounds like they had covid at least once if the antibody test is to be believed, but they didn’t mark that they had covid even a single time. Antibody test +, No symptoms, Marked 0 cases


## 2.2 Symptoms

### Asymptomatic covid

108 said
>Twice, I have had COVID like symptoms, but tested negative both times.

Also 16:
>Barely even knew I had it. Only aware cause those around me were sicker and testing

76, another reason not to believe this data:
>As far as I’m concerned it’s just the seasonal flu. No big deal. I only tested due to the insistence of a paranoid roommate I had at the time.

They marked having covid 4 times, but not only is it unclear if they ever had covid as opposed to the flu it is also unclear if the test result for covid was even positive.

347 marked that they had not had covid but that
>I had an antibody test that came back positive once but I've never been sick.

### Symptomatic

281 says
>Might have had Covid in January 20 20. This was before it was announced. The symptoms were unlike anything I’ve ever had in my 74 years was tested for antibodies but had none for months later.

They didn’t mark that they had covid even a single time. They had the symptoms but the antibody test was negative. Antibody test -, Symptoms, Marked 0 cases

114 said
>I have never taken a Covid test so I don’t know if I officially had Covid. However, in late 2021 I have a bad cold, resulting in losing my sense of smell.

And marked that they did not have covid

And 128 said 
>I BELIEVE I had Covid. I never took a test. I had loss of smell & taste which I had never experienced before so I assumed it was Covid. I was also in close contact to a family member who DID test positive for it.

And marked that they did have covid

190 marked that they had covid once but said:
>Only one positive covid test, but based on the gut dysbiosis after an infection months before, I may have had it then also.  Both times treated with IVM and other FLCCC protocol, but the November infection (tested positive at the ER b/c home test was negative so thought it was influenza) left me with long-covid which I continue to treat.

Hard to interpret this

341 displays an issue with this my rather simple method of searching through the notes for instances of test as they come up from “latest”. Along with false positives like this, there are sure to be false negatives, such as if someone said they “verified through antigen” for example would not contain the word test. They also highlight a key shortcoming of the survey What does vax level even mean?:
>I’m 54 years old, so I have had whatever childhood vaccines were typically given in that era/at that time. I haven’t taken the shingles vaccine or any of the la**test** recommendations for middle aged people. 

## 2.4 "General vax level"


1063 marked that they are .25 vaccinated but said:
>Not "vaccinated" growing up but unfortunately having joined the U.S. Army I received a whole slew of them upon enlistment (~1997) and received the 1st of a 5 shot Anthrax "vaccine" series while in Afghanistan…

393 kills me. Marked that they had c19 but says:
>I've been exposed - spent weekends with - family and friends who tested positive for COVID yet never got it.

1090 helps elucidate the issues with claiming efficacy of any particular protocol:
>I stopped testing for covid in 2022, so I could have had it. But I got well quickly using Dayquil and Nyquil.



## 2.3 "Long COVID"

# 3 Re-analysis

Steve compares the "general vax compliance" numbers instead of the COVID vax compliance numbers. They are not equivalent but he uses the phrase "the vaccine" which muddles things. 

He included "No Answer". "No Answer" doesn't mean "0".

He compared the “No vaccines at all” vs. the “High” and “Very high” groups. He didn't compare “No vaccines at all” vs. any % vaccine

General issues with survey interpretation as clarified below.

After going through his data, the vaxxed (for COVID) and tested participants reported an avg of 1.1 cases while the unvaxxed and tested reported an avg of 1.2 cases. This has the vaxxed about 10% less likely to get COVID than the unvaxxed. 

Even if you look at "any general vax" compaired to "no general vax", in participants who mentioned testing and not testing, the average # of cases was nearly identical. There was a difference in the averages of less than 0.01 cases...

Participants who tested reported 1.6x more covid cases than untested. 

![plotly sankey kirsch v2](https://github.com/amaddeus/punished-kirsch/assets/65098643/0856ba2e-45b0-4301-a512-008e605e5bcd)

### Steve kirsch did his analysis at 16736; so will I. 

He claimed
>I am writing this at the 16,736 mark in the database. The database may be gamed after this.

But his analysisactually starts at 16806

To start at the beginning,

>How many separate COVID injections did you take?

was not a required answer. 

>How many TOTAL times have you had COVID? If you cannot remember, pick the closest number to what you recall

was also not a required answer. 

25 people removed for not recording how many times they had C19. 
>885, 969, 1181, 1538, 2149, 5668, 5925, 6281, 7721, 9333, 9370, 9844, 10050, 10973, 12069, 12075, 12381, 12670, 12814, 12860, 14761, 14916, 15376, 15388, 16029

43 people removed for not recording how many times they had separate COVID injections. 
>460, 551, 647, 790, 1196, 1217, 1613, 2058, 3319, 3442, 3511, 4662, 4721, 5095, 5214, 5518, 5839, 6337, 6597, 7010, 7329, 7391, 7687, 7852, 7969, 8296, 8476, 8591, 8707, 8812, 9009, 9386, 10028, 10118, 10747, 11164, 11558, 11719, 12586, 12621, 13453, 14003, 14409

Also, this is not a representative sample of the population.
As 6597 puts it:
>...I used to clean your carpets…

Who are the sorts of people who respond to a Steve kirsch survey?

9954 people wrote notes.
