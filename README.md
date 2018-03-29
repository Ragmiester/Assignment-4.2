# Assignment-4.2
d=list(map(str,input("enter the words: ").split(" ")))
def lenlet(x): return len(x)
ans=list(map(lenlet, d))
print("lenght of words are: ", ans)
a=input("Enter the charecter to check vowel: ")
def vche(x):
    if x in "AEIOUaeiou": return True
    else: return False
ans=list(map(vche, a))
print(ans)
