# Computer Science Summer Work
### Tasks to do during the summer:
  * Organisation Skills
  * Notetaking 
  * Contextualisation
  * Abstract Thinking
  * Programming Skills - Algorithms
  * Logical Thinking - Pattern Recognition
  * Research and Critical Thinking

### Task:
#### Watch this Ted Talk on how computers learn to recognise objects instantly. After watching this video, discuss the benefits, limitations, and risks of the subject in the context of:
 * Travel and Tourism
 * Gaming and Entertainment
 * Education and Learning
 * Transport and Navigation
 * Medicine and Healthcare

### Outcome:
#### Record the answers on a page on your GitHub. For each given context – you will write a short paragraph of the benefits, limits, and risks of fast image recognition in the context presented.

### Response:
#### Travel and Tourism:

* Benefits - Allows for the security of airports to be heavily refined as luggages and bags pass through the screening system. Allows for any foreign travellers who are travelling to their holiday destination to be able to differenciate between certain objects within their own language, making it easier for those to be able to commute without having the need to ask other people within a different language. Will also allow for a much easier border control system, as humans, who have the ability to make mistakes when checking passports, will be fully replaced by a barrier utilising an image recognition software to gain access through.

* Limits - May not be as efficient or as effective as the current screening procedure (computer tomography (CT)), thus leading to slower boarding times and a higher probablity of minor delays as passengers will have to wait longer for their items to be checked and passed through security. 

* Risks - Should the image recognition algorithm fail for any reason (i.e. display the wrong word to a certain image), there is a probablity that dangerous items may be able to slip through the security section of an airport, leading to potential hijacks on a plane. In addition, tourists may find it inconvenient to pull out their phone to determine an object if there is a translator/tour guide present, as the translator/tour guide can easily determine and translate the requested object as opposed to the image recognition algorithm.

#### Gaming and Entertainment:

* Benefits - Allows for games to be enhanced for players who wish to integrate image recognition software should a game be compatible with it, as this could allow for gamers to easily be able to differenciate between any allies and potential enemies within a fighting game. In addition, cinemas may be able to use this service during screening to be able to detect any prohibited items such as cameras being used while the film is running, as cameras are strictly prohibited to avoid copyright issues.

* Limits - If a racing game requires a fast image recognition software, then there may be a probability that the software will be sluggish or a visual nuisance should the car be driving at a speed of 100 miles per hour. 

* Risks - Should the image recognition algorithm fail for any reason, this could potentially allow children to bypass the age restriction system that is implemented within certain games that are rated 18 plus, thus leading to children being exposed to inappropriate content. In addition, concerts who utilise image recognition software in order to detect any suspicious items before a show is set to begin may suffer from a breach in security if this software fails, thus leading to dangerous/prohibited items be able to reach into the concert.

#### Education and Learning:

* Benefits - Allows for teachers to be able to easily teach students the value of certain objects in a way that is interactive and modern for students, thus leading to a prolonged attention span during lessons, and decreased probability of students being distracted from the work. Will also heavily enhance the security of the school by allowing students to be verified using the image recognition app, thus leading to a more efficient registration system, and ensuring that any unwanted personnel are being identified to prevent any incidents such as school shootings from occurring. 

* Limits - Facial recognition software for allow for the names of the students to be verified, but will not be able to determine age, ethnicity, gender, etc. of that student.

* Risks - Any students who may have similar physical characteristics may lead to the image recognition system failing and registering the wrong student, thus leading to inconsistencies and major errors whenever fire alarm is set to go off within the school premises. Registering the wrong student will also lead to false reports when students are being given their attendance and punctuality record, which is vital information for both the school and the student.

#### Transport and Navigation:

* Benefits - Allows for CCTV cameras to easily be able to identify prohibited items present within a specific area, provided that the CCTV has the range to cover that area fully, whether it be within a platform, or bus stop. Allows for automatic driving to be enhanced making it safer for the driver, and allowing the automated system to detect whether an object is within close proximity to the car so that the car can decelerate and stop.

* Limits - Other systems will still have to implemented within a car to ensure that the car is fully capable of driving automatic, which will inevitably affect manufacturing costs and may render the car to only reach a smaller target market, as opposed to other cheaper automatic cars which do not utilise this system.

* Risks - A small defect in the image recognition system may render the car unsafe to drive, as failure to detect certain objects whilst the car is in drive mode may lead to potential collisions and external damage to the car itself. Failure for the image recognition system to detect the correct owner of a car may possibly lead to car theft and the ability for the attacker to steal any contents which may appear to be inside the car.

#### Medicine and Healthcare:

