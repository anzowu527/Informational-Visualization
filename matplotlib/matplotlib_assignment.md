## Basic Steps I did:
I used the California COVID dataset that was in this folder for the assignment
1. Imports and data
2. Create a date_offset column: I converted the string dates to numerical date (to datetime.date object), and then did the math
3. Normaize the case counts: becasue I want to draw curves of cases for all counties across time, and different counties cannot be directly compared becasue their base population differs
4. Make a quick plot of one county
5. Check the Statistical Summaries: we want the median and IQR, taken across counties
6. We need a running average: this step make the graph smoother for the viewer to make sense of the visualization
7. Draw the final graph 
