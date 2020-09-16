def solution(n):
    answer = []
    s = 0
    while n > 0:
        s =  n % 10
        n = n // 10
        answer.append(s)
    return answer
