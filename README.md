# Data_analysis-Practice

#2-1 리스트 슬라이싱


#2-1-1 리스트 슬라이싱 기본
"""
numbers = [1, 2, 3, 4, 5]
first_four = numbers[:4]
print(first_four)  # 출력: [1, 2, 3, 4]
"""

#2-1-2 홀수번째 항목 출력
"""
numbers = [10, 20, 30, 40, 50, 60, 70, 80, 90]

# 홀수 번째 항목을 출력해라
every_other = numbers[::2] #처음부터 끝까지 2칸씩 건너뛰기 코드임
print(every_other)  # 출력: [10, 30, 50, 70, 90]
"""

#2-1-3 리스트 역순 출력
"""
numbers = [10, 20, 30, 40, 50, 60, 70, 80, 90]
reverse_list = numbers[::-1]
print(reverse_list)  # 출력: [90, 80, 70, 60, 50, 40, 30, 20, 10]
"""

#2-1-4 행렬 출력

"""
matrix = [
    [1, 2, 3],
    [5, 6,7,8],
    [9, 10, 11, 12]
    [13, 14, 15, 16
     ]

# 첫 두행 출력
first_two_rows = matrix[:2]
"""


### 3강


# 3-1 언패킹
"""
coordinates = (10, 20)

# 튜플 언패킹

print(f'x좌표: {x}, y좌표: {y}')

rgb = [255, 128, 0]
# 리스트 언패킹

print(f'빨강: {red}, 초록: {green}, 파랑: {blue}')

word = 'ABC'
# 문자열 언패킹

print(f'첫 번째 문자: {first}, 두 번째 문자: {second}, 세 번째 문자: {third}')

"""

"""
def get_dataset_stats(values):
  return min(values), max(values), sum(values) / len(values)

data = [12, 8, 21, 17, 5, 32, 14]

# 함수값 return 언패킹

minimum, maximum, average = get_dataset_stats(data)
print(f'최솟값: {minimum}, 최댓값: {maximum}, 평균: {average:.2f}')
"""
"""
student_scores = [
    ('김철수', 85, 92, 78),
    ('이영희', 92, 88, 95),
    ('박지민', 75, 83, 90)
]

# 반복문에서 언패킹 사용
for name, database, python, cloud in student_scores:
  average = (database + python + cloud) / 3
  print(f'{name}의 평균 점수: {average:.1f}')

"""

"""
monthly_sales = [1200, 1350, 1420, 1500, 1300, 1580, 1620, 1700, 1800, 1850, 1900, 2000]

# 1월, 2월 및 나머지 월 매출액
first, second, *remaining = monthly_sales
print(f'1월 판매액: {first}')
print(f'2월 판매액: {second}')
print(f'나머지 월 판매액: {remaining}')

# 1월, 12월 및 나머지 월 매출액
first, *middle, eleventh, last = monthly_sales
print(f'첫 달(1월) 판매액: {first}')
print(f'마지막 달(12월) 판매액: {last}')
print(f'중간 달(2~11월)의 판매액: {middle}')
"""

# 3-5 언더스코어
"""
students = [
    (20251234, '김철수', '컴퓨터과학', 2, 3.8),
    (20265678, '이영희', '생활과학부', 3, 4.2),
    (20243456, '박민수', '사회복지학과', 1, 3.5)
]

# 이름 및 성적 만 출력
for    :
    print(f'{name}의 성적: {grade}')
    
    
    def get_coordinates( ):
    return (10, 20, 30)

# 함수 return 값 언더스코어 사용


print(y)
"""

#3-2 예외 처리



# try 문
"""
try:
    number = int(input(f'정수를 입력하세요: '))
    result = 10 / number
    print(f'결과: {result}')

# except 문
except ZeroDivisionError:
    print('0으로 나눌 수 없습니다.')
except ValueError:
    print('유효한 정수를 입력하세요.')
"""

