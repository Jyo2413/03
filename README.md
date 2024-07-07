(using built-in functions):
import statistics
Numlist = []
n = int(input("Enter the value of n : "))
for i in range(0, n):
 ele = int(input('Enter number '+ str(i+1)))
 Numlist.append(ele)
print('The list of elements is',Numlist)
print('Mean=',statistics.mean(Numlist));
print('Variance=',statistics.variance(Numlist));
print('Standard deviation=',statistics.stdev(Numlist));





def BinToDec(b):
return int(b, 2)
bnum = input("Enter a Binary Number: ")
dnum = BinToDec(bnum)
print("Equivalent Decimal Value = ", dnum)
def OctToHex(o):
return hex(int(o, 8))
onum = input("Enter an Octal Number: ")
hnum = OctToHex(onum)
print("Equivalent Hexadecimal Value =", hnum[2:].upper())
