# Assignment #1

### Tasks
* Continue watching Abe's video #2 (from 5:49 https://youtu.be/M4EkW4VwhcI?t=349)
* Watch video #3

Everybody in your group should get an IBM Q account, store their access token on their computer, and be able to use it, e.g., do the same as Abe in Video #3.

Familiarize yourself with the view on the IBM Quantum Experience website which shows the available quantum devices with their job queues.

Get a little deeper into the matter:
* Read the Qiskit overview on https://qiskit.org/documentation/the_elements.html

##### Programming assignment
* Write Qiskit code which creates a GHZ state *|000⟩+|111⟩/√2*, test it using the simulator which runs on your local computer.
* Run your quantum circuit on one of the quantum devices (pick one which has a short queue).
* Figure out how to change the number of *shots*, i.e., how often the quantum circuit is run. (This link will help: https://qiskit.org/documentation/apidoc/execute.html)

##### Hand in

1. Find a fancy name for your group
1. Create a sub-folder of this folder (Ooc-prog_qc/assignment-01) with that name
1. Upload (pull request) the following to your group's sub-folder:
     * A file containing a function `make_ghz3(shots, device)` which creates quantum circuit, sends it to the given quantum device to be run for the given number of shots. The function should return an object of the class `Result` (https://qiskit.org/documentation/stubs/qiskit.result.Result.html).
