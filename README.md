# Step 1: Iterate over each character in the sentence
for char in sentence:
    # Step 2: Increment length counter
    length += 1
    
    # Step 3: Increment word counter if space is encountered
    if char == " ":
        words += 1
    
    # Step 4: Increment vowel counter if character is a vowel
    if char.lower() in "aeiou":
        vowels += 1

# Step 5: Output results
print("Length of sentence:", length)
print("Number of words in sentence:", words)
print("Number of vowels in sentence:", vowels)


Initialize counters for length, words, and vowels
length = 0, words = 1  # Assume the sentence has at least one word
vowels = 0

sentence = input("Dolapo is a ceo.")

(const sentence = "Dolapo is a ceo."; for (let i = 0; i < sentence.length; i++) { const char = sentence.charAt(i); if (char === '.') { break; // exit loop when the point is reached } length++; // increment length counter if ('aeiou'.includes(char.toLowerCase())) { vowelCount++; // increment vowel counter } if (char === ' ') { wordCount++; // increment word counter } } If the last character is not a space, increment the wordCount counter. csharp Copy code const sentence = "Dolapo is a ceo."; for (let i = 0; i < sentence.length; i++) { const char = sentence.charAt(i); if (char === '.') { break; // exit loop when the point is reached } length++; // increment length counter if ('aeiou'.includes(char.toLowerCase())) { vowelCount++; // increment vowel counter } if (char === ' ') { wordCount++; // increment word counter } }

If the last character is not a space, increment the wordCount counter.

const sentence = "Dolapo is a ceo."; for (let i = 0; i < sentence.length; i++) { const char = sentence.charAt(i); if (char === '.') { break; // exit loop when the point is reached } length++; // increment length counter if ('aeiou'.includes(char.toLowerCase())) { vowelCount++; // increment vowel counter } if (char === ' ') { wordCount++; // increment word counter } } if (sentence.charAt(sentence.length - 1) !== ' ') { wordCount++; // increment word counter if last character is not a space }

Output the length of the sentence, the number of words in the sentence, and the number of vowels in the sentence.

console.log(Length of sentence: ${length}); console.log(Number of words: ${wordCount}); console.log(Number of vowels: ${vowelCount});

Now When we run this code with the example sentence, the output should be:

Length of sentence: 15, Number of words: 4, Number of vowels: 7
