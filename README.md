# lesson-1-homework-Sardor.pay
dars 
## set, conditional, statement
# str, dictionary, tuple, int, float, list
# mutable \ imutable
# mutable --- list,dict
# imutable --- str, tuple, int, float
# ordered \ unordered
# ordered --- list, tuple, str
# unordered --- dict, set
s = {1,2,3,'a', 'gvahd'}
# rules for set creation
# rule 1 --- Har bir element ozgarMAS BOLISHI KERAK
# rule 2 --- har bir element faqat bir marta ishlatilishi mumkin
# rule 3 ------ unordered -- indexing va slicing set da ishlatilmaydi !!  
s = {1,2,3,[1,2,3]}
s
s.add (45)
s
s.copy()
s2 = copy
s2
ls = {"akmal", "anvar", "malika", "akmal"}
set(ls)
colors = ['blue', 'white', 'green', 'blue', 'green']
set(colors)
ls = {"akmal", "anvar", "malika", "akmal"}

set(ls)
colors = ['blue', 'white', 'green', 'blue', 'green']

set(colors)
s1 = {1,2,3,4}
s2 = {3,4,5,6}

s1.intersection(s2)
s1 & s2
s1.difference(s1)
s1.difference(s2)
s2.difference(s1)
s1.union(s2)
s1 | s2
s1 - s2
s1 | s2 - s2 - s1
# Conditional statement
## bolean --- bool 
## bolean --- bool 
True
False
None
bool(1)
bool(-1)
# rule 1 true agar 0 dan boshqa har qanday holatda
# rule 1 true agar 0 dan boshqa har qanday holatda
bool(1)
bool(0)
bool('')
# comparison --- >,>=,<,<=,==,!=
4>5
a = 3
a = 3
a == 3
a = 5
a != 3
if 2 < 5;
if 2 < 5:
if 2 < 5:
    print('success')
    if 2 == 5:
    print('success')
    age = int (input("yosingni kirit"))
if age>=18:
    print("San prava olishing mumkin")
else:
    print ('Yoshing yetarli emas')
    age = int (input("yosingni kirit"))
if age>=18:
    print("San prava olishing mumkin")
else:
    print ('Yoshing yetarli emas')
city = input ("qayerda yashaysan? ")
if city == 'Tashkent':
    print('seni ishga olamiz')
else:
    print('uzur,kechirasan')
    result = int(input("ielts balini sorash? ")) 
if result >= 7:
    print('sanga 2 mln beramiz')
else:
    print('uzur,kechirasan, ukam damini ol hech narsa yoq senga')
    products = ['laptop', 'monitor', 'mouse']
product_sold = input("nima sotib olding")
if product_sold in products:
    print('senga katta chegirma bor')
else:
    print('kechirasan senga hech narsa yoq')    
    hafta_kuni = int(input("hafta kunini kirit"))
if hafta_kuni == 1:
    print ("bugun Dushanba")
elif hafta_kuni == 2:
    print ("bugun Seshanba")
else:
    print ("notogri malumot") 
    age = int(input("yoshingni kirit"))
if age>=18:
    yes_prava = input("Haydovchilik guvohnomasi bormi yoki yoq")
    if yes_prava == 'Ha':
        print ('oq yol')
    else: 
        print ('Siz prava bor')
else:
    print('Uzr prava yoq')
year = int(input('yilni kiriting'))
if year%4==0:
    if year%100 == 0:
        if year%400 ==0:
            print('kabisa yili')
        else:
            print('kabisa yili emas')
    else:
    def Social_depart(name):
    print(f"Social{name}, department")
Social_depart('department')

        print('kabisa yili')
else:
    print('kabisa yili emas')          

    # funksiya ---
## bulit+in --- pyton ozida mavjud funcionlar
## user-defined
id('hello')
def my_function(): # --- snake_case ---
    print('Hello')
    my_function()
    def my_function():
    print('Social')
    def Social_depart(name):
    print(f"Social{name}, department")
Social_depart('department')
def taklifnoma (name='fuqaro', ziyofat='tugilgan kun'):
    print(f"Salom {name}, seni {ziyofat}ga taklif etaman")
taklifnoma (name= 'Sardor', ziyofat="toy")
def taklifnoma (name='fuqaro', ziyofat='tugilgan kun'):
    print(f"Salom {name}, seni {ziyofat}ga taklif etaman")
taklifnoma (name= 'Sardor', ziyofat="toy")
def taklifnoma (name='fuqaro', qotarga='mazza qilib pivo, konyak, tekkila ichish kuniga'):
    print(f"Salom {name}, seni {qotarga}ga taklif etaman")
taklifnoma ("Javlon")

def add_numbers(a,b):
    print(a+b)

add_numbers(10,10)
def my_function(nembers):
    res = i
    for i in numbers:
        res = res * icn
    print('60**2')
add_numbers(120)
def my_function(n):
    for i in range (1,n):
        if 2**i<n:
            print(2**i)
my_function(100)
def my_function(n):
    for i in range (1,n):
        if 2**i<n:
            print(2**i)
my_function(350)
def my_function2(n):
   a=1
   while 2**i<n:
            print(2**a)
my_function(21)
def power_two(number):
    num = 1
    # kiyik --- kiyik -- palindrome
чапдан ва ўнгдан ўқигандан тўғри ёзилиши 
def pol_func(soz):
    b=soz[::-1]
    if soz == b:
        print ('kiyik')
    else:
        print ('kiyik emas')
pol_func('polidrom')

    while 2**num < number:
        print(2**num)
        num = num+ 1
power_two(100)

def pol_func(soz):
    b=soz[::-1]
    if soz == b:
        print ('kiyik')
    else:
        print ('kiyik emas')
pol_func('polidrom')
## print
## return

def test():
    print('Hello')
test()
def test():
    return 'Hello'
test()
a = 5 
def test():
    print ('Hello')
a = test()
print(a)
def test():
    return 'Hello'
b = test()
b
def replace_value(name):
    with open('exampla.txt') as f:
        data = f.read()
        data = data.replace('Javlon', name)
        return data
new_data = replace_value('Sardor')
with open('exampla.txt', 'w')  as f:
        f.write(new_data)
        # d = {"blue":3, "red":1, "yellow":1, "green":2}

d = {}

for word in ls:
    if word not in d.keys():
        d[word] = 1
    else:
        d[word] = d[word] + 1
d
ls = ['blue','red', 'yellow', 'green', 'blue', 'green']
def func3(rang):
    return ls.count(rang)
d={}
for r in ls:
    d[r]=func3(r)
d
def factorial(num):
    if num in [20]:
        return 5
    else:
        return num * factorial (num-5)
factorial (20)    
