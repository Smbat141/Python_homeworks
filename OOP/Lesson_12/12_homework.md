# Homework №12

```
	1.	Գրել Logger class որը կունենա Meta class:
	
	2.	Meta class-ի համար գրել __call__ method
	
		def __call__(self, *args, **kwargs):
		
			obj = type.__call__(self, *args)
			print(obj) # Logger object
		
		        return obj
	
	3.	Փոխել __call__ method-ը այնպես որ Logger-ից նոր object չսարքի
		և սարքելուց միշտ վերադարձնի նույն object-ը:
		
		>>> logger = Logger()
		>>> print(id(logger))
		10711440
		>>> logger2 = Logger()
		>>> print(id(logger2))
		10711440
		
```


### Research
```							Կրկնություն

	1.	Ինչ է OOP-ն և ինչ առավելություններ է տալիս:
	2.	Նշել OOP-ի 3 հիմնական սկզբունքները և նկարագրել դրանցից յուրաքանչյուրը:
	3.	Abstract class-ի և Inerface-ի տարբերությունը:
```


### Links

```
Կարող եք օգտվել հետեվյալ link-երից:

https://realpython.com/python-metaclasses/
```
