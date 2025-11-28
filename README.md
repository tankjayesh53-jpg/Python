📁 Python-Pyramid-Patterns/
│-- README.md
│-- pattern_01.py
│-- pattern_02.py
│-- pattern_03.py
│-- ...
│-- pattern_65.py
python pattern_01.py     # For Pattern 1
python pattern_02.py     # For Pattern 2
...
python pattern_65.py     # For Pattern 65
rows = int(input("Enter rows: "))
for i in range(1, rows + 1):
    print(" " * (rows - i), end="")
    for j in range(1, i + 1):
        print("* ", end="")
    print()
   *
   * *
  * * *
 * * * *
* * * * *
rows = int(input("Enter rows: "))
for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()
    1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
Fork → Modify → Pull Request 👍
