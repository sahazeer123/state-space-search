# state-space-search
implemented state search space problems in c
I have implemented jug problem using backtracking.We have initial state and final goal state.To reach final state state space search is required.So i defined 6 transition function to generate  state.Each transition function produces new state.New state is checked if it is valid or not.If it is valid and not repeated it is added to doubly linked list.If the produced new state is not valid function produces another state using other transition functions.If no transition function is able not able to produce valid state,the last state is removed (basically backtracking concept).
                                     If i reached goal state i print the content of doublylist.I have to print 
all the list content until my list becomes NULL.It happens only when after all backtracking.Finally print the count of number of possible solution.  
