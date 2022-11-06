# Two-Sum

def main(value, target):
	for i in range(0, len(value)):
		for j in range(i+1, len(value)):
			if value[i]+value[j] == target:
				return [i,j]	



value = list(map(int, input().split()))
target = int(input())
res =main(value, target)
print(res)
