# Topology_solver
Calculates accurate result of Topology
Problem statement: write a program to count the number of preorders of a set of N elements for small N elements. For example, consider a set of 3 elements A={1, 2, 3}. From this set, we can make 29 suborders:

Or, the problem can be solved by counting the number of all possible topologies:

 1. {(1, 1), (2, 2), (3, 3)} 
 2. {(1, 1), (2, 2), (3, 3), (1, 2)} 
 3. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3)} 
 4. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (2, 1), (2, 3)}
 5. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (2, 1), (2, 3), (3, 1), (3, 2)}
 6. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (2, 3)}
 7. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (2, 3), (3, 2)}
 8. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (3, 1), (3, 2)}
 9. {(1, 1), (2, 2), (3, 3), (1, 2), (1, 3), (3, 2)}
10. {(1, 1), (2, 2), (3, 3), (1, 2), (2, 1)}
11. {(1, 1), (2, 2), (3, 3), (1, 2), (2, 1), (3, 1), (3, 2)}
12. {(1, 1), (2, 2), (3, 3), (1, 2), (3, 1), (3, 2)}
13. {(1, 1), (2, 2), (3, 3), (1, 2), (3, 2)}
14. {(1, 1), (2, 2), (3, 3), (1, 3)}
15. {(1, 1), (2, 2), (3, 3), (1, 3), (2, 1), (2, 3)}
16. {(1, 1), (2, 2), (3, 3), (1, 3), (2, 1), (2, 3), (3, 1)}
17. {(1, 1), (2, 2), (3, 3), (1, 3), (2, 3)}
18. {(1, 1), (2, 2), (3, 3), (1, 3), (3, 1)}
19. {(1, 1), (2, 2), (3, 3), (2, 1)}
20. {(1, 1), (2, 2), (3, 3), (2, 1), (2, 3)}
21. {(1, 1), (2, 2), (3, 3), (2, 1), (2, 3), (3, 1)}
22. {(1, 1), (2, 2), (3, 3), (2, 1), (2, 3), (3, 1), (3, 2)}
23. {(1, 1), (2, 2), (3, 3), (2, 1), (3, 1)}
24. {(1, 1), (2, 2), (3, 3), (2, 1), (3, 1), (3, 2)}
25. {(1, 1), (2, 2), (3, 3), (2, 3)}
26. {(1, 1), (2, 2), (3, 3), (2, 3), (3, 2)}
27. {(1, 1), (2, 2), (3, 3), (3, 1)}
28. {(1, 1), (2, 2), (3, 3), (3, 1), (3, 2)}
29. {(1, 1), (2, 2), (3, 3), (3, 2)}
