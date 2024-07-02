# Object-Oriented-Analysis-Design-Review-8

## User-Interface Design

### 6-Phase SDLC index

1. Identify problem
2. Plan and monitor project
3. Analyze details
4. **Design components**
5. Build / Develop solution
6. Deploy / Implement solution

### User Interface

- Input and output that directly involve a human actor
- A dialog inbetween the user and system
- Focuses on:
  - User Experience (Human Computer Interaction / HCI)
  - Usibility / User-friendliness
- An User-Centered Design
  - Evaluate designs to ensure usability
  - Development is use iterative

### Metaphors that can to assist in UI design 

#### Direct Manipulation

UI icons manipulating objects that looks & works like a real-life counterpart
- User drag folder to trash can would delete the folder

#### Desktop

Organizing visual display into distinct regions, with a large empty workspace in the middle, with tools on the perimeter

#### Document

Representing data in files that looks like paper documents, sometimes with hyperlinks.
- The user fills in a form on app or website, in reality when they click "submit", only commands or requests are sent to program or server

#### Dialog

The user and computer accomplishing a task by engaging a configuration-like conversation to confirm, cancel, adjust, toggle, input, and other actions
- The user clicks "troubleshoot printer", the computer prints questions step-by-step, the user responds by selecting paths to troubleshoot

-----

### Interface Design Fundamentals / Principles

#### Human-Interface Objects

**Affordance**: The appearance of the object suggests its function

**Visibility**: Visible on display & feedback to user's action

#### Consistency
The interface should be consistent:
- Across platforms
- Within a suite of applications
- Within a particular application
- **Continuity**: Across releases over time

#### Discoverability
- To help users discover “hidden” features or objects
- **Active discovery**: mouse hovers, pop-ups, tool tips
- Visual Diagrams to guide users

#### Dialog Closure
- **Closure on Dialogues** End of a series of actions
- **Protect user’s work** at end and for partially complete work
- Provide undo to reverse actions

#### Readability & Navigation
- Readable text for all users (type, size, color) 
- Clear navigation
- Reverse navigation (a way out)

#### Usability & Efficiency
- Shortcut keys for experienced users
- Meaningful error messages
- Simplicity

-----

### Analysis Models & Input Forms

**Software sequence diagram**
- Defines input messages, which indicates what forms

**Use Cases**
- Defines menu hierarchy
- Different types of users may define different menus
- Also useful for subset use cases for different users
- Once the hirarchy is established, menus can be implemented in a variety of ways

**Story boards**
- Defines dialogs with its flow of activities
- A graphic organizer consisting illustrations displayed in sequence to visualize interactions
- Think of the natural flow of a dialog between user and computer for an use case

```
-----Story board-----
SYSTEM: What would you like to do?
ACTOR: I'd like to check out
SYSTEM: Okay, what is your email address or account number
ACTOR: *provides email*
SYSTEM: Are you *name* living in *address*?
ACTOR: Yes
SYSTEM: Are you checking out for *list of items* in your cart?
ACTOR: Yes
SYSTEM: How would you like to ship the item: *shipping options*
ACTOR: I want *shipping option 1*
SYSTEM: Your estimated delivery will be in *days*, total cost would be *money*

-----Dialog-----
1. Main Menu --> Cart button --> Check out drop down button
2. Enter email dialog --> Confirm name and address
3. Select shipping option --> Total cost display --> Confirm Payment
```

-----

### Interface Design Fundamentals

#### Questions to ask

1. Is the system a custom application or browser based?
2. What kinds of devices will the user-interface need to support?
3. What operating systems will the user-interface run on? 

#### Fundamentals - Know your user

1. **Focus on users**
  - To create a smooth and convinent interface to achieve user goals
2. **Pay attention to patterns**
  - To help users feel fimiliar and comfortable, or "at home"
3. **Stay consistent**
  - Users can to "do it again" by simply repeating the same action
  - Windows 8 failed to stay consistent
4. **Use visual hierarchy**
  - Allow the user to focus on what is the most important
  - Corretly define size, color, and placement of each element
5. **Provide feedback**
  - Interface should speak to your user at all times, when the user performs an action
  - Make sure the user clarily know that they've performed a right/wrong action
