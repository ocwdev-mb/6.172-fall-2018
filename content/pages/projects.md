---
content_type: page
description: Project structure and instructions for 6.172 Performance Engineering
  of Software Systems.
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 2109edee-721a-f9ce-a61f-e50482c54cb1
---

Project Structure
-----------------

Each project will consist of a beta submission, code and design review with a Deputy, and a final submission. You must also submit a write-up that describes your implementation for each beta and final submission. The exact grading scheme for the projects will vary. The assignment handout for each project will include a section describing exactly how your implementation will be evaluated. A large portion of the grade will be on how fast your code runs. The grading scale is fixed and determined by the course staff. You are not competing with others in the class. The teams with the fastest correct implementations for the beta and final submissions will receive the adoration of their peers. After all, being fast is cool!

### Weekly Status Report

In addition to working with your team, you are expected to write a brief, paragraph-long weekly status report. This report is to be prepared individually, and should serve as your summary of what has happened with your project(s) since the last status report. In particular, describe how you spent your project time since the last status report: give an hourly breakdown for major tasks such as designing, coding, debugging, testing, meeting with your team, and meeting with your MITPOSSE Deputy. You may find it helpful to keep a log. Moreover, describe any issues that may have arisen, such as with teammates—or rather, especially with teammates.

### Beta Submission

For the beta, you should focus on creating a correct implementation and developing a good set of tests. You should also try to make it as fast as possible! We will generally give more weight to the performance of your final submission, however.

After the beta submission deadline, all submissions will be anonymized and posted online so that you can learn from what others have done. Please do not put personal details that could be used to identify your submission, such as names of team members, into your code or comments. In addition, beta results will be posted, so that you can see how your submission compared to the rest of the class. (Once again, you are not competing against each other, but it is helpful to see how others have done.) Please look at others’ submissions to learn from them. You may borrow ideas for your final submission, but you may not steal code outright from your classmates or any other sources. We will be checking code for any such instances of cheating. The work you submit must be your own, but it is fine to seek inspiration from your classmates’ beta submissions after they are posted. A good strategy to avoid copying code inadvertently is to leave a significant interval of time (e.g., an hour) between when you look at someone else’s code and when you write your own version.

### Design/Code Reviews (MITPOSSE)

After the beta submission, your Deputy will comment on your code using GitHub’s code-review tools. You will coordinate with your Deputy to schedule a face-to-face or video conference design/code review. Please be responsive to your Deputy in setting up the meeting. Read and reply to your Deputy’s comments before your design review. Although your Deputy will not be involved in grading, your responsiveness to the Deputy’s comments—as evidenced by your GitHub comments and subsequent modifications to your project codebase—will be evaluated by course staff to determine the MITPOSSE portion of your project grade. This portion of the grade will be assigned individually to each member of the team. Failure to schedule or attend design/code reviews constitutes grounds for failing the class.

### Final Submission

The final submission will generally be due about a week and a half after the beta. We will announce a performance goal for the final submission shortly after the beta submission deadline. The performance goal will be set to be challenging, but achievable with effort. Projects that do not meet or exceed the performance goal will receive partial credit based on how close they get to the performance goal. We also will expect that you have incorporated feedback from your Deputy and have improved your implementation’s code quality and documentation. Your final submission will be anonymized and posted online for classmates to see.

### Write-Ups

The day after each beta or final submission, you must submit a short write-up describing your code. Describe the structure of your code, how you diagnosed the bottlenecks, the optimizations you implemented, and what kinds of speedup the various optimizations produced. Feel free also to describe things that did not work and what you learned from the experiments.

Project Teams and Deputies
--------------------------

### Team Contract

Project teams are formed via team contracts. A team contract is an agreement between you and your teammates to establish a set of conventions about how your team will operate. Ideally, it will ensure a smooth team project experience—think back to good or bad aspects of past team projects when negotiating it. At a minimum, your contract must answer the following questions:

