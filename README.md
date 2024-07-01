immutable_var = ("Алексей", 25, True)
print("Кортеж immutable_var:", immutable_var)
try:
    immutable_var[0] = "Михаил"
except TypeError as e:
    print("Ошибка:", e)
mutable_list = ["яблоко", "банан", "вишня"]
print("Исходный список mutable_list:", mutable_list)
mutable_list[0] = "киви"
mutable_list[1] = "манго"
print("Измененный список mutable_list:", mutable_list)
