# Overview

This repository contains raw data, questionnaires, and information for surveys I conducted on the Dartmouth College student body from the Spring 2016 to Spring 2018 terms, as part of my work for _The Dartmouth_ (The D) student newspaper. I initially wrote up results in various articles (a link to them can be found [here](https://www.thedartmouth.com/search?a=1&o=date&ty=article&au=Alexander+Agadjanian)). Although my main interest was the political attitudes of students, most surveys covered other student and campus topics.

The `surveys` folder contains sub-folders for each individual survey I ran, and within them are an accompanying questionnaire and survey dataset. The below table of contents describes describes asked in each survey. I also provide a few details on the process of sampling and weighting below.

# Survey Sampling and Weighting

To survey students, I contacted them through email with Qualtrics survey links from an official newspaper account, drawn from an internal list of all student body email addresses. I typically sent two email requests for any given survey in the field, and recorded responses for about a week after the initial request (through informal testing and knowledge of campus life, Sunday and Tuesday/Thursday nights were determined as the best times to solicit responses).

Starting with the "Election, 2016 fall" survey, I generated survey weights for the data (in the data posted here, weights are not included as a field for earlier surveys). Weighting was done in two rounds. Using administrative data from the College’s Office of Institutional Research and other sources, responses were first weighted by Greek affiliation for all eligible students (i.e. excluding freshmen, who cannot join Greek houses). Responses were then weighted for all students by class year, gender, and race/ethnicity, with international student status and varsity athlete status being added later to the weighting process. Iterative post-stratification (raking) was the method used for [weighting](http://www.miacosta.com/blog/creatingpost-stratificationweightsinr), done with the [“survey” package in R](https://cran.r-project.org/web/packages/survey/survey.pdf).

# Table of Contents
**Senior Survey, 2016 spring**:

- sexuality, GPA, legacy status, financial aid (+ regular demographics), ideology, party identification, favorability ratings (Clinton, Bernie, Trump; school admin., school president, on-campus BLM, The D, Dartmouth Review, etc.), 2016 election vote intention, graduating in debt/amount, satisfaction with Dartmouth education/other school experiences, alcohol/drugs/sex frequency, hours of sleep, Dartmouth Seven, post-graduation state of residence/plans, area of work after graduation/salary, desired area of work in 10 years
 
**Survey 1, 2016 summer**: 

- school president job approval, favorability ratings (recent Greek house derecognitions, ending need-blind admission for internationals, etc.; Divest Dartmouth, on-campus publications, etc.), support level for on-campus and national BLM movements, recent BLM demonstrations and "Blue Lives Matter" response, recent high-profile tenure denial, retention of faculty of color, presence of Greek life (eliminated, stay the same, etc.), corporate/consulting recruitment on campus, free speech, following traditions

**Survey 2, 2016 summer**:

-party identification, ideology, Obama approval, 2016 election vote intention, favorability ratings (Clinton, Trump, Johnson, Stein), motivations for vote choice, perceived most likely outcome of election, issue importance, primary vote choice

**Sex Life, 2016 fall**:

- what do you consider a "hook up," age of losing virginity, number of sexual partners in your life, honesty with parents/friends about your sex life, how often you masturbate, sexual experiences

**Housing, 2016 fall**: 

- new housing system favorability, new housing system events attendance

**Traditions, 2016 fall**: 

- valuing and closely following traditions, playing pong, parts of Dartmouth Seven completed, favorite big weekend, Dartmouth challenges (e.g. Lou's), awareness of Dartmouth Charter mission, favorite/least favorite traditions

**Careers, 2016 fall**: 

- career plans before and after coming to Dartmouth

**Election, 2016 fall**: 

- likelihood to vote and vote choice in 2016 election, voting motivations (for/against Clinton/Trump), satisfaction with candidate options, own ideology and perceived ideology of Clinton/Trump, feelings about the campaign, party identification

**Political Beliefs, 2016 fall**: 

- own ideology, guesses about % of students who are liberal/conservative, Dartmouth's traditional political leanings in the past

**Religion, 2016 fall**: 

- classes/dining interference with religious observances, religious affiliation

**Community Issues, 2017 winter**: 

- feeling connected to campus social life and to town of Hanover, involvement with and closeness to Greek houses, perceptions about exclusivity of Greek life and the size of its presence on campus, Living Learning Communities (LLCs), international students community and how well integrated they are

**Social Programming, 2017 winter**: 

- impact of social programming events on your time at Dartmouth, participation in and perceptions of events, alternative social spaces to Greek life on campus

**STDs, 2017 spring**: 

- sexually active, condom use, ever gotten an STD/STI or know someone that did, STDs/STIs effect on sexual activity, health services and STDs/STIs, talking about STDs/STIs among students

**Awakening, 2017 spring**: 

- planned college major consistency, priorities in class selection (practical knowledge vs. pure intellectual interest, easiness vs. interest), socioeconomic status on campus (own SES, others', SES diversity, effect on student relations), religion (own religion, importance of religion, spritual vs. religious)

**Politics, 2017 spring**: 

- right direction/wrong track, comfort with roommate with opposing political views, allow speakers to talk on campus (e.g. Charles Murray, Mitt Romney, Richard Spencer, etc.), governemnt financial regulations, raising taxes on the wealthy, Trump job approval, importance of issues, [FIRE scale](https://www.christopherdesante.com/wp-content/uploads/2018/08/dsFIREapsa18.pdf), increasing diversity in US, party identification

**Senior Survey, 2017 spring**: 

- favorability ratings (school president/dean/provost/admin., Dartmouth Dining Services, College Dems/Reps, on-campus BLM, faculty, Moving Dartmouth Forward), support/oppose (AD/SAE derecognition, Phiesta cancellation, Freedom Budget, pledge term abolishment; Trump, Clinton, Wall Street, major parties, Sununu, etc.), hard alcohol ban, desired role of admin. in student life, sexual assault prevention efforts/resources, post-grad donation in light of admin/controversies, importance to time at Dartmouth (academics, social life, Greek life, extracurriculars, etc.), alcohol/drugs/sex, substance use (marijuana, tobacco, cocaine, LSD, study drugs), Dartmouth Seven, 2016 election impact (more likely to run for office, work in politics, join protests, consume news), own ideology before vs. after Dartmouth, post-grad plans/salary, desired field in 10 years, sexual orientation before vs. after Dartmouth

**Freshman Issue, 2017 summer**: 

- how many friends met during freshman year, where friends were met (residence halls, parties, etc), "firsts" during freshman year (alcohol, sex, marijuana, drugs, study drugs), frequency of party-going, missing home, regrets about coming to Dartmouth, all-nighters, freshman year workload, freshman class experiences

**Homecoming, 2017 fall**: 

- Dartmouth's uniqueness and school qualities, increasing size of student body, importance of US News rankings, Good Samaritan Policy

**Politics, 2018 spring**: 

- relations with students with opposing beliefs (befriend, date, work/study with, trust them), losing friends because political disagreement, professor ideology and course selection, how often politics are brought up (classes, with friends, in clubs/organizations), free speech (how secure, positive vs. open learning environment, campus climate prevents people from saying things), party identification

**Senior Survey 2018 spring**: 

- favorability ratings (president, admin., faculty, etc.; #MeToo movement, Trump, Wall Street, Supreme Court, news media, etc.), hard alcohol ban, role of admin in student life, Greek system in better vs. worse shape over last 4 years, sexual assault prevention, mental health resources, faculty diversity during recruitment/tenure granting, factors influencing choice of major, importance to social life (Greek life, clubs, house communities, etc.), first time (alcohol/drugs/sex), substance use, number of people dated at Dartmouth, how many of closest friends share same political beliefs, ideology before vs. after Dartmouth, post-grad plans and role of family's financial situation, financial assistance for living expenses from parents after graduation, sexual orientation before vs. after Dartmouth