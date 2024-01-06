# strings_app

website = "http://www.fatmasever.com"

course = "Python Kursu: Baştan Sona Python Programlama Rehberiniz (40 saat)"

result = '    Hello World  '

result1 = result.strip()

result2 = result.lstrip(/:pth)  # sadece soldan karakter silmek için lstrip()

result3 = result.rstrip(cmo)  # sadece sağdan karakter silmek için rstrip()

print(result)


res = 'www.fatmasever.com'

res = res.replace('www.','    ').replace('.com','    ').strip()

#ya da

res = res.strip('w.com')

print(res)


course = course.lower()

print(course)


website = website.count('a')

website = website.count('www',0,10)   # 0 ila 10. index içinde www var mı?

print(website)

website = website.startswith('www')

print(website)

website = website.endswith('com')

print(website)

website = website.find('.com')

#ya da

website = website.index('.com')

website = website.find('.com',0,10)  # 0 ila 10. index içinde .com var mı?

website = website.find('Python')

website = website.rfind('Python')

print(website)

course = course.isdigit()  # isalpha() # karakterlerin hepsi nümerik mi, alfabetik mi?

print(course)

result = 'Hello'.isalpha()


s = 'contents'

s = s.center(50,'*')

s = s.ljust(50,'*')   # sadece sol tarafı * ile 50 karaktere tamamlar.

s = s.rjust(50,'*')   # sadece sağ taraf

print(s)

course = course.replace(' ','-')

print(course)

result = 'Hello World'

result = result.replace('World', 'There')

print(result)


course =course.split()

print(course)
