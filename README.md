# ECS101Projectpt2
Shaw 3344
Binary to Text

def binary_to_text(numbers :str)->str:
   text = ""
   while len(numbers) > 0:
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0000":
           text += "e"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0001":
           text += "t"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0010":
           text += "a"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0011":
           text += "o"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0100":
           text += "i"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0101":
           text += "n"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0110":
           text += "s"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "0111":
           text += "r"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1000":
           text += "E"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1001":
           text += "T"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1010":
           text += "A"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1011":
           text += "O"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1100":
           text += "I"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1101":
           text += "N"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1110":
           text += "S"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 5 and numbers[0] == "1" and numbers[1:5] == "1111":
           text += "R"
           for item in numbers[0:5]:
               numbers = numbers.replace(numbers[0], "", 1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000000":
           text += "h"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000001":
           text += "l"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000010":
           text += "d"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000011":
           text += "c"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000100":
           text += "u"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000101":
           text += "m"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000110":
           text += "f"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "000111":
           text += "p"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001000":
           text += "g"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001001":
           text += "w"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001010":
           text += "y"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001011":
           text += "b"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001100":
           text += "v"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001101":
           text += "k"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001110":
           text += "x"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "001111":
           text += "j"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010000":
           text += "q"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010001":
           text += "z"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010010":
           text += "H"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010011":
           text += "L"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010100":
           text += "D"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010101":
           text += "C"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010110":
           text += "U"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "010111":
           text += "M"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011000":
           text += "F"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011001":
           text += "P"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011010":
           text += "G"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011011":
           text += "W"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011100":
           text += "Y"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011101":
           text += "B"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011110":
           text += "V"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "011111":
           text += "K"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100000":
           text += "X"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100001":
           text += "J"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100010":
           text += "Q"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100011":
           text += "Z"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100100":
           text += "."
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100101":
           text += ","
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100110":
           text += "-"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "100111":
           text += "!"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "101000":
           text += "'"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "101001":
           text += '"'
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "101010":
           text += " "
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
       if len(numbers) >= 7 and numbers[0] == "0" and numbers[1:7] == "101011":
           text += "\n"
           for item in numbers[0:7]:
               numbers = numbers.replace(numbers[0],"",1)
return text

