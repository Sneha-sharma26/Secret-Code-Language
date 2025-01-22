# Secret-Code-Language
It contains the code to translate a message into secret code language using some rules.
Rules:
# Program should ask whether you want to code or decode
# Coding:
  if the word contains atleast 3 characters, remove the first letter and append it at the end. Now, append three random characters at the starting and the end.
  else:
    simply reverse the string
    
# Decoding:
  if the word contains less than 3 characters, reverse it
  else:
    remove the 3 random characters from start and end. Now remove the last letter and append it to the beginning
