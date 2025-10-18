from datetime import datetime, timedelta

def tomorrow_date():
    tomorrow = datetime.now() + timedelta(days=1)
    return tomorrow.strftime("%Y-%m-%d")

if __name__ == "__main__":
    print(f"Tomorrow's date will be: {tomorrow_date()}")
