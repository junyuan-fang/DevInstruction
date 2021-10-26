# Lapio

* ``` man ls ```  
* ``` cat esimerkki.txt ``` cat (katenoi), joka tulostaa suoraan tiedoston sisällön komentorvissa
* ``` head -n 1 esimerkki.txt ``` Show the first line of the file 
* ``` tail -n 2 esimerkki.txt ``` Show the last two lines of the file
* ``` grep "salai" päiväkirja.txt ``` grep (search globally for a regular expression and print)
* ``` ^ ``` 正则表达式， 开头的字符 例如 ```grep -i "^word" new.txt ``` 以word字符串开头的行，大小写不限
* ``` $ ``` 正则表达式， 结尾的字符 例如 ```grep -i "word$" new.txt ``` 以word字符串结尾的行，大小写不限
