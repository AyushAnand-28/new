def climbStairs(n):
    if n==0 or n==1 or n==2:
        return n
    return climbStairs(n-1)+climbStairs(n-2)
