---
content_type: page
parent_title: Readings
parent_uid: 579c055a-ccb4-eb7e-bb6b-f294146b45a5
title: Reading Questions 6a
uid: a1eca054-8419-85ed-6989-003dd6abbe41
---

Reading Questions Answer Checker
--------------------------------

To check your answers put them in the appropriate box and click the 'Check' button. Every checker box can do arithmetic and calculate standard functions (see [calculator help]({{< baseurl >}}/pages/assignments/calculator-help)). If you give decimal answers, give them to at least 3 decimal places.

As you work you should have pencil and paper handy for calculations and thinking!

Note: some questions ask for a formula. For the checker we ask you to plug a value into the formula. For your pset you still need to give the whole formula.

//DEBUG PARAMETERS //Because we don't show solutions for pset checkers we use //this to give a showanswer button during the debugging phase var debugans = undefined; //release //var debugans = kDebugAnswer; //debug problemNumber = 0; wl("\<h3>Calculator\</h3>"); writecalculator("psetcheckcalcid", "Calculate"); whr(kdivcol,kdivwid);

//Problem 1 problemNumber++; wl(problemheader(problemNumber)); var s; var partName, problemName, buttonLabel, answerArray, correct; s = "True or False. The mean divides the probability mass in half."; wl(s); wl(kbr); partName = problemNumber; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; correct = "False"; var answerArray = \["True", correct\]; writeMultipleChoiceRadioGroup(answerArray, problemName, correct, buttonLabel); wl(kp); whr(kdivcol,kdivwid);

//Problem 2 problemNumber++; wl(problemheader(problemNumber)); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["Find the mean and variance of $X &#x223c;$ U(0,4).", kbr, "(U(0,4) is the uniform distribution.)"\]; wl(s.join(' ')); wl(kp); s = "(i) Mean" wl(s); wl(kbr); partName = problemNumber + " (i)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 2, buttonLabel, 0.001, kuseCorrectVal); wl(kp); s = "(ii) Variance" wl(s); wl(kbr); partName = problemNumber + " (ii)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 1.33333, buttonLabel, 0.001, "4/12 &#x2248; 1.3333"); wl(kp); whr(kdivcol,kdivwid);

//Problem 3 problemNumber++; wl(problemheader(problemNumber)); var s; var partName, problemName, buttonLabel, answerArray, correct; s = \["Find the mean and variance of the sum of four independent U(0,4) random variables.", kbr, "What is the range?"\]; wl(s.join(' ')); wl(kp); s = "(i) Mean" wl(s); wl(kbr); partName = problemNumber + " (i)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 8, buttonLabel, 0.001, kuseCorrectVal); wl(kp); s = "(ii) Variance" wl(s); wl(kbr); partName = problemNumber + " (ii)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 5.33333, buttonLabel, 0.001, kuseCorrectVal); wl(kp); s = "(iii) Lower limit of range" wl(s); wl(kbr); partName = problemNumber + " (iii)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 0, buttonLabel, 0.001, kuseCorrectVal); wl(kp); s = "(iv) Upper limit of range" wl(s); wl(kbr); partName = problemNumber + " (iv)"; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 16, buttonLabel, 0.001, kuseCorrectVal); wl(kp); whr(kdivcol,kdivwid);

//Problem 4 problemNumber++; wl(problemheader(problemNumber)); var s; var partName, problemName, buttonLabel, answerArray, correct; s = "Find the 0.7 quantile of $X &#x223c; $U(2,32)."; wl(s); wl(kbr); partName = problemNumber; problemName = "prob" + partName; buttonLabel = "Check problem " + partName; writeNumericBox(partName+"id", 23, buttonLabel, 0.01, kuseCorrectVal); wl(kp); whr(kdivcol,kdivwid);