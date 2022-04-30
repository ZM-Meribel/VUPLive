---
tags:
  - Introduce
  - Vtuber
  - Other
title: 帮助
hide:
---
# 如何编写Wiki?


  ***A:点击右上角的小电视图标前往 Github 仓库编写并提交Pull Requests,在通过审核后即可显示在本wiki中 !***


# 编写技巧
## 缩写

虚拟主播
*[虚拟主播]: 虚拟主播又名皮套人

``` py
虚拟主播
*[虚拟主播]: 虚拟主播又名皮套人
```
## 提醒块

### 默认标题
!!! note 

    VupLive wiki 是一个公平公正的V圈百科
    
```  
!!! note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```
### 自定义标题
!!! note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```  
!!! note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```

### 删除标题
!!! note ""

    VupLive wiki 是一个公平公正的V圈百科
```  
!!! note ""

    VupLive wiki 是一个公平公正的V圈百科
```

### 可折叠提醒块(默认折叠)
??? note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```  
??? note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```

### 可折叠提醒块(默认打开)
???+ note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```  
???+ note "提醒"

    VupLive wiki 是一个公平公正的V圈百科
```
### 内嵌的提醒块

=== "末尾的提醒块"
    !!! info inline end
    
        Lorem ipsum dolor sit amet, consectetur
        adipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat
        finibus, justo purus auctor massa, nec
        semper lorem quam in massa.
    
    
    ```
    !!! info inline end
    
        Lorem ipsum dolor sit amet, consectetur
        adipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat
        finibus, justo purus auctor massa, nec
        semper lorem quam in massa.
    ```
    用于向右对齐（左侧表示 rtl 语言）。`inline end`
=== "开始的提醒块"
    !!! info inline 
    
        Lorem ipsum dolor sit amet, consectetur
        adipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat
        finibus, justo purus auctor massa, nec
        semper lorem quam in massa.
    
    ```
    !!! info inline 
    
        Lorem ipsum dolor sit amet, consectetur
        adipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat
        finibus, justo purus auctor massa, nec
        semper lorem quam in massa.
    ```
    用于向左对齐（对于 rtl 语言，右对齐）。`inline`

