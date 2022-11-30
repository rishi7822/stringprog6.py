# stringprog6.py
Python 3 code to demonstrate  Maximum frequency character in String  naive method
# initializing string
 printing original string
 # Maximum frequency character in String
 all_freq = {}
for i in test_str:
    if i in all_freq:
        all_freq[i] += 1
else:
    all_freq[i] = 1
result = max(all_freq, key = all_freq.get)
