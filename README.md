def countApplesAndOranges(s, t, a, b, apples, oranges):
    # Write your code here
    count=0
    sum=0
    for i in apples:
        i+=a
        if(i>=s and i<=t):
            count+=1
    print (count)
    for j in oranges:
        j+=b
        if (j>=s and j<=t):
            sum+=1
    print(sum)
        
