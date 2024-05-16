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

![Example Sequence Diagram](images/example_sequence_diagram.png)

---

## Lifeline

- **Definition:** Represents an individual participant in the interaction.
- **Usage:** Shows object existence over time.
![Lifeline Example](images/lifeline_example.png)

---

## Actor

- **Definition:** Represents a user or system role outside the modeled system.
- **Usage:** Interacts with the system via messages.
![Actor Example](images/actor_example.png)

---

## Activation

- **Definition:** Represents the time an object is performing an operation.
- **Usage:** Shown as a solid vertical bar.
![Activation Example](images/activation_example.png)

---

## Call Message

- **Definition:** Represents a method invocation from one object to another.
- **Usage:** Indicated by an arrow with a solid line.
![Call Message Example](images/call_message_example.png)

---

## Return Message

- **Definition:** Indicates return of control from a called object to the caller.
- **Usage:** Shown as an arrow with a dashed line.
![Return Message Example](images/return_message_example.png)

---

## Self Message

- **Definition:** Message sent by an object to itself.
- **Usage:** Arrow looped back to the same lifeline.
![Self Message Example](images/self_message_example.png)

---

## Recursive Message

- **Definition:** Message sent by an object to itself in a recursive context.
- **Usage:** Similar to self message but denotes recursion.
![Recursive Message Example](images/recursive_message_example.png)

---

## Create Message

- **Definition:** Indicates creation of a new object.
- **Usage:** Arrow with a lifeline at the receiving end.
![Create Message Example](images/create_message_example.png)

---

## Destroy Message

- **Definition:** Represents destruction of an object.
- **Usage:** Arrow with an X at the receiving end.
![Destroy Message Example](images/destroy_message_example.png)

---

## Duration Message

- **Definition:** Shows the distance between two time instants for a message invocation.
- **Usage:** Shown as a solid line at an angle
![Duration Message Example](images/duration_message_example.png)

---

## Example Sequence Diagram

![Example Sequence Diagram](images/example_sequence_diagram_2.png)

---

## Conclusion

- Sequence Diagrams are powerful tools for visualizing system behavior.
- They facilitate communication and design decisions.
- Mastering them enhances system understanding and collaboration.

---

## Questions?

Any questions?
