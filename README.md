# My first MD file
## Section 1
**list**   
* three spaces is a return in md
* 1 hash# is biggest, 6 hashes# is smallest
---
---
## Section 2
**Picture**   
![This is my picture info.](random.png)   

---
---
## Section 3
``` python
for i in list:
    print("Hello World")
```
``` python
# Activity 1 (page 17)

# Create a list of 100 random numbers
def createRandomList(amount,min_value,max_value):

    '''args

    amount: amounr of number to be created
    min_value: smallest number to be created
    max_value: largest number to be created'''

    # initialize list
    random_numbers = []

    #Create a random number and append it to the list amount times
    for _ in range(amount):
        random_num = random.randint(min_value, max_value)
        random_numbers.append(random_num)
    
    return random_numbers

list_of_random_numbers = createRandomList(100, 1, 100)

print(list_of_random_numbers)
```