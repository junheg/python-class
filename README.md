# python-class# 
year = int(input())
# print(year-543)

# a, b, c, d, e, f = map(int, input().split())
#
# chess = [a, b, c, d, e, f]
#
# chess_rull = [1, 1, 2, 2, 2, 8]
#
# for i in range(len(chess)):
#
#     chess[i] = chess_rull[i] - chess[i]
#
# print(*chess)

a, b, c = map(int, input().split())

print((a+b)%c)
print(((a%c)+(b%c))%c)
print((a*b)%c)
print(((a%c)*(b%c))%c)
