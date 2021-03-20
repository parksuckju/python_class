# python_class
suckju's house
=============
> a=10
>>print(a)
print(type(a))
b="hello my name is suckju "
print(b)
print(type(b))
print("안녕하슈"[0:4])
list_a= [1,2,3,4,5,6,7,8,9,10]
print(a)
list_a.append(11)
print(list_a)

#33
#HIHIHI
print("-" * 80)

t1 = 'python'
t2 = 'java'
t3 = t1 + ' ' + t2 + ' '
print(t3 * 4)

name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13
print("이름:%s 나이:%d" % (name1,age1))
print("이름:%s 나이:%d" % (name2,age2))

license_plate = "24가 2210"
print(license_plate[4:])

string ="홀짝홀짝홀짝"
print(string[::2])

string = "PYTHON"
print(string[::-1])

phone_number = "010-1111-2222"
phone_number1 = phone_number.replace("-", " ")
print(phone_number1)

phone_number = "010-1111-2222"
phone_number1 = phone_number.replace("-", "")
print(phone_number1)

url = "http://sharebook.kr"
print
string = 'abcdfe2a354a32a'
string =string.replace("a","A")
print(string)

rl = "http://sharegjghjbook.kr"
url_split = url.split('.')
print(url_split[-1])

print("-" * 80)

t1 = 'pyton'
t2 = 'java'
print((t1 +' '+t2 +' ')* 4)

name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13
print("이름: %s 나이: %d"%(name1,age1))
print("이름: %s 나이: %d"%(name2,age2))

name1 = "김민수" 
이름:%s 나이:%d" % (name1,age1))

30

print("이름:%s 나이:%d" % (name2,age2))

31



32

license_plate = "24가 2210"

33

print(license_plate[4:])

34



35

string ="홀짝홀짝홀짝"

36

print(string[::2])

37



38

string = "PYTHON"

39

print(string[::-1])

40



41

phone_number = "010-1111-2222"

42

phone_number1 = phone_number.replace("-", " ")

43

print(phone_number1)

44



45

phone_number = "010-1111-2222"

46

phone_number1 = phone_number.replace("-", "")

47

print(phone_number1)

48



49

url = "http://sharebook.kr"

50

print

51

string = 'abcdfe2a354a32a'

52

string =string.replace("a","A")

53

print(string)

54



55

rl = "http://sharegjghjbook.kr"

56

url_split = url.split('.')

57

print(url_split[-1])

58



59

print("-" * 80)

60



61

t1 = 'pyton'

62

t2 = 'java'

63

print((t1 +' '+t2 +' ')* 4)

64



65

name1 = "김민수" 

66

age1 = 10

67

name2 = "이철희"

68

age2 = 13

69

print("이름: %s 나이: %d"%(name1,age1))

70

print("이름: %s 나이: %d"%(name2,age2))

71



72

name1 = "김민수" 

73

age1 = 10                                       이름 나이 출력
name2 = "이철희"
age2 = 13
print("이름: {} 나이: {}".format(name1, age1))
print("이름: {} 나이: {}".format(name2, age2))



name1 = "김민수" 
age1 = 10
name2 = "이철희"
age2 = 13

b = "5,969,782,550"
a = b.replace(",","")

분기 = "2020/03(E) (IFRS연결)" 
print(분기[:7])


for 변수 in [10,20,30]:
  print(변수)
  print("----------")        10 하고 --- 20 하고 --- 30 하고 -- 나온다음 석희가 나온다
print("박석희")

print("++++")  
for 변수 in [10,20,30]:         변수를 말그대로 10 20 30 출력
  print(변수)

리스트 = ["SK하이닉스", "삼성전자", "LG전자"]
for 문자열 in 리스트:           3개의 브랜드에 문자열의 개수를 출력해준당
  print(len(문자열))

리스트 = ['dog', 'cat', 'parrot']문자열이 출력되고 문자열 문자의 개수도 나온다
for 문자열 in 리스트:
  print(문자열 , len(문자열))

리스트 = ['dog', 'cat', 'parrot']    3개의 단어의 0번째 배열에 있는 알파벳만 출력한다 따라서 d c ㅔajs sjdgsej
for 문자열 in 리스트:
  print(문자열[0])

리스트 = [1,2,3]                  반복문에 의해 1 2 3이 다 곱셉에 대입되이 결구 3*1 3*2 3*3 의 숫자가 열
for 곱셈 in 리스트:
  print("3 *",곱셈 ,"=",3*곱셈)

리스트 = ["가", "나", "다", "라"] 첫번째부터 쭉 시작되니 0인 가는 출력안되고 나부터 라까지 따라서 나다라 이다
for 변수 in 리스트[1:]:
  print(변수)

리스트 = ["가", "나", "다", "라"]  처음에 0부터 시작하여 스탑하니 가 출력 다음 쭉 하고 2에서 멈추니 2번째 다 출력 된다 따라서 가다 출력
for 변수 in 리스트[: :2]:
  print(변수)

리스트 = ["가", "나", "다", "라"] -1로 인해서 뒤로 라다나가 순서로 출력
for 변수 in 리스트[: :-1]:
  print(변수)
