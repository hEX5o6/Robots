# For ; Dr.web Suliman Matrex m5i_ Mexwa511 Firasc0der MrJoker1337 

# Team ; alqwat > silver ~ Almrshdi511 ~ mastaQs

# c0ded : By 0x3heX~!5o6

# This is tool Get file in robots.txt

# For ; Muslims

try:
	import requests as xp
	import re
except:
	print ('''
       > install requests Bro ^.^
		''')
print('''

 
 [+] >>>  c0Ded : By 0x3hEX~506

	''')
def ref (url):
	try:
	    try:
		xpx = url+'/robots.txt'
		req = xp.get(xpx).text
		if 'Disallow:' in req:
		    print('::: >> :'+xpx)
		    print('   [+]    Get file ^.^ ')
		    rex = re.findall('Disallow:(.*)',req)
		    for x in rex:
			print('                : '+x)
			xr = url+x
			rs = xr.replace(' ','')
			op = open('roboots.txt','a').write(rs+'\n')
	        else:
		   print('  Not : '+url)
            except:
		pass
        except Exception as x:
     	       raise x
r = raw_input(' >>>>>>>>  Enter list : ')
try:
   opx = open(r,'r').readlines()
except:
	print(' Enter name file True')
for rp in opx:
	ref(rp)