6. **Be Forgiving**
  - People will make mistakes no matter what
  - UI should allow and tolerate user error, avoiding restart everything all over
7. **Empower your user**
  - Once a user became experienced with your interface:
    - Reward him/her
    - Take off the training wheels
    - Break down the complex tasks into simple steps
    - Provide more abstract ways, like keyboard shortcuts etc.
8. **Speak their language**
  - Keep things conversational
  - Provide concise labels for actions
9. **Keep it simple**
  - Add only necessary features
10. **Keep moving forward**
  - UI mistakes happens, fix it

-----

### Quiz:

#### System Design - Theory

Individual system component that connects to a higher-level program or process
- Module

Flexibility and scalability are two attributes of a system that is:
- Maintainable

A system is ________ if it supports business requirements and meets user needs.
- Effective

-----

#### System Design - Prototyping

Prototyping is involved in User Interface design, not system Design
- False, both, unless its wireframing prototype

The end product of ________ is a user-approved model that documents and benchmarks the features of a finished system.
- Throwaway prototyping

-----

#### User Interface

What describes how users interact with a computer system and is the key to usability
- User Interface (UI)

As most users are visual learners, a well-designed ________ can increase productivity and help them learn a new system rapidly.
- Graphical user interface (GUI)

The ________, complete with mouse and screen icons, was introduced by Apple in the early 1980s.
- Graphical user interface (GUI)

When a user interface has obvious features that lead or invite users to try things so as to discover hidden features it is called what?
- Active Discovery

Opening screen with well-placed command buttons used for navigating a system describes a(n):
- Switchboard

The ability to link a summary field to the supporting detail, and to dynamically view that detail on a screen, is called:
- Drill down

Interface that does not distract the user and calls no attention to itself
- Transparent interface

-----

#### Interface Design - Theory

Designers should be sure to include cancel buttons on all dialog boxes which allow the user to back up. This is an example of what?​
- Easy reversal of actions

Shortcut keys are an interesting feature, but are seldom used by experienced users.​
- False

User interface design is frequently added to the system after the business rules and business logic has been designed.
- False

Sometimes in user interface design it is a good practice to have controls that are hidden and not visible.​
- True

The overriding issue on the design of data entry screens is to minimize errors.​
- True

Ease of learning and ease of use are often in conflict.
- True

Use of fancy fonts always add interest and clarity to a web page and are recommended for many online systems.​
- False

A sample report, called a ________ , is provided to users for approval and normally includes enough records to show all of its design features.
- Mock-up

Industry leader ________ believes that the best interfaces are the ones that users do not even notice, especially if they prevent productivity losses due to system navigation issues.
- IBM

##### Desktop & Mobile Platform

The primary principles of UI design of a desktop system include principles which also generally apply to other types of devices. Which of the following principles is NOT an important guideline when considering the layout and format of a particular screen.​
- Dark colors should be avoided.

Which of the following are the two primary characteristics of smartphone UI design that are different than UI desktop design?
- Limited screen size
- Touch Screen

Even though tablets and smartphones have many common properties, probably the biggest benefit of designing for a tablet is the ease of navigation.
- True

##### Gestalt Principles of Closure

Which of the following is not a principle of Closure?​
- Have clear navigation path.

List all Gestalt principes of Closure:
- Figure-ground
- Similarity
- Proximity
- Common region
- Continuity
- Closure
- Focal point

-----

#### Interface Design - Diagrams

Sketch that shows a general screen layout and design
- Storyboard

Storyboarding should result in a detailed dialog design.
- False

Interface designers can solicit user feedback by presenting initial screen designs to them in the form of a:
- Storyboard

Which analysis model provides the best starting point for identifying screens for user interface design?​
- System sequence diagrams

One effective way to present large volumes of data is to summarize it and present it...
- in graphical chart or diagram.

-----

#### HCI Metaphor - Dialog

Software (such as typical tax preparation software) which in essence interviews the user is following which user interface metaphor?​
- Dialog metaphor

Using the dialogue metaphor, it is important the each dialogue has a defined beginning and ending. This concept is referred to as
- Closure

To implement the dialog metaphor requires voice communication and voice recognition capabilities on the computer.​
- False

