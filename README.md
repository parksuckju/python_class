##license_plate = "24가 2210"
```
print(license_plate[4:])
```
###string ="홀짝홀짝홀짝"
```
print(string[::2])
```
###string = "PYTHON"
```
print(string[::-1])
```
```
phone_number = "010-1111-2222"
phone_number1 = phone_number.replace("-", " ")
print(phone_number1)
```
```
phone_number = "010-1111-2222"
phone_number1 = phone_number.replace("-", "")
print(phone_number1)
```
```
url = "http://sharebook.kr"
print
string = 'abcdfe2a354a32a'
string =string.replace("a","A")
print(string)
```
```
rl = "http://sharegjghjbook.kr"
url_split = url.split('.')
print(url_split[-1])
```
```
print("-" * 80)
```
```
t1 = 'pyton'
t2 = 'java'
print((t1 +' '+t2 +' ')* 4)
```
```
name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13
print("이름: %s 나이: %d"%(name1,age1))
print("이름: %s 나이: %d"%(name2,age2))
```
```
name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13
print("이름: {} 나이: {}".format(name1, age1))
print("이름: {} 나이: {}".format(name2, age2))
```

```
name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13
```
```
b = "5,969,782,550"
a = b.replace(",","")
```
###분기 = "2020/03(E) (IFRS연결)"
```print(분기[:7])
```
##반복문
```
for 변수 in [10,20,30]:
  print(변수)
  print("----------")
print("박석희")
```
```
print("++++")  
for 변수 in [10,20,30]:
  print(변수)
```
###리스트 = ["SK하이닉스", "삼성전자", "LG전자"]
```for 문자열 in 리스트:
  print(len(문자열))
```
###리스트 = ['dog', 'cat', 'parrot']
```for 문자열 in 리스트:
  print(문자열 , len(문자열))
```
###리스트 = ['dog', 'cat', 'parrot']
```for 문자열 in 리스트:
  print(문자열[0])
```
###리스트 = [1,2,3]
```for 곱셈 in 리스트:
  print("3 *",곱셈 ,"=",3*곱셈)
```
###리스트 = ["가", "나", "다", "라"]
```for 변수 in 리스트[1:]:
  print(변수)
```
###리스트 = ["가", "나", "다", "라"]
```for 변수 in 리스트[: :2]:
  print(변수)
```
###리스트 = ["가", "나", "다", "라"]
```
for 변수 in 리스트[: :-1]:
  print(변수)
```
###리스트 = [3, -20, -3, 44]
```
for 변수 in 리스트:
   if 변수 < 0:
     print(변수)
```
###리스트 = [3, 100, 24, 44]
```for 변수 in 리스트:
   if 변수 % 3 ==0:
     print(변수)
```
###리스트 = [13,21,12,14,30,18]
```
for 변수 in 리스트:
    if 변수 <20:
      if 변수 % 3 == 0:
        print("4번문제  : " , 변수)
```
###리스트 = ["I", "study", "python", "language", "!"]
```
for 변수 in 리스트:
  if len(변수) >= 3:
    print(변수)
```
###리스트 = ["A", "b", "c", "D"]
```
for 변수 in 리스트:
  if 변수.isupper():
    print(변수)
```
###upper 사용방법!!!
```
문자열 에서 가로를 열어줌
a = "hello"
print(a.upper())
```
