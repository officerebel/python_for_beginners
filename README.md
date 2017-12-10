# python_for_beginners


string
pi = 3.14
print str(pi)


ministry = "The Ministry of Silly Walks"

dot notation
print len(ministry)
print ministry.upper()


str = "Monty Python"
print str


Printing Variables
the_machine_goes = "Ping!"
print the_machine_goes

String Concatenation
print "Spam " + "and " + "eggs"


Explicit String Conversion
str(3.14)
print "The value of pi is around " + str(3.14)




String Formatting with %, Part 2
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)


Getting the Current Date and Time
from datetime import datetime
now = datetime.now()
print now



from datetime import datetime
now = datetime.now()
print now
print now.year
print now.month
print now.day


from datetime import datetime
now = datetime.now()

print '%s/%s/%s' % (now.month, now.day, now.year)



from datetime import datetime
now = datetime.now()

print '%s/%s/%s' % (now.month, now.day, now.year)
print '%s:%s:%s' % (now.hour, now.minute, now.second)

from datetime import datetime
now = datetime.now()

print '%s/%s/%s %s:%s:%s' % (now.year, now.month, now.day, now.hour, now.minute, now.second)

