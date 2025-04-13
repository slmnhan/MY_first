# MY_first
This some what you can say is tutorial
def multi(x):
<br>
    if x == 0:
    <br>
        return 1
 <br>
    else:
     <br>
        x = multi(x-1)
       <br>
        print(x)
       <br>
        y = x * multi(x-1)
       <br>
        print(y)
<br>
        return y
    <br>    
        

    
multi(4)
this is my first day of understanding the recursion of functions