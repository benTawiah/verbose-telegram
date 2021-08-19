bmicalculator
 def bmi_calculator(name, weight, height_m):
     bmi = weight / (height_m ** 2)
     if bmi < 25:
         return name + 'not overweight'
     else:
         return name + "overweight"
