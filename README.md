# Patterns_in_python
 ### 1.
       *
       * *
       * * *
       * * * *
       * * * * *

## code:
    num = int(input("enter the number of rows"))
    for i in range(1,num+1):
       for j in range(1,i+1):
          print("*",end=" ")
        print()
        
### 2.
       *
       * * *
       * * * * *
       * * * * * * *
       * * * * * * * * *
## code:
       num = int(input("enter the number of rows:"))
       k=1
       for i in range(1,num+1):
           for j in range(1,k+1):
               print("*",end=" ")  
           k=k+2    
           print()    
   
 ### 3. 
         *
        * *
       * * *
      * * * * 
     * * * * *
      
## code:
        num=int(input("enter the number of rows:"))
        for i in range(0,num):
            for j in range(0,num):
                print(end=" ")
            for j in range(0,i+1):
                 print("*", end=" ")
            print()        
### 4.
       * * * * *
       * * * * 
       * * *
       * *
       *
## code:
        num=int(input("enter the number of rows:"))
        for i in range(num,0,-1):
           for j in range(0,num-i):
              print(end="")
           for j in range(0,i):
               print("*",end="")
           print()
### 5.
      * * * * *
       * * * *
        * * *
         * *
          *
      
## code:
        n=int(input("enter the no of rows:"))
        for i in range(1,n+1):
            for j in range(1,n+1):
                if j>=i:
                    print("*",end='')
                else:
                    print(" ",end='')
             print()  
      
