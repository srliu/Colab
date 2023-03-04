# hackmd教學
###### tags: `MarkDown語法`
---
## 1.簡介
---
hackmd是一個方便的筆記軟體，使用**markdown**語法可以很輕易地以純鍵盤的形式把你想整理的東西記錄下來
## 2.標題
---
# 我是標題啦哈哈
我是內文啦哈哈
## 我是標題啦哈哈
我是內文啦哈哈
### 我是標題啦哈哈
我是內文啦哈哈
#### 我是標題啦哈哈
我是內文啦哈哈
##### 我是標題啦哈哈
我是內文啦哈哈
###### 我是標題啦哈哈(啊我比內文還小是怎樣)
我是內文啦哈哈
## 3.字體格式
---
1. 粗體：**我是粗體**、__我也是粗體__
2. 斜體：*我是斜體*、_我也是斜體_
3. 刪除號：~~我是刪除號~~
4. 底線：++我是底線++
5. 標記：==我是標記==
6. 旁註標記：{我是主要文字|我是旁註標記}
7. 引用：


>我沒說過這句話
> [name=魯迅] [time=Sun, July 28, 1936 11:23 PM][color=#35bee8]
6. 程式碼：
- C++
```cpp=
include <bits/stdc++.h>
using namespace std;

int main()
{
    cout << "Hello world!";
}
```
- Python
```python=
a = 10 
b = 20
print(a + b)
```
6. checkbox
- [x] 社課
- [ ] 小社課
- [ ] 聯課
- [ ] 社展
- [x] 考幹題

## 4.清單
---
### 有序清單
1. 這是清單適合你將需要條列式的東西打下來
1. 你會發現其實就算標題號打錯也會顯示正確(真香)
2. 而且他會自己幫你列標號，真香~
    1. 你當然可以製作巢狀結構
    2. 就像這樣
        3. 不過我沒試過他具體能到多少層就是了
### 無序清單
- 這是無序清單
- 適合你將沒有前後關聯的東西打下來
    - 當然也可以製作巢狀結構
        - 就像這樣，很方便明瞭吧！ 

## 5.表格
---
| 標題一   | 標題二   |
|-|-|
| B   | B   |

| 靠左對齊 | 靠右對齊 | 靠中對齊 | 
|:------ |------: |:--------:|
| B      | B      |B         |
| C      | C      |C         |

## 6.插入影像
---
[這是一個連結](https://youtu.be/dQw4w9WgXcQ)
[這也是一個連結]()
**這則是一個yt連結**
{%youtube  dQw4w9WgXcQ%}
**我插了一張圖在這裡**
![](https://i.imgur.com/UAkrSdN.jpg =100x100)

## 7.特殊顏色區塊
---
:::success
民進黨的感覺
:::

:::info
國民黨的感覺
:::

:::warning
時代力量的感覺
:::

:::danger
共產黨的感覺
:::

:::spoiler 藏起來的資訊
黑箱的感覺
:::

## 8.可愛的圖案
---
:male_sign::female_sign:
:man_and_woman_holding_hands:
:kiss:
:point_right: :ok_hand:
:clap: :clap: :clap:
   
:rainbow: :rainbow-flag: :rainbow-flag::rainbow-flag::rainbow:
[完整列表](https://gist.github.com/rxaviers/7360908)

## 9.目錄
---
>table of contents
>
>[toc]

## 10.數學符號
---
That's another story.


| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Text     | Text     | Text     |

