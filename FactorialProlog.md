# Code 

         fact(0,1).
           fact(M,N):-
              N1 is M-1,
              fact(N1,M1),
              N is M1*M.
    
    
# Query


         fact(5,V)
