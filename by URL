import requests as req

resp = req.get("https://en.wikipedia.org/wiki/The_Goldfinch_(painting)")

#print(resp.text)
file = open("wikifle.rtf","w")
file.write(resp.text)
file.close()

file = open("wikifle.rtf","r")
print(file.read())
file.close()
