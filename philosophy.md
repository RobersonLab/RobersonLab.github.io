---
title: Lab Philosophy
layout: page
description: Expectations and lab philosophy
---

<h1 id="h1nopad">General Expectations</h1>
<h2>Balancing your life</h2>
Life isn't neatly compartmentalized into work and home. Your life includes both parts, and you have to figure out how to juggle them. This isn't a job where you need to come in and punch the clock. You will have greater day-to-day flexibility than many other professions. I generally expect people to be here approximately normal business hours during the week. Depending on the type of experiments you are running and approaching deadlines you may have to stay late, come in early, or work at home. That's the nature of this job. Find the right balance that fits our lab culture and your life. 

<h2>Lab meetings</h2>
We have group lab meeting weekly or biweekly. During busy travel periods we may reduce to monthly. Everyone is expected to attend. We will discuss what everyone has been doing, troubleshoot problems, and brainstorm new ideas. Bring your lab notebook and any relevant plots / data. Some meetings may involve reviewing interesting / relevant literature or an in-depth presentation from one member. We will have practice talks as needed for anyone giving a seminar or job talk. I will also ask for an email summary of what has been happening since last lab meeting and what you plan on doing next.

We will also schedule in short 1-on-1 meetings separate from lab meeting to individually discuss progress and troubleshoot issues.

<h2>Lab Safety</h2>
You may not perform any work in the lab unless you have completed the appropriate safety trainings. This includes basic human subject research training, basic lab safety training, annual safety training, and lab specific training. Appropriate use of gloves (nitrile preferred), other personal protective equipment, and secondary containers is expected at all times. No food or drink is allowed in the lab (we work with potentially infectious human tissue). <strong>All human tissue should be considered infectious and universal precautions taken.</strong>

No flip-flops or other open toed shoes should be worn into the lab. We use phenol in DNA extractions. Phenol will burn you but is anesthetic when it drips on your skin; you may not feel it. This and the many other caustic / corrosive / mutagenic chemicals we use make safety a top priority.

<h2>Record keeping</h2>
Lab notes should be kept in gridded, page numbered computation lab notebooks. Binders with loose paper inserts or spiral bound notebooks make it much easier to lose pages. All records, both analog and digital, are expected to be written in legible English. Each notebook should be labeled with the name of the investigator, the date the notebook was started, and the date of the last entry. Notebooks should be stored in the lab and not taken off campus to reduce the chance of loss or theft. The first few pages should be left blank for a table of contents. All entries should be written in ink and the content should have sufficient detail to reproduce the experiment. Each entry should be dated and explain the purpose of the experiment. Any copies of gels or blots should <strong><em>always have lanes and markers labeled. Always note manufacturer and lot numbers for antibodies.</em></strong> Temporary trainees (undergraduates, rotation students, research assistants, and temporary fellows) may use one of several rotation student notebooks rather than using only a small portion of a new one.

Digital record keeping can be harder to manage. For all command-line analysis, it is preferable to use a Makefile or other script to organize your tasks. These are especially handy when later you need to repeat the same kind of analysis. Notes should still be kept for computational work. We can discuss appropriate options, such as a shared Box folder, Google Docs, or other.

<h2>Reagents</h2>
Temporary trainees should use reagents from a shared rotation student box. Avoid raiding the primary samples and reagents. If you need help ask the lab staff. They're smart cookies and actually know where things are far better than I do.

<h3>Plasmids</h3>
All sequence confirmed plasmids should be given a unique name, and at least one aliquot stored in a lab plasmid box. Every plasmid should have a FASTA or GenBank format file associated with it, including annotation of the features and purpose. Each construct should also have a SnapGene file shared in the group Box folders for general reference.

<h3>Primers</h3>
All primers that are not designated for single use should have an aliquot in one of the central lab primer boxes. All relevant information should be entered in the shared lab primer database, including the Tm, expected product size, sequence, genome build used and purpose. <strong>Primer stocks should be created at 500&#956;M.</strong>

