Submission by Kristian Snyder
Part 1 is located at part1.pdf, with source at part1.md.
Example run of part 2 is in proof.png.

To run part 2 (this info is also in part2-river.frl):

1. Open FRIL REPL
2. reload "depth_first.frl" (sample file given)
3. reload "part2-river.frl" (successor function, invalidation testing)
4. ?((solve_DF (n n n n n n n) (s s s s s s s) S))
   the above means try and move the missionaries, the cannibals, 
   and the boat from the north to the south