A metaphor of human-computer interaction (HCI) in which interacting with the computer, is much like carrying on a conversation is called
- Dialog metaphor

Each dialog within the system should be organized with a clear sequence–a beginning, middle, and end. This describes which of the rules for designing interactive interfaces?
- Design dialogs to yield closure.

-----

#### HCI Metaphor - Document

A metaphor of human-computer interaction, in which interaction with the computer involves browsing and entering data on electronic documents, is referred to as a
- Documents

Collect input data, trigger input actions, provide original transaction record
- Source Documents

Whether they are paper-based or provided online, ________ collect input data, trigger or authorize an input action, and provide a record of the original transaction.
- Source documents

________ are output documents that are entered back into the same or another information system.
- Turnaround documents

Output document that is entered back into the same or another system
- Turnaround document

-----

#### HCI Metaphor - Document zones

The ________ zone is an area of a form's layout that contains the codes, identification information, numbers, and dates that are used for storing the completed document.
- Control

The ________ zone is often at the bottom of a source document and contains any signatures that are required.
- Authorization

The ________ zone takes up at least half of the space on a form and contains captions and areas for entering variable data.
- Body

-----

#### Metaphor - Desktop

An approach where the visual display is organized into regions and includes an arrangement of common tool icons is called a ____.
- Desktop metaphor

-----

#### Input Methods / Types

________ input is usually performed on a specified schedule, so it would be beneficial to a payroll department who wants to process and release paychecks at the same time each week.
- Batch

The keyboard is an example of a(n) ________ input technology.
- Traditional

Advanced optical recognition is an example of a(n) ________ input technology.
- Evolving

Artificial intelligence is an example of a(n) ________ input technology.
- Emerging

Includes measures to ensure that input data is correct, complete, and secure
- Input Control

The use of handheld scanners to read optical strips on library books is an example of:
- Source data automation

Online input method combining online data entry and automated data capture
- Source Data Automation

The RFID scanner is a device used for ________ , which is the easiest, most accurate, and least expensive data input strategy.
- Automated data capture

-----

#### Design Prototyping

Produces an early, rapidly constructed working version of a proposed system
- Prototyping

A ________ is an early, rapidly constructed working model of an information system that allows users to test it in a risk-free environment and either approve it or request changes.
- Prototype

What is third of five phases in the systems development life cycle
- System design

Produces a full-featured, working model of an information system
- System prototyping

_______ produces a full-featured, working model that is ready for implementation if all requirements have been met.
- System prototyping

Verifies user requirements, after which the prototype is discarded
- Design Prototyping

________ is used to verify user requirements, after which the prototype is discarded and implementation continues.
- Design prototyping

-----

#### Program features

Control features, such as menu bars and toolbars, can be placed on a(n) ________ , which is like a graphical version of a main menu.
- Switchboard

Employees use ________ , an essential means of internal and external business communication, to exchange documents, data, schedules, and business-related information.
- E-mail

If a user opens an application's Help feature, the software may use ________ technology to retrieve a list of topics that relate to the question the user has entered.
- Natural language

A(n) ________ is an interface feature that is used to initiate an action such as printing a form or requesting help.
- Command button

A(n) ________ is an interface feature that contains icons or buttons that represent shortcuts for executing common commands.
- Toolbar

A(n) ________ is an interface feature that is used to switch between on and off statuses.
- Toggle button

________ is a recommended data entry method in which a blank form that duplicates or resembles the source document is completed on the screen.
- Form filling

Designers must think like users when developing ________ interfaces, which incorporate terms and metaphors that are familiar to users.
- User-centered

-----

#### Computer Systems

Large firms often use ________ to scan and store images of original documents, which results in high-quality records management and archiving.
- Computer Output to Microfilm (COM)

Despite government incentives to increase the use of ________ , there is reluctance on the part of many physicians who feel that the software is difficult to use and does not meet their needs.
- Electronic Health Record (EHR)

When using a CASE tool or screen generator for documentation, number the screen designs and save them in a hierarchy similar to a(n):
- Menu tree
- Note: Computer-Aided Software Engineering (CASE)

-----

#### Human-Computer Interaction Theory

________ describes the relationship between computers and people who use them to perform their jobs.
- Human-Computer Interface (HCI)

