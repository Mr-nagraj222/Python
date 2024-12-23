# Python
1️⃣ Reverse a string without using Python slicing.
string="Nagaraju"

def reversestring(string):
    lst=[]
    for i in range(len(string)-1,-1,-1):
        lst.append(string[i])
    return "".join(lst)


reversestring(string)

############################Aother Way ##############################|
string="Nagaraju"

def reversestring(string):
    rev_string=""
    for ch in string:
        rev_string=ch+rev_string
    return rev_string


reversestring(string)

############################Aother Way ##############################|
string="Nagaraju"

def reversestring(string):
    return string[::-1]    


reversestring(string)

############################Aother Way ##############################|

string="Nagaraju"

def reversestring(string):
    return "".join(reversed(string))    


reversestring(string)