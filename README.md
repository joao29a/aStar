aStar
=====

A* Algorithm

Note: If you only want to use the AStar algorithm, you need to create another class
    and inherit the AStar class. It is necessary to implement the heuristicEstimate,
    distBetween and neighborNodes methods in order to use. The implementation is according
    to your problem.

NumberPuzzle Execution:
    It is necessary to pass five arguments on command line
        - 1st: Input file. Containing the beginning state
        - 2nd: Outfile file. Containing the desired state (Goal)
        - 3rd: The weight of the first heuristic (0 if you don't want to use)
        - 4th: The weight of the second heuristic
        - 5th: The weight of the third heuristic

    Example:
        $ python2.7 NumberPuzzle.py examples/Exemplo1.txt goal.txt 0 0 1
