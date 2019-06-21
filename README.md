# AAD_HW09

This repository include **starter code**, **Espresso AndroidTest** and **Travis setting**, which are used for automatically grading in **Android Application Development course in National Cheng Kung University (NCKU)** in 2019 Spring Semester.

Materials:
- **Lesson 9: Preferences and settings** in Codelabs for Android Developer Fundamentals (V2). 
<https://developer.android.com/courses/fundamentals-training/toc-v2>

Feel free to fork this repository if you are also working on this codelab and want to testing your answer.
For more instructions, please follow the [homework rules slides](https://github.com/ncku-csie/AAD_HW01/blob/master/Homework%20Rules.pdf). 
If you have further questions, please contact android@imslab.org

These test cases are written by Intelligent Mobile Service laboratory and Cyber Physical System Laboratory in NCKU.

---

Please follow the instructions on the **Homework** sections in these codelabs.

- [9.1: Shared preferences](https://codelabs.developers.google.com/codelabs/android-training-shared-preferences/index.html)
- [9.2: App settings](https://codelabs.developers.google.com/codelabs/android-training-adding-settings-to-app/index.html)

## Part 1. Questions (30 pt)
Please submit your answer on moodle.
<https://moodle.ncku.edu.tw/course/view.php?id=104771>

**[Notice]** 
- You only have **one chance** to submit your answer.
- Your score on moodle (out of 100) * 20 % = your points in this part. <br>
For example, you score on moodle is 50, and then you got 50 * 20 % = 10 pt for this homework

| Codelab | Questions |
| --- | ----------- |
| 09.1 | 2 Questions |
| 09.2 | 3 Questions |


## Part 2. Android Tests (70 pt)

Please submit your code to the **master** branch in this repository for grading.

<table>
    <thead>
        <tr>
            <th>Codelab</th>
            <th>Starter Project</th>
            <th>Test File</th>
            <th>Questions</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=3>09.1</td>
            <td rowspan=3>SharedPrefs</td>
            <td rowspan=3>SharedPrefsTest</td>
            <td>rotateSavePrefs</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>testSharedPref</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>testResetButton</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td rowspan=4>09.2</td>
            <td rowspan=4>DroidCafeWithSettings</td>
            <td rowspan=4>DeliveryTest</td>
            <td>testDeliveryPrefsInGeneral</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>testDeliveryPrefsContent</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>testToastWithDeliveryPrefs</td>
            <td>10 pt</td>
        </tr>
        <tr>
            <td>testUpdateSummary<br>
            <strong>(This is not extra credit. You must implement this function.)</strong></td>
            <td>10 pt</td>
        </tr>
    </tbody>
</table>

**For Codelab 09.1, please follow the restrictions below !!!**

1. **The name of the preference file is `com.example.android.sharedprefs`**
2. **The text of the reset button is `RESET`.**


**[Notice]** 

- Please do not modify the following files:
  - .travis.yml
  - <Project>/app/src/androidTest/*
  - gradle files
- Once any modifications or any cheating behavior are detected, you will got 0 pt for this homework.
- Creating a new branch to develop and testing locally are highly recommended.
