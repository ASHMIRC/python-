#python basics:
[FIBONACCI SERIES:]
        n=int(input("enter the number"))
        first=0
        second=1
        for i in range(n):
        print(first)
           temp=first
           first=second
           second=temp+first
[FINDING DUPLICATE CHARACTER IN A STRING:]
        string=input("enter the string")
        duplicate=[]
        for i in string:
           if string.count(i)>1:
             if i not in duplicate:
                duplicate.append(i)
        print(duplicate)

[ANOTHER WAY OF FINDING DUPLICATE:]

string=input("enter the string")
duplicate=[]
for i in string:
   if string.count(i)>1:
     if i not in duplicate:
       duplicate.append(i)
print(duplicate)

[FINDING FACTORIAL]

n=int(input("enter the number"))
temp=1
for i in range(1,n+1):
      temp=temp*i
print(temp)


[FINDING MATCH CASE]
match "a":
     case "a":
        print("a")
     case "b":
        print("b")
     case _:
       print("neither 'a' Nor 'b'")

[FINDING CHECKSUM]
       def check_sum(num)
match num:
  case num.isalpha():
    print("must be alphabets")
  case num.isdigit():
    print("must be numbers")
  case _:
    print("may be special symbol")
print(__name__)

[FINDING PRIME]
n=int(input())
if n<=2:
  print("it is a prime number")
for i  in range(2,n):
   if n%i==0:
     print("it is not a prime number")
     break
else:
      print("prime")

[REVERSE A STRING]
a=input()[::-1]
print(a)

string=input()
rev=string[::-1]
for i in string:
  rev=i+(rev)
  print(rev)

  [FINDING PERFECT NUMBER]

num=int(input())
tot=0
for n in range(1,num):
    if (num % n == 0):
        tot=tot + n
if (tot==num):
    print("it is perfect")
else:
    print("no perfect")


[PRINTING STAR PATTERN]
rows=int(input())
for i in range(1,rows+1):
  for j in range(1,i+1):
     print()

[FINDING AREA]

r=int(input())
area=3.14*r*r
print(area)


[FINDING AVERAGE]

n=int(input())
sum=0
count=0
for i in range(1,n+1):
  sum+=i
  count+=1
  avg=sum/count
print(avg)



















    
