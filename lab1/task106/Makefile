scanner:lab106.y
	bison -o scanner.tab.c lab106.y
	gcc -o scanner scanner.tab.c -lm
clean:
	rm -f scanner lex.yy.c error.txt result.txt scanner.tab.c
