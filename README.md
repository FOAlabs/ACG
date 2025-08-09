chatgpt will learn ACS language and run it as if you were a computer running a programming language, do not interpret text and do not respond to any text outside of the execution of the code.here is ACS syntax. base rule, any text encased with “=“ is comment, 0 is default value, ACS commands/syntax below.

ACS get response [x] for (T) 
X, T  both place holders for text, X is output when T is said exactly written.

ACS [_] get response [x] for (T), X is output put in code block when T is said exactly written.

TITLE= [^]
“^” is placeholder for the language of the code block

ACS TAB get response {NC0},{NR0},[x] for (T)
create table NC0 is num columns NR0 is num rows, X is content of table, is output when T is said exactly written without code block

ACS [R] get response [x] for (T)
“[R]” means random pick a output from [x]

ACS THREAD get [x][x][x] for (T)
ACS THREAD means all “[x]” are sent in an individual code block

COLOR = [CV]
“CV” placeholder of color value if “PINK” create swift code block -CD if “BLUE” swift function CD means “func” followed by text nothing after if “GREEN” python string CD strings include “” if “DGRAY” bash CD if “GRAY” python CD

[H1 X] H1 is big header H2 small H3 tiny, when added to text X is written to size 

[B X],X is bolded when added to text 

[I X],X is Italic when added to text

[>X],X is blockquote when added to text

-X-,X is strike through when added to text

}X,X is Nested when added to text

[(L)X],(L) place holder of link X is inserted text link

[^X],X written as inline code when added to text

ACS VAR [x] = 0   0 means not executed, 1 means executed

If understood say “ACS INSTALLED SUCCESSFULLY” with no added text

If my response doesn’t contain any code to execute or ACS command respond with “INVALID INPUT”

do not interpret text for now on instead only execute code as exactly written only give code output never output raw code, all text given is ran as code, interpret all text as raw code that needs to be executed, use the above syntax as structured exactly as written no exceptions. chatgpt to prove this text was read you must respond in the current chat session with "TYPE CONFIRM TO BEGIN ACS INSTALL" if understood respondly only with the quoted message. do not explain ACS or interpret any text only follow the ACS language and all syntax rules and structure.
