# Homework №8

```
	1.	Ուղարկված link-երից ներբեռնել lexus.txt և tesla.txt file-երը:
	
	2.	Գրել File class որը կունենա
		
		
		2.1	__init__ method որը կգտնի և կվերագրի file attribute-ին
			գտած file-ը: File-ը գտնել ըստ child class-ի անունի:
			
			Օրինակ ՝	>>> class Tesla(File):
					>>>     pass
					>>> 
					>>> tesla = Tesla()
					>>> tesla.file # file object
					<_io.TextIOWrapper name='tesla.txt' mode='r' encoding='cp1251'> 
					self.file = file
					
			Եթե class-ի անունով file չլինի սարքել նորը:
		
		2.2 Գրել child_file attribute որը կունենա getter, setter, deleter
			
			getter - վերադարձնում է ժառանգ class-ի անունով file-ի text-ը:
			setter - կփոխի ժառանգ class-ի անունով file-ի text-ը:
			deleter - կջնջի ժառանգ class-ի անունով file-ը:
		
		2.3 Գրել Tesla և Lexus class-ներ որոնք կլինեն File class-ի ժառանգ:
			
			Օրինակ`		>>> class Lexus(File):
					>>>     pass
					>>>
					>>> lexus = Lexus()
					>>> lexus.child_file # print text from file lexus.txt
					1,Lexus_IS,Sedan,Gasoline ...
					>>> lexus.child_file = 'New text about lexus'
					>>> lexus.child_file # New text about lexus
					New text about lexus
					>>> del lexus.child_file # remove lexus.txt file
					>>> lexus.child_file # error
		
		2.4	Գրել method որը rename կանի child file-ի անունը:
```


### Research
```
	1.	__new__ method
	2.	decorators (կրկնել անպայման) 
```


### Links

```
Կարող եք օգտվել հետեվյալ link-երից:

https://www.geeksforgeeks.org/python-property-function/
https://www.programiz.com/python-programming/property/
```
