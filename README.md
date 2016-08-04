# RegexPatterns
RegexPatterns



at least one w followed by any number of x's
wx*

any number of backslashes followed by any number of asterisks
\\+\*+

any five characters
(.....)

2 or more of the same word
(\w{2,})(\s\1)+


words containing all vowels
\b(?=\w*a)(?=\w*e)(?=\w*i)(?=\w*o)(?=\w*u)\w+\b

e before i, but not i before e
(\b(?=[^i]*e)\w+) ((?=\w*i)\w+\b)


(?) the last names of people from a comma-delimited list of first names, last names and emails 
[^/]*/([^/]*)/

/(?:[^\,]*\,){2}([^,]*)/

a date in the format mm/dd/yyyy or mm-dd-yyyy
\b([\d]{1,2})\/([\d]{1,2})\/([\d]{4})\b

an email
(\w+@\w+)\.(\w{3,10})




 /^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
		var goodemail = re.test(email);



egrep .*ing /usr/share/dict/words
