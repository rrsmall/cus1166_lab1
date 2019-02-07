print("Hello World")

#with just input() I recieved errors
myname = raw_input("What is your name: ")
print("Hello " + str(myname))

print("Hello again %s" % myname)

i = 120
print("Variable i has the value {i}")

f = 1.6180339
print("Variable f has the value {f} and its type of {type(f)}")

b = True
print("Variable has the value {b}")

n = None
print("Variable n has the value {n}")

c = (10,20,10)
print("c[0] has the value {c[0]} and is of type: {type(c)}")

s = set()
s.add(1)
s.add(4)
s.add(6)
print(s)

grades = {"Tom" : "A", "Mark" : "B-"}
grades["Tom"]
grades["Anna"] = "F"
print(grades)

mydictionary = dict()

x=10
if (x>0):
    print("The number x is positive")
elif(x<0):
    print("The number x is negative")
else:
    print("The nmber x is zero")

for i in range(5):
    print(i)

#for i_idx, i value in enumerate(range(2,10))
#    print(f"{i_idx} - {i_value}")

def is_even(x):
    if(x % 2) == 0:
        return True
    else:
        return False

class Book:
    def __init__ (self, title="Software Engineering", isbn=""):
        self.title = title
        self.isbn= isbn
    def printBok(self):
        print(self.title + "," + self.isbn)

def square(x):
    return x*x

def main():
    pass

#if __name__ == "__main__"
#    main()

#from mymodule.helper_utils import square
#print(square(100))
