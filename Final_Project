#!/usr/bin/env python3

# script to count the number of plants in three categories: processed, unprocessed, and dead
filename = 'my_data.txt'

# initial banter about purpose of counter
print("Let's see how your research is progressing:")

# counters used for tracking data
yes_counter=0
no_counter=0
NA_counter=0
DNA_counter=0

# assingment of variable f to open the data file
f = open(filename, "r")

# for loop to interate data and count lines with particular key words: yes, no, na
for line in f.readlines():
    if " yes" in line:
        yes_counter+=1
    if " no" in line:
        no_counter+=1
    if " NA" in line:
        NA_counter+=1
    if " (DNA)" in line:
        DNA_counter+=1
    f.close()

# printout of each counter
print("  Number of plants you've processed = ", yes_counter)
print("  Number of plants needing your attention = ", no_counter)
print("  Number of dead plants = ", NA_counter)
print("  Number of DNA samples = ", DNA_counter)

# encouraging, yet snarky printout
print("Great job! Now, back to work!")
