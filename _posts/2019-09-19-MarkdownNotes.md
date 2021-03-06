---
layout:     post
title:      Markdown简单语法
subtitle:   
date:       2019-09-20
author:     BY DW
header-img: img/post/post-bg-2.jpg
catalog: true
tags:
    - Markdown
    - 轻量级编程
---
# [编程语言]：Markdown简单语法
> 参考内容 [Markdown教程](https://www.runoob.com)  
> 在线调试链接 [Markdown在线编辑器](https://c.runoob.com/front-end/712)


## 标题
可以使用  
>	

	一级标题	
	=================  
	二级标题  
	-----------------  

标题可以使用加#键实现，可以加多个#实现多级标题  
## 段落  
可以使用两个空格加回车    
或者直接空一行  
## 字体  
使用*和_  
 
    *斜体文本*  
    
    _斜体文本_  
    
    **粗体文本**   
    
    __粗体文本__   
    
    ***粗斜体文本***  
    
    ___粗斜体文本___ 

效果如下所示：    

*斜体文本*  

_斜体文本_  

**粗体文本**  

__粗体文本__  

***粗斜体文本***  

___粗斜体文本___   

## 分隔线  
三个以上的星号、减号、下划线可以建立分割线，行内不能有除了空格以外的任何东西（减号不加空格会被按照二级标题处理）
>  

    ***  
    - - -  
    ___  

效果如下所示：    

***  

- - -  

___  

## 删除线  
前后两个波浪线`~~($Var)~~`可以实现  
    ~~(效果)~~

## 列表  
行的开头使用*，+，-，数字使用1. 字母使用a，默认数字>符号>字母，和tab键无关

    1. 使用数字
        * 使用 * 
        + 使用 +   
            a. 使用字母  
        - 使用 -  

效果：  
1. 使用数字
    * 使用 * 
    + 使用 +   
        a. 使用字母  
    - 使用 -   

## 区块  
区块使用tab键或四个空格进行缩进，行首使用>  

    > 1. 1st  
    > + 2nd  
    >> * 3rd  

显示为：  

> 1. 1st  
> + 2nd  
>> * 3rd  

列表中使用区块需要加上四个空格

## 代码
单行代码使用``包围起来  
区块代码统一使用tab或四个空格进行缩进  

`单行代码`

    多行代码1
    多行代码2

## 链接
输入： `百度 [百度](https://www.baidu.com)`  
效果：百度: [百度](https://www.baidu.com)  
或者  

    百度: [百度][1]
    [1]: https://www.baidu.com  

## 图片
输入： `![alt 属性文本](图片地址 "可选标题")`  

## 表格  

    | 左对齐 |  居中  | 右对齐 |  
    | :---- |  :---: | ----: |  
    | 单元格 | 单元格 | 单元格 |  
    | 单元格 | 单元格 | 单元格 |  

| 左对齐 |  居中  | 右对齐 |  
| :---- |  :---: | ----: |  
| 单元格 | 单元格 | 单元格 |  
| 单元格 | 单元格 | 单元格 |  

## 高级(截取网络示例)  

### 1. 支持html元素：  
    使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑   

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑  

### 2. 转义字符   

使用\  
\% \* \@

### 3. latex 公式   

使用`$$ $$`嵌套latex格式的公式  
$$ \log \prod_1^n $$
## 注意事项  
1. 不要再标题中加入标点符号  
2. git预览和浏览器中对空格的敏感程度不一样  
