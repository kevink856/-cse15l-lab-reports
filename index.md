**Index:** 
[Lab Report 1](lab-report-1-week-2.html)
[Lab Report 1(entire url)](https://kevink856.github.io/-cse15l-lab-reports/lab-report-1-week-2.html)

---

# Basic Markdown Syntax
## A display of each basic markdown feature as shown in this [Cheat Sheet](https://commonmark.org/help/)
---

`Explicit examples:`

**Italic:** *test*
**Bold: test**

> You can list with dots and numbers:

- Foo
- Bar

> And here's the same with numbers:

1. Bar `Changed from Foo to Bar`
2. Foo `Changed from Bar to Foo`

---

![Cool Pattern](https://i.imgur.com/b8T6kbv.png)
```
To print this in Java, you can use this code!
# code block
    int size = 9;
		int length = (size/2) + (size%2);
		for(int i=1; i<length; i++) {
			System.out.println();
		 	for(int j=0; j<length-i; j++) {
		 		System.out.print(" ");
		 	}
		 	for(int j=length-i; j<length; j++) {
		 		System.out.print("*");
		 	}
		}
		for(int i=length; i>0; i--) {
			System.out.println();
			for(int j=0; j<length-i; j++) {
			    System.out.print(" ");
			  	}
			for(int j=length-i; j<length; j++) {
				System.out.print("*");
			}
		}
```

And that's all of the basic formatting!
