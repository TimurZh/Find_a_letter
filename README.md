# Find_a_letter
num_words_1 = 0
num_words_3 = 0

for x in words:
    if x[0]=="k":
        num_words_1 += 1
    if x[2]=="k":
        num_words_3 += 1
print(num_words_1)
print(num_words_3)
