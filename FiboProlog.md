# Code: 



          fib(0,0).
             fib(1,1).
             fib(X,Y):- 
    
               X > 1,
               A is X-1,
               B is X-2,
               fib(A,F1),
               fib(B,F2),
               Y is F1+F2. 
               
               
 # Query
 
      
            fib(3,V)
