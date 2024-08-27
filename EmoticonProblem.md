# Emoticon Problem
# defining a function
def replace_emot(sentence):
    # dictionary
    emoticons = {"smile": ":)", "grin": ":D", "sad": ":(", "mad": ">:("}
    words = sentence.split()
    new_sentence = [emoticons.get(word, word) for word in words]
    return ' '.join(new_sentence)
# make the user input a sentence that includes the words in the dictionary
user_input = input("Input: ")
result = replace_emot(user_input)
# output statement
print(result)
