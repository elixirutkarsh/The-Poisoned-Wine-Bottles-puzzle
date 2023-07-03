# The-Poisoned-Wine-Bottles-puzzle
Problem Statement:
You are a detective trying to solve a murder case. The victim was poisoned by drinking wine from one of twelve bottles at a dinner party. Unfortunately, you don't know which bottle is poisoned, but you do know that the poison takes exactly 24 hours to take effect. You also have a group of 24 rats that can be used to test the wine. If a rat drinks from a poisoned bottle, it will die within 24 hours. Your task is to identify the poisoned bottle within 24 hours using the rats as effectively as possible.

Solution:
Divide the 24 rats into groups of three, labeled 1 to 8. Number the bottles from 1 to 12.
Take three rats from group 1 and assign them to drink from bottles 1, 2, and 3. Similarly, assign rats from groups 2 and 3 to drink from bottles 4, 5, 6, and 7, 8, 9, respectively. Repeat this process for groups 4 to 8, assigning them to bottles 10, 11, 12.

Now, wait for 24 hours. If any rat from a particular group dies, you can determine the poisoned bottle. For example, if one rat from group 5 dies, it means the poisoned bottle is bottle number 8 (group number + 5).

If no rats die within 24 hours, it means the poisoned bottle is either 1, 2, or 3 (as rats from group 1 drank from these bottles). To identify the exact bottle among the three, take one rat from group 1 and split it into three parts. Assign each part to drink from one of the three remaining bottles. Wait for another 24 hours. The part of the rat that dies will indicate the poisoned bottle.
