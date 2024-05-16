---
marp: true
---

<style>
  /* Custom Matrix-style CSS */
  section {
    background-color: black;
    color: green;
    font-family: 'Courier New', Courier, monospace;
  }

  h1, h2, h3, h4, h5, h6 {
    color: #00FF00;
  }

  img {
    border: 2px solid #00FF00;
    display: block;
    margin: 0 auto;
  }

  ul, ol {
    color: green;
  }

  ul li, ol li {
    padding-left: 20px;
  }
</style>

# Sequence Diagram Basics
## Caleb Werth

---

## Introduction to UML Sequence Diagrams

- **Definition:** UML Sequence Diagrams depict how objects in a system interact over time.
- **Usage:** Useful for visualizing dynamic behavior and message flow.

![width:600px](images/example_sequence_diagram.png)

---

## Lifeline

- **Definition:** Represents an individual participant in the interaction.
- **Usage:** Shows object existence over time.
![height:350px](images/lifeline_example.png)

---

## Actor

- **Definition:** Represents a user or system role outside the modeled system.
- **Usage:** Interacts with the system via messages.
![height:350px](images/actor_example.png)

---

## Activation

- **Definition:** Represents the time an object is performing an operation.
- **Usage:** Shown as a solid vertical bar.
![height:350px](images/activation_example.png)

---

## Call Message

- **Definition:** Represents a method invocation from one object to another.
- **Usage:** Indicated by an arrow with a solid line.
![height:250px](images/call_message_example.png)

---

## Return Message

- **Definition:** Indicates return of control from a called object to the caller.
- **Usage:** Shown as an arrow with a dashed line.
![height:250px](images/return_message_example.png)

---

## Self Message

- **Definition:** Message sent by an object to itself.
- **Usage:** Arrow looped back to the same lifeline.
![height:350px](images/self_message_example.png)

---

## Recursive Message

- **Definition:** Message sent by an object to itself in a recursive context.
- **Usage:** Similar to self message but denotes recursion.
![height:350px](images/recursive_message_example.png)

---

## Create Message

- **Definition:** Indicates creation of a new object.
- **Usage:** Arrow with a lifeline at the receiving end.
![height:250px](images/create_message_example.png)

---

## Destroy Message

- **Definition:** Represents destruction of an object.
- **Usage:** Arrow with an X at the receiving end.
![height:250px](images/destroy_message_example.png)

---

## Duration Message

- **Definition:** Shows the distance between two time instants for a message invocation.
- **Usage:** Shown as a solid line at an angle
![height:250px](images/duration_message_example.png)

---

## Alt Box vs. Opt Box

- **Alt Box:**
  - Represents alternative branches in a sequence.
  - Only one branch is chosen based on a condition.
  
- **Opt Box:**
  - Represents optional interactions or conditions.
  - Like a single "if" clause with no "else"


---

## Alt Box vs. Opt Box

![width:700px](images/alt_opt_box_example.png)

---

## Loops and Breaks

- **Loops:**
  - Represent repetitive interactions within a sequence.
  - Allow modeling of iterative processes or repeated actions.
  
- **Breaks:**
  - Interrupt a loop or iteration under certain conditions.
  - Allow modeling of conditions that terminate a loop prematurely.


---

## Loops and Breaks

![width:700px](images/loop_break_example.png)

---

## One More Example Sequence Diagram For Fun

![width:700px](images/example_sequence_diagram_2.png)

---

## Bottom Line

### Sequence diagrams offer a visual representation of interactions between objects in a system, aiding in understanding system behavior.

---

## Questions?