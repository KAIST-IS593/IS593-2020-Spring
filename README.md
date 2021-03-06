# IS593: Language-based Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs: Changhoon Song (songch@kaist.ac.kr) , Hyunsoo Shin (hyunsooda@kaist.ac.kr)
- Time: Mon/Wed 09:00 - 10:30
- Office hour: Mon 10:30 - 11:30, N5 #2321
- Location: N1 #114

## Course Description
This course teaches a series of topics to build safe software systems based on programming language theories and techniques. The course covers formal semantics of programming languages and state-of-the-art techniques to formally estimate software behavior to prevent security vulnerabilities beforehand. In addition, the course introduces new waves in language-based security, thereby encouraging students to imagine and realize secure and reliable programming systems.

## Grading
- Homework: 50%
- Project: 30%
- Midterm: 0% (due to the COVID-19 outbreak)
- Final: 20%

## Textbook
- Lecture slides will be provided
- Xavier Rival and Kwangkeun Yi, [Introduction to Static Analysis: an Abstract Interpretation Perspective](https://mitpress.mit.edu/books/introduction-static-analysis), MIT Press, 2020

## Homework
This course includes programming assignments through which students will learn how to design
and implement program analyzers.
We will use Github/Github Classroom to provide skeleton code and manage submissions.
Make sure you have a Github account and get the [student developer pack benefits](https://education.github.com/pack).
Moreover, student should get familiar with `git`.
If you are new to `git`, see this [book](https://git-scm.com/book/en/v2).
Students will use the [OCaml](https://ocaml.org) programming language for the assignments.

All submissions will be managed using Github.
For each assignment, a unique invitation URL for Github Classroom will be posted at [KLMS](http://klms.kaist.ac.kr).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late


## Project
Students will propose their own project topics in the middle of the semester
and present their final results at the end. See the [guidelines](slides/project.pdf) for the details.
Here are a selected list of research papers that use static analysis for interesting problems in different area:
- Security
  - [Airbus Controller SW Verification](https://dl.acm.org/doi/abs/10.1145/781131.781153)
  - [API Misuse Detection](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_yun.pdf)
  - [Side-channel Attack Detection](https://dl.acm.org/doi/10.1145/3314221.3314647)
  - [Android Malware Detection](https://dl.acm.org/doi/10.1145/2594291.2594299)
  - [Smart Contract Program Analysis](https://arxiv.org/pdf/1908.11227.pdf)
  - [Web Security Analysis](https://www.ndss-symposium.org/ndss2014/programme/simulation-built-php-features-precise-static-code-analysis/)
- Software Engineering
  - [Code Clone Detection](https://dl.acm.org/doi/10.1145/1985793.1985835)
- Operating Systems
  - [Filesystem Bug Detection](https://dl.acm.org/doi/10.1145/2815400.2815422)
  - [Linux Kernel Malicious Extension Detection](https://dl.acm.org/doi/10.1145/3314221.3314590)
- Architecture
  - [Cache Behavior Analysis](https://dl.acm.org/doi/10.1145/3290367)

This [tool](https://github.com/travitch/whole-program-llvm) will be useful when you run your LLVM analyzer
for realword programs.

## Academic Integrity Violation
Students who violates academic integrity will get an F.

## Schedule
|#|Topics|[<img src="icons/youtube.png" width="24" />](https://www.youtube.com/playlist?list=PL9W7NRh6iA3LbGz0MAhjgK3cp1k6XAWkY)|Reading|Homework|
|-|------|------------------------------------------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)|||
|1|[Introduction](slides/lecture1.pdf)|[1](https://youtu.be/gyj4fhyJPS0)|[Chap. 1]|[<img src="icons/github-classroom.png" width="16" />HW0: Hello-world](https://classroom.github.com/a/44eaPjC4)|
|2|[Operational Semantics](slides/lecture2.pdf)| [2-1](https://youtu.be/-YxeTsAUECU), [2-2](https://youtu.be/1-pliKG_0Ik), [2-3](https://youtu.be/KdGpJRS4rzo), [2-4](https://youtu.be/HDI8Nh8DCe8), [2-5](https://youtu.be/Na4_GYxkiRY)||[<img src="icons/github-classroom.png" width="16" />HW1: OCaml Programming](https://classroom.github.com/a/rvf_2XD7)|
|3|[Denotational Semantics](slides/lecture3.pdf)|[3-1](https://youtu.be/WQF-X3qDSSw), [3-2](https://youtu.be/KEHa5poSAKU), [3-3](https://youtu.be/wRnVioSVQmU), [3-4](https://youtu.be/J8VoPOq7AR4), [3-5](https://youtu.be/9bUuxx8t4vo), [3-6](https://youtu.be/BYxDChIU9DA)||
|4|[Concepts in Language-based Security](slides/lecture4.pdf)|[4-1](https://youtu.be/u2NYCP9bsOM), [4-2](https://youtu.be/6SVU3DiNmpc), [4-3](https://youtu.be/bh5NOqFmxN0), [4-4](https://youtu.be/BC4GdYl1U6Q)|[Chap. 2], [Chap. 9]|[<img src="icons/github-classroom.png" width="16" />HW2: SmaLLVM Interpreter](https://classroom.github.com/a/oCh53sTk)|
|5|[Abstract Interpretation](slides/lecture5.pdf)|[5-1](https://youtu.be/MjteUx_DFuk), [5-2](https://youtu.be/HmNHUV5fJYU), [5-3](https://youtu.be/a5T6uHnzBFU), [5-4](https://youtu.be/A0h0h-gqaX4)|[Chap. 3]|
|6|[Design and Implementation of Static Analysis](slides/lecture6.pdf)|[6-1](https://youtu.be/of4E5pvkWYs), [6-2](https://youtu.be/8dbp60bFoqE), [6-3](https://youtu.be/loWFM9TjZ-0), [6-4](https://youtu.be/Ku87TGcoR8c), [6-5](https://youtu.be/wMmyz8Vgel8)|[Chap. 4]|[<img src="icons/github-classroom.png" width="16" />HW3: SmaLLVM Analyzer](https://classroom.github.com/a/ZqvcX99C)|
|7|[Static Analysis for Advanced Programming Features](slides/lecture7.pdf)|[7-1](https://youtu.be/G4q27kD__go), [7-2](https://youtu.be/DxqnaxOxhJk), [7-3](https://youtu.be/pd6a1vTS-Hw), [7-4](https://youtu.be/RdsS1t2YGTc), [7-5](https://youtu.be/648kdDKCGK8)|[Chap. 8.1], [Chap. 8.2]|
|-|<s>Midterm Exam</s>|||[<img src="icons/github-classroom.png" width="16" />HW4 : ThriLLVM Analyzer](https://classroom.github.com/a/dMRQMGGb)|
|8|[Advanced Static Analysis Techniques (1): Iteration Techniques](slides/lecture8.pdf)|[8-1](https://youtu.be/BScbjvkdYvI), [8-2](https://youtu.be/YmdYPoDWaRs)|[Chap. 5.2]|
|9|[Advanced Static Analysis Techniques (2): Sparse Analysis](slides/lecture9.pdf)|[9-1](https://youtu.be/z00JzM2RDtU), [9-2](https://youtu.be/gwj9Obl-Q7o)|[Chap. 5.3], [[PLDI12](https://dl.acm.org/doi/abs/10.1145/2254064.2254092)]|
|10|[Advanced Static Analysis Techniques (3): Selective X-sensitivity](slides/lecture10.pdf)|[10-1](https://youtu.be/qD7XOoIploc), [10-2](https://youtu.be/KezYDnPm94U)|[[PLDI14](https://dl.acm.org/doi/10.1145/2594291.2594318)]||
|11|[Advanced Static Analysis Techniques (4): Modular Analysis](slides/lecture11.pdf)|[11-1](https://youtu.be/XAMdR2vyDPE), [11-2](https://youtu.be/20iyDmJsdpY)|[Chap. 5.4], [[InferBo](https://research.fb.com/blog/2017/02/inferbo-infer-based-buffer-overrun-analyzer/)]|
|12|[New Wave in Language-based Security (1): Program Analysis with AI](slides/lecture12.pdf)|[12-1](https://youtu.be/lGU96-Lz88E), [12-2](https://youtu.be/6g81uIjcAQU), [12-3](https://youtu.be/OSR8JG_kuUs), [12-4](https://youtu.be/uRsarrA2ggg)|[[PLDI18](https://dl.acm.org/doi/10.1145/3192366.3192417)], [[PLDI19](https://dl.acm.org/doi/10.1145/3314221.3314616)], [[ICSE19](https://dl.acm.org/doi/10.1109/ICSE.2019.00027)]|
|13|[New Wave in Language-based Security (2): Program Debloating](slides/lecture13.pdf)|[13-1](https://youtu.be/xKQ4RNma9qQ), [13-2](https://youtu.be/nJYtPhNEhXQ), [13-3](https://youtu.be/8bdjv6aYfgg)|[[TSE2002](https://dl.acm.org/doi/10.1109/32.988498)], [[ICSE18](https://dl.acm.org/doi/abs/10.1145/3180155.3180236)], [[CCS18](https://dl.acm.org/doi/10.1145/3243734.3243838)]|[<img src="icons/github-classroom.png" width="16" />HW5: ThriLLVM Debloater](https://classroom.github.com/a/EkKjhwGn)|
|14|[New Wave in Language-based Security (3): Program Synthesis](slides/lecture14.pdf)|[14-1](https://youtu.be/YpJzrV9EpKk), [14-2](https://youtu.be/vyN-FHhH5ZA), [14-3](https://youtu.be/mV3KFHWbsME)|[[Book](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf)], [[PLDI18](https://dl.acm.org/doi/10.1145/3296979.3192410)], [[IJCAI19](https://www.ijcai.org/Proceedings/2019/0847.pdf)|[<img src="icons/github-classroom.png" width="16" />HW6: SmaLLVM Synthesizer](https://classroom.github.com/a/SsJkpNVU)|
|-|Project Presentation (6/17, 6/22, 6/24)||
|-|Final Exam||
