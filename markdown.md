### Markdown記法まとめ
[markdown](https://qiita.com/tbpgr/items/989c6badefff69377da7)

### 見出し
    # 見出し1
    ## 見出し2
    ### 見出し3
    #### 見出し4
    ####　見出し5
    #####　見出し6

___

### 箇条書きリスト
    - リスト1
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