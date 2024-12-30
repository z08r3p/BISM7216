java c
Business Process Improvement (BISM7216)
Assignment   1- Process Modelling with BPMN (Individual Assignment)
300 marks (30% of course   grade)
Submission Type
•          Milestone   1:   Submit   an   Excel   document   containing two worksheets   (using   assignment template)
•            Milestone 2: Submit a   Word   document.
•          Final   submission:   Submit the   full   BPMN process   model   in   three   file   formats:   a   Signavio   archive         (SGX), a PDF, and a   .bpmn file.   Please note   that   all   subprocesses   must be   included   in the   above            files. Note: If   elements   of   the   overall   process   are   missing   due   to   missing   subprocesses, marks   will be   deducted.
File Naming Format
All filenames must start with the   format:
StudentNumber_LastName_A1Process (e.g.,   1234356_Surname_A1Process).
Submission Method
•             Submit via the Blackboard Assignment   1 submission folder.
•            Ensure   you   receive   a   submission   receipt.
•          Remember,   this   is   an   individual   assignment. Assignment   2   is   our   only   group   assignment.
Background  your task
AI Solutions Co. is a leading technology   firm   specializing   in   developing   artificial intelligence   solutions   for      various industries. Recently, the company has been focusing on enhancing its   customer   support processes to improve client satisfaction and retention. The Managing Director   (MD) has   appointed   Lisa   Smith   as   the General   Manager   of   Customer   Experience   (GM   CX). One   of   the   key   responsibilities   of   this   role   is   ensuring that customer support tickets are managed efficiently, issues are resolved promptly,   and   high   customer satisfaction ratings are maintained.
With over   10 years of   experience in the company, Lisa has   a thorough understanding   of   AI   Solutions   Co.’s   value chain. Her previous roles in Corporate Strategy and Project Management have   equipped her   with   valuable insights into both upstream and downstream activities of   customer   support. Despite her   extensive   experience, Lisa is concerned about her familiarity with the current   customer   support process.
Lisa engages you, the Business Analyst, to review the existing documentation   and notes   from the previous   GM CX. During a 90-minute kick-off   meeting, you both identify   some   small   amendments,   resulting   in   a confirmed process walkthrough. Lisa seeks to visualize the process using BPMN to facilitate discussions with her team and the MD.
The process begins when the GM CX receives a notification from   a   client about   an   issue   with   one   of   AI
Solutions Co.’s solutions. Notifications can come through various channels   such as   email, phone,   chat,   or   the company’s support portal. The GM CX   then   creates an   entry   in   the   Support   Management   System   (SMS) and performs an initial triage to classify the issue. Issues   can be   classified   as   critical,   high,   medium,   or low priority. The   SMS then generates an automated message to the   client to   inform. them   of   the   details. The client then has 24 hours to reply with confirmation, or to make   any request for   change   in   the   issue   description.
If   no response or confirmation is received from the client, then the   Support Team will update the   system by   changing the issue status to idle, and if   no response   is received   within   two   weeks,   the   Support   Management   System automatically closes the issue. Where a response is received   from the   client,   GM   CX   identifies   the ideal resource or resources for this issue, based on the criticality   and   specific   requirements   of   the   issue,   and   updates the   SMS.
At   the   sametime   as   GM   CX   is   identifying   the   ideal   resource,   if   it   is   a   critical   issue, the   SMS   also   notifies the MD who then activates their dashboard and monitors the issue resolution process to   support   the   GM CX in the first few months of   her new role. Critical issues   are   addressed   by   a   Critical   Issue   Resolution
Team, comprising the Support Engineer and the   Support Manager. This team   follows   the   steps   for resolving High Priority  Complex issues as defined below, but instead   of   the   Support   Engineer conducting   the   activities, the   Critical   Issue   Resolution   Team   conducts   them   asa   small   team,   and   within   a   shorter timeframe. 3 working days. Usually, the Critical Issue Resolution   Team   completes this work within   the timeframe, but if   the critical issue is not successfully resolved within   3   days,   the   Critical   Issue
Resolution Team informs the GM CX, who forwards   it to a   third-party   software   engineering   company
(SEC), contracted to resolve critical issues within an extra three working days.   Any   solutions prepared by   the   SEC are subject to further testing prior to implementation on   the   test   computing   environment,   as
defined for High Priority  Complex issues. All critical   issues   are resolved in   one   of   these   two   ways,   and      after the resolution passes testing, the GM CX informs the client   of   the resolution   and updates the   SMS   of that communication.
For high priority issues, the   Support Engineer   drafts a proposed solution,   and   forms   a   Support Assessment   Team, inviting the GM CX, Head of   Engineering, QA Lead,   and   the   Data   Privacy   Officer   if   personal   data      is involved, to a meeting, and updating the   SMS. If   this team identifies the   issue   as high priority   and
complex, then the QA Lead assesses the proposed solution provided by the   Support Engineer during   the      Support Assessment Meeting, checks the schedules and planned resources. These   assessment actions   are
repeatedly   done   as   part   of   the   meeting   in   random   order   until   the   team   is   confident   the   quality   of   the
solution is appropriate for resolving the issue. If   the team identifies that the   high priority   and   complex   issue   involves data anomalies, the Support Engineer then engages   a   third-party Data   Analyst to   review   logs   and         system analytics and provide a root cause analysis. The turnaround for receiving the   review   from   the Data         Analyst is 5 days. If   the review is not received within the timeframe, then the   issue   is   escalated   to   Critical            issue status, which will follow that process as already defined. Where   a   timely response   is received   from
the third-party Data Analyst, the   Support Engineer incorporates the insights into   fixing the   issue,   following      the approach as agreed at the   Support Assessment Team meeting. Once the   fix   is   coded, for   critical,   or high   priority  complex issues, the QA Lead verifies the   fix through   rigorous   testing,   and updates   the   SMS   on details of   the   solution.
All medium-priority and low-priority issues follow the same   steps, whereby: the   Support   Manager
acknowledges receipt, reviews the issues, and discusses them with the assigned   Support Engineer, updating   the   SMS accordingly. The Support Engineer then drafts a Resolution   Plan, providing   a   high-level   summary of   how the issue will be addressed, and defining roles and responsibilities. The   Support   Manager   then
reviews and either confirms the Resolution Plan, in which case the   Support Engineer then has   one week to         fix the issue, or if   the Support Manager requires changes to the   Resolution Plan,   he   will   draft recommended   changes for the Support Engineer to integrate into a new plan, which the   Support   Manager   then reviews.
These steps can be iterated multiple times, until the   Support Manager is happy with   the   proposed   solution.   To fix these types of   issues, the Support Engineer implements the   Resolution plan,   and,   once   the   fix   is
coded, conducts preliminary testing. Once the fix is tested, the   Support Engineer   implements   it   on   the   test   computing environment, and updates the   SMS, which then sends   an automated   message   to   the   client
requesting confirmation that the issue is resolved. Once the   SMS receives   the confirmation   from   the   client,   the   Support Manager approves promotion of   the fix to the production environment, and closes the   issue,
allowing the   SMS to create a report which can then be used in the   Resolution   Close-out Meeting   (RCoM)   later. If   the client does not approve the fix,   and requests further   investigation   of   the   issue, then   the   SMS
notifies the GM CX who forwards it to the third-party   software   engineering   company for   resolution,   who   will inform. the GM CX of   the resolution in   due   course. Any   solutions prepared by the   SEC   are   subject to   further testing prior to implementation on the test computing environment. At that point, the   GM   CX
informs the client of   the resolution and updates the outcome in the   SMS.   If   the   client   does not respond, the SMS will send one reminder, and if   no response is received within   1 further week, automatically   changes         the status of   the   issue   to   “closed”   .
At any point before the issue is resolved, the client can   cancel   the   issue   ticket by   sending   a   standard   cancellation message to the SMS. Once such a message   is received, the   system then   automatically   set   the   status of   the issue to “cancelled”, and automatically issues   a   “stop work” message   to   any   resources currently w代 写BISM7216 Business Process Improvement Assignment 1Python
代做程序编程语言orking on it, and the   Support Engineer reverses changes (if   any) made to   the   test   computing   environment. An automated message is concurrently sent to the customer   to   confirm   the   cancellation.
Once an issue of   any classification is resolved, and after updating the   client, the   SMS   sends   an   automated   feedback request to the client. Once the client feedback is received by the   SMS, the   Support Manager
reviews this, and adds it to the list of   issues to be reviewed by the   Support Assessment   Team.   This team   discusses the methods used, any efficiencies and improvement ideas that the   Support Manager then
analyses and adds into a Monthly   Support Report to be reviewed by GM   CX.   GM   CX then   discusses
concerns (if   any) with the   Support Manager and uploads the report plus the relevant client feedback into   the   SMS in any case. If   no feedback is received from client,   then   a   weekly   reminder   is   sent   to   client until   the
feedback is received or 3 weeks have passed (in which   case the   SMS   adds   a   “no-feedback”   tag to   that   issue). Once a month, the MD conducts a   Customer   Experience   Review   Meeting to   evaluate   the
effectiveness of   the support process and identify which process improvements   should be prioritised. It
should be noted that where client feedback was received, it is discussed in this meeting and   incorporated   into future   support strategies.
Guidance on your objectives
Lisa aims to ensure the process is clearly visualized to   facilitate   discussion   and   secure the   necessary
support from the MD. As such, she relies on   you   to   document   any   assumptions   and present   them   within   the   BPMN model.
The overall marking rubric is outlined on the final page. Marks   are   allocated not   just   for   correct modelling         of   the   scenario, but   also   for   the   pragmatic   quality   of   the   model   (i.e. use   of   modelling   guidelines,   aesthetics,   general   ease   of   interpretation   and   maintenance   for   the   model’s   audience).
As such, please ensure your models are easy to   read when   printed   at   A3   size   (consider your   audience).
You will need to choose the appropriate level of   detail (abstraction),   and   also   avoid   leaving   excessive   blank   spaces in your model, which would result in your model being longer or wider than otherwise   necessary.
(Signavio’s “create or remove free space” tool can help   you   tidy   the   model;   don’t   forget   to   tidy   the   messages too once you’ve optimised   the   space!)
Your final submission will not be considered complete unless all three   files are   submitted by the   deadline.
Please   read   the   requirements   overleaf, and   carefully   comply   with   them!
Student Tasks (your   deliverables)
Milestone   1 (M1) (total   50 marks)
Deadline: Thursday 22/08/2024   14:00
Note: No BPMN model is required for   this   milestone.Tasks: Please download the Microsoft Excel template (Excel file) containing   three   worksheets   and use   the tables in worksheets to provide your answers, then save and   submit the   Excel   for Milestone   1   (M1).   The worksheets contain:
a.         Your understanding of   all the actors / organisational artefacts in this process (i.e.   lanes   and pools.   Please   include   both   black   and   white   box   modelled   pools).
i.                NB: if   there are multiple   entities within   the   same   pool   (i.e.   lanes), please   group   them together   in the table   so that the structure   is   clear.
b.       Your   understanding   of   one   positive   outcome, and   one   negative   outcome   of   this   process   in   the   same Microsoft Excel template.
c.         Your understanding of   all the events (start, intermediate and end   as relevant),   and   activities   in   this   process using the table in the worksheet that will be provided in the Excel spreadsheet.
i.                Please remember to use the   same   language   (i.e. the   same verbs   and   nouns)   as   in   the   process      walkthrough. If   you don’t use the   same language or convert it into   BPMN-style   labels using      those same nouns and verbs in the appropriate   order,   the   customers   and model users will not   understand what you’re referring to and give you zero marks!
PDFs or other file formats are not permitted; please use only   the   Excel   template   as provided.
Milestone 2 (M2)   (total 40 marks):
Deadline: Thursday 29/08/2024   14:00
Task: Please submit, this time using a Microsoft Word   document – two   different complex   and more   advanced   BPMN   constructs   that   are   necessary   to   achieve   high   semantic   and   pragmatic   quality   in   this process. Please also explain, in less than 200 words   for each,   why you   have   chosen   those   constructs   as   necessary to best model this process. (Please explain why you use it in this specific   context.) You may   use a fragment of   a BPMN model to help explain. Keep in   mind   that   a   complex   and   advanced   BPMN   construct   is a set of   BPMN symbols (constructs) that when   combined,   are   more   complex   than   any   individual   component. Listen attentively to Lecture 5 for further   information   on what   is both   complex   and   advanced/extended.
NB: you do not need to submit a   full   or   complete   BPMN   model   for this   milestone.
Final submission   | BPMN model   (total 210 marks):   Deadline: Friday 6/09/2024   14:00
Task: a   full   BPMN   2.0   As-is   model   of   this   process   walkthrough, using   the   BPMN   2.0 norms   constructs taught on this   course.
1.    Please insert your name on the main Signavio model page,   below the   last pool   i.e.   on the   model   itself   (in   addition to the filename). Please use the StudentNumber_LastName   format, and you can use   the   Text
Annotation tool under Artefacts in the Signavio   Shapes menu. Your student number and   surname   must be   visible   on   the   mainpage   of   all   files.
2. Please make sure that your final Blackboard submission   includes   THREE   files,   as   shown   in the image   to the   left:
• The   SAP Signavio archive (SGX) file   (select all   files   in your   Signavio process   explorer   window   before   choosing   this   option).
• The   .bpmn file from Signavio that   contains   your
model (select only the main process, then Export
BPMN 2.0 XML, and in the options, please   ensure   it   includes any linked subprocesses (see   image). NB:            Signavio only exports local subprocesses   in this
way, not   Global   subprocesses, so   be   mindful   of   that   when   you   model   and   export.
• The   .pdf   image   file   of   ALL   your   process   (including   sub-processes, by   selecting   all   relevant files in your   Signavio process explorer window before choosing this option).
Assignment   1 Marking Guide/Rubric
Feedback after Milestones   1, and 2 will   be provided in your tutorials.
Marks will be issued only once, after all three components have been   submitted.
All   stages   of   the   assignment   will   be   marked   based   on   the   following   marking   rubric      allocation   of   marks.   The following criteria are distributed carefully   across   all milestones and   final   submission.
Criteria
High Level Competency 80% -   100%
Adequate Competency   50%   -   79%
Developing   Competency 0%   -   49%
Lanes/Pools
   
30 marks
All   internal/external
process   participants   have been   correctly   modelled.
Some internal/external
process   participants   are
missing or are   incorrectly
modelled.
Most internal/external
process   participants   are
missing or are   incorrectly
identified.
Activities
   
40 marks
All activities,   including
appropriate   sub-processes
have   been   correctly
labelled and modelled.
Some activities   or
appropriate   subprocess
are missing   or are
incorrectly identified.
Most activities   or
appropriate   subprocesses are
missing or are   incorrectly
identified/ modelled.
Decision      Gateways
65 marks
All gateways have   been         correctly modelled, using      appropriate gateway types.
Some gateways   are
missing   or   are   of
incorrect type.
Most gateways are missing
or are incorrectly identified/
modelled.
Sequence   flows
   
35 marks
All   sequence   flows have   been correctly modelled.
Some   sequence   flows are
missing or are   incorrectly
identified.
Most   sequence flows   are
missing or are   incorrectly
identified/ modelled.
Events
   
65 marks
All events   have   been
correctly modelled, using   the correct   event types.
Some events   are missing   or   are   of   incorrect   type.
Most events are missing   or
are incorrectly
identified/modelled.
Message Flows
   
25 marks
All message   flows have
been   identified   and   are
correctly modelled.
Some message   flows are
missing or are   incorrectly
identified/ modelled.
Most message   flows are
missing or are   incorrectly
identified/ modelled.
Pragmatic   Quality
   
40 marks
Consistent   use   of
modelling guidelines, well
structured, easy   to read
model.
Some inconsistencies
exist in   applying
modelling guidelines,
and/or issues with model
user   friendliness.
Little   or   no   evidence   of
application of   modelling
guidelines,   significant issues
with model user friendliness.
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