A key principle of human-computer interaction (HCI) that states that all controls should be noticeable is called
- Visibility

A key principle of human-computer interaction (HCI), that states that the appearance of any control should suggest its functionality, is called what?
- Affordance

Which of the following is not one of the standard methods to aid a user to find and utilize hidden controls or actions that are not obvious?​
- Affordance

List all Human-Computer Interaction principles:
- Learnability: Guessability, Affordance, immediate/ eventual honesty
- Flexibility
- Consistency & standards
- Visibility of system status
- Robustness & error prevention
- Aesthetic & minimalist design
- Help users recognize, diagnose & recover from errors
- Help and documentation
- User control & freedom
- Enable frequent users to use shortcuts
- Offer informative feedback
- Design dialogs to yield closure
- Permit easy reversal of actions
- Support internal locus of control
- Reduce short-term memory load

-----

#### HCI - Input Handling

A system is ________ if it can handle input errors, processing errors, hardware failures, or human mistakes.
- Reliable

#### HCI - Input Validation

A(n) ________ can be used to verify that data items fall between a specified minimum and maximum value.
- Range

Used to identify and correct errors before they enter a system
- Data Validation Rule (DVR)

Verifying that the credit card number on a customer order matches the credit card number in a customer's file is an example of a(n):
- Validity check

Data ________ are used to identify incorrect data and correct errors prior to being entered into the system.
- Validation rules

Template or pattern that restricts data entry and prevents errors
- Input Mask

If a customer record requires a credit card number, a(n) ________ would not allow the record to be saved until a user has entered a suitable value into the credit card number field.
- Existence check

Network application that controls access to and from workstation interfaces
- Port Protector

Microsoft Access uses ________ to help in preventing errors when data is entered into fields, such as telephone numbers, postal codes, and Social Security numbers.
- Input masks

Batch control totals are often called ________ totals because they are not meaningful numbers themselves, but are useful for comparison purposes.
- Hash

-----

#### HCI - Types of Output / Feedback

Since it is not always clear that Web page objects are clickable, or when a control has recognized the click, designers should be careful to apply the principle of
- Feedback

Upper-level managers might use a(n) ________ report because their primary concerns often relate to total figures rather than detailed information.
- Summary

An academic advisor might use a(n) ________ report to identify only those students who have grade point averages below 2.0.
- Exception

Operating systems deliberately include an electronic “click” sound for keyboard and mouse activities. This describes which of the eight golden rules for designing interactive interfaces?
- Offer informative feedback

-----

#### HCI - Standard Output / Feedback

________ is a term that refers to the commonly accepted belief that the quality of an information system's output is only as good as the quality of its input.
- Garbage in garbage out (GIGO)

Electronic reports can provide a ____ on the report to activate a lower-level report, which provides more detailed information.​
- Hot spot hyperlink

________ are a form of Web-based output that can be downloaded from a variety of content providers and stored on a portable player.
- Podcasts

________ are a form of Web-based output that are written to deliver fact as well as opinion to Web readers.
- Blogs

Database programs, such as Microsoft ________ , allow users to easily create groups and subgroups as well as reports that calculate and display totals, averages, and record counts.
- Access

-----

#### HCI - Exception / Error Feedback

A good example of an error message might be, “The account information is missing critical data. Please re-enter.”
- False

#### HCI - Reports

Report that produces one or more lines of output for each record processed
- Detail Report

Protects sensitive data, which can only be read if a user has decoding software
- Encryption

Report that displays only records that meet a specific condition or conditions
- Exception Report

Reports that are used by high-level managers to assess the overall health and performance of the organization are called what?
- Executive Reports

A(n) ________ will produce one or more lines of output for each record that is processed.
- Detail report

Modern IT departments tend to rely on customer-designed output rather than ________ , which were the reams of printed reports that were commonly produced in the past.
- Greenbar report (cold report)

Prevents a user from saving a record until a suitable value is entered
- Existence Check

A feature of a well-designed report is the ________ , which identifies the report, and contains the report title and date.
- Report header

A feature of a well-designed report is the ________ , which appears at the end of the report and may include grand totals for numeric fields as well as other end-of-report information.
- Report footer
