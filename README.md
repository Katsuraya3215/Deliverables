# Deliverables 26/1/17

## 概要
ifの条件分岐を使った、選択→入力→表示ツール

## 実行方法
```python
def main():
    signal = input("Signal color? ")

    if signal == "red":
        print("No")
    elif signal == "yellow":
        print("Slow down")
    elif signal == "blue" or signal == "green":
        print("Go")
    else:
        print("Invalid signal color...")

if __name__ == "__main__":
    main()
```

