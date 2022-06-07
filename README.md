# check-wether-the-give-phone-no-is-valid-or-not

else:
    valid_code = True
    break
if(valid_code==True):
  while True:
    num = input('Enter a mobile number to validate: ')
    Pattern = re.compile("[7-9][0-9]{9}")
    if Pattern.match(num):
      print('Valid Mobile Number')
      break
    else:
	    print("Invalid Mobile Number")
