# Automate Your Gmail 
<br>

> **Description** <br><br>
**Using this Program you can send Emails to Multiple users at the same time, also it is possible to send the same mail
multiple times** .
<br><br>

<br><br>

### ***Features***

***

<br>

* This program creates a simple **database** within  users device which stores the Email address of the users ones entered which helps in avoiding writing email adresses every time you run the script.<br><br>
![](select.png)

<br>

* You can set the **path** to the database here
    ```python
    path = "Write the path of Database "
    ```

* You can Choose **Multiple Email** addreses at the same time
    ```python
    while(TO!='-1'):
    TO = input("\nEmail TO (enter \'-1\' to exit ): ")
    TOO.append(TO)
    From(TO)

    ```
* The **Multiline Body** is accepted just like actull Email
    ```python
    lines = []
    while True:
        line = input()
        if line:
            lines.append("\n")
            lines.append(line)
        else:
            break

    ```
* **SEND Multiple files** at the same time - **( New feature - Updated_Bot.py )**
    ~~~python

        "1. Send ->> .Pdf, .Txt  etc. "
        "2. Sends Multiple Files to Mutiple People at same time "

    ~~~
* ### **Drag and Drop File**
    ~~~python

        '''
        You can drag and drop the file on the intrepter or CMD ,It will take the file path 
        and will convert it into the correct format on its own 
        
        '''

    ~~~
<br><br>


### ***SAMPLE***
***

<br><br>

![](working.png)
