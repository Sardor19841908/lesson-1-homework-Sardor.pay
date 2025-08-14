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
        print('kabisa yili')
else:
    print('kabisa yili emas')          
    
