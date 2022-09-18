## Design:

![Design](/Design.png "Design")

## Learnings from the project:-

- **The percentage is calculated with respect to the width of the generated box’s containing block. Note that this is true for margin-top and margin-bottom as well.**
  - Apart from margin left and right, margin top and bottom also considers width of element in case we specify it in percentage. This is strange, but this happens.



- margin: auto doesn't work in 2 cases.
    - Summary: Margin only works when width of element is set.
    - If element is block level and it's width is not set. So, we need to set element's width to make it work.
    - If element is inline, then we need to make it block level by using display: block in order to make it work.

