# Homework №4

```
	1.	Ինչ կտպի mro() method-ը և ինչու(փորձեք research անել, հասկանալ ալգորիթմը և բացատրել)

		class A(object):
			def __init__(self):
				print ("A")

		class B(A):
			def __init__(self):
				print ("B")

		class C(A):
			def __init__(self):
				print ("C")

		class D(B, C):
			def __init__(self):
				print ("D")

		print(D.mro())
		
	2.	Գրել AbstractFile class որը կունենա translate() և write() method (որոշեք թե որը պետք է լինի abstract և որը սովորական method)
	
		2.1 Գրել EnglishFile class որը կլինի AbstractFile-ի ժառանգ
		
		2.2 translate() method-ը պետք է ընդունի ռուսերեն տառերով գրված տեքստ և վերադաձնի անգլերեն տառերով գրված տեքստ:
		    Մեծատառ և փոքրատառ հաշվի չառնել:

		2.3 write() method-ը արդեն թարքմանված տեքստը պետք է գրի file-ում:
		
		2.4 Գրել RussianFile class որը կունենա նույն method-ները բայց տեքստը անգլերենից կդարձնի ռուսերեն:

	Օրինակ ՝	hello world -> хелло ворлд
			писать код  -> pisat kod
			
				
```

### Research
```
	1. super() in multiple inheritance
```


### Links

```
Կարաք օգտվեք ստեղից

https://www.programiz.com/python-programming/multiple-inheritance
https://www.geeksforgeeks.org/abstract-classes-in-python/
```
