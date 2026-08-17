import os

print("Pesimist bot başlatılıyor...")
print("BOT_TOKEN:", "VAR" if os.getenv("BOT_TOKEN") else "YOK")
print("API_ID:", "VAR" if os.getenv("API_ID") else "YOK")
print("API_HASH:", "VAR" if os.getenv("API_HASH") else "YOK")
