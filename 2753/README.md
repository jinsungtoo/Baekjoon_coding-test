<img width="1149" alt="image" src="https://user-images.githubusercontent.com/115756142/228451553-8694a480-e56a-4edd-8df9-4d2b7465f21c.png">


    a = int(input())
    if (a % 4 == 0 and a % 100 != 0):
        print(1)
    elif a % 400 == 0:
        print(1)
    else:
        print(0)
