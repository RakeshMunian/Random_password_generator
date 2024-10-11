# Random_password_generator
import random
import string
pass_len= 10
charvalues=string.ascii_letters+string.digits+string.punctuation
password="".join([random.choice(charvalues)
                  for i in range (pass_len)])
print ("Your Random Password Is :", password)
