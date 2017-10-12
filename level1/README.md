## Level 1

We want to build a small program that, given a list of users with their gender, computes a list of matches between them. A match is a unique couple between two users of the input list. A user cannot be matched with more than one another. For now, we'll keep things simple and only match a man with a woman.

Note that you have to handle the case where the users count is not even, and put the remaining unmatched user in a separated list.

Write the code that reads `input.json` and generates `output.json`