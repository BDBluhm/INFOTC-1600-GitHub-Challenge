Return to <a href= "https://github.com/BDBluhm/INFOTC-1000-Midterm/blob/main/README.md"> Homepage
# Previous Work
I have been stuying infotech for about 4 years now, having started at NCC in the Information Technology course in my junior year of highschool. In that course we learned about both computer hardware and software, as well as studying cyber security the second year of the course. I earned my PCPro Certification in 2021, which tested basic operation and repair of computer hardware components, and proper software usage. During my senior year I was hired as an intern in the data analytics department of Cerner, where I helped to sort problematic software errors and get them resolved. 

In college I've been studying programming languages in my intofech classes. I worked in Python last year, and one python project I'm particularly proud of is this one;
````
while(True):
    try:
        userinput = input("Enter the name of the file: ")
        break
    except Exception as error:
        print(f"{error}")
        
while(True):
    
   with open(userinput,'r') as inputfile:
    sumtotal = 0
    for line in inputfile:
        try:
            sumtotal += int(line)
        except ValueError:
            pass
    
    with open(userinput, 'r') as inputfile:
        for count, line in enumerate(inputfile):
            count = count + 1
            pass

    average = (sumtotal / count)
       
    with open(userinput, "r") as inputfile:        
        data = [int(x) for x in inputfile.readlines()]        
    maxvalue = max(data)

    with open(userinput, "r") as inputfile:        
        data = [int(x) for x in inputfile.readlines()]        
    minvalue = min(data)

    valuerange = maxvalue - minvalue

    inputdict = {
        "Sum": sumtotal,
        "Count": count ,
        "Average": average ,
        "Maximum": maxvalue ,
        "Minimum": minvalue ,
        "Range": valuerange ,
    }

    break

while(True):
    try:
        print("Options: Sum, Count, Average, Maximum, Minimum, or Range.")
        datachoice = input("Please enter what information you'd like to see: ")

        if datachoice == "Sum":
            print(inputdict["Sum"])
        elif datachoice == "Count":
            print(inputdict["Count"])
        elif datachoice == "Average":
            print(inputdict["Average"])
        elif datachoice == "Maximum":
            print(inputdict["Maximum"])
        elif datachoice == "Minimum":
            print(inputdict["Minimum"])
        elif datachoice == "Range":
            print(inputdict["Range"])

        
    except Exception as error:
        print(f"{error}")
 ````
This code takes a text file as input, and reads its lines. Any numbers the program finds inside will be calculated out into =="Sum", "Count", "Average", "Maximum value", "Minimum value"==, and =="Range"==. The user can then choose what they want to see out of the data gathered by the program. Its not perfect by any meaning, but this was the biggest program I've made up to this point, and I had a lot of fun making it and getting it to work. 
