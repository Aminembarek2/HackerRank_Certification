# HackerRankCertification

### Python Reverse Word and Swap Cases

```
#
# Complete the 'reverse_words_order_and_swap_cases' function below.
#
# The function is expected to return a STRING.
# The function accepts STRING sentence as parameter.
#

def reverse_words_order_and_swap_cases(sentence):
    data = sentence.split()
    reversed_data = data[:: -1]
    reversed_sentence = " ".join(reversed_data)
    return reversed_sentence.swapcase()

```
### Python String Transformation 

```
def transformSentence(sentence)
    data = sentence.split()
    result=""
    for i in data:
      result+=i[0]
      for j in range(1,len(i))
        if i[j-1].Lower()<i[j].lower():
          result+=i[j].upper()
        elif i[j-1].Lower()>i[j].lower():
          result+=i[j].lower()
        else:
          result+=i[j]
    result+=" "
    
    return result
'''
