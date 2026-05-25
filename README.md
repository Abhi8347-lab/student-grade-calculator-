# student-grade-calculator-


print('WELCOME!! I HOPE YOUR TEST WENT WELL PLEASE CHECK THE GRADE')
subject = input('PLEASE ENTER CANDIDATES NAME')
marks =float(input('Enter the your marks__'))

if marks>= 90:
   print('CONGRATULATIONS YOU GOT AN A GRADE')
elif marks>=80:
    print('CONGRATULATIONS YOU GOT B GRADE ')
elif marks>=70:
    print('YOU CAN IMPROVE YOU GOT D GRADE')
elif marks>=60:
    print('YOU NEED TO IMPROVE YOU GOT D GRADE') 
elif marks>100:
     print('result invalid')
else :
    print('SORRY YOU FAILED')