### 支持的类型
??? example "点开列表查看"
    `note`
    !!! note 

        VupLive wiki 是一个公平公正的V圈百科
    `abstract,,summary,tldr`
    !!! abstract 

        VupLive wiki 是一个公平公正的V圈百科
    `info,,todo`
    !!! info 

        VupLive wiki 是一个公平公正的V圈百科
    `tip,,hint,important`
    !!! tip

        VupLive wiki 是一个公平公正的V圈百科
        `success,,checkdone`
    !!! success 
    
        VupLive wiki 是一个公平公正的V圈百科
    `question, , helpfaq`
    !!! question 
    
        VupLive wiki 是一个公平公正的V圈百科
    `warning, , cautionattention`
    !!! warning 
    
        VupLive wiki 是一个公平公正的V圈百科
    `failure, , failmissing`
    !!! failure 
    
        VupLive wiki 是一个公平公正的V圈百科
    `danger, error`
    !!! danger 
    
        VupLive wiki 是一个公平公正的V圈百科
    `bug`
    !!! bug 
    
        VupLive wiki 是一个公平公正的V圈百科
    `example`
    !!! example 
    
        VupLive wiki 是一个公平公正的V圈百科
    `quote, cite`
    !!! quote 
    
        VupLive wiki 是一个公平公正的V圈百科
    `cc`
    !!! cc 
    
        VupLive wiki 是一个公平公正的V圈百科
    `huo`
    !!! huo 
    
        VupLive wiki 是一个公平公正的V圈百科
    `dy`
    !!! dy 
    
        VupLive wiki 是一个公平公正的V圈百科
    `home`
    !!! home 
    
        VupLive wiki 是一个公平公正的V圈百科
    `bilibili`
    !!! bilibili 
    
        VupLive wiki 是一个公平公正的V圈百科
    `youtube`
    !!! youtube 
    
        VupLive wiki 是一个公平公正的V圈百科
    `twitter`
    !!! twitter 
    
        VupLive wiki 是一个公平公正的V圈百科
    `twitech`
    !!! note 
    
        VupLive wiki 是一个公平公正的V圈百科
    `github`
    !!! github 
    
        VupLive wiki 是一个公平公正的V圈百科
    `bing`
    !!! bing 
    
        VupLive wiki 是一个公平公正的V圈百科
    `discord`
    !!! discord 
    
        VupLive wiki 是一个公平公正的V圈百科
    `acfun`
    !!! acfun 
    
        VupLive wiki 是一个公平公正的V圈百科
    `pixiv`
    !!! pixiv 
    
        VupLive wiki 是一个公平公正的V圈百科
    `providence`
    !!! providence 
    
        VupLive wiki 是一个公平公正的V圈百科
    `chaoslive`
    !!! chaoslive 
    
        VupLive wiki 是一个公平公正的V圈百科
    `nijisanji`
    !!! nijisanji 
    
        VupLive wiki 是一个公平公正的V圈百科
    `aien`
    !!! aien 
    
        VupLive wiki 是一个公平公正的V圈百科
    `ayiduo`
    !!! ayiduo 
    
        VupLive wiki 是一个公平公正的V圈百科
    `a-soul`
    !!! a-soul 
    
        VupLive wiki 是一个公平公正的V圈百科
    `bazooka`
    !!! bazooka 
    
        VupLive wiki 是一个公平公正的V圈百科
    `chobitslive`
    !!! chobitslive 
    
        VupLive wiki 是一个公平公正的V圈百科
    `creatorcoffee`
    !!! creatorcoffee 
    
        VupLive wiki 是一个公平公正的V圈百科
    `eros`
    !!! eros
    
        VupLive wiki 是一个公平公正的V圈百科
    `facemoe`
    !!! facemoe 
    
        VupLive wiki 是一个公平公正的V圈百科
    `fys`
    !!! fys 
    
        VupLive wiki 是一个公平公正的V圈百科
    `futureland`
    !!! futureland 
    
        VupLive wiki 是一个公平公正的V圈百科
    `houou`
    !!! houou 
    
        VupLive wiki 是一个公平公正的V圈百科
    `hmkj`
    !!! hmkj 
    
        VupLive wiki 是一个公平公正的V圈百科
    `Keronsas`
    !!! Keronsas 
    
        VupLive wiki 是一个公平公正的V圈百科
    `lepuslive`
    !!! lepuslive 
    
        VupLive wiki 是一个公平公正的V圈百科
    `mz`
    !!! mz 
    
        VupLive wiki 是一个公平公正的V圈百科
    `mys`
    !!! mys 
    
        VupLive wiki 是一个公平公正的V圈百科
    `namelessproject`
    !!! namelessproject 
    
        VupLive wiki 是一个公平公正的V圈百科
    `xld`
    !!! bazooka 
    
        VupLive wiki 是一个公平公正的V圈百科
    `nova`
    !!! nova 
    
        VupLive wiki 是一个公平公正的V圈百科
    `palette`
    !!! palette 
    
        VupLive wiki 是一个公平公正的V圈百科
    `projectlupinus`
    !!! projectlupinus 
    
        VupLive wiki 是一个公平公正的V圈百科
    `psp`
    !!! psp 
    
        VupLive wiki 是一个公平公正的V圈百科
    `qianniao`
    !!! qianniao 
    
        VupLive wiki 是一个公平公正的V圈百科
    `redcircle`
    !!! redcircle 
    
        VupLive wiki 是一个公平公正的V圈百科
    `ssr`
    !!! ssr 
    
        VupLive wiki 是一个公平公正的V圈百科
    `virtualconcept`
    !!! virtualconcept 
    
        VupLive wiki 是一个公平公正的V圈百科
    `vid`
    !!! vid 
    
        VupLive wiki 是一个公平公正的V圈百科
    `vg`
    !!! vg
    
        VupLive wiki 是一个公平公正的V圈百科
    `vr`
    !!! vr 
    
        VupLive wiki 是一个公平公正的V圈百科
    `vomnis`
    !!! vomnis 
    
        VupLive wiki 是一个公平公正的V圈百科
    `xyxy`
    !!! xyxy
    
        VupLive wiki 是一个公平公正的V圈百科
    `xfjt`
    !!! xfjt 
    
        VupLive wiki 是一个公平公正的V圈百科
    `zdbgj`
    !!! zdbgj
    
        VupLive wiki 是一个公平公正的V圈百科
    `novus`
    !!! novus 
    
        VupLive wiki 是一个公平公正的V圈百科
