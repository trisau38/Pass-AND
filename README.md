# Pass-AND
Pass transistor is used to reduce the number of transistors to implement an AND gate. In this
circuit, if the B input is high the left NMOS is turned ON and copies the input A to the output
o/p. When B is low the right NMOS pass transistor is turned ON and passes a ’0’ to the output
o/p.
Boolean expression: Y = A*B

## Circuit Diagram:
![pass_and_cir](https://user-images.githubusercontent.com/108890713/219367499-50a002a6-d7e5-4c3b-8d04-88faa1d4229e.jpeg)

## Euler’s Path:
Since Euler’s path is defined for complementry mosfet gates, so we cannot find the Euler’s
path for pass transistor logic.

## Stick Diagram:
Stick Diagram is constructed from the knowledge of traversal of Euler’s path. Since Euler’s
path is not defined for the pass transistor logic, so we cannot design its stick diagram.

## Magic Layout
![pass_and_mag](https://user-images.githubusercontent.com/108890713/219367870-49511c8f-5b8b-48f7-8e7d-57da3c32d534.png)

## AC Analysis Output:
![pass_and_out](https://user-images.githubusercontent.com/108890713/219367991-e52a9585-2c72-4596-8096-9c603308212a.png)

## Calculations:
rise time = 2.5ns
fall time = 1.3ns
Here, rise time comes out to be nearly the double of the fall time.

## Observation:
It is observed that the output is AND of the two inputs and the rise time obtained is almost the
double of the fall time. This happens because of the delay of inverter also gets added during
the rise time. Also, we observe that the output obtained has lower voltage than the input
voltage. The reason is because the threshold voltage gets subtracted from the input.
