# Assignment-2
Write a Python function that takes in a string and returns the string with all the vowels removed.
def fun(str):
    vowels="AEIOUaeiou"
    answer=""
    for i in str:
        if i not in vowels:
            answer+=i
    return answer
str="Lets Upgrade"
fun(str)
