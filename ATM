#Bank ATM function

#input number of Rs.2000,Rs.500,Rs.100,Rs.20 in ATM Machine
s2000=int(input())
s500=int(input())
s100=int(input())
s20=int(input())
goal=int(input())

def denomination(s2000,s500,s100,s20,goal):
    #Assigning Sum values
    s1=0
    s2=0
    s3=0
    s4=0
    #Check whether the amount is divisible by 20
    if goal%20==0:
        #if the amount is greater than 2000 
        while goal>=2000:
            if s2000>0:
                goal=goal-2000
                s1=s1+1
                s2000=s2000-1
                break
        #if the amount is greater than 500 and lesser than 2000    
        while goal>=500 and goal<2000:
            if s500>0:
                goal=goal-500
                s2=s2+1
                s500=s500-1
                break
        #if the amount is greater than 100 and lesser than 500   
        while goal>=100 and goal<500:
            if s100>0:
                goal=goal-100
                s3=s3+1
                s100=s100-1
                break
        #if the amount is greater than 20 and lesser than 100   
        while goal>=20 and goal<100:
            if s20>0:
                goal=goal-20
                s4=s4+1
                s20=s20-1
                break
        #if cannot provide full amount
        if goal>0:
            print(0)
            
        #if full amount can be satisfied
        else:
            print(s1,s2,s3,s4)
    #if the amount is not divisible by 20
    else:
        print(0)
            
denomination(s2000,s500,s100,s20,goal)
