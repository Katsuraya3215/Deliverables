# Deliverables 

##実施日
2026/1/17

## 概要
ifの条件分岐を使った、選択→入力→表示ツール

## 実行方法
```python
signal = input("Signal color?")
if signal == "red":
    print("Stop")
elif signal=="yellow":
    print("Slow down")
elif signal=="blue" or signal=="green":
    print("Go")
else :
    print("Invalid signal")
```

##実施日　
2026/1/19

##概要
while,match-case,break,continueを使ったデモンストレーション

##使用用途
数字を選択して、それぞれに合った選択肢を表示、もしくは終了するプログラム

#サンプルコード

```　python
while 1 == 1:
    command = int(input("Select 1, 2, 3 (0: Exit) "))
    match command:
        case 1:
            print("Menu 1")
        case 2:
            print("Menu 2")
        case 3:
            print("Menu 3")
        case 0:
            break #whileの処理から抜ける
        case _:
            print("Invalid command,try again")
            continue #それ以降の処理をスキップして反復処理を実行
    print("Menu processed correctly")
```



