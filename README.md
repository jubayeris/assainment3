# assainment3

total_seconds = int(input("Enter the total number of seconds: "))


hours = total_seconds // 3600
minutes = (total_seconds % 3600) // 60
seconds = total_seconds % 60


print("Hours:", hours)
print("Minutes:", minutes)
print("Seconds:", seconds)

