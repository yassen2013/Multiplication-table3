# Multiplication-table3
num1 = float( input("ادخل الرقم الاول"))
num2 = float( input("ادخل الرقم الثاني"))


sum_result = num1 + num2
diff_result = num1 - num2
prod_result = num1 *num2
quot_result = num1 / num2 if num2 != 0 else"غير معرف"


print(f"{num1} + {num2} = {sum_result}")
print(f"{num1} - {num2} = {diff_result}")
print(f"{num1} * {num2} = {prod_result}")
print(f"{num1} / {num2} = {quot_result}")
