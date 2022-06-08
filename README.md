# Python-ta-
Code to determine if a number is a prime number
# src/app.py

def solution(n):
    
# Program to determine prime numbers
number = int(input ("Enter your number: "))
if number > 1: 
  for I in range(2, number):
    if number%i ==0:
        print (f"{number} is not a prime number.")
        break
    else:
       print (f"{number} is a prime number.")
#end of code

if __name__ == "__main__":
    if len(sys.argv) <= 1:
        sys.exit(os.error("Argument required"))

    n = int(sys.argv[1])
    print(solution(n))
