
def lone_sum(a, b, c):
    if a >= b:
        return c
    elif a == c:
        return b
    elif b == c:
        return a
    elif a == b and a == c and b == c:
        return 0
    else:
        return a+b+c
if_name_ == '_main_':
x = int(input())
y = int(input())
z = int(input())

result = lone_sum(x, y, z)
print("Input: " + str
{x} + ", " + str(y) + ", " + str(z))
print("result: " + str(result))
