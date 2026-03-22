import subprocess
import time

# Set the countdown duration
seconds = 10

print(f"Closing Discord in {seconds} seconds...")

# Loop to show a countdown in the console
for i in range(seconds, 0, -1):
    print(f"{i}...", end="\r") # \r keeps the countdown on the same line
    time.sleep(1)

print("\nGoodbye Discord.")
subprocess.run("taskkill /IM discord.exe /F", shell=True)
