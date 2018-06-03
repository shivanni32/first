t=0
p=0
import math
def rle( ):
        global p
        global t
        n1=int(input("enter left position"))
        p=p-n1
def rrig( ):
        global p
        global t
        n2=int(input("enter right position"))
        p=p+n2
def rup( ):
        global p
        global t
        n3=int(input("enter up  position"))
        t=t+n3
def rdow( ):
        global p
        global t
        n4=int(input("enter down position"))
        t=t-n4
def cal( ):
    print(round(math.sqrt(p**2+t**2)))
f=1
while f:
        print("1.left")
        print("2.right")
        print("3.up")
        print("4.down")
        print("5.calculate")
        print("6.exit")
        s1=int(input("enter choice"))

        if(s1==1):
                rle( )
        elif(s1==2):
                rrig( )
        elif(s1==3):
                rup( )
        elif(s1==4):
                rdow( )
        elif(s1==5):
                cal( )
        elif(s1==6):
                f=0
        else:
                print("enter valid input")


        
