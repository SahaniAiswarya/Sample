# Sampl
str="India won the match by 5 wickets"
print(str.find("5"))
print(str.replace("5","9"))
print(str.replace("wickets","runs"))

str="alpha,beta,gamma"
parts=str.split("a")
print(parts)
joined=":".join(parts)
print(joined)
joined=",".join(parts)
print(joined)

str='he'
text='hellohellhellohellhellohellohell'
print(text.count(str,0,len(text)))

str1="dog is humans best friend"
str2="the climate is very dangerous")
print(str1.endswith("end",0,len(str1)))
print(str2.startswith("th",0,len(str2)))

str1="dog is everyone best friend"
str2="the climate is very dangerous"
print(str1.endswith("end",0,len(str1)))
print(str2.startswith("th",0,len(str2)))

text="how was the meal today?"
print(text.find("how",0,len(text)))
print(text.rfind("meal",0,len(text)))

text="jamesbond007"
print(text.isalpha())
print(text.isalnum())
print(text.isdigit())
print(text.isspace())

str="hi"
print(str.ljust(20,"#"))
print(str.ljust(20,"-"))
print(str.ljust(2,"#"))
print(str.ljust(10,"&"))
print(str.ljust(12,"*"))
print(str.rjust(12,"*"))
