# Assignment 6 Part 1 - Writeup

**Name:** Piero Barsanti 
**Date:** 11/21/25

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:** R2 score tells you the variance it is accounting for and it tells you if there is a pattern in the data. If it is closer to 1, the pattern is clearer. If closer to 0, there is little, to no pattern in your data.




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**MSE LITERALLY MEANS THE AVERAGE OF THE ERRORS SQUARED AND WE USE IT TO SEE THE DIFFERENCE BETWEEN THE PREDICTIONS AND THE ACTUACL FACTUAL DATA.




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**THE MAX NUMBER OF HOURS STUDIED IS 9.6 AND THE LEAST IS 2.6. OUR RANGE IS 2.6-9.6 WHICH MEANS IT HAS NO DATA FOR ABOVE 9.6 HOURS SO IT USES THE SAME PATTERN FROM BEFORE AND IT WILL NOT BE ACCURATE BECAUSE WE DONT HAVE THE DATA. 




---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:** THE RELATIONSHIP IS NOT BAD BUT IT IS LESS THAN THA ICE CREAM. IT IS LINEAR AND POSITIVE BECAUSE IT GOES UP AND THE RELATIONSIP CAN FORM A LINE.




---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. STUDY TOOLS
2. INTERNET ACCESS
3. THE DIFFUCULTY OF THE TEST


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:** TO SHOW WHAT PREDICTIONS SHOULD LOOK LIKE AND GIVE IT A RANGE TO MAKE PREDICTIONS IN. IT WOULD GIVE YOU THE SAME PREDICTIONS.




---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:** FINDING WHAT CODE I NEEDED TO CHANGE FROM ICE CREAM EXAMPLE TO THE A6 PART 1 PY WAS DIFFICULT BECAUSE THE SLIGHTEST LETTER CHANGED MY RESULTS COMPLETLY. I THOROUGHLY CHECKED THAT I DID NOT HAVE EITHER ICE CREAM, OR TEMPERATURE.




---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**
X = 



---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
