[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18535181&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

Explain what software engineering is and discuss its importance in the technology industry.
    is the establishment and use of sound engineering principles, metod, tools that can be used to produce high quality sotware that is reliable and work efficiently on real machine.
      (a). it's reliable-ensures software performs as expected without bias.
      (b). it is efficiency-helps to optimize developer workflow while maintaing high quality standards.
      (c). scalability & flexibility-ensures the system can handle an increased lead without affecting performance.
      (d). security-implement protction practise like authentiction, authorization and encryption to secure information.
Identify and describe at least three key milestones in the evolution of software engineering.
      (a). mastering complexity-it enables efficient reuse of object-orientd software.
      (b).mastering productivity-it focuse only ontasks and processes that provide the customer with added value in the product being created.
      (c). mastering intelligency-is the development of problem-solving techniques.
List and briefly explain the phases of the Software Development Life Cycle.
      >phase 1: planning- it involves definng the software's purpose and scope.
      >phase 2: requirements analysis- it seeks toidentify and record the precise requirements of the final users.
      >phase 3: design- it is all about building the framework.
      >phase 4: coding- it is the converting of software design into tangible code.
      >phase 5: testing- it is a thorough examination of the software of any bugs or glitches that might have slipped through during coding.
      >phase 6: deployment- it is the rollling out of the meticulouslytested and fine-tunned softwareto its end-users.
      >phase 7: maintenance- it is  the constant assistance and improvement,which guarantees the software's best possible functioning and longevity and ensures it meets customer expectations.

Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.
      >In waterfall communication is less frequent and more formal in nature while in agile communication is frequent and less formal.
      >in waterfallthe project structure is laid out in detail before work begins while in agile planning and structure are highly fluid components that can shift and adjus as evolving situuations demand.

Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.
                                    **software developer**
roles and responsibilities
  >he/she assistes the development team with all facets of softwaredesign and coding
  >learning the code base, participating in design meetings, writing simple codes, addressing bugs, and helping the development manager with all desisgn-realated software developer job duti.
  >they ensure that the code is up to the company's quality standards, clearly understandable and fulfills all the projet objectves.
  >creating high-quality software architecture and design.
  >identify prioritize and carryout tasks across the softwre developmet life cycle.
  >greate toools and applications by developing clean, efficient code.
  >utilize tools and programming to automate tasks.
  >code review and debugging.
  >conduct validation and verification tests.
  >work with internal teams and vendors to repair and improve goods.
  >document phases of development and monitor systeems.
  >ensure software is up to mark using recent technologies.
                              ** quality assurance engineer**
    >software testing engineering: focuses on executing and analyzing test to ensure software quality.
    >test analst: eamines requirements and design test casee
    >test automation angineer: builds scripts to run automated testes.
    >test architect: designs and implements the overall testing archittecture.
    >test manager: oversees and coordinates the team to archive projecc goals.
    >QA team lead; participates in QA rocesses, checks status, and manages the team. Often, he deals with management tasks rather than tech ones.
                               ** project manager**
roles
    >ensures a projct successfully moves from planing to completion
    >they oversees every asoect of th project, ensuring it stays within the budget and meets th required quality standards
    >they manage timelines and unexpected changes to the project's scope.

responsibilities
    >planning- he/she is responsiblefor formulating a project plan to meet the project's objectives while adhering to an approved budget and timeline
    >leadership- the ability o speak openly and freuently wth all stakeholders is critical.
    >execution- requires frequent, open ommunication with the project team members and stakeholders, ensuring eefectve project management practices are applied throughout.
    >time management- staaying on schedule is crucial to completing any project.
    >budget management- project managers need bubget for a project and stick to it as closely as possible. if certain prts of th project end up costing more than anticipated, project managers moderate the spend and             reallocate funds when necessary
    >documentation- a project mnager must develop effective ways to measure and analyze the project's progress
    >maintenance- the project manager devise methods for properly supporting the final deliverable going forward, even if tey are not directly overseeing its day-to-day operations.
Discuss the importance of Integrated Development Environments (IDEs) and Version ControlSystems (VCS) in the software development process. Give examples of each.
    >collaboration: enables multiple dvelopers to work on the same codebase without conflicts.
    >change tracking: records detailed history of changes, allowing easy analysisof each modification.
    >branching and merging: supports creating branches for new features and merging them back into the main code.
    >error recovery: allows reverting to previous versions if new changes introduce errors

What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.
            challenges                                                    solutions
 >unclear software reuirements.                            >define the project from vision to expected outcome.
>lack of communication & collaboraton.                     >frequent meetings and clear communications.
>poor code quality and bugs.                               >automate processes and incorporate CI/CD in workflows.
>unrealistic timelines.                                    >accurate time estimation.

Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.
>unit testing- is an essential software developmet practice that identifies issues before they escalate into more significant problems.
>integration tests- different modules or services used by your application work well together.
>acceptance testiing- are formal tests that verify if a system satisfiesnbusiness requirements.

#Part 2: Introduction to AI and Prompt Engineering


Define prompt engineering and discuss its importance in interacting with AI models.
prompt engineering is the process of refining what you ask a generative AI tool to do. 

Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.
prompt:
    """
    table departments, columns =[departmentid, departmentName]
    table students, columns =[departmentid, studentid, stdentname]
    create a MYSQL query for all students in the computer science department
    """
output:
select studentsid, students name
from students
WHERE Departmentid in (SELECTED
Departmentid from deprtments
WHERE DepartmentName = 'computer science');

