# Homework №16
```
	1.   Գրել login module:
			
		1.1     login լինելուց ստուգեք decorator-ի միջոցով user-ի role-ը
			և կախված role-ից ցույց տվեք user-ներին:
		
			user - տպեք միայն իր տվյալները
			admin - տպեք բոլոր admin-ների և user-ների տվյալները
			super_admin - տպեք բոլոր տեսակի user-ների տվյալները
		
		1.2	Օգտվելով time module-ից ստուգեք login function-ը ինչքան 
			ժամանակում է կատարվում decorator-ի միջոցով (առաջադրանքը կատարել research-ից հետո)

	2.  Գրել registration module:

		1.1	registration լինելուց ստուգեք user-ի տվյալները և չհամապատասխանելու դեպքում ցույց տվեք 
			համապատասխան error message:
			
			first_name, last_name - պետք է կազմված լինի minimum 4 և maximum 30 տառերից: 
			email - պետք է վերջում լինի @gmail.com
			age - պետք է int և 0-112-ի միջակայքում
			role -  չի կարող user-ը լրացնել, միշտ պետք է լինի user
			country - պետք է կազմված լինի minimum 3 և maximum 25 տառերից:
		
		1.2	Գրել decorator registration function-ի համար որը կընդունի parametr country-ների list
			և եթե registration-ի ժամանակ user-ի գրած country-ին չի լինի list-ում ցույց տալ error message:
```

### Research
```
	1.	functools module - wraps 
	2.	time module 
```



### Links
```
Կարաք օգտվեք ստեղից

https://realpython.com/primer-on-python-decorators/
```
