# 一级标题  

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题  

###### 共六级标题

---
**段落**  

第一个段落,两个段落之间空一行

这是第二段落

这是第三段落  

---
**换行**  

this is first line  
如果想实现换行，只需要在前一行最后面两个空格+回车即可实现换行，或者通过`<br/>`<br/>
实现换行  

---
**标记**  
1. 通过双`*`或者双下划线`_`包裹给文字**加粗****加粗**  
2. 通过单`*`或者单`_`包裹实现*斜体文字*  
3. 通过混合`__*`实现 ***斜体加粗***,要注意如果以双下划线`__`开始，开始的地方要与前面的一个文字保留一个空格  
4. 通过双波浪线`~~`包裹给文字加~~删除标记~~  

---
**列表**  
使用`+`or`-`加空格实现无序列表 
- 无序1
- 无序2  
 
使用数字+空格实现有序列表  
1. 有序列表1  
2. 有序列表2  

列表嵌套  
1. 有序列表1  
   - 嵌套的无序列表1  
   - 嵌套的无序列表2  
2. 有序列表2  
   + 嵌套的无序列表1  
   + 嵌套的无序列表2  

整个列表结束后要和下一行通过段落结束  

---

**链接**  
文字超链接语法：`[content](url)`  
[百度一下](https://www.baidu.com)  
图片链接语法：`![content](url)`  
![picture 0](images/a3f7f5e2fb728ff02b0163fbeaa8eda643b63b690a515a7c8c3fd1ab8257003f.jpeg)  

---  
**引用**  
使用`>`一级引用，在一级引用里通过`>>`实现二级引用  
>这是一级引用  
dddddddddddd  
ddd  
>>这是二级引用  
二级引用  

通过段落结束引用  

---

**代码**
行内代码直接使用单反引号\``这是一个行内代码`  
代码块使用三个反引号\`\`\`包裹,后面可以紧接着语言  
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
---
**分割线**  
使用三个\-\-\-表示分割线，分割线上下一行保持空行  

**表格**  
通过英文竖线和横线实现简单表格  
|表头列1|表头列2|表头列3|
|---:|:---:|---|
|行1列1|行2列2|行3列3|
|右侧对齐|居中对齐|不对齐|  








