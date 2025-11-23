# simple typing speed test
import time

text = "The quick brown fox jumps over the lazy dog"
print("Type this sentence:")
print(text)
input("Press Enter when you are ready...")

start = time.time()  # start timer
typed = input("Start typing here:\n")
end = time.time()    # end timer

total_time = end - start
words = len(typed.split())  # count words
if total_time > 0:
    wpm = (words / total_time) * 60
else:
    wpm = 0

correct_chars = 0
for i in range(min(len(text), len(typed))):
    if text[i] == typed[i]:
        correct_chars += 1
accuracy = (correct_chars / len(text)) * 100

print(f"\nTime taken: {total_time:.2f} seconds")
print(f"Words per minute: {wpm:.2f}")
print(f"Accuracy: {accuracy:.2f}%")
