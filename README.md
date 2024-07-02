# Object-Oriented-Analysis-Design-Review-8

## User-Interface Design

Core process 4 - Design

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