* Benefits - Allows for staff to ensure that any patient impersonation is rectified, and ensure that patients are being diagnosed efficiently and correctly, thus eliminating the possibility of human error which could potentially lead to the wrong medication/treatment for the patient and cause the patient to become more ill. Will also allow for any medication to be more accurately inserted into the patient, as the system can easily allow the administrator to focus into a specific section of a body with precision and ease.

* Limits - Any invasive surgeries which require the medical team to insert an object inside the body may not be able to utilise image recognition to detect abnormalities inside the body, due to the possible risk of infection. Ultrasound may still be heavily utilised in favour of executing this rather than image recognition. 

* Risks - A redundancy in staff as a result of implementing image recognition to debug most problems with regards to diagnosing a patient may lead to a larger proportion of skilled workers without any job, thus leading to protests and the loss of human interaction with the patient. Some patients may not like automacy of registering themselves and being diagnosed through an image recognition algorithm. 

### Task:
#### A palindrome is a word that reads identically backward or forward. Consider the word “RACECAR”, what steps would you take to identify whether it was a palindrome? Write these down using concrete terms. Do the same for another word “DEFIED”. Given the concrete examples, consider the generalized problem - informally describe an algorithm in English, that can identify any palindromes.

### Outcome:
#### In the course of thinking about the algorithm – you would replace the text sequence with an index. The index is the beginning of an abstraction. You would create a flow and probably repeat the process …. Fleshing out an algorithm. You would refine this until it becomes trivial to write the program.

### Research:
#### What other examples are there of abstractions in Computer Science?

### Response:

#### "RACECAR":

* Step 1 - Read the word "RACECAR" from left to right and proceed to read the word from right to left.
* Step 2 - Check whether the outer most letters are the same. In this case, both the first and last letter have the letter "R".
* Step 3 - If the outer most letters are the same, begin checking the next outer most letters (i.e. the 2nd and 6th letter of the word "RACECAR"). In this case both the 2nd and the 6th letters have the letter "A".
* Step 4 - Repeat this process until you have reached the middle letter of the word (i.e. the 4th letter which is "E"). If all other letters have been checked through thoroughly, then you can consider the word "RACECAR" to be a palindrome. 

#### "DEFIED":

* Step 1 - Read the word "DEFIED" from left to right and proceed to read the word from right to left.
* Step 2 - Check whether the outer most letters are the same. In this case, both the first and last letter have the letter "D".
* Step 3 - If the outer most letters are the same, begin checking the next outer most letters (i.e. the 2nd and 5th letter of the word "DEFIED"). In this case both the 2nd and the 5th letters have the letter "E".
* Step 4 - Next, begin checking the next outher most letters (i.e. the 3rd and 4th letter of the word "DEFIED"). In this case the 3rd letter "F" does not correspond with the 4th letter "I". As a result, you cannot consider the word "DEFIED" to be a palindrome.

#### Informal Algorithm:

* Step 1 - Determine whether the word has a total of even or odd letters.
* Step 2 - Begin with the outer most letters and proceed until you have reached the middle letter (if the word happens to contain an odd set of letters). Only proceed if the outer most letters are equal. Use a comparison operator for this.
* Step 3 - If all letters are equal (with the exception of the middle letter for any word that contains an odd set of letters), then you may consider and print out the statement that this word is a palindrome. 

#### Other examples of abstractions in Computer Science may include:
* A car
* A microwave
* An ATM machine
* Pressing the stop button on a bus
* Playing the piano

### Programming Skills - Algorithms
#### Register with Sololearn and Repl.It . SoloLearn is an online learning platform for programming. Repl.it is an online platform that allows you to code without the need to install a programming development environment on your machine. On Sololearn, select the Python Learning course, and complete modules 1, 2 and 3 that cover fundamentals of programming. Throughout the materials, Sololearn provides you with a button that runs the example code provided - however, rather than running the example programs written in Python on Sololearn - type the code out in Repl and run it there. The act of typing these examples is Active Learning.")
#### Module 1 - Welcome to Python! to Quotient and Remainder
print("Hello World!")
print("Hi")
print('Hello world!')
print('Hello world!')
print('Spam and eggs...')

print(2 + 2)
print(5 + 4 - 3)
print(2 * (3 + 4))
print(10 / 2)

print(3 / 4)
print(0.42)
print(8 / 2)
print(6 * 7.0)
print(4 + 1.65)
print(1 + 2 + 3 + 4.0 + 5)

print(2 ** 5)
print(5 ** 3)
print(9 ** (1 / 2))
print(8 ** (1 / 3))

