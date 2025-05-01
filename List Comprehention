import random
from statistics import median, mean

# Create a random list of 1000 numbers between -50 and 50
numbers = [random.randint(-50, 50) for _ in range(1000)]

# 1. Filter negative numbers
negatives = list(filter(lambda x: x < 0, numbers))

# 2. Filter to get only odd numbers
odds = list(filter(lambda x: x % 2 != 0, numbers))

# 3. Filter numbers below the median
med = median(numbers)
below_median = list(filter(lambda x: x < med, numbers))

# 4. Map: Add 5 to each number
plus_five = list(map(lambda x: x + 5, numbers))

# 5. Map: Return squares of the numbers
squares = list(map(lambda x: x ** 2, numbers))

# 6. Map and Filter: Add 20 to values below 30
added_20_below_30 = list(map(lambda x: x + 20, filter(lambda x: x < 30, numbers)))

# 7. Filter numbers greater than mean and add 10
avg = mean(numbers)
greater_than_mean_plus_10 = list(map(lambda x: x + 10, filter(lambda x: x > avg, numbers)))

# 8. Count occurrences of number 10 using map, lambda, and count
is_ten_list = list(map(lambda x: x == 10, numbers))
count_of_10 = is_ten_list.count(True)

# Print results (you can comment/uncomment these to see each one)
print("1. Negative numbers:", negatives[:10])
print("2. Odd numbers:", odds[:10])
print("3. Below median:", below_median[:10])
print("4. Plus 5 to each:", plus_five[:10])
print("5. Squares:", squares[:10])
print("6. Add 20 to values < 30:", added_20_below_30[:10])
print("7. > Mean + 10:", greater_than_mean_plus_10[:10])
print("8. Count of 10s:", count_of_10)
