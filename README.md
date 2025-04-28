# cmsc204-project-1-a-password-checker-solved
**TO GET THIS SOLUTION VISIT:** [CMSC204-Project 1-A Password Checker Solved](https://www.ankitcodinghub.com/product/cmsc204-project-1-a-password-checker-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;49774&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC204-Project 1-A Password Checker Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<h2>Project 1</h2>
Create a Java application that will check for valid passwords.&nbsp; The following rules must be followed to create a valid password.

<ol>
<li>At least 6 characters (long)</li>
<li>10 or more characters is a strong password, between 6 and 9 characters is a weak (but acceptable) password</li>
<li>At least 1 numeric character</li>
<li>At least 1 uppercase alphabetic character</li>
<li>At least 1 lowercase alphabetic character</li>
<li>No more than 2 of the same character in a sequence</li>
</ol>
Hello123 – OK

AAAbb123 – not OK

Aaabb123 – OK

<strong>Academic Honesty Policy Reminder</strong> | <strong>Do your own work</strong> – each submitted project will be compared against other submissions from current and previous semesters.

<strong>requirements</strong>

<ul>
<li>When the application begins, the user will be presented with a screen that states the above instructions for creating a password, two text entry boxes for typing in a password, and three buttons. (See provided sample runs.)</li>
<li>If the user wants to check a single password, they will type in the password in both boxes and select the “Check Password” button.</li>
<li>If the user wants to read in and check a list of passwords, they will select the “Check Passwords in File” button, be presented with a file explorer, and select the file to read from. Those passwords that failed the check will be displayed, with their error message.</li>
<li>If the user presses the “Alt” key, a letter will be underlined in each button label. That letter is the “mnemonic” that can use as a shortcut (Alt plus the letter) to execute the button.</li>
<li>If the user hovers his cursor over a button, a tooltip will be shown.</li>
</ul>
<strong>Specifications</strong>

<strong>Data Element</strong>

<ul>
<li>String</li>
</ul>
<strong>Data Structure</strong>

<ul>
<li>ArrayList of Strings</li>
</ul>
<strong>Classes – Utility &amp; Others</strong>

<ul>
<li>Create a PasswordCheckerUtility class based on the Javadoc given you. The PasswordCheckerUtility class will have at least three methods:
<ul>
<li>One method will check the validity of one password and return true if the password is valid and throw an exception if invalid.</li>
<li>One method will check for a “weak password”, i.e., one whose length is between 6 and 9, inclusive. Do NOT throw an exception.</li>
<li>One method will check an ArrayList of passwords and return an ArrayList with the status of any invalid passwords (weak passwords are not considered invalid). The ArrayList of invalid passwords will be of the following format:
<ul>
<li>&lt;password&gt;&lt;space&gt;&lt;message of exception thrown&gt;</li>
</ul>
</li>
<li>The methods will have the following headers:
<ul>
<li>static boolean isValidPassword(String pwdString);</li>
<li>static boolean isWeakPassword(String pwdString);</li>
<li>static ArrayList&lt;String&gt; invalidPasswords(ArrayList&lt;String&gt; passwords);</li>
</ul>
</li>
<li>Always check for the length of the password first, since that is the easiest and fastest check. Once the password fails one rule, you do not need to check the rest of the rules.</li>
</ul>
</li>
</ul>
<strong>The GUI (Provided)</strong>

<ul>
<li>Buttons are provided to allow user to check validity of one password or a file of passwords</li>
<li>The user may be asked to enter the password and to re-type the password. If the two are not the same, the user is informed</li>
<li>A <u>tool tip</u> and a <u>mnemonic</u> are available for each of the buttons</li>
<li>A FileChooser asks the user to select the input file</li>
<li>Methods of PasswordCheckerUtility are used to process the passwords.</li>
<li>Try/catch structures catch exceptions thrown by PasswordCheckerUtility methods</li>
<li>Provided UI driver should work just fine, however, you are welcome to modify it or create your own. With that said, your project must satisfy (successfully passed) all of the specified requirements</li>
</ul>
&nbsp;

&nbsp;

<strong>Exceptions</strong>

<ul>
<li>Create exception classes for each exception listed in PasswordCheckerUtility Javadoc and listed below:</li>
</ul>
<ol>
<li>Length of password is less than 6 characters (class LengthException)</li>
</ol>
<ul>
<li>Message – The password must be at least 6 characters long</li>
</ul>
<ol start="2">
<li>Password doesn’t contain an uppercase alpha character (class NoUpperAlphaException)</li>
</ol>
<ul>
<li>Message – The password must contain at least one uppercase alphabetic character</li>
</ul>
<ol start="3">
<li>Password doesn’t contain a lowercase alpha character (class NoLowerAlphaException)</li>
</ol>
<ul>
<li>Message – The password must contain at least one lowercase alphabetic character</li>
</ul>
<ol start="4">
<li>Password doesn’t contain a numeric character (class NoDigitException)</li>
</ol>
<ul>
<li>Message – The password must contain at least one digit</li>
</ul>
<ol start="5">
<li>Password contains more than 2 of the same character in sequence (class InvalidSequenceException)</li>
</ol>
<ul>
<li>Message – The password cannot contain more than two of the same character in sequence.</li>
</ul>
<ol start="6">
<li>For GUI – check if Password and re-typed Password are identical (class UnmatchedException)</li>
</ol>
<ul>
<li>Message – The passwords do not match</li>
<li>Throw this exception from the GUI, not the utility class.</li>
</ul>
<strong>Programming Concepts</strong>

This project utilizes the following concepts:

<ul>
<li>ArrayList</li>
<li>Tooltips</li>
<li>Mnemonic</li>
<li>Read Files</li>
<li>Javadoc</li>
<li>JUnit Tests</li>
<li>Exceptions</li>
<li>GitHub</li>
</ul>
<strong>GitHub</strong>

<ul>
<li>As you are working on your project, utilize your GitHub repro (upload your project files to a directory named Project1_Passwords. You will need to submit a screenshot of your repro during submission.</li>
</ul>
<strong>Testing </strong>

<ul>
<li>As a typical user, I should be able to utilize your program without running into too much difficulties!&nbsp; Thoroughly test your project</li>
</ul>
<ul>
<li>Think about the public and private test cases which your instructor will test your project against</li>
<li>If there are more than one errors in a password, use the order (as specified in the UI) to throw exceptions. For example, if a password is “xxyyzzwwaa”, it fails rules 2 and 4 above.&nbsp; Throw a NoUpperAlphaException, not a NoDigitException</li>
</ul>
<strong>File Format</strong>

The file will be in the following format: One password per line

&nbsp;