print(20 // 6)
print(10 // 4)
print(20 % 6)
print(1.25 % 0.5)
print(7 % (5 // 2))

offer2 = 0.01 * (2 ** 30)
print(offer2)

#### Module 2 - Strings to In-Place and Walrus Operators
print("Python is fun!")
print('Always look on the bright side of life')
print('Brian\'s mother: He\'s not an angel. He\'s a very naughty boy!')

print('One\nTwo\nThree')
print("""This is a multiline text""")

print("Spam" + 'Eggs')
print("2" + "2")
print("Spam" * 3)
print(4 * '2')

user = "James"  
age = 42
This_is_a_normal_name = 7

x = 7
print(x)
print(x + 3)
print(x)
spam = "Eggs"
print(spam * 3)
x = 123.456
print(x)
x = "This is a string"
print(x + "!")

x = input()
print(x)
name = input("Enter your name: ")
print("Hello, " + name)

age = int(input())
print(age)
age = 42
print("His age is" + str(age))
name = input()
age = input()
print(name + " is " + age)

x = 2
print(x)
x += 3
print(x)
x = "Spam"
print(x)
x += "Eggs"
print(x)
num = int(input())
print(num)
print(num:=int(int(input()))

x = int(input())
y = int(input())
total = (x + y)
print(total)

#### Module 3 - Booleans and Comparisons to Range
my_boolean = True
print(my_boolean)
print(2 == 3)
print("hello" == "hello")
print(1 != 1)
print("eleven" != "seven")
print(2 != 10)
print(7 > 5)
print(10 < 10)
print(7 <= 8)
print(9 >= 9.0)
print("Annie" > "Andy")

if 10 > 5:
  print("10 greater than 5")
print("Program ended")
num = 12
if num > 5:
  print("Bigger than 5")
  if num <= 47:
    print("Between 5 and 47")

x = 4
if x == 5:
  print("Yes")
else:
  print("No")
num = 3
if num == 1:
  print("One")
elif num == 2:
  print("Two")
elif num == 3:
  print("Three")
else:
  print("Something else")

print(1 == 1 and 2 == 2)
print(1 == 1 and 2 == 3)
print (1 != 1 and 2 == 2)
print (2 < 1 and 3 > 6)
print(1 == 1 or 2 == 2)
print(1 == 1 or 2 == 3)
print (1 != 1 or 2 == 2)
print (2 < 1 or 3 > 6)
print(not 1 == 1)
print(not 1 > 7)

print(False == False or True)
print(False == (False or True))
print((False == False) or True)
grade = 88
if (grade >= 70 and grade <= 100):
  print("Passed!")

words = ["Hello", "world", "!"]
print(words[0])
print(words[1])
print(words[2])
empty_list = []
print(empty_list)
number = 3
things = ["string", 0, [1, 2, number], 4.56]
print(things[1])
print(things[2])
print(things[2][2])
m = [
  [1,2,3],
  [4,5,6]
]
print(m[1][2])
str = "Hello world!"
print(str[6])
nums = [7, 7, 7, 7, 7]
nums[2] = 5
print(nums)
nums = [1, 2, 3]
print(nums + [4, 5, 6])
print(nums * 3)
words = ["spam", "egg", "spam", "sausage"]
print("spam" in words)
print("egg" in words)
print("tomato" in words)
nums = [1, 2, 3]
print(not 4 in nums)
print(3 not in nums)

nums = [1, 2, 3]
nums.append(4)
print(nums)
nums = [1, 3, 5, 2, 4]
print(len(nums))
words = ["Python", "fun"]
index = 1
words.insert(index, "is")
print(words)
letters = ['p', 'q', 'r', 's', 'p', 'u']
print(letters.index('r'))
print(letters.index('p'))
print(letters.index('z'))

i = 1
while i <= 5:
  print(i)
  i = i + 1
print("Finished!")
x = 1
while x < 10:
  if x % 2 == 0:
    print(str(x) + " is even")
  else:
    print(str(x) + " is odd")
  x += 1
i = 0
while True:
  print(i)
  i = i + 1
  if i >= 5:
    print("Breaking")
    break
print("Finished")
i = 1
while i <= 5:
  print(i)
  i += 1
  if i == 3:
    print("Skipping 3")
    continue 

words = ["hello", "world", "spam", "eggs"]
for word in words:
  print(word + "!")
str = "testing for loops"
count = 0
for x in str:
  if (x == 't'):
    count += 1
print(count)

numbers = list(range(10))
print(numbers)
numbers = list(range(3, 8))
print(numbers)
print(range(20) == range(0,20))
numbers = list(range(5, 20, 2))
print(numbers)
for i in range(5):
  print("Hello!")

n = int(input())

for x in range(1, n):
    if x % 3 == 0 and x % 5 == 0:
        print("SoloLearn")
    elif x % 2 == 0:
        continue
    elif x % 3 == 0:
        print("Solo")
    elif x % 5 == 0:
        print("Learn")
    else:
        print(x)
