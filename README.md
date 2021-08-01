# Decrypt
def convert(s):
    s1=""
    for i in range(len(s)):
        if(s[i]=='a' or s[i]=='A'):
            s1=s1+chr(ord(s[i])+25)
        elif(s[i].isalpha()):
            s1=s1+(chr(ord(s[i])-1))
        else:
            s1=s1+s[i]
    print(s1)
    

if __name__ =="__main__":
    convert("Btqjsjohgjoamfsuxfouzuxfouzpof@gjoamz.dpn")