*   How will you communicate outside of meetings? (Email list? Real-time messaging platform?)
*   If someone in the group decides to drop the class, what obligations do they have to their team mates?
*   How will work be divided among team members?
*   How will the work be reviewed? How will you manage your code branches?
*   Is it acceptable for some team members to do more work than the others in order to get the team an A?

You are strongly encouraged to cover more in your contract. If your team has problems working together, and you have little in your team contract, there isn’t as much the course staff can do to help you. We will review your team contracts and let you know of any concerns we have.

### Team Dynamics

With the exception of the code-review part of the project grade, team members will generally receive the same grade on their joint project. You are required to make a substantial contribution to each project. If a team member does not make a substantial contribution to the project, the course staff will adjust the student’s individual grade accordingly.

To help ensure that all team members contribute, we will be reviewing the Git commit logs to assess the dynamics of your team. Please ensure that commits are well balanced among your team members’ user names. We understand that with pair programming, commits from one team member may represent work by others, but it is up to the pair to ensure that commits are balanced.

If you feel that a team member is not pulling his or her weight, please contact the course staff as soon as possible.

### MITPOSSE

The course staff has recruited senior software engineers from industry to share with you their invaluable experience and give you concrete advice on your design and code. These Masters in the Practice of Software Systems Engineering (MITPOSSE) will review your code and comment on its design, structure, and style. Well-designed code is easier to performance engineer.

The course staff will not involve MITPOSSE “Deputies” in the grading process, but your participation in code and design reviews will be evaluated by the course staff to determine the MITPOSSE portion of your project grade. We want you to perform well in the class, and your Deputy’s expertise can help you produce better projects and a higher grade. Your assigned Deputy has agreed to volunteer a significant amount of their time to help you learn. We have hand-picked these volunteers from among the top software engineers. They know what they are talking about. All have extensive experience with real-world, on-the-job design reviews.

Please accord these Deputies your greatest respect, since they are volunteering their time to help you succeed in the class. You can learn a lot from them. Be punctual. Be prepared. Be gracious. Thank them!

Project Files
-------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
Assignment
{{< thclose >}}
{{< thopen >}}
code files
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}


{{% resource_link 271aca8d-d9fe-0ff1-59ae-31396a180f17 "Project 1: Bit Hacks (PDF)" %}}


{{< tdclose >}}
{{< tdopen >}}


{{% resource_link 6bd28177-85cf-3e7c-04c8-cfe9b7cd9f1e "Project 1 Materials (ZIP)" %}}

This file contains: 2 .py files, 3 .h files, and 3 .c files.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{% resource_link ac1794b0-1bec-7e14-b4fd-34d5b1a7d2aa "Project 2: Collision Detection (PDF)" %}}


{{< tdclose >}}
{{< tdopen >}}


{{% resource_link e73f8fc3-0a60-9509-b847-f708815a72c0 "Project 2 Materials (ZIP)" %}}

This file contains: 1 .py file, 9 .h files, 7 .c files, and 7 .in files.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{% resource_link d2fb8ee3-3763-2ab3-e256-fa1704375053 "Project 3: Serial Dynamic Memory Allocation (PDF)" %}}


{{< tdclose >}}
{{< tdopen >}}


{{% resource_link ea2f2988-a1ea-1d21-6268-2f86478fae28 "Project 3 Materials (ZIP)" %}}

This file contains: 3 .py files, 10 .h files, and 11 .c files. 


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{% resource_link b13a935d-b7ea-2a78-a165-82065bba55be "Project 4: Leiserchess (PDF)" %}}


{{< tdclose >}}
{{< tdopen >}}


{{% resource_link 6f1ff098-e89d-9c6f-1e63-9de093fd9495 "Leiserchess Rules (PDF)" %}}

{{% resource_link 7be0c0bd-328f-4497-8afe-81c47e3ca303 "Project 4 Materials (ZIP - 2.3MB)" %}}

This file contains: 4 .py files, 52 .h files, 14 .c files, 32 .cpp files, 8 .java files, 6 .js files, 6 .pptx files, 4 .dta files, 1 .pdf file, 1 .html file, 1 .css file, and 1 .key file.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}