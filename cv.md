<h3>RESUME</h3>
<h1>MISHA GRYGA</h1>
<hr>
<h1>Contacts</h1>
<h3>E-mail: 1337excuseme@gmail.com</h3>
<h3>Phone: (097) 006-13-88</h3>
<h3>Telegram: @WAIR1337</h3>
<hr>
<h1>About me</h1>
My name is Misha Gryga, I'm 18.<br>    
I study at university Ruby, Java, Python, C++,c#, has taken many courses in these programming languages,<br>  
but most of all I like to write on HTML, CSS, and JS and I hope thatI will be able to connect my life with web technologies.<br>

<h1>Example program</h1>
<h4>He task I did in the Python course.<h4>
<h3>Ave, Caesar</h3>
At the entrance to the program is a line of text in English, in which you need to encrypt all the words.<br>  
Each word in the string should be encrypted with a Caesar cipher (cyclic shift to the length of the word).<br> 
Lowercase letters remain lowercase, and uppercase letters - uppercase.<br> 
Input data format <br> 
A line of text in English is fed to the program input.<br>
Output format<br>
The program must output the encrypted text in accordance with the condition of the task.<br>
Note. Non-English characters do not change.<br>

Test data<br> 
Sample Input 1:<br>
Day, little one. "Year" is a mistake!<br>
Sample Output 1:  <br>
Gdb, qmgi. "Ciev" ku b tpzahrl!<br> 
Sample Input 2:<br>
my name is Python!<br>
Sample Output 2:<br>
oa reqi ku Veznut!<br>
<h3>Solution</h3>
<pre>
s=str(input())
p=s.lower()
p=p.split()
s=s.split()
n = []
xxx=[]
abc = ' abcdefghijklmnopqrstuvwxyz'
ABC = ' ABCDEFGHIJKLMNOPQRSTUVWXYZ'
znak = [" ", ",", ".", "!", "?", '"']
for i in range(len(p)):
    c=0
    for j in range(len(p[i])):
        for b in range(len(abc)):
            if p[i][j]==abc[b]:
                c+=1
    n.append(c)
vvv=[]
for i in range(len(s)):
    zz=''
    for j in range(len(s[i])):
         for g in range(len(abc)):
             if s[i][j]==abc[g]:
                 vv=g+n[i]
                 if vv>26:
                     zz+=abc[vv-26]
                 else:
                     zz+=abc[vv]
             elif s[i][j]==ABC[g]:
                 vv=g+n[i]
                 if vv>26:
                     zz+=ABC[vv-26]
                 else:
                     zz+=ABC[vv]
         for dd in range(len(znak)):
                 if(s[i][j]==znak[dd]):
                    zz+=znak[dd]      
    vvv.append(zz)
print(*vvv)
</pre>
<hr>
<h1>Education</h1>
I study at Uzhhorod National University.<br> 
Specialty: software engineering.<br>
He took various courses on the Sololearn and Stepik platforms.<br>
<hr>
<h1>English</h1>
I studied English at school.<br>
Now I study it at the university in a professional direction.<br>  
I can assess my level of English Pre-Intermediate (A2).<br>
<hr>
