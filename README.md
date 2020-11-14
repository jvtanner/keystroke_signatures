# keystroke signatures

Did you know that computers can identify you not only by what you write, but also by how
you write? Coursera uses Biometric Keystroke signatures for plagiarism detection. If you
cannot write a sentence with the same statistical distribution of key press timings as in your
previous work, they assume that you are not the person sitting behind the computer. In this
problem we provide you with three files:

• personKeyTimingA.txt has keystroke timing information for a user A writing a
passage. The first column is the time in milliseconds (since the start of writing) when
the user hit each key. The second column is the key that the user hit.
• personKeyTimingB.txt has keystroke timing information for a second user (user B)
writing the same passage as the user A. Even though the content of the passage is the
same the timing of how the second user wrote the passage is different.
• email.txt has keystroke timing information for an unknown user. We would like to
know if the author of the email was user A or user B.


Let X and Y be random variables for the duration of time, in milliseconds, for users A and B (respectively) to type a key. Assume that each keystroke from a user has a duration that is an independent random variable with the same distribution.

a. [Coding] Complete the function part_a provided in the starter code. This function takes
in a filename (which is either personKeyTimingA.txt or personKeyTimingB.txt) and should return E[X] or E[Y], respectively.
b. [Coding] Complete the function part_b provided in the starter code. This function
should return E[X2] or E[Y 2], depending on which file is supplied as filename.
