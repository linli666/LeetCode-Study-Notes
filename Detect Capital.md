#
####
```
        word_cap = word.upper()
        new_word = zip(word,word_cap)
        count = 0
        for item in new_word:
            if item[0] == item[1]:
                count += 1
        if count == 1:
            if word[0] == word_cap[0]:
                return True
            else:
                return False
        elif count == 0 or count == len(word):
            return True
        else:
            return False
```
