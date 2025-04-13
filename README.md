# MY_first
This some what you can say is tutorial
def multi(x):
    if x == 0:
        return 1
    else:
        x = multi(x-1)
        print(x)
        y = x * multi(x-1)
        print(y)

        return y
        
        

    
multi(4)
this is my first day of understanding the recursion of functions
