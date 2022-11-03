
fib::Int->Int
fib n|n==0=0
fib n|n==1=1
fib n|n/=0=fib(n-1)+fib(n-2)


main = do
        putStrLn("Enter the fib index: ")
        ain<-getLine
        let n = (read ain:: Int)
        print(fib n)
