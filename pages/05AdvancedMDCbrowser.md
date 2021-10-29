# Advanced Formbuilding in the browser

In the third session we've had a first look at kobotoolbox. In this session we will expand on that knowledge. 
For this session, we will repeat:
- Adding questions
- Question types
- Making questions mandatory
- How to add multiple languages

We will learn:
- Grouping
- Skip logic (conditional questions)
- Cascading select
- Restrain answers
- Calculations
- Layout

## Grouping questions in the browser

Draft a set of questions that you would wish to group together. Then press the CTRL Key and select/click on all the questions (with the help of your mouse) that you wish to group. You should see the questions getting highlighted to blue as shown in the image below. Then press Create group with selected questions (marked under the red box) as shown in the image:

![Group questions](https://support.kobotoolbox.org/_images/group.png)

You should now be able to see your new group. It should be slightly different (enclosed within a shaded box) then the normal question you generally see. Then you can rename your group to give it a representative name. The process is also visualized in the video below: 

![Grouping](https://raw.githubusercontent.com/tijsziere/tijsziere.github.io/main/images/05_AdvancedMDC/grouping.gif)

[more information on grouping here](https://support.kobotoolbox.org/group_repeat.html?highlight=group%20questions#grouping-a-set-of-questions)

## Skip logic

Skip logic is also sometimes referred to as ‘branching’ or ‘relevant conditions’. By default, all questions are always visible. Skip logic controls which question should be displayed only if a certain condition (or conditions) is fulfilled. Conditions are always applied to the question or group that should be sometimes hidden, sometimes visible.

```
**Example**
Q1: Are you currently in school?
Q2: What’s your school level? 
Q3: Which grade are you in?

You would want to display the third question only if the respondent answers ‘Yes’ to the first question.
```

These conditions can be added to each question by clicking on Settings inside the question card (top right of each question), then select "Skip Logic" on the left. Then click on "+ Add a condition" and fill this in. This process is illustrated below. To add multiple conditions, add your first one, then click on the "+ Add a condition" button. When using two or more conditions, be sure to choose between the two options: whether the question should match **any** (at least one) of these criteria, or **all** of them.

![SkipLogic](https://raw.githubusercontent.com/tijsziere/tijsziere.github.io/main/images/05_AdvancedMDC/condition.gif)

[more information on skip logic here](https://support.kobotoolbox.org/skip_logic.html?highlight=skip%20logic)


## Cascading Select

Cascading select questions are sets of questions whose options depend on the response to a previous question. For example, your form may first ask the region where a respondent is from, and then in the next question list only the districts in that region and then follow up with only the villages of that district.

### Create your cascading select in Excel
Download [this template](https://raw.githubusercontent.com/tijsziere/tijsziere.github.io/main/images/05_AdvancedMDC/CascadingSelect.xlsx) and open in Excel. If you want, you can change the values to match your situation.

### Import cascading select into kobotoolbox
Then import the cascading select question into kobotoolbox by clicking the cascading select icon on the top left and copy and paste the data from excel in the popup window that appears. This is also illustrated in the video below:

![Cascading Select](https://raw.githubusercontent.com/tijsziere/tijsziere.github.io/main/images/05_AdvancedMDC/cascading.gif)

[more information on cascading select here](https://support.kobotoolbox.org/cascading_select.html?highlight=cascading%20select)

## Restrain answers