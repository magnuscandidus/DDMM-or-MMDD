# DDMM-or-MMDD
# cook your dish here
for i in range(int(input())):
    d  = list(map(int,input().split('/')))
    if d[0]<=12 and d[1]<=12 :
        print("BOTH")
    elif d[0]<=12 and d[1]>12 :
        print("MM/DD/YYYY")
    elif d[0]>12 and d[1]<=12 :
        print("DD/MM/YYYY")
    
    
