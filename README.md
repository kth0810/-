# a = input()
# if a[7] == "1" or a[7] == "3":
#     print("남자")
# elif a[7] == "2" or a[7] == "4":
#     print("여자")

# num = input("주민등록번호: ")
# back = num.split("-")[1]
# if 0 <= int(back[1:3]) <= 8:
#     print("서울입니다")
# else :
#     print("서울이 아닙니다")

# a = input()
# b, c = a.split("-")
# d = int(a[0])*2
# e = int(a[1])*3
# f = int(a[2])*4
# g = int(a[3])*5
# h = int(a[4])*6
# i = int(a[5])*7
# j = int(a[7])*8
# k = int(a[8])*9
# l = int(a[9])*2
# m = int(a[10])*3
# n = int(a[11])*4
# o = int(a[12])*5
# p = d+e+f+g+h+i+j+k+l+m+n+o
# q = int(p)%11
# r = 11-q
# if int(a[13]) == r:
#     print("유효한 주민등록번호입니다")
# else:
#     print("유효하지 않은 주민등록번호입니다")

# a = input()
# b, c = a.split(":")
# if b == "0":
#     if int(c) < 45:
#         print("23", int(c)+60-45)
# elif 0 < int(b):
#     if 45 < int(c):
#         print(int(b), int(c)-45)
# elif 0 < int(b):
#     if int(c) < 45:
#         print(int(b)-1, int(c)+60-45)

# l = [10, 20, 30]
# for i in range(31):
#     if i in l:
#         print(i)

# l = [100, 200, 300]
# for i in range(301):
#     if i in l:
#         print(i+10)

# l = ["김밥", "라면", "튀김"]
# for i in l:
#     print("오늘의 메뉴:"+i)

# l = ["sk하이닉스", "삼성전자", "LG전자"]
# for i in l:
#     print(len(i))

# l = ["dog", "cat", "parrot"]
# for i in l:
#     print(i, len(i))

# l = ["dog", "cat", "parrot"]
# for i in l:
#     print(i[0])

# l = [1,2,3]
# for i in l:
#     print("3 *",i)

# l = [1,2,3]
# for i in l:
#     print("3 *", i, '=', 3*i)

# l = ["가", "나", "다", "라"]
# for i in l[1:]:
#     print(i)

# l = ["가", "나", "다", "라"]
# for i in l[::2]:
#     print(i)

# l = ["가", "나", "다", "라"]
# for i in l[::-1]:
#     print(i)

# l = [3, -20, -3, 44]
# for i in l:
#     if i < 0:
#         print(i)
#
# l = [3, 100, 23, 44]
# for i in l:
#     if i%3 == 0:
#         print(i)

# l = [13, 21, 12, 14, 30, 18]
# for i in l:
#     if (i < 20 and (i%3==0)):
#         print(i)
