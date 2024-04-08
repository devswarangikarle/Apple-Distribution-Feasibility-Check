# Apple-Distribution-Feasibility-Check
You have n apples and m people. Each apple weighs exactly 1 kg. To distribute the apples among the people, you can cut each apple into halves as many times as needed. Determine if it's possible to distribute the apples among the m people such that each person gets an equal weight of apples.

n, m = map(int, input().split())
while m % 2 == 0:
    m //= 2
print("Yes" if n % m == 0 else "No")