## 代码块
??? info "代码块"
    ``` py
    import tensorflow as tf
    ```
    
    ``` 
    
    ``` py
    import tensorflow as tf
    ```
??? info "带标题的代码块"
    ``` py title="bubble_sort.py"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
    ```
    ``` py title="bubble_sort.py"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
    
??? info "带行号的代码块"
    ``` py linenums="1"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
    ```
    ``` py linenums="1"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```

??? info "带有突出显示行的代码块"
    ``` py hl_lines="2 3"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
    ```
    ``` py hl_lines="2 3"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
    
??? info "内联代码块"
    The `#!python range()` function is used to generate a sequence of numbers.
    ```
    The `#!python range()` function is used to generate a sequence of numbers.
    ```
    
## 内容选项卡

???+ note "内容选项卡"
    === "C"
    
        ``` c
        #include <stdio.h>
    
        int main(void) {
          printf("Hello world!\n");
          return 0;
        }
        ```
    
    === "C++"
    
        ``` c++
        #include <iostream>
    
        int main(void) {
          std::cout << "Hello world!" << std::endl;
          return 0;
        }
        ```
???+ note "列表内容选项卡"        
    === "无序列表"
    
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
    
    === "有序列表"
    
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci  
    ```    
    === "无序列表"
    
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
    
    === "有序列表"
    
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci  
    ```    
???+ note "列表内容选项卡"     
    !!! example "提醒中的内容选项卡"
    
        === "Unordered List"
    
            ``` markdown
            * Sed sagittis eleifend rutrum
            * Donec vitae suscipit est
            * Nulla tempor lobortis orci
            ```
    
        === "Ordered List"
    
            ``` markdown
            1. Sed sagittis eleifend rutrum
            2. Donec vitae suscipit est
            3. Nulla tempor lobortis orci
            ```    
    ``` 
    !!! example "提醒中的内容选项卡"
    
        === "Unordered List"
    
            ``` markdown
            * Sed sagittis eleifend rutrum
            * Donec vitae suscipit est
            * Nulla tempor lobortis orci
            ```
    
        === "Ordered List"
    
            ``` markdown
            1. Sed sagittis eleifend rutrum
            2. Donec vitae suscipit est
            3. Nulla tempor lobortis orci
            ```    
    ``` 
    
## 数据表
### 普通
| 方法        | 描述                          |
| ----------- | ----------------------------- |
| `GET`       | :material-check:     获取资源 |
| `PUT`       | :material-check-all: 更新资源 |
| `DELETE`    | :material-close:     删除资源 |

``` 
| 方法        | 描述                          |
| ----------- | ----------------------------- |
| `GET`       | :material-check:     获取资源 |
| `PUT`       | :material-check-all: 更新资源 |
| `DELETE`    | :material-close:     删除资源 |
``` 
### 列对齐方式

=== "左对齐"
    ``` 
    | 方法        | 描述                          |
    | :---------- | :---------------------------- |
    | `GET`       | :material-check:     获取资源 |
    | `PUT`       | :material-check-all: 更新资源 |
    | `DELETE`    | :material-close:     删除资源 |
    ``` 
    
    | 方法        | 描述                          |
    | :---------- | :---------------------------- |
    | `GET`       | :material-check:     获取资源 |
    | `PUT`       | :material-check-all: 更新资源 |
    | `DELETE`    | :material-close:     删除资源 |
    
=== "中心对齐"
    ``` 
    | 方法        | 描述                          |
    | :---------: | :---------------------------: |
    | `GET`       | :material-check:     获取资源 |
    | `PUT`       | :material-check-all: 更新资源 |
    | `DELETE`    | :material-close:     删除资源 |
    ``` 
    
    | 方法        | 描述                          |
    | :---------: | :---------------------------: |
    | `GET`       | :material-check:     获取资源 |
    | `PUT`       | :material-check-all: 更新资源 |
    | `DELETE`    | :material-close:     删除资源 |

=== "右对齐"
    ``` 
    | 方法        | 描述                          |
    | :---------: | :---------------------------: |
    | `GET`       | :material-check:     获取资源 |
    | `PUT`       | :material-check-all: 更新资源 |
    | `DELETE`    | :material-close:     删除资源 |
    ``` 
    
    | 方法       | 描述                          |
    | ---------: | ---------------------------:  |
    | `GET`      | :material-check:     获取资源 |
    | `PUT`      | :material-check-all: 更新资源 |
    | `DELETE`   | :material-close:     删除资源 |

### 可排序的表格
  ``` 
    | Method      | Description                          |
    | ----------- | ------------------------------------ |
    | `GET`       | :material-check:     Fetch resource  |
    | `PUT`       | :material-check-all: Update resource |
    | `DELETE`    | :material-close:     Delete resource |
  ``` 


| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

## 脚注（脚注可以写在下一行，但必须缩进四个空格）
``` 
Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]
[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
``` 
Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]
[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
    
## 包含更改建议的文本
``` txt  title="例子"
    Text can be {--deleted--} and replacement text {++added++}. This can also be
    combined into {~~one~>a single~~} operation. {==Highlighting==} is also
    possible {>>and comments can be added inline<<}.
    
    {==
    
    Formatting can also be applied to blocks by putting the opening and closing
    tags on separate lines and adding new lines between the tags and the content.
    
    ==}
    
``` 
Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}
### 带突出显示的文本
```
 ==标记==
 ^^下划线^^
 ~~删除线~~
```
 ==标记==
 
 ^^下划线^^
 
 ~~删除线~~
 
### 带有子标和上标的文本 
``` 
 - H~2~0
 - A^T^A
```

 - H~2~0
 - A^T^A
 - 
### 键盘快捷键
``` 
++ctrl+alt+del++
``` 
++ctrl+alt+del++


## 带有图标的文字

 :fontawesome-brands-html5: __HTML__ 
 
 :fontawesome-brands-js: __JavaScript__ 
 
 :fontawesome-brands-css3: __CSS__ 
 
 :fontawesome-brands-internet-explorer: __Internet Explorer__ 
## Twemoji
您可以在 [这里](https://emojipedia.org/twitter/) 查找短代码
 :smile: 
 
## 带颜色的图标
 :octicons-heart-fill-24:{ .heart }
 
 :fontawesome-brands-twitter:{ .twitter }
 
## V圈的图标
 :vquan-1::vquan-2::vquan-3::vquan-4::vquan-5::vquan-6::vquan-7::vquan-8::vquan-9::vquan-10::vquan-11::vquan-12::vquan-13::vquan-14::vquan-15::vquan-16::vquan-17::vquan-18::vquan-19::vquan-20::vquan-21::vquan-22::vquan-23::vquan-24::vquan-25::vquan-26::vquan-27::vquan-28::vquan-29::vquan-30::vquan-31::vquan-32::vquan-33::vquan-34::vquan-35::vquan-36::vquan-37::vquan-38::vquan-39::vquan-40::vquan-41:
 
 对应的短代码分别是：
 ``` 
  :vquan-1::vquan-2::vquan-3::vquan-4::vquan-5::vquan-6::vquan-7::vquan-8::vquan-9::vquan-10::vquan-11::vquan-12::vquan-13::vquan-14::vquan-15::vquan-16::vquan-17::vquan-18::vquan-19::vquan-20::vquan-21::vquan-22::vquan-23::vquan-24::vquan-25::vquan-26::vquan-27::vquan-28::vquan-29::vquan-30::vquan-31::vquan-32::vquan-33::vquan-34::vquan-35::vquan-36::vquan-37::vquan-38::vquan-39::vquan-40::vquan-41:
  ``` 
## 图像

=== "左"
    ``` 
    ![Image title](https://dummyimage.com/300x200/eee/aaa){ align=left }
    ``` 
    ![Image title](https://dummyimage.com/300x200/eee/aaa){ align=left }
    
=== "右"
    ``` 
    ![Image title](https://dummyimage.com/300x200/eee/aaa){ align=right }
    ``` 
    ![Image title](https://dummyimage.com/300x200/eee/aaa){ align=right }
    
=== "带标题的图像"
    <figure markdown>
      ![Image title](https://dummyimage.com/600x400/){ width="300" }
      <figcaption>Image caption</figcaption>
    </figure>
    ``` 
    <figure markdown>
      ![Image title](https://dummyimage.com/600x400/){ width="300" }
      <figcaption>Image caption</figcaption>
    </figure>
    ``` 
    
=== "图像延迟加载"
    ``` 
    ![Image title](https://dummyimage.com/600x400/){ loading=lazy }
    ``` 
    ![Image title](https://dummyimage.com/600x400/){ loading=lazy }
    
=== "图像亮模式和暗模式"
    ``` 
    ![Image title](https://dummyimage.com/600x400/f5f5f5/aaaaaa#only-light)
    ![Image title](https://dummyimage.com/300x200/21222c/d5d7e2#only-dark)
    ``` 
    ![Image title](https://dummyimage.com/600x400/f5f5f5/aaaaaa#only-light)
    ![Image title](https://dummyimage.com/300x200/21222c/d5d7e2#only-dark)
    
    
## 列表
=== "无序列表"
    ```
        - Nulla et rhoncus turpis. Mauris ultricies elementum leo. Duis efficitur
          accumsan nibh eu mattis. Vivamus tempus velit eros, porttitor placerat nibh
          lacinia sed. Aenean in finibus diam.
            * Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
            * Nam vulputate tincidunt fringilla.
            * Nullam dignissim ultrices urna non auctor.
    ```
         
    - Nulla et rhoncus turpis. Mauris ultricies elementum leo. Duis efficitur
        accumsan nibh eu mattis. Vivamus tempus velit eros, porttitor placerat nibh
        lacinia sed. Aenean in finibus diam.
        
        * Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
        * Nam vulputate tincidunt fringilla.
        * Nullam dignissim ultrices urna non auctor.    
=== "有序列表"   
    ```
        1.  Vivamus id mi enim. Integer id turpis sapien. Ut condimentum lobortis
            sagittis. Aliquam purus tellus, faucibus eget urna at, iaculis venenatis
            nulla. Vivamus a pharetra leo.
        
            1.  Vivamus venenatis porttitor tortor sit amet rutrum. Pellentesque aliquet
                quam enim, eu volutpat urna rutrum a. Nam vehicula nunc mauris, a
                ultricies libero efficitur sed.
        
            2.  Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet
                rutrum. Pellentesque aliquet quam enim, eu volutpat urna rutrum a.
        
                1.  Mauris dictum mi lacus
                2.  Ut sit amet placerat ante
                3.  Suspendisse ac eros arcu
    ```
    1.  Vivamus id mi enim. Integer id turpis sapien. Ut condimentum lobortis
        sagittis. Aliquam purus tellus, faucibus eget urna at, iaculis venenatis
        nulla. Vivamus a pharetra leo.
    
        1.  Vivamus venenatis porttitor tortor sit amet rutrum. Pellentesque aliquet
            quam enim, eu volutpat urna rutrum a. Nam vehicula nunc mauris, a
            ultricies libero efficitur sed.
    
        2.  Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet
            rutrum. Pellentesque aliquet quam enim, eu volutpat urna rutrum a.
    
                1.  Mauris dictum mi lacus
                2.  Ut sit amet placerat ante
                3.  Suspendisse ac eros arcu    
                
=== "定义列表" 
    `Lorem ipsum dolor sit amet`
    
    :   Sed sagittis eleifend rutrum. Donec vitae suscipit est. Nullam tempus
        tellus non sem sollicitudin, quis rutrum leo facilisis.
    
    `Cras arcu libero`
    
    :   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
        ut eros sed sapien ullamcorper consequat. Nunc ligula ante.
    
        Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
        Nam vulputate tincidunt fringilla.
    ```        
        `Lorem ipsum dolor sit amet`
        
        :   Sed sagittis eleifend rutrum. Donec vitae suscipit est. Nullam tempus
            tellus non sem sollicitudin, quis rutrum leo facilisis.
        
        `Cras arcu libero`
        
        :   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
            ut eros sed sapien ullamcorper consequat. Nunc ligula ante.
        
            Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
            Nam vulputate tincidunt fringilla.
        Nullam dignissim ultrices urna non auctor.
    ```
=== "任务列表"     
    - [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
    - [ ] Vestibulum convallis sit amet nisi a tincidunt
        * [x] In hac habitasse platea dictumst
        * [x] In scelerisque nibh non dolor mollis congue sed et metus
        * [ ] Praesent sed risus massa
      - [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
    ```
        - [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
        - [ ] Vestibulum convallis sit amet nisi a tincidunt
            * [x] In hac habitasse platea dictumst
            * [x] In scelerisque nibh non dolor mollis congue sed et metus
            * [ ] Praesent sed risus massa
        - [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
    ```