# peptide_combination_problem
Drug discovery is a costly and time consuming process that usually involves experimentally testing
molecules (drug candidates) in a wet-lab in order to assess their efficacy. More than often, combinations
of molecules could lead to better efficacy.

The intuition behind using combination of molecules is that, if a molecule A has good efficacy, and another
molecule B also does, one might expect them to be as good or better together than individually (even
though this might not always hold).

Additionally, the number of possible combinations of molecules grows quite quickly with the number of
molecules (and testing molecules costs a lot of money!), meaning we need to be clever while designing
ways to evaluate sets of molecules.

This process involves automation of the wet-lab tests and you have been assigned with the task of defining
a strategy to optimise combinations of molecules against their antiviral effect.

You receive a very long list of n molecules as input and is also given access to the automation robot that will
do the wet-lab tests, through a programming interface, via the function test wet lab robot(mol[1 . . . k]).
It receives a list of one or more molecules as input and returns a positive number denoting the efficacy of
the molecule(s) (the larger this value, the better!).

Your job is to develop algorithms that optimises molecule efficacy, given a set of molecules, using the robot
as little as possible.

![image](https://user-images.githubusercontent.com/19381768/197389173-99ff7ee9-5180-4722-9874-fd2b2154f7a4.png)

figure. peptide permutation problems

image source: https://www.fhybea.com/en/permutation-definition-examples.html

# pseudocode problems
(a) Describe with your own words (and in pseudocode) two different greedy approaches to optimise the
combination of molecules, one with linear time complexity (O(n)) and the other with quadratic time
complexity (O(n2)), where n is the number of input molecules. Remember that the most costly
operation is the function test wet lab robot.

(b) Do any of your approaches always find the optimal solution? (e.g., does this problem have optimal
substructure?) Briefly justify.
