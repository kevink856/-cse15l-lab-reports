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

1. Foo
2. Bar

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
