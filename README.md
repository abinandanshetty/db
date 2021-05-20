while(True):
            input1 = input("Enter your name:")
            input2 = input("Enter your phone number:")
            input3 =input("Enter your place of coming:")
            input4=input("Enter your body temperature:")


            file = open("database.txt", "a+")

            file.write(input1 + " " + input2 +" " +input3 + " " + input4 + "\n") #appending the input for the file 

file.close()

