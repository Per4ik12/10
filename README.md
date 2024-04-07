# 10
Урок 8
Задание 1

def is_palindrome(s):
    s = s.replace(" ", "").lower()  
    return s == s[::-1]  

string = input("Введите строку: ")
if is_palindrome(string):
    print("yes")
else:
    print("no")

    Задание 2

    def compress_spaces(s):
       if len(s) > 1000:
        return "Длина строки превышает 1000 символов"
    
       words = s.split()
    
       compressed_s = ' '.join(words)
    
    return compressed_s

input_string = input("Введите строку: ")

result = compress_spaces(input_string)
print("Измененная строка:", result)