<h3>Samples</h3>
Many of the samples that we work with are precious and may difficult or impossible to replace. Whenever possible keep samples in their primary box and take the minimum aliquot needed for your experiments in your own reagent box. Minimize freeze-thaw cycles. <strong>Don't throw away even empty sample tubes.</strong> Unless this is a renewable resource, such as cell line derived DNA, put tubes with little DNA left in a dead-tube box. Small amounts of DNA can be whole-genome amplified or used for very low input sample preps.

<h2>Digital information</h2>

<h3>File naming</h3>
File names should be self-descriptive. Including dates in names can be very useful for figuring out when the data were generated. If dates are incorporated into filenames always use ISO-8601 date format, i.e. YYYY_MM_DD_filename, or if needed expand to YYYY_MM_DD_HHMM_filename. Given the sometimes large volume of files we generate this provides an easy way for a lexical sort to also sort by date.

<h3>Coding</h3>
Don't write code expecting no one will ever read it. Try to adhere to current laboratory coding styles and conventions per language. Good code should be commented appropriately, use descriptive variable names, be well-structured, and complete enough that someone else could successfully reuse it. General code and scripts can be added to a private lab git repository on Bitbucket for development. Reusable code will be placed in the lab's public github repository after QC and validity testing. <strong>Assume that any script you use in data analysis or figure generation may end up as supplementary material accompanying our papers and in the public repository.</strong> It is worth it to design all code, including simple wrappers, to write detailed log information including a timestamp, the options that were set, the version of the script, and any key statistics or messages at the end.

<h2>Scientific Meetings</h2>
Local, national, and international meetings are critically important venues to disseminate our research, and are a key learning and networking tool. Graduate students and postdoctoral trainees especially should regularly submit abstracts for platform talks at appropriate meetings (such as ASHG). If eligible you will be expected to apply for travel awards. If your abstract is accepted for a poster, take care when designing it. Not only will it be seen by a large audience at the meeting, but we may post full-size PDF versions on <a href="http://figshare.com/authors/Elisha_Roberson/98532">FigShare</a>.

<h2>Publications</h2>
For many Ph.D. jobs, the main currency of your reputation is peer-reviewed publications. In biomedical research, the order of authorship on a paper matters. Our goals are to conduct reproducible research with clearly defined experimental methods. We do not want to make the methods, results or data difficult to interpret. Expect to generate a healthy amount of supplemental material to make our work as clear as possible.

<h3>Expectations for authorship</h3>
We adhere to the Washington University <a href="http://wustl.edu/policies/authorship.html">guidelines</a> for authorship (listed below). Any disputes over inclusion or order should be directed to me. If someone meets all three criteria for authorship, they will be included. Otherwise they will not. <strong>Simply supplying a reagent, particularly a published one, does <em>not</em> qualify for authorship.</strong>

<ol>
<li>Scholarship - contribute significantly to the conception, design, execution, and/or analysis and interpretation of data.</li>
<li>Authorship - participate in the drafting, reviewing and/or revising of the manuscript for intellectual content.</li>
<li>Approval - approve the final manuscript to be published.</li>
</ol>

<h2>Leaving the lab</h2>
We expect you to be a good lab citizen when you leave the lab. You should clean up and organize your bench, freezer boxes, and reagents. Your data should be well-annotated and understandable. File locations on your desktop or the lab server should be clear to me and any relevant support staff. Your lab notebook will stay behind, but copies can be made for you. Any code should be checked into the appropriate lab repository. All keys should be turned in by your last day. Always leave contact information with me before you go.

<h1>Specific Expectations</h1>

<h2>Undergrads</h2>
We work with both precious samples and dangerous chemicals. Don't expect to walk in on the first day and pick up a pipette. For an undergrad to come to the lab for a short-term project a specific goal will need to be identified with me and someone in the lab daily will need to be available as a mentor. This type of experience should help you become comfortable with lab safety and lab techniques, and to explore science as a profession. Don't wait to ask for help or to let me know if something goes wrong.

