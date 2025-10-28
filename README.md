from datetime import datetim

def daily_activity_1_v2():
    now = datetime.now()
    print(f"[v2] Daily GitHub activity #1 - {now.strftime('%Y-%m-%d %H:%M:%S')}")

if __name__ == "__main__":
    daily_activity_1_v2()
