# OM
A course on Operations Management.
Taught on-campus at [SPU](http://en.sspu.edu.cn)  and maintained to be friendly to online students (both english and russian).


#### Manifesto:
* __Optimize for the curious.__ For all the materials that aren’t covered in detail there are links to more information and related materials (D.Silver/Sutton/blogs/whatever). Assignments will have bonus sections if you want to dig deeper.
* __Practicality first.__ Everything essential to solving reinforcement learning problems is worth mentioning. We won't shun away from covering tricks and heuristics. For every major idea there should be a lab that makes you to “feel” it on a practical problem.
* __Git-course.__ Know a way to make the course better? Noticed a typo in a formula? Found a useful link? Made the code more readable? Made a version for alternative framework? You're awesome! [Pull-request](https://help.github.com/articles/about-pull-requests/) it!

# Course info
* Lecture slides are [here](https://yadi.sk/d/loPpY45J3EAYfU).
* Telegram chat room for YSDA & HSE students is [here](https://t.me/rlspring18)
* Grading rules for YSDA & HSE students is [here](https://github.com/yandexdataschool/Practical_RL/wiki/Homeworks-and-grading)
* Online student __[survival guide](https://github.com/yandexdataschool/Practical_RL/wiki/Online-student's-survival-guide)__
* Installing the libraries - [guide and issues thread](https://github.com/yandexdataschool/Practical_RL/issues/1)
* Magical button that launches you into course environment: 
    * [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/yandexdataschool/Practical_RL/master) - comes will all libraries pre-installed. May be down time to time.
    * If it's down, try [__google colab__](https://colab.research.google.com/) or [__azure notebooks__](http://notebooks.azure.com/). Those last longer, but they will require you to run installer commands (see ./Dockerfile).
* Anonymous [feedback form](https://docs.google.com/forms/d/e/1FAIpQLSdurWw97Sm9xCyYwC8g3iB5EibITnoPJW2IkOVQYE_kcXPh6Q/viewform) for everything that didn't go through e-mail.
* [About the course](https://github.com/yandexdataschool/Practical_RL/wiki/Practical-RL)

# Additional materials
* A large list of RL materials - [awesome rl](https://github.com/aikorea/awesome-rl)
* [RL reading group](https://github.com/yandexdataschool/Practical_RL/wiki/RL-reading-group)


# Syllabus
The syllabus is approximate: the lectures may occur in a slightly different order and some topics may end up taking two weeks.

SHANGHAI SECOND POLYTECHNIC UNIVERSITY
FACAULTY OF TECHNOLOGY

OPERATIONS MANAGEMENT
SYLLABUS
 
Instructor:
Li Yan, liyan@sspu.edu.cn
 
Office Room/Hours:
14#400/
Wednesday 1:00 to 4:00 p.m.
or by appointment
 
Version: 06/29/2018

Course Title: 		Operations Management
Course Number: 	B 2011112
Course Type:		Required Course
Session: 		48
Credit: 		3
Designed for: 		Undergraduate Students at Shanghai Second Polytechnic University
Prerequisites: 		Elementary knowledge of Management, Operational Research
Related Courses: 	Principles of Management; Principles and Applications of ERP
Course Evaluation: 	Exam
Program Designer: 	Li Yan

Grading
I will assign grades according to the following distribution:  
A:  10-15 percent 
B:  20-25 percent 
C:  30- 40 percent 
D:  20-25 percent 
E:  5-10 percent
Materials
	Operations Management, 7/E, Nigel Slack, Pearson, 7th edition (13 Jun 2013). Operations Management 13th edition, William J. Stevenson, Published by McGraw-Hill Education(2018).
	Course materials are available through the course page. 
	Pre-class videos: I will record some lectures for viewing prior to class. This will enable us to maximize time devoted to problem solving. These will be posted on the course page.  
Student Assessment
Case Analysis -- 30% 
The case analysis will address the questions associated with one of the course case studies or readings. The write-up will be no more than 750 words long (3 double-spaced pages).  The case analysis is due before the class when it will be discussed.

Class Participation -- 30% 
Class participation is essential to the course since much of what you learn will come through conversations with your colleagues. You participation grade is based on in class comments/discussion, post-class insights (emailed after each class), and responses to “challenges.” 
 
Attendance—40%
Punctual attendance is also part of your overall grade. If you miss more than 3 classes, your final grade will be reduced by half a letter grade; a full grade if you are absent 5 or more times. You must provide a written response to the Discussion Questions for any missed classes. If you are late more than 3 times, your final grade will be reduced by half a letter grade.
Course Objectives and Overview
Operations management is of central importance to any organization, whether they are manufacturing companies producing physical products or organizations offering services, or whether the organization is in the private, public or voluntary sectors. 
This one-term course introduces students to problems and analysis related to the design, planning, control, and improvement of manufacturing and service operations. Class sessions involve explaining concepts, working examples, and discussing cases. A wide range of topics are covered, including: process analysis, supply network management, service and product development, planning and scheduling methodologies and practices, and inventory and quality management. 
This course will give learners a thorough understanding and knowledge of operations management and its organizational and managerial applications. The course will be taught using a blend of cases, theoretical and practical readings, and interactive simulations exercises. The course features experiential learning through a consulting project with a local government agency or non-profit organization. Students work in teams of 4-6 classmates to tackle a real operations management issue facing a client. The projects begin the second week of classes and culminate in a presentation to the class and client as well as a formal report at the end of term. 
At the end of the course students will be able to: 
	See opportunities to improve operations. 
	Diagnose the problems and barriers to creating value. 
	Design effective and efficient solutions. 
	Apply concepts to solve client issues. 
The course will focus on the provision of services. As such it will be unlike traditional courses in Operations Management that focus on manufacturing products. Rather students will learn how organizations provide services and information to produce public value.  
The course is ideal for learners working in organizations, or who would like to work in organizations, and who want to contribute to the development of the organization in the area of operations management.
Course Outline 
The major topics covered in this course are: 
1.	Operations management
Key teaching objectives
	To enthuse students with the `hands-on' excitement that can be gained from an understanding of operations management (`... I want to prevent you ever enjoying a theatre performance, restaurant meal, or shopping experience ever again. I want you continually to be looking for the operations implications of every operation you enter. You are going to be turned into sad people who cannot go anywhere without thinking of how you could improve the processes). 
	Convince students that all organizations really do have an operations function, therefore operations management is relevant to every organization. 
	Convince students that all managers are operations managers because all managers manage processes to produce outputs. (`Even marketing managers are operations managers. What you learn as marketing in business school is really the "technical" side of marketing. Of course this is important, but marketing managers also have to produce marketing reports and information, without mistakes in them, on time, relatively quickly, flexibly enough to contain the latest information, and without using an army of marketing analysts to do so. In other words, they are producing services for internal customers').
	To introduce the some key ideas in the chapter, namely:
	Operations managers manage transformation processes, with inputs and outputs. 
	Operations can be analysed at three levels; the level of the supply network; the level of the operation itself (sometimes called the level of the organization); and the level of individual processes.
	Operations differ in terms of their volume, variety, variation and visibility (the four Vs). 
	Operations managers engage in a set of activities, devising operations strategy, designing operations, planning and controlling operations and improving operations.
Difficulties and Methods
Teaching the material in Chapter 1 of the book is both the most important and the most difficult part of teaching an operations management course. Most important because it is vital that students develop an enthusiasm for the subject and this is best attempted early in the course. Difficult because one has to establish some key principles before the `building blocks' of the subject have been taught. We have found it useful always to work from whatever experience the students have. Undergraduates are more difficult because they usually have less experience, but even so they have experienced many different operations from a customer's point of view. Therefore, one can ask them about recent experiences as a customer (both good and bad) and base a discussion on the importance of operations management around those experiences.
2.	Operations strategy
Key teaching objectives
	To convince students that operations management isn't always `operational'. Although most of the book does deal with the more operational aspects of the operations function's activities, operations managers have a very significant strategic role to play. 
	To stress to students the importance of how the operations function sees its role and contribution within an organization. (`... you can go into some organizations and their operations function is regarded with derision by the rest of the organization, how come, they say, that we still can't get it right. This is not the first time we have ever made this product or delivered this service. Surely, we should have learned to get it right by this time! The operations people themselves know that they are failures, the organization does nothing but scream at them, telling them so..... Other companies have operations functions who see themselves as being the ultimate custodian of competitiveness for the company. They are the A team, the professionals, the ones who provide the company with all they need to be the best in the market...'). 
	To show students that there is a progression of operations excellence (using Hayes and Wheelwright's nomenclature) from Stage 1 to Stage 4. 
	To explain that there really is something very important embedded within operations processes. The skills of people within the operation and the processes they operate are the repository of (often years of) accumulated experience and learning. 
	To give examples of how markets and operations must be connected in some way. Whether this is operations being developed to support markets, or markets being sought which allow operations capabilities to be leveraged, doesn't matter. The important issue is that there should always be a connection between the two.
Difficulties and Methods
Clearly, it is a vitally important issue for any practicing operations manager, but sometimes undergraduates can be confused by the distinction between operations strategy and operations management. The PowerPoint slides for this chapter do include a couple which help to explain the difference, but it can still be confusing. This is partly because there is not such a clear separation between operations management and operations strategy as we sometimes imply. In the operations area especially, we need to include the accumulated learning which comes from day-to-day management of operations resources. This is why the 4th edition includes both the bottom-up perspective and the operations resource perspective. Notwithstanding the difficulties, if it is decided to include a session on operations strategy (usually towards the beginning of the course) we have found it best to treat it as a `backdrop' to the main thrust of the course.
3.	The design of products and services
Key teaching objectives
	To convince students that product and service innovation and design is such an important issue in terms of its impact on operations management, and that it should be treated within operations management. 
	To establish the importance of design and innovation in competitive success. 
	To establish the fact that the design of services is just as important (probably more important) as the design of products. 
	To emphasize the process nature of product and service design (`all operations are processes which produce some mixture of goods and services. Within any organization some of its processes will be producing designs for their own products and services. Therefore, product and service design is an operation like any other'.). 
	To examine the overlap between design of products and services on one hand and the design of the processes which produce them on the other. 
	To establish some of the general issues in the design process such as the way design processes start with a large number of options and finish with a single selected design, the importance of creativity in the design process, the importance of evaluation (using the criteria of feasibility, acceptability and vulnerability), the use of simulation in design, the increasing importance of environmental issues and so on. 
	To take the students through the various stages of the design process while at the same time stressing that describing a process in this way is a great simplification of reality. 
	To demonstrate the benefits of interactive design.
Difficulties and Methods
One of the main issues in deciding how to teach this subject is whether to restrict its scope to pure services, pure products or whether to try to span all types of product/service offerings. The chapter attempts to do the latter. However, as with most texts, it takes a predominantly `product design' perspective which it then extends to cover services. We have found this rather `compromising' approach to work best for general OM modules.
4.	Process design
Key teaching objectives
	To convince students of the broad relevance of the design issue to processes as well as products and services.
	To stress the importance of volume and variety in design.
	To introduce the concept of process types.
	To convince students of the broad relevance and importance of the details of process design 
	To establish the idea that detailed process design must be connected to the overall objectives of the operation.
	To give experience in simple process mapping.
	To introduce Little’s Law as a fundamental law of operations and process management.
	To introduce the implications of variability in process behaviour
Difficulties and Methods
A number of issues are covered in this chapter. It is possible to cover these issues under other headings. For example, some of the chapter could be included in a lesson on product and service design (which is covered in Chapter 4). Similarly, the part of the chapter which deals with volume-variety and its influence on process types could be used as an introduction to process layout (which is covered in Chapter 6). However, we generally find it useful to start out on the ‘design’ part of an operations management course by having a lesson on ‘design’ treated in general terms and process design in particular. This is because many students have never thought about design outside its narrow ‘product design’ meaning. It is important therefore to convince them of the importance of treating design as a broad operations management activity. It is one which applies as much to the design of processes as the design of products and services.
5.	Location, layout and flow
Key teaching objectives
	To identify the main factors on the location decision.
	To introduce the concept of layout type.
	To describe the basic layout types in terms of the nature of the flow of transformed resources through the process.
	To stress that most real layouts are hybrids of the pure types.
	To identify some of the simple approaches that can be used to determine the exact nature of a layout.
Difficulties and Methods
A number of issues are covered in this chapter. It is possible to cover these issues under other headings. For example, some of the chapter could be included in a lesson on product and service design (which is covered in Chapter 5). Similarly, the part of the chapter which deals with volume-variety and its influence on process types could be used as an introduction to process layout (which is covered in). However, we generally find it useful to start out on the `design' part of an operations management course by having a lesson on `design' treated in general terms and process design in particular. This is because many students have never thought about design outside its narrow `product design' meaning. It is important therefore to convince them of the importance of treating design as a broad operations management activity. It is one which applies as much to the design of processes as the design of products and services.
6.	People, jobs and organization
Key teaching objectives
	To stress the importance of the human contribution to producing and delivering products and services.
	To establish how operations managers contribute to Human Resource strategy.
	To illustrate the different forms an organization can take.
	To identify the differences between different approaches to job design.
	To give students some experience of some of the difficulties in adopting each individual
	approach to job design.
	To demonstrate how the same job can be designed in very different ways.
Difficulties and Methods
This is a vital part of any course in operations management. If anything, our textbook (like most in the area) devotes too little time to the human aspects of operations management. This is not because we do not think it to be important. On the contrary, we understand that it is at the heart of any practical treatment of operations management. However, most colleges and universities do not exhibit the degree of multi-skilling and flexibility which is described in the chapter itself. Often there are colleagues in the Organizational Behaviour or Human Resource Management areas who devote whole courses to this sort of subject. Often a typical operations management course is left to deal largely with the more technical and methodological aspects of organizations. However, notwithstanding the fact that these issues may be treated elsewhere in any programme, we are firmly of the view that no operations management course is complete without some treatment of people, job design and work organization.
7.	Capacity management
Key teaching objectives
	To convince students of the ubiquitous nature of medium-term capacity planning and control. 
	To point out the importance of aggregating capacity and demand while at the same time illustrating the inaccuracies that brings into the process. 
	To clearly identify the alternative approaches to capacity management together with their advantages and disadvantages. 
	To try and give a sense of the dynamic nature of capacity planning and control.
Difficulties and Methods
This topic is one of the easier topics in operations management to teach. First, it is an issue which quite clearly is important to all different types of operation. This means that it is relatively easy to find examples with which to stimulate the class. Second, it is not difficult to persuade the class that it is a very important issue. They have all had experience of queuing because capacity cannot meet demand at banks, restaurants, etc. They can also usually appreciate the problems of excess capacity where machines are lying idle and people underutilized. Third, there are a number of very clear approaches to managing capacity in the medium-term which have easily articulated advantages and disadvantages. Because of this, it is not difficult to promote debate. Fourth, the issue has an interesting ethical dimension in terms of whether the use of temporary labour and part-time contracts is ethically acceptable. All of which makes it a joy to teach!
8.	Aggregate planning and master scheduling
Key teaching objectives
	Explain what aggregate planning is and how it is useful.
	Identify the variables decision makers have to work with in aggregate planning.
	Describe some of the strategies that can be used for meeting uneven demand.
	Describe some of the graphical and quantitative techniques planners use.
	Disaggregate an aggregate plan.
	Describe the master scheduling process and explain its importance.
Difficulties and Methods
In earlier chapters, we looked at certain problems that involve long-range planning such as facility location, layout, and major equipment purchase decisions. Aggregate planning involves medium-range planning. The planning horizon for medium-range plans varies from a couple of months to 18 months. A major component of aggregate planning is to plan aggregate production and inventory levels to achieve a desired level of customer service. In preparing the aggregate plan, a major consideration is to check the desired production plan against the estimated capacity. On the other hand, in determining the estimated capacity, we must take into account the expected demand and the resulting medium-range production plan. We use the term aggregate plan in lieu of medium-range production plan because it generally involves the production plan for a group or a family of products (aggregation of products) and over months or quarters rather than days or weeks (aggregation of time).
Even though the aggregate plan is a function of many different factors, the key factor is the forecasted demand over the length of the medium-range planning horizon. After an aggregate plan that is consistent with the forecasted demand and capacity is developed, it is disaggregated into shorter time periods. The process of disaggregation is the beginning of short-range planning using master scheduling and operations scheduling. Both master scheduling and operations scheduling are designed to implement the medium-range plan on the shop floor.
In determining the aggregate plan, integration and communication between various functions of the firm are vital. Expected changes in the workforce levels need to be communicated to the human resources department, while any major equipment purchases, layout changes, and capacity additions must involve the approval of the finance department. On the other hand, changes in anticipated inventory levels and, especially, expected stockouts must be discussed with the marketing department.
9.	Scheduling
Key teaching objectives
	Explain what scheduling involves and the importance of good scheduling.
	Compare product and service scheduling hierarchies.
	Describe scheduling needs in high-volume systems.
	Describe scheduling needs in intermediate-volume systems.
	Describe scheduling needs in job shops.
	Use and interpret Gantt charts.
	Use the assignment method for loading.
	Give examples of commonly used priority rules.
	Discuss the theory of constraints and that approach to scheduling.
	Summarize some of the unique problems encountered in service systems, and describe some of the approaches used for scheduling service systems.
Difficulties and Methods
A major portion of the chapter is devoted to production scheduling. I generally emphasize production scheduling because it has more “meat” than other areas of scheduling and because it enables students to get a better grasp on what scheduling involves and some of the tools available.
It is important to spend at least a few moments to establish the basic differences in scheduling needs among high volume, intermediate volume and job shop systems. It is also important to compare and contrast the scheduling needs of service operations and the scheduling needs of manufacturing operations.
10.	ERP
Key teaching objectives
	To place ERP in the context of operations planning and control. More especially, to understand its role as the source of the information necessary for planning and control. 
	To illustrate the importance and difficulties associated with ERP systems. 
	To emphasize the importance of information such as product structures and bills of materials. 
	To emphasize the role of MRP in the first level of disaggregation from capacity planning and control (the master production schedule). 
	To clarify some of the simple arithmetic which drives the MRP mechanisms.
Difficulties and Methods
There are two main tasks in teaching ERP. The first is to discuss the importance and role of ERP systems. ERP is not difficult to understand in principle but hugely difficult to carry out in practice. It is as well to centre discussion around the managerial implications of investing and managing such an investment. The second is simply to explain the basic mechanics of MRP calculations. This is not difficult but it can be complex. We have found it beneficial to start with very simple examples indeed. A two or three component product plus another of similar simplicity with some common components is a useful starting point. After that there is a decision as to where to take the subject. On specialized courses it is then necessary to go into some of details of MRP calculations. The supplement to the chapter does this, although it does not really get too far into these details because most students (other than those on specialist courses) do not need that level of knowledge. If this is the direction taken then a more specialist text is required. We would recommend Vollmann, Berry and Whybark (reference given in Selected Further Reading).
11.	Inventory planning and control
Key teaching objectives
	To define what we mean by inventory. 
	To identify why inventory occurs in different types of operation and in supply chains generally. 
	To establish the underlying assumptions and cost drivers of inventory through the use of order quantity formulae. 
	To establish some of the practical difficulties of managing inventories in a dynamic sense.
Difficulties and Methods
This is a relatively quantitative chapter. Partly this is because the various quantitative models of stock control have within them the assumptions upon which we base most inventory management. Therefore, working through the mathematics of stock control we are implicitly establishing the key cost drivers and principles of the subject. The other reason for taking a more quantitative approach is that it is traditional. Most textbooks in this area are expected to have the inventory models covered in this way. Perhaps, this is a mistake we all make as teachers. It may be convenient to teach the mathematics of stock control, but how relevant is it? This is a question we can only decide individually. Our approach is to limit the use of mathematical models. So, for example, we hardly ever go beyond establishing the basic economic order quantity (EOQ) formula. The important point is to examine the assumptions within the models. This allows one to look at the various cost elements affected by inventory, examine issues such as cost of capital, look at how (for example) the cost of keeping inventory might affect stock control decisions and so on.
12.	Lean synchronization
Key teaching objectives
	To distinguish between the different contributions of JIT to operations management generally (it is a philosophy, it is a set of techniques, it is a way of planning and controlling movement through processes). 
	To get students to understand the benefits of low between-stage inventory in spite of its counterintuitive feel. 
	To link in JIT to the topics covered in other areas of the subject. 
	To explain some of the criticisms of JIT. 
	To demonstrate the fundamental difference between pull and push control.
Difficulties and Methods
13.	Supply network management
Key teaching objectives
	To demonstrate the ubiquity of supply chains and networks in business.
	To demonstrate how effective supply chain management has a major impact on the profitability of all businesses.
	To clarify the sometimes mystifying collection of terms contained within supply chain management, such as logistics, materials management, and so on.
	To establish the idea of different types of relationship which can exist between a pair of operations within a supply chain.
	To demonstrate the natural dynamic behaviour of supply chains over time.
Difficulties and Methods
The great advantage of teaching network management is that it has become a ‘hot topic’ in business generally. Most people will have heard of it even if they don’t know exactly what it means. The positive side of this is that there is no problem in engaging students’ attention, nor in finding examples of effective and ineffective supply chain management. The downside is that some of the issues are subtle, or strategic, or complex, or all three. Perhaps the most important objective of any session in supply chain planning and control is to convince students that supply chain management is not just about the movement of materials, or just a fancy term for logistics, or something that only applies to manufacturing, or something that is merely fashionable. Supply chain management is, in some ways, a fundamental change in how we see the role of operations. It really is about integrating a supplier’s operation with a customer’s operation. In fact it changes the nature of trading. In executive education we now spend much of our time teaching operations management ideas to sales and market people! Mainly because of a supply chain perspective, they are starting to understand that they cannot sell effectively to their business customers if they do not understand their customers operations. They therefore need the skills of operations management analysis to answer the fundamental question of how their operation can help their customer’s operation to be more effective.
14.	Project management
Key teaching objectives
	To point out the ubiquitous nature of project management in everyday life as well as in operations management. 
	To provide an understanding of how projects are always different from each other in some way or other.
	To introduce the overall stages involved in project planning and control. 
	To provide a basic understanding of network planning techniques, together with the associated mathematical manipulations.
Difficulties and Methods
Project management is a relatively easy topic to teach. With only a little explanation most students can recognize it as something which they do themselves (even if they didn’t understand that they did it) and that clearly has relevance in all types of operation. The dilemma is not so much how to make it relevant but how to manage the two ‘halves’ of project management. The first half is the qualitative aspect of project management which deals with such things as project environment, project objectives, managing the people within projects, understand what can go wrong and so on. The second half is the way we use models (usually network models) to help with the project planning and control process. The first half, which deals with the qualitative aspects, is as most of us who have managed projects know, by far the more important. Yet the quantitative side of the subject is in some ways easier to teach. Undergraduates especially find the qualitative aspects difficult because they have relatively little experience on which to base their discussions. Even with more experienced students such as MBAs, a purely qualitative approach can become unstructured. What we tend to do is to start by introducing the nature of projects and project management and then relatively quickly get into network planning in a (very simple) quantitative sense. This allows us to get into the qualitative elements later. Especially, if exercises can be set where the network diagram indicates some sort of qualitative problem, working from the model to a more generic discussion can work well.
15.	Quality management
Key teaching objectives
	To demonstrate the importance of planning and controlling quality and experience the real problems faced in defining measuring and controlling quality characteristics. 
	To provide hands-on experience of planning and controlling quality. To convince students of the importance of SPC and acceptance sampling. 
	To introduce the four key ideas in the chapter: · · · Quality is consistent conformance to customers' expectations. Poor quality as perceived by the customer results from one of or a combination of the four quality gaps. Quality planning and control involves defining the quality characteristics, deciding how to measure each characteristic, setting quality standards and controlling against those standards. SPC and acceptance sampling are important techniques for controlling quality.
Difficulties and Methods
Again, this is a topic with an important, but not always obvious, message. This underlying message concerns the link between an organization's general `approach' to how it thinks about operations management and what it actually does in practice. In teaching lean, it is relatively easy to make this linkage. In other words, a company's philosophy of operations (if it has one) really does have an impact on what it does. If it has a high tolerance of in-process inventory, it will find it difficult to identify where improvement should be taking place. If it does not value the contribution which everyone throughout the operation can make to improvement, it will never release the full potential within its workforce. If it values high utilization above fast throughput time, it will not understand the real underlying costs of its operations processes. This is an important message and fortunately there are plenty of opportunities while teaching lean to continually reinforce this message.
16.	Operations improvement
Key teaching objectives
	To convince students of the fundamental importance of operations performance to any operations manager. 
	To relate performance measurement and benchmarking both to each other and to the overall topic of operations improvement. 
	To get over the idea that improvement must be prioritized in some way. 
	To contrast continuous against breakthrough improvement. 
	To describe operations in terms of overcoming trade-offs.
Difficulties and Methods
Again, this is one of those topics which can be taught either from a general managerial perspective or as a set of techniques. Of course, we have to get both perspectives over to the students; the issue is `how do we mix these two elements'. In some topics (such as project management) we have found it useful to start with techniques and then draw the managerial implication out of them, whereas this topic of `improvement' seems to work best the other way round. Getting straight into improvement techniques without any broad managerial context has not worked particularly well for us. Rather it is better to discuss improvement generally to begin with. 
Teaching Hours
No.	Content	Total Hours	Lecturing	Practicing	Discussion	Assignment
1	Operations management  	3	2		1	
2	Operations strategy  	3	2		1	
3	Innovation and design in services and products	3	2		1	
4	Process design  	3	2		1	
5	Location, layout and flow  	3	2		1	
6	People, jobs and organization	3	2		1	
7	Capacity management  	3	2		1	
8	Aggregate planning and master scheduling	3	2		1	
9	Scheduling	3	2		1	
10	ERP	3	2		1	
11	Inventory planning and control  	3	2		1	
12	Lean synchronization  	3	2		1	
13	Supply network management  	3	2		1	
14	Project management	3	2		1	
15	Quality management  	3	2		1	
16	Operations improvement	3	2		1	
	Total	48	32		16	

* [__week1__](https://github.com/yandexdataschool/Practical_RL/tree/master/week1_intro) RL as blackbox optimization
  * Lecture: RL problems around us. Decision processes. Stochastic optimization, Crossentropy method. Parameter space search vs action space search.
  * Seminar: Welcome into openai gym. Tabular CEM for Taxi-v0, deep CEM for box2d environments.
  * Homework description - see week1/README.md. 
  * ** YSDA Deadline: 2018.02.26 23.59**
  * ** HSE Deadline: 2018.01.28 23:59**
  
* [__week2__](https://github.com/yandexdataschool/Practical_RL/tree/master/week2_value_based) Value-based methods
  * Lecture: Discounted reward MDP. Value-based approach. Value iteration. Policy iteration. Discounted reward fails.
  * Seminar: Value iteration.  
  * Homework description - see week2/README.md. 
  * ** HSE Deadline: 2018.02.11 23:59**
  * ** YSDA Deadline: part1 2018.03.05 23.59, part2 2018.03.12 23.59**
  

* [__week3__](https://github.com/yandexdataschool/Practical_RL/tree/master/week3_model_free) Model-free reinforcement learning
  * Lecture: Q-learning. SARSA. Off-policy Vs on-policy algorithms. N-step algorithms. TD(Lambda).
  * Seminar: Qlearning Vs SARSA Vs Expected Value SARSA
  * Homework description - see week3/README.md. 
  * **HSE Deadline: 2018.02.15 23:59**
  * ** YSDA Deadline: 2018.03.12 23.59**
     
* [__week4_recap__](https://github.com/yandexdataschool/Practical_RL/tree/master/week4_%5Brecap%5D_deep_learning) - deep learning recap 
  * Lecture: Deep learning 101
  * Seminar: Simple image classification with convnets

* [__week4__](https://github.com/yandexdataschool/Practical_RL/tree/master/week4_approx_rl) Approximate reinforcement learning
  * Lecture: Infinite/continuous state space. Value function approximation. Convergence conditions. Multiple agents trick; experience replay, target networks, double/dueling/bootstrap DQN, etc.
  * Seminar:  Approximate Q-learning with experience replay. (CartPole, Atari)
  * **HSE Deadline: 2018.03.04 23:30**
  * ** YSDA Deadline: 2018.03.20 23.30**

* [__week5__](https://github.com/yandexdataschool/Practical_RL/tree/master/week5_explore) Exploration in reinforcement learning
  * Lecture: Contextual bandits. Thompson Sampling, UCB, bayesian UCB. Exploration in model-based RL, MCTS. "Deep" heuristics for exploration.
  * Seminar: bayesian exploration for contextual bandits. UCB for MCTS.
  
  * ** YSDA Deadline: 2018.03.30 23.30**

* [__week6__](https://github.com/yandexdataschool/Practical_RL/tree/master/week6_policy_based) Policy gradient methods I
  * Lecture: Motivation for policy-based, policy gradient, logderivative trick, REINFORCE/crossentropy method, variance reduction(baseline), advantage actor-critic (incl. GAE)
  * Seminar: REINFORCE, advantage actor-critic

* [__week7_recap__](https://github.com/yandexdataschool/Practical_RL/tree/master/week7_%5Brecap%5D_rnn) Recurrent neural networks recap
  * Lecture: Problems with sequential data. Recurrent neural netowks. Backprop through time. Vanishing & exploding gradients. LSTM, GRU. Gradient clipping
  * Seminar: character-level RNN language model

* [__week7__](https://github.com/yandexdataschool/Practical_RL/tree/master/week7_pomdp) Partially observable MDPs
  * Lecture: POMDP intro. POMDP learning (agents with memory). POMDP planning (POMCP, etc)
  * Seminar: Deep kung-fu & doom with recurrent A3C and DRQN
    
* [__week8__](https://github.com/yandexdataschool/Practical_RL/tree/master/week8_scst) Applications II
  * Lecture: Reinforcement Learning as a general way to optimize non-differentiable loss. G2P, machine translation, conversation models, image captioning, discrete GANs. Self-critical sequence training.
  * Seminar: Simple neural machine translation with self-critical sequence training

* [__week9__](https://github.com/yandexdataschool/Practical_RL/tree/master/week9_policy_II) Policy gradient methods II
  * Lecture: Trust region policy optimization. NPO/PPO. Deterministic policy gradient. DDPG. Bonus: DPG for discrete action spaces.
  * Seminar: Approximate TRPO for simple robotic tasks.

* [Some after-course bonus materials](https://github.com/yandexdataschool/Practical_RL/tree/master/yet_another_week)
  

# Course staff
Course materials and teaching by: _[unordered]_
- [Pavel Shvechikov](https://github.com/bestxolodec) - lectures, seminars, hw checkups, reading group
- [Oleg Vasilev](https://github.com/Omrigan) - seminars, hw checkups, technical support
- [Alexander Fritsler](https://github.com/Fritz449) - lectures, seminars, hw checkups
- [Nikita Putintsev](https://github.com/qwasser) - seminars, hw checkups, organizing our hot mess
- [Fedor Ratnikov](https://github.com/justheuristic/) - lectures, seminars, hw checkups
- [Alexey Umnov](https://github.com/alexeyum) - seminars, hw checkups

# Contributions
* Using pictures from [Berkeley AI course](http://ai.berkeley.edu/home.html)
* Massively refering to [CS294](http://rll.berkeley.edu/deeprlcourse/)
* Sevaral tensorflow assignments by [Scitator](https://github.com/Scitator)
* A lot of fixes from [arogozhnikov](https://github.com/arogozhnikov)
* Other awesome people: see github contributors