<h2>Rotation students</h2>
I will try to let you know up front if we have room and funding for another student. Rotations typically last weeks to a few months. You need a rotation goal for a method to learn, disease to study or other short-term project. Important advice: not all 'good' scientists are great mentors. Not all good mentors are great scientists. Find someone that can push you to become great scientist. You're not just picking a project for your dissertation. You're picking a project that will change over time, a lab you will work with for years, and a mentor that will have influence over your future career. 

<h2>Clinical fellows</h2>
We sometimes take medical school students, M.D. fellows, and M.D. / Ph.D. fellows for short term projects. These can last anywhere from a few months to a few years. Generally these research experiences are funded through your program. You will be working on a mini-project or assisting other lab members with experiments. You are encouraged to apply for an appropriate K award to help fund protected research time, especially if you are interested in an academic clinician track position. We welcome new research ideas and interesting patient populations to study.

<h2>Masters Research Assistants / Interns</h2>
We sometimes take Research Assistantship & Intern students from Wash U Masters Bio[statistics|informatics] programs. Usually this is when we need extra help on projects around the lab. Your input is always appreciated, and if you have ideas for new research directions, let us know! These positions are usually limited to a 6 month - 1 year period, and you will likely be assigned to a project where extra hands are needed. For coding projects, you will be expected to have your weekly work committed to a lab repository to track progress. You will also be expected to give at least one practice talk during lab meeting prior to any presentations about your work in the lab.

<h2>Graduate students</h2>
Graduate student training typically lasts 4-5 years. We will do our best to help you become a great scientist. While we all will help you along the way, you're expected to take ownership of your project and grow your independence. You will be expected to produce solid first-author publications. Collaborations can be a great way to increase your impact and grow your network, but should be discussed before committing. Around the time of developing your dissertation proposal you will be expected to submit for a fellowship (typically F31 or foundation award) to support your training. The process helps focus your thinking, develop a long-term research plan, and start a funding history.

<h2>Postdocs</h2>
The postdoctoral training period is critically important for future success in academia, and can increase your competitiveness for other careers. Typical length is 1-4 years. Projects should be discussed early and often to help you establish your niche in the lab and in the research community. At least one solid project should transfer with you if you wish to start an academic research program. A postdoc should be a haven of protected research time. You are best served by gaining your independence, applying for funding (F32 or foundation funding early, K awards later) and producing multiple high-quality publications. Establishing collaborations will be critical for developing your future professional network, but consider each opportunity carefully to avoid overcommitting. The current funding climate is grim. It's likely you will need both an excellent publication record and some form of funding to end up on the short-list for faculty positions.

<h2>Staff</h2>
Technicians and staff scientists make the lab go round. Everyone is going to rely on you for advice, assistance and consistent, high-quality data collection. You're the lab glue. Staff positions are generally appointed on a 6- or 12-month trial basis. If you are a good fit for the lab I hope that you will stay with us for many years and become the stable core of our group.

<h2>Eli</h2>
I will work to keep this lab funded and producing good research. I will help you get the reagents and equipment you need for your experiments. I will help you learn to design strong experiments and interpret the results. I will do my best to make you a talented, critical, and fair scientist. I will help you learn how to write papers, reviews, and grants. I will push you out of your comfort zone and support you during the qualifying exams, thesis defenses, seminars, platform presentations, and job talks. I will help prepare you for your preferred career path, regardless of where you want it to lead. I will help you through the failures and congratulate you on your successes, both in the lab and out. I will be honest with you, and expect you to tell me when you need help. You are more than the research that you do in the lab. You can be sure that I care about your life goals and overall happiness. Fair warning: I have strong opinions about open science and science policy, and will frequently express them in loud tones.
