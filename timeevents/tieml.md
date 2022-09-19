##### September 2022

# <center>TimeML and TieML</center>

(C) 2021-2022 [Damir Cavar](https://www.linkedin.com/in/damircavar/), Ali Abdulaziz Aljubailan, Soyoung Kim, [Billy Dickson](https://www.linkedin.com/in/billy-dickson/), [Andrew Davis](https://www.linkedin.com/in/adavis94/), [Matthew Fort](https://www.linkedin.com/in/matthew-fort-07b802236/), [Ludovic Mompelat](https://www.linkedin.com/in/ludovic-mompelat-8a1960b8/), [Zoran Tiganj](https://homes.luddy.indiana.edu/ztiganj/), [Yuna Won](http://www.yunawon.net)


## TimeML:

- Times
    - Marked using TIMEX3 tag (extension of TIMEX2)
    - Contains attributes such as Document Creation Time, Type (e.g. Date, Time, Duration, Set) and Temporal Function, among others.
- Events
    - Marked using the EVENT tag
    - Lists particular informtion about the event such as event class (e.g. Reporting, Perception, Aspectual, I-Action, I-State, Occurence)
    - In the ISO-TimeML standard, tense and aspect are also listed under the EVENT tag.
<!--- need to distinguish these better--->
- Signals
    - Marked using the SIGNAL tag
    - Mark function words that establish a relationship between two events, or a time and an event (e.g. before, after, when)
- Links
    - Specifies relationship between events, times, or time and events
    - Encodes informtion such as durations and ordering relationships
    - Three types of links including T-LINK (temporal link), S-LINK (subordinate link), and A-LINK (aspectual link)


## TIE-ML:

<!--- need to at E,R,S explanation --->
- EventID
    - Integer
    - Each clause is treated as an event and given an ID
- Timeline
    - Integer
    - Ordering of an event in relationship to all other events.
    - Duplicate values indicate simultaneous occurence.
- Local
    - Two Event IDs in sequence
    - e.g. (2, 1) where event with EventID = 2 occurs before event with EventID = 1
    - Used with temporal connectives like *before* and *after*
- Reference
    - Marks explicit time and dates
    - Default value is publication time
- Link
    - Integer
    - Value represents another event's EventID
    - Denotes a relationship to another event.
- Tense
    - Marks the tense of the clause
    - PAST, PRESENT, FUT
    - Default is NONE representing infinitive forms
- Perfect
    - Boolean
    - Marks the presence of perfect aspect 
    - Default is FALSE
- Progressive
    - Boolean
    - Marks the presence of progressive aspect
    - Default is FALSE

<!---
### How TeML time and event capture information in relation to TimeML:
Times
- Timeline, Local, Reference
- 
Events

- EventID, Tense, Perfect, Aspect
- 
Signals
- Local, Reference
- 
Links
- Timeline, Link
- 
--->
