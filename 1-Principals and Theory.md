# Principals and Theory

## Table of Contents <!-- omit in toc -->

* [Principals and Theory](#principals-and-theory)
  * [Links to notes on specific Design Principals](#links-to-notes-on-specific-design-principals)
  * [Lecture #01](#lecture-01)
    * [Why is software hard to design?](#why-is-software-hard-to-design)
    * [Why is this bad?](#why-is-this-bad)
    * [How can we create better designed products](#how-can-we-create-better-designed-products)
    * [The key goals of Human Computer Interactions](#the-key-goals-of-human-computer-interactions)
    * [User-Centered Design Process](#user-centered-design-process)
    * [User Experience Requirements](#user-experience-requirements)
  * [Lecture #02](#lecture-02)
    * [Affordance](#affordance)
    * [Signifier](#signifier)
    * [Mapping](#mapping)
    * [Examples of previous three](#examples-of-previous-three)
    * [Feedback](#feedback)
  * [Lecture #03](#lecture-03)
    * [Conceptual Model](#conceptual-model)
    * [Constraints](#constraints)
  * [Lecture  #04](#lecture--04)
    * [Seven Stages of Action](#seven-stages-of-action)
      * [Gulf of Execution](#gulf-of-execution)
      * [Gulf of Evaluation](#gulf-of-evaluation)
      * [Examples](#examples)
    * [Emotional States](#emotional-states)
  * [Lecture #05](#lecture-05)
    * [Cognitive Walkthrough Document](#cognitive-walkthrough-document)
    * [How to Do a Cognitive Walkthrough](#how-to-do-a-cognitive-walkthrough)
  * [Lecture #06](#lecture-06)
    * [Perception Guidelines](#perception-guidelines)
      * [Shneiderman's guidelines](#shneidermans-guidelines)
      * [Nielsen's UI guidelines](#nielsens-ui-guidelines)
  * [Lecture #07](#lecture-07)
    * [Perception Guidelines (Cont.)](#perception-guidelines-cont)
    * [Implication for Design](#implication-for-design)
  * [Lecture #07 (Cont.)](#lecture-07-cont)
    * [Human Perception \& Color Vision](#human-perception--color-vision)

## Links to notes on specific Design Principals

* [Affordance](#affordance)
* [Signifier](#signifier)
* [Mapping](#mapping)
* [Feedback](#feedback)
* [Conceptual Model](#conceptual-model)
* [Constraints](#constraints)

## Lecture #01

### Why is software hard to design?

* Difficult to use (poor usability)
* Doesn't support the functionality that people actually need (not useful)
* Hard to get requirements right
* Hard to translate requirements into *usable* and *useful* software
* Human behavior is difficult to predict
  * no exact method
  * impossible to anticipate all possible conditions of use
* "Time is money"

### Why is this bad?

* Decreased sales
* dissatisfied customers/negative perceptions
* poor reviews
* increased need to for training

### How can we create better designed products

* Design is Not and Exact Science
* Experience + Methodology + Aesthetics = Good Design
* Human or User centered development
  * Guided by empirical studies wit actual users
  * users incorporated into the design process early on
  * users sometimes even join design team

### The key goals of Human Computer Interactions

1. To develop and refine theories and principles of human computer use and human-computer communication
1. to develop techniques and practices for designing and developing human usable software

### User-Centered Design Process

![User-Centered Design Process](Images/Good%20Design.png)

### User Experience Requirements

Establish human subjective experience goals in **observable, measurable terms**

## Lecture #02

### Affordance

Relationship between a person and an object that suggests what can be done with object

* Relationship between interacting agent (usually a person) and an object
* Affordances are NOT a property
* Must be perceivable
  * (SIGNIFIER) placing dots of super clean glass, making it less likely to be perceived as something to be passed through!

### Signifier

A marking, label, or other indication that describes where the action should take place (labels, markers, sounds, etc)

* Accidental Signifiers
  * a bookmark intended for saving a spot in a book can also be used to gauge how much of the book is left

### Mapping

It is the relationship between a set of controls and the items they control

* the relationship between a control and the action it produces
* Think of "Key Mapping"
  * you map the key (control) of an action (in-game action)
* Can also be physical, think of "thumbs up"

### Examples of previous three

* A stove with knobs:
  * The burners can be turned on (Affordance).
  * You know what knob to use because the diagram (Signifiers).
  * The knobs turn on the burners (map).

### Feedback

Sending information back to the user about what has been done

* Includes sound, tactile, and visual feedback
* Feedback should
  * be immediate (people get frustrated quickly)
  * be prioritized (a cacophony doesn't help)
  * not be too little or too much
  * help the user know whether progress toward goal has been made
  * be relevant

## Lecture #03

### Conceptual Model

![Conceptual Model](Images/Conceptual%20Model.png)

A description, usually simplified, of how a device works

* How do you view the interaction of an interface
  * the conceptual model of the thermostate
* Has three parts:
  1. Designer's Model
     * Designer Implements design model in system image
  2. User's Model
     * User Model determines what's understood
  3. System
  * System Image conveys design model to user
* This can cause some issues if the user does not have the same conceptual model as the designers

### Constraints

Perceived limitations of the actions that are possible with an object based on object's appearance

* A constrant is a limitation of usage
* Toggle switches are constrained to be on or off
* It's purpose is to limit the amount of incorrect options they can do

Types of Constraints:

1. Physical - A physical limitation (USB type)
2. Cultural - Allowable actions in social situations
   * Can be universal or culturally specific
   * can change over time
     * Face forward in elevator
3. Semantic - A limitation based on the interpretation or meaning (icons/symbols)
4. Logical - What is left over when all other actions are exhausted

Others:

* Cultural Norms, Conventions, Standards
  * Greetings, Flashing headlights, etc.
  * On Light Switches in the US are up, while in the UK they are down
  * These can be addressed in internatonal standards
* Transfer Effects: **Prior experience influencing how we expect to use/interact with an object**
  * MS Word Ribbons when converting to a new system
* Visibility
  * Elevator only showing possible actions
  * Suffers when there are too many interactions and not enough controls

## Lecture  #04

### Seven Stages of Action

1. Form the goal
2. Plan the action sequence
3. Specify the action sequence
4. Execute the action sequenced
5. Perceive state of the system
6. Interpret state of system
7. Compare outcome to goal

![Seven stages of action model](Images/7%20Stages.png)

#### Gulf of Execution

Occurs when user can't map intention to action

* "How do I work this?"
* "What can I do?"

Execution: Stages 2-4:

* Planning (a specific action to satisfy the goal)
* Specifying the action (within the system)
* Execution the action (within the system)

Influenced by **Familiarity**, **Signifiers**, **Mapping** and **Conceptual Model**

#### Gulf of Evaluation

Occurs when user can't tell whether action succeeded

* "What happened?"
* "Is this what I wanted?"

Evaluation: Stages 5-7

* Perceiving the state of the system
* Interpreting the state of the system
* Comparing the outcome against the goal

Influenced by **Feedback**

#### Examples

Shortening a Microsoft Word Document

1. Goal: Shorten the Word document
2. Plan: Delete a specific word
3. Specify: Position cursor to right of word and hit delete (macOS) multiple times
4. Execute: Actually perform deletion
5. Perceive: Letters are disappearing
6. Interpret state: Word is being deleted
7. Compare: Goal met

Change Course Schedule in Microsoft Excel

1. Goal: Change class dates on old schedule so that they match new dates
2. Plan: Change date of first class from 1/11 to 1/12
3. Specify: Position cursor in cell of first date, type in 1/12
4. Execute: Perform the steps
5. Perceive: All dates are changing instantly
6. Interpret: All dates are one more than previously shown
7. Compare: Goal met!

Replacing all instances of quick with swift in Microsoft Word

1. Goal: Replace all instances of quick with swift
2. Plan: Use Find and Replace functionality
3. Specify: Use the keybind `ctrl-h (^h)` to open the Find and Replace tab. Type in quick in the find section, and swift in the replace section
4. Execute: Perform the find and replace
5. Perceive: All the **correctly spelled** instances of quick will be changed to swift
6. Interpret state: Quick was replaced `x` amount of times
7. Compare: Goal met

### Emotional States

| Visceral | Behavioral | Reflective|
| - | - | - |
| Reaction to present state (pre-emotional) | reaction to matches between present state and learned patterns | After-thefact reasoning, analysis, and decision-making |
| Responses are fast and subconscious producing affective state | Responses are largely subconscious producing actions we can't explain | Responses are slow, deep, and conscious |
| Linked to musculature | Linked to thoughts | linked to assigning causality |

![Seven stages - emotion](Images/7%20Stages%20Emotions.png)

* ***Visceral*** emotions generated in performing and perceiving: Calmness or anxiety
* ***Behavioral*** emotions generated by expectations relative to specifying or interpreting: relief or despair
* ***reflective*** emotions generated by planning or comparing: Satisfaction, pride, blame

## Lecture #05

### Cognitive Walkthrough Document

A Cognitive Walkthrough can be seen as an application of Norman's "seven stages" model

An individual or group simulates a user completing asks with a user interaface
  
* Goals
  * Preemptively determine any potential gulfs. See [Gulf of Evaluation](#gulf-of-evaluation) and [Gulf of Execution](#gulf-of-execution)
  * Generates ideas for improving user interface design
* Advantages
  * No real users needed
  * Can be performed at any stage of development
* Disadvantages
  * Value depends on skill of evaluator(s)
  * Analysis can be narrow and superficial
  * Does not estimate severity or scope of problems identified

### How to Do a Cognitive Walkthrough

1. Gather materials
    * Description of characteristics of typical users
    * List of core tasks that focus on areas of design that need to be evaluated.
      * Correct sequences of actions for each task
    * Representation of user interface to be evaluated
2. Walk through correct action sequences from perspective of typical users, asking the following questions at each step:
    * Will the user know what to do next to achieve task? (Form correct goal?)
    * Will the user notice how to perform the correct action? (Gulf of execution?)
      * Will the user interpret the system response correctly? (Gulf of evaluation?)
3. Record successes, failures (and why the interface fails), design suggestions, and comments
4. Brainstorm potential solutions to problems identified

[Example](Lectures/L05-Cognitive-Walkthrough.pdf) @ page 7 (Only for local repos that include the Lectures folder)

## Lecture #06

### Perception Guidelines

Guidelines are based on human psychology

* UI Guidelines are based on how *people* perceive, think, learn, act
* UI guidelines are *not* rote recipes
* Applying them effectively requires understanding their scientific basis
  * Determining rule applicability & precedence
  * Balancing trade-offs between competing rules

#### Shneiderman's guidelines

1. Strive for consistency
2. Cater to universal usability
3. Offer informative feedback
4. Design task-flows to yield closure
5. Prevent errors
6. Permit easy reversal of actions
7. Make users feel they are in control
8. Minimize short-term memory load

#### Nielsen's UI guidelines

1. Visibility of system status
2. Match between system & real world
3. User control & freedom
4. Consistency & standardsError prevention
5. Recognition rather than recall
6. Flexibility & efficiency of use
7. Aesthetic & minimalist design
8. Help users recognize, diagnose, & recover from errors
9. Provide online documentation & help

## Lecture #07

### Perception Guidelines (Cont.)

* Expectation-induced blindness
  * being "blind" to slightchanges: "next" and "back" being switched at a random page
* Habituation
  * similar to the previous
  * Something we see so often we ingore it: terms-of-service
* Inattentional blindness
  * the gorilla going into the middle of the basketball passing scene
  
### Implication for Design

1. Avoid Ambiguity
   1. ensure users interpret information displays uniformly
   2. if ambiguity is unavoidable
      1. use standards or conventions
      2. "prime" users to resolve ambiguity
2. Be consistant
   1. users will have expectations based on context
   2. they will expect controls and information to be in consistent locations
   3. they will also expect them to have the same function and appearance across different screens
3. Understand users' goals
   1. users' goals strongly influence what they perceive
   2. ensure that exactly the information and functionality needed are readily available at every step of interaction
   3. realize that users may not notice or discover items unrelated to their goals

## Lecture #07 (Cont.)

### Human Perception & Color Vision

How does the brain co,bine cones to allow us to see color?

By Subtraction!

* Red-green difference signal channel compoutes differences in signals from medium-low-frequency cones
* Yellow-bluedifference signal channel subtracts signals from high and low-frequency cones
* Luminance (black-white) signal channel adds signals from low-and medium-frequency cones
* Nearby signals from these channels are subtracted to produce color vision<https://en.wikipedia.org/wiki/Color_vision>

Ability depends on their presentation

* Paleness-The paler the colors are, the  harder it is to tell them apart 
* Color patch size-The smaller the color patches, the harder it is for us to distinguish between them
* Separation-The more separated the patches are, the harder it is for us to distinguish between them

Color-blindness is a limiting factor

* People who are color blind *can* see colors!
* They just have trouble distinguishing certain pairs of color
  * one or more color subtraction channels are not working normally
* 8% or men, 0.5% of women have this issue

Red-green color blindness is most common

* Colors that would be hard for red-green colorblind people to distinguish:
  * Dark red from black
  * Blue from purple
  * Light green from white
* To test a design, put it through a color-blindness filter

We do not have complete control over color

* Colors may appear different on different displays, which vary by make, model, driver, and settings
* Many colors look the same on gray scale displays
* viewing angle can influence colors
* colors may be washed out by ambient light

Peripheral vision

* Spatial resolution of human vision is best within *foveal field*
* 