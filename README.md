# task3exercises
ex1,ex2,ex3,ex4,ex5

EX1:
n1={"day1":"monday","day2":"tuesday"}
n2={"date1":"one","date2":"two"}
n1.update(n2)
print(n1)                   

OUTPUT FOR EX1:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task3ex1.py
{'day1': 'monday', 'day2': 'tuesday', 'date1': 'one', 'date2': 'two'}

Process finished with exit code 0



EX2:
month={"one":"january","two":"february","three":"march","four":"april","five":"may"}
del month["four"]
print(month)

OUTPUT FOR EX2:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task3ex2.py
{'one': 'january', 'two': 'february', 'three': 'march', 'five': 'may'}

Process finished with exit code 0



EX3:
l1=["day","night"]
l2=["sun","moon"]
n1=dict(zip(l1,l2))
print(n1)

OUTPUT FOR EX3:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task3ex3.py
{'day': 'sun', 'night': 'moon'}

Process finished with exit code 0



EX4:
colour={"pink","blue","black","grey","red","green","indigo","brown"}
n=len(colour)
print(n)

OUTPUT FOR EX4:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task3ex4.py
8

Process finished with exit code 0



EX5:
n1={1,2,3,4,5}
n2={4,5,6,7,8}
print(n1)
print(n2)
print("After removing the intersection of n2 from n1:")
print(n1-n2)

OUTPUT FOR EX5:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task3ex5.py
{1, 2, 3, 4, 5}
{4, 5, 6, 7, 8}
After removing the intersection of n2 from n1:
{1, 2, 3}

Process finished with exit code 0









