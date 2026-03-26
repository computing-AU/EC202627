
Define a Function with Name calculate_fine() Pass necessary formal parameters based on test cases

    Prints and returns the fine for an overdue book and special message if fine reaches maximum capped amount.
    Fine = ?, capped at max_fine.

    Parameters:
        book_title   :   Title of the book
        days_overdue :   Number of days past the due date
        daily_rate   :   Fine per day (INR 5:00 )
        max_fine     :   Maximum fine cap (INR: 150)

    Returns:
        float: The final fine amount

Input:

python3 DNY_01.py

The not to do list
5
Output: 25.0

python3 DNY_02.py

The Handbook of Psychology
10
Output:  
150.0

python3 DNY_03.py

calculate_fine("The not to do list",30)

Output: You have accumulated the maximum fine of INR: 150.0

run py DNY_04.py

calculate_fine("The not to do list",5,10.0)

Output: 50.0

run py DNY_04.py
calculate_fine("The not to do list",40)

Output: 150.0



Additional 10 Marks will be given for structure of the code.
