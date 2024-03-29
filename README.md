# white-leap
## Did the leap quantum?

All the following assumes that I've understood correctly what I've read and 
learned. These are just notes to assist with *my own* learning process.
Most of the following is drawn from or inspired by the demo's and
documentation from https://cloud.dwavesys.com/leap.

Quantum computing (QC) **could** solve "N=NP?" since QC has something to do
with Shor's algorithm which pwns prime factorization (help) and "Prime 
factorization [...] is widely believed to be NP-complete."<sup>[1]</sup> 
and "[...] if anyone ever comes up with a polynomial-time solution to an 
NP-complete problem, that will also give a polynomial-time solution to any 
NP problem."<sup>[2]</sup>

So are we simply waiting for QC with enough qubits? Does it matter if it is
universal gate QC or quantum annealing QC?

## constraint satisfaction problem 

## Reversing classical boolean logic
Is it possible to reverse a classical boolean logic circuit?
If we have an OR gate with 2 inputs and 1 output, there seems no way to
deduce from True or False the exact configuration of the input, as there
are multiple possibilities.
For example, if OUTPUT is 1 there are 3 possible configurations for INPUT:
```
INPUT   OUTPUT
A   B   C
0   1   1
1   0   1
1   1   1
```

I'm not sure what QC does here exactly, but it returns minimal values, but
apparently not necessarily the minimum value. In the first from Leap about
a multiplication circuit, there can be multiple valid input values.
I suppose that in contrast with classical computing one does not have to
validate candidate input values. How this then works in QC still boggles
my mind.


[1]: https://www.nature.com/articles/srep43048
[2]: https://stackoverflow.com/a/127831
