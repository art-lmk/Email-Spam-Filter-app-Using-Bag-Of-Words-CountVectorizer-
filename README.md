# Email-Spam-Filter-app-Using-Bag-Of-Words-CountVectorizer-


Hello! 👋 This is my project where I built a machine learning model that can tell if an email is a real message or just annoying spam!

Imagine your email inbox is like your mailbox at home. Sometimes you get important letters from friends and family, but other times you get junk mail like ads for things you don't want. This program is like a super-smart helper that looks at every email and says, "This is good!" or "Throw this in the trash! 🗑️"

How Does It Work? 
1. Think about how you know if a message is spam. If an email has words like "WINNER!", "FREE!", "Cash prize!", or "Click here!", you might get suspicious, right?

2. The spam filter works the exact same way! It's like a Word Detective 🕵️‍♂️.

3. Learning Phase: First, I showed my computer program thousands of example emails(spam.csv dataset) that were already labeled as "SPAM" or "NOT SPAM" (we call this "ham"). This is like giving the detective a big book of clues.

4. Counting Words: The model's tool is called CountVectorization. This is a big, fancy word for "Word Counter."

It goes through all the example emails and makes a giant list of every word it finds.

5. For each email, it counts how many times each word appears. It notes if spam emails use the word "FREE" a lot, and if real emails use words like "meeting" or "homework" more often.

6. Making a Guess (Prediction): Now, when I give it a brand new email it has never seen before:

7. The Word Counter (CountVectorizer) counts the words in the new email.

The model then compares these words to what it learned from the examples.

It adds up the clues: "Hmm, this new email has the words 'WINNER', 'FREE', and 'prize' 10 times. That sounds a lot like the spam emails I learned from. I think this is probably spam!"
