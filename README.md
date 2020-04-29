# leap-year-checker
# a simple program to check if a year is a leap year

year = int(input())
if year % 4 == 0 and year % 100 != 0 or year % 400 == 0:
    print("Leap")
else:
    print("Ordinary")
# if it can be / 4 and 100 != leap year
