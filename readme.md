## Shefaa lababneh
## ((نساء مبرمجات - Female Arab Coders))

* __Course one:__    

    [Introduction to Python](https://www.udemy.com/course/introduction-to-python)


* __Course two:__  

    [Introduction to Git and GitHub](https://www.udemy.com/course/introduction-to-git-and-github)

* __Course three:__

    [The Basics of Website Building Using: HTML, CSS, and JavaScript.](https://www.udemy.com/course/html-css-javascript-arabic)
    
## التحدي الاول
      print('Hello '+input("enter your name:"))


## التحدي الثاني
      number = int (input("enter number: "))
      if number %2 == 0 :
          print("number is even")
      else:
          print("number is odd")

## التحدي الثالث
      print('choose one : student_names , student_score , student_count ')
      student = input ("student_names" , "grade_names" , "both ")

      grade_names = ['grade_one' , 'grade_two' , 'grade_three']

      if student == student_names :
          def student_names(grade_names):
              if grade_names == grade_one :
                  list(grade_one.keys())
              elif grade_names == grade_two :
                  list(grade_two.keys())
              elif grade_names == grade_three :
                  list(grade_three.keys())
      elif student == student_score :
          def student_score (student_names,grade_names):
               if grade_names == grade_one :
                  sum (grade_one())
               elif grade_names == grade_two :
                   sum (grade_two())
               elif grade_names == grade_three :
                   sum (grade_three())
      elif student == student_count:
          def student_count(grade_names):
              if grade_names == grade_one :
                 len (grade_one())
              elif grade_names == grade_two :
                 len (grade_two())
              elif grade_names == grade_three :
                 len (grade_three())

      grade_one = {'Sami': [19, 18, 19.5, 30, 10],
       'Ahmad': [15, 14, 16, 21, 7],'Faris': [18, 19, 17, 26, 9],
       'Salem': [20, 20, 19, 30, 10],'Mahmoud': [12, 13, 11, 18, 7]}
      grade_two = {'Lana': [17, 19, 20, 28, 9],
      'Dina': [18.5, 19.5, 20, 29, 10],
       'Maha': [20, 20, 18, 26, 9],
        'Abeer': [16, 18, 19.5, 25, 8]}
      grade_three = {'Rima': [18, 19, 18, 26, 9],
       'Tala': [20, 20, 19, 29, 10],
       'Lamar': [19, 20, 18, 26, 9],
       'Rola': [15, 14, 16, 19, 7],
      'Naya': [9, 6, 11, 14, 7],
       'Dalal': [1, 5, 2, 6, 7],
        'Ola': [19.5, 20, 20, 29.5, 10]}

      print('if you done enter Done , else more')
      finish = input ('Done','more')
        if finish == 'Done':
            break
        else :
              print('choose one : student_names , student_score , student_count ')
