# Technical-Writing-101
## Making knowledge comprehensive

One of the challenges that most people face during new concepts is how to turn them into practice and solve a daily task. A good technical writer can guide from A to B while explaining an idea. Even the most complex projects require an approach that follows a frame of collection. Having such template - structural writing makes the thought more clear and sharp. It also helps build the readiness for the editorial process.

Agile methodology is providing a more flexible working environment addressing the "Time for a project to be moved forward". 

On the other hand, the Waterfall method opens the steady "rope" approach while climbing into the project scale. The process split into action and confirmation for success. First is setting a piece to the puzzle (planning phase) and then validation (development phase).

Based on the business logic, both ways have pros and cons. The biggest question on agile is the deadline and the waterfall - starting from scratch.

Regardless of the selected method for a project, structural writing satisfies the construction. Also, the format provides a fail-safe mechanic that can be very powerful in writing.

As such structural writing steps on the norm of expanding current knowledge as a technique for writing, data implementing a strategy to the collection, and shortening the time for building a project.


[![7](https://user-images.githubusercontent.com/124214430/221617844-e1314000-44c3-4f18-b512-8a7b71e377d1.png)](https://youtu.be/gIQclTHRqBg "Put hover text here!")

# Holder for figures 
Holder for figures is writen under Python. In this example, the code replaces all occurrences of the exclamation mark in the given text with the same exclamation mark followed by a newline character. The output shows the modified text with the replaced symbols on new lines.

```
def edit_text(text, word, start_num):
    count = start_num
    new_text = ""
    for w in text.split():
        if w == word:
            new_text += str(count) + " "
            count += 1
        else:
            new_text += w + " "
    return new_text.strip()

# Read in text file
with open("Ready-to-Python.txt", "r") as file:
    text = file.read()

# Edit text and write to output file
word = "muffin"

# muffin = number for figure replacement

start_num = 1
new_text = edit_text(text, word, start_num)

with open("output.txt", "w") as file:
    file.write(new_text)

```

**Text for editing**:

![1](https://user-images.githubusercontent.com/124214430/224059574-3f48f45b-dfe7-4230-9148-b1967c2c381c.png)

**Text after editing**:

![2](https://user-images.githubusercontent.com/124214430/224059610-76b145e7-6c1d-43d0-9132-df850b2886af.png)

> This comes very handy when in a document the holder for figures in which multple screenshot need to be set as a number.
>> The text may require structuring (working on how).
