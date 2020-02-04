# study_note

学習メモ

___

### Markdown記法まとめ
[markdown.md](https://github.com/RyotaEisaki/study_note/blob/master/markdown.md)

### 見出し
    # 見出し1
    ## 見出し2
    ### 見出し3
    #### 見出し4
    ####　見出し5
    #####　見出し6

___

### 箇条書きリスト
     リスト1
        - ネスト リスト1_1
            - ネスト リスト1_1_1
            - ネスト リスト1_1_2
        - ネスト リスト1_2
    - リスト2
    - リスト3
- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3

### 番号付きリスト
    1. 番号付きリスト1
        1. 番号付きリスト1_1
        1. 番号付きリスト1_2
    1. 番号付きリスト2
    1. 番号付きリスト3
1. 番号付きリスト1
    1. 番号付きリスト1_1
    1. 番号付きリスト1_2
1. 番号付きリスト2
1. 番号付きリスト3

### 引用
    > 引用1
    > 
    > 引用2
> 引用1
> 
> 引用2

### 二重引用
    > 引用
    > 
    > 引用2
    >> 引用2＿1
    >> 
    >> 引用2_2
> 引用
> 
> 引用2
>> 引用2＿1
>> 
>> 引用2_2

### 打ち消し
    ~~打ち消し~~
~~打ち消し~~
追加情報としたい内容を、detailsタグで囲みます。そして、要約として表示したい文章をsummaryタグで記載します。


### 折り畳み
折り畳み

<details><summary>折り畳み</summary>説明</details>


### pre記法(スペース4個orタブ)
#### Tab
    class Hoge
        def hoge
            print 'hoge'
        end
    end

#### Space
    class Hoge
      def hoge
        print 'hoge'
      end
    end

### code記法
    インストールコマンドは`gem install hoge` 
インストールコマンドは`gem install hoge` 

### 強調
#### 強調1
    normal *italic* normal
    normal _italic_ normal
normal *italic* normal
normal _italic_ normal

#### 強調2
    normal **bold** normal
    normal __bold__ normal
normal **bold** normal
normal __bold__ normal

#### 強調3
    normal ***bold*** normal
    normal ___bold___ normal
normal ***bold*** normal
normal ___bold___ normal

### チェックボックス
    - [ ] タスク1
    - [x] タスク2
- [ ] タスク1
- [x] タスク2

### 数式の挿入

    ```math
    \left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
    \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
    ```

```math
\left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

### 水平線
    ***

    ___

    ---

    *    *    *
***

___

---

*    *    *

### リンク
    [Google先生](https://www.google.co.jp/)
 
[Google](https://www.google.co.jp/)

    [Google2](google)
    その他の文章
    [Google3](google)

[Google2](google)
その他の文章
[Google3](google)

### 画像表示
    ![代替テキスト](gazou.png "タイトル")
  ![代替テキスト](gazou.png "タイトル")

  ### 表組
    |header1|header2|header3|
    |:--|--:|:--:|
    |align left|align right|align center|
    |a|b|c|
|header1|header2|header3|
|:--|--:|:--:|
|align left|align right|align center|
|a|b|c|
