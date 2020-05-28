## Welcome to GitHub Pages


- [刷題](#刷題)
  * [高頻一百連結](#高頻一百連結)
  * [紀錄](#紀錄)
  * [Problems](#problems)
  * [Frequent-Used Library](#frequent-used-library)
    + [Array](#array)
    + [Random](#random)
- [Programming Book](#programming-book)
- [Programming Course](#programming-course)
	- [The Missing Semester of Your CS Education](#the-missing-semester-of-your-cs-education)
- [Java](#java)
  * [IntelliJ](#intelliJ)
	+ [Version Control](#version-control)
- [Python](#python)
  * [numpy](#sub-heading-1)
- [Android Development](#android-development)
  * [Reference](#reference)
- [Markdown Quick Lookup](#markdown-quick-lookup)

Mac 鍵符號
- Command 鍵 ⌘
- Shift 鍵 ⇧
- Option（或 Alt）鍵 ⌥
- Control（或 Ctrl）鍵 ⌃
- Caps Lock 鍵 ⇪

# Prepare Interview
Stage-1: JuneStuttgart small company -> Large company
Stage-2: September Berlin or Munich large company
Stage-3: November Amazon in Dublin, and Singapore


# Amazon Wants This
This requirement is a position from a typical Software Development Position in Amazon Dublin

### BASIC QUALIFICATIONS
- Bachelor’s Degree in Computer Science or related field.  
- 2+ years of software engineering experience.  
- A proven track record in architecting and shipping innovative and highly scalable cloud systems in an agile environment.  
- Exceptional communication skills.  
- A proven track record of making good technical judgement.  
- Excellent problem solving skills.  
- Highly organized individual  
- Computer Science fundamentals in data structures  
- Computer Science fundamentals in algorithm design, problem solving, and complexity analysis  
- Proficiency in, at least, one modern programming language such as Java or other

### PREFERRED QUALIFICATIONS

- Master’s Degree preferred.  
- Experience with various industry analytics and monitoring platforms.  
- Machine learning experience.  
- Experience building complex software systems that have been successfully delivered to customers  
- Knowledge of professional software engineering practices, including coding standards, code reviews, source control management, build processes, testing, and operations  
- Ability to take a project from scoping requirements through actual launch of the project  
- Experience of building solutions using AWS technologies.

# [Programming Book](https://drive.google.com/drive/folders/1_afYce_KHKfEtYlaGUonWOQSmTcjy3f1?usp=sharing)

- [《疯狂Java讲义第4版》](https://drive.google.com/file/d/1Q0qyitxsjvgoZaayHz4TO8oHuLHMaE9g/view?usp=sharing)
- [《疯狂Android讲义第3版》](https://drive.google.com/file/d/1Ky2T2K3zByyDQLnCvKzO76sD42LpTcoi/view?usp=sharing)
- [《程序员的自我修养—链接、装载与库》](https://drive.google.com/file/d/1ydLFZ7QUl_iEOIOsdfkq-MiQM6Yfnss4/view?usp=sharing)
- [《Thinking.In.Java.4th.Edition》](https://drive.google.com/open?id=1cbNwWrzHdRqjqR_vc_V5vSRfz34vqjTt)
- [《Fluent Python》](https://drive.google.com/file/d/1AV59fwciY2RwgEN11vs5V9_G_mJhyy6e/view?usp=sharing) 
- [《Python Data Science Handbook》](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [《Cracking the Coding Interview》]

# [Programming Course]
- 《CS61B Data Structure》by UC Berkeley
	- [https://sp18.datastructur.es/](https://sp18.datastructur.es/)
	- [https://sp19.datastructur.es/](https://sp19.datastructur.es/)
	- Screencast of sp18
- [《Algorithms, Part I》by Princeton](https://www.coursera.org/learn/algorithms-part1/home/welcome)
- [《The Missing Semester of Your CS Education 》by MIT](https://missing.csail.mit.edu/)
- [《 Introduction to Git and GitHub by Google》by Google](https://www.coursera.org/learn/introduction-git-github/home/welcome)
-  [《Android Developer Fundamentals》by Google](https://developer.android.com/courses/fundamentals-training/toc-v2)


## The Missing Semester of Your CS Education
###  Course overview + the shell

- Why learn terminal? GUI has limited function, and text-based command terminal is more general, and versatile
- privilege: x: execute, have the permission to access the entire parent folder of certain file/directory
useful command

```markdown
 //program take #input as input argument
 #program < #input 
 
 //program its export output to #output
 #program > #output
 
 //program append output to #output
 #program >> #output  
 
 // means space (because shell differentiate different argument by space character 
 \
 
 // takes an input write to a file and also show it
 tee 
```

### Vim 小技巧
set number 開啟行數顯示
修改.vimrc 加入set number讓vim都可以顯示行數


## Android Developer Fundamentals
[學習紀錄](https://docs.google.com/document/d/1s32QPhb5lg1lOj1ke2YFubwk6O8naeVqfNGvok5X3c4/edit?usp=sharing)
# Java
- [w3schools](https://www.w3schools.com/java/): 網站把所有常用的python syntax都列入，每次忘記直接來查

## Concurrency
[Oracle Documentation](https://docs.oracle.com/javase/tutorial/essential/concurrency/index.html)
[Google Java Style Guide](http://google.github.io/styleguide/javaguide.html#s2.2-file-encoding)

## IntelliJ
- [Josh’s IntelliJ Editor Settings](https://drive.google.com/drive/folders/1Y5cHl-nNe731EgG4pAk2Dokgbu4ZpV5E?usp=sharing):CS61B Josh自己tune的的color scheme,兩個字：好看！黑背景、高對比、關鍵字一目瞭然，用過就回不去！[original page](https://sp18.datastructur.es/materials/lab/lab2setup/lab2setup)

### I/O
#### Writing to Files[https://www.youtube.com/watch?v=Bws9aQuAcdg](https://www.youtube.com/watch?v=Bws9aQuAcdg)
### Version Control

- [Version control](https://www.jetbrains.com/help/idea/version-control-integration.html)
- [Check out a project from a remote host (clone)](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#clone-repo)
- [Push your Project to Github directly](https://youtu.be/Zx74laLnFvw)
1. VCS | Enable Version Control Integration
2. VCS | Import into Version Control | Create Git Repository
3. Add files to the local repository: 做這一步之後所有檔案的顏色會從紅色變成綠色、從unresolved files改成default changelist
4. VCS | Import into Version Control | Share Project on Github
- [Exclude files from version control (ignore)](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#ignore-files)

### [All we need to know about git](https://www.jetbrains.com/help/idea/using-git-integration.html)
1. [如何在IDE中與github repo協作](https://youtu.be/lyiBnyPPnG4)
	- FETCH: 把remote commit file抓到local但不改變local <- 不想要被蓋掉選這個！
	- PULL: FETCH + auto MERGE + auto COMMIT to local <- 無腦拿remote蓋掉全部，如果local有改動就很危險
	- UPDATE PROJECTS: FETCH from all remote branches + MERGE + COMMIT to local
2. 



# GitHub
- [Coursera: Introduction to Git and GitHub by Google](https://www.coursera.org/learn/introduction-git-github/home/welcome)
- [Git Official Documentation](https://git-scm.com/book/en/v2): 講得很完整！
- [Git/Github操作手册](https://zhuanlan.zhihu.com/p/58547172)

# Python
## Reference
- [Fluent Python](https://drive.google.com/file/d/1AV59fwciY2RwgEN11vs5V9_G_mJhyy6e/view?usp=sharing) 
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): 非常實用的入門書，把python data science最重要的numpy, matplotlib都介紹一遍, 基本function就不需要一直去查overstack查的很心累
- [w3schools](https://www.w3schools.com/python/default.asp): 網站把所有常用的python syntax都列入，每次忘記直接來查

##  numpy
### 從文字檔load進數值到numpy array numpy.loadtxt

```markdown
np_array = np.loadtxt(f, comments='#', skiprows=1)
```

### numpy.ndarray.tostring
一個點 <class 'numpy.float64'> 用formatter
ndarray 必須改用 ndarray.tostring
不能用tostring(ndarry[0])

```markdown
# correct
str_single_point = 'mean_x= ' + '{:.2f}'.format(mean[0])
print(str_single_point)

# correct
str_array = np.ndarray.tostring(mean, precision=3)

# error
str_array = np.ndarray.tostring(mean[0], precision=3)
```

### 解線性代數 [numpy.linalg.solve](https://docs.scipy.org/doc/numpy/reference/generated/numpy.linalg.solve.html)

```markdown
numpy.linalg.solve
```

# 刷題 

## [高頻一百連結](https://leetcode.com/problemset/top-interview-questions/)

## 紀錄

Sun|Mon|Tue|Wed|Thu|Fri|Sat  
---|---|---|---|---|---|---
5.3|5.4|5.5|5.6|5.7|5.8|5.9
11  |11  |12(+1) |-  |13(+1)  |14(+1)  |-
5.10|5.11|5.12|5.13|5.14|5.15|5.16
14  |16(+2)|- |17(+1)|-|-|-
5.17|5.18|5.19|5.20|5.21|5.22|5.23
-|-|-|18(+1)|-|-|
5.24|5.25|5.26|5.27|5.28|5.29|5.30
-|19(+1)|-|-|-|-|


Nr.|1st|2nd|3rd
---|---|---|---
1| v | - | - 
2| v | - | - 
8| v | - | - 
4| v | - | -
124| v | - | - 
380| v | - | - 
383| v | - | - 
384| v | - | - 
454| v | - | -

## Frequent-Used Library

Object cloning means to create an exact copy of the original object.

```markdown
 clone()
```

### Array
```markdown
// return a copy array
Arrays.copyOf(original, original.length);

// Copies the specified array, truncating or padding with zeros (if necessary) so the copy has the specified length.
Arrays.copyOf(int[] original, int newLength);

// fill the array with designated value
Arrays.fill(array, value);
```
### [Random](https://docs.oracle.com/javase/8/docs/api/java/util/Random.html)

```markdown
//nextInt(int bound), from 0 to bound - 1
int rand = Random.nexInt(maxNum + 1); // from 0 to maxNum
```

### Iterator

```markdown
Iterator.hasNext();

Iterator.next();
```

### [HashMap](https://docs.oracle.com/javase/8/docs/api/java/util/HashMap.html)
```markdown
HashMap.replace(K key, V value);

HashMap.put(K key, V value);

<V> = HashMap.get(K key);

<V> = HashMap.getOrDefault(K key, V value);

Set<K> = HashMap.keySet();

```

### [Character](https://docs.oracle.com/javase/7/docs/api/java/lang/Character.html)
```markdown
Character.isDigit(char ch);
Character.isLetter(cahr ch);
Character.isSpaceChar(char ch);

```
### [Integer](https://docs.oracle.com/javase/7/docs/api/java/lang/Integer.html)
**Parse String to Integer**
``` markdown
int i = Integer.parseInt(myString);
```

### [String]()
[Convert float to String](https://www.javatpoint.com/java-float-to-string)
```
String.valueOf()

float f=12.3F;//F is the suffix for float  
String s=String.valueOf(f);  
```

### Math
```
int ran = Math.random();


```

### LinkedList



## Problems

### TODO
- 8. String to Integer (atoi)

### 1. Two Sum

最優解法是用HashMap記錄餘數與index, 很巧妙
```
for (int i = 0; i < nums.length;i++) {
    if (map.containsKey(nums[i])){
        res[0] = map.get(nums[i]);
        res[1] = i; break;
    } else {
        map.put((target - nums[i]),i);
    }
}
```
### 2. Add Two Numbers
corner case: 考慮最高位進位問題
最優解法

### 8. String to Integer (atoi)
看似簡單直觀，但有很多corner case, 然後對API也要很熟悉，光在tactical debug就超過一小時...
最優解法：


### 15. 3Sum  (Medium)

### 46. Permutation (Medium)
[三種解法in java](https://blog.csdn.net/happyaaaaaaaaaaa/article/details/51534048)
類型：backtrack（回溯法)
【思路-Java、Python】回溯算法|递归实现[解法說明](http://www.noteanddata.com/leetcode-46-Permutations-java-solution-note.html)
【思路2-Java】回溯算法|递归实现
【思路3-Java】非递归实现


### 124. Binary Tree Maximum Path Sum (Hard)
[java解答](https://www.geeksforgeeks.org/find-maximum-path-sum-in-a-binary-tree/)
這題tricky的地方是，helper function要回報只能選一個child，但如果是max sum update就可以考慮both children

```
class Solution {
    
    public int maxPathSum(TreeNode root) {

        MaxValNode maxValNode = new MaxValNode(Integer.MIN_VALUE);
        pathSumRecursive(root, maxValNode);
        
        # don't use return pathSumRecursive(root, maxValNode);
        # because this means we want root to return its selection!
        return maxValNode.maxVal;
    }
    
    public class MaxValNode {
        private int maxVal;
        
        public MaxValNode(int val) {
            this.maxVal = val;
        }
    }
    
    private int pathSumRecursive(TreeNode node, MaxValNode maxValNode) {
        if (node == null) {
            return 0;
        }
        
        int leftMax = Math.max(pathSumRecursive(node.left, maxValNode), 0);
        int rightMax  = Math.max(pathSumRecursive(node.right, maxValNode), 0);
        int sum = node.val + leftMax + rightMax;
        maxValNode.maxVal = Math.max(maxValNode.maxVal , sum);
        return node.val + Math.max(leftMax, rightMax);
    }
}
```

### 380. Insert Delete GetRandom O(1)
[花花醬解法](https://www.youtube.com/watch?v=y240Qh9H9uk)
HashMap to store array index + array for index output

### 383 Ransom Note (Easy)
 
要快的話就用array lookup, 不要用hashMap
```
public class Solution {
    public boolean canConstruct(String ransomNote, String magazine) {
        if(ransomNote.length() > magazine.length())
            return false;
        int []chars= new int[26];
        for(int i=0; i< magazine.length(); i++){
            chars[magazine.charAt(i)- 'a']++;
        }
        for(int i=0; i< ransomNote.length(); i++){
            chars[ransomNote.charAt(i)- 'a']--;
            if(chars[ransomNote.charAt(i)- 'a'] < 0){
                return false;
            }
        }
        return true;
    }
}
————————————————
版权声明：本文为CSDN博主「负雪明烛」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/fuxuemingzhu/java/article/details/54178342
```
### 384. Shuffle an Array (Medium)
[解法參考](https://leetcode.jp/leetcode-384-shuffle-an-array-%E8%A7%A3%E9%A2%98%E6%80%9D%E8%B7%AF%E5%88%86%E6%9E%90/)

### 454. 4Sum II (Medium)
用hashMap的觀念沒錯，我的方法太搞剛，還考慮把AB為零的先挑出來，再組一次array
[花花將快速解](https://zxi.mytechroad.com/blog/hashtable/leetcode-454-4sum-ii/)
```
    public int fourSumCount(int[] A, int[] B, int[] C, int[] D) {
        
        //TODO: how to declare a array of object
        HashMap<Integer, Integer> mapA, mapB, mapC, mapD, mapABnonZero, mapCDnonZero;
        mapABnonZero = new HashMap();
        mapCDnonZero = new HashMap();
        
        mapA = constructHashMap(A);
        mapB = constructHashMap(B);
        mapC = constructHashMap(C);
        mapD = constructHashMap(D);
        
        int solABCounts = twoSumCount(mapA, mapB, mapABnonZero);
        int solCDCounts = twoSumCount(mapC, mapD, mapCDnonZero);
        int solABCDCounts = twoSumCount(mapABnonZero, mapCDnonZero, mapA);
        int finalSol = solABCounts*solCDCounts + solABCDCounts;
        
        return finalSol;
```

### 476.	Number Complement (Easy)   
記住Java還是support shift >>


# Android Development
## Reference
### 谷歌官方教程
- 官方網站: [Android Developer Fundamentals](https://developer.android.com/courses/fundamentals-training/toc-v2)
- 影片:[Android Developer Fundamentals on Youtube](https://www.youtube.com/playlist?list=PLlyCyjh2pUe9wv-hU4my-Nen_SvXIzxGB):谷歌官方教程，有些api版本比較舊，需要多注意。
- [課程投影片](https://drive.google.com/open?id=1eu-LXxiHocSktGYpG04PfE9Xmr_pBY5P)
- 代碼: [colab source code] (https://developer.android.com/courses/fundamentals-training/toc-v2)
- gitbook: [Android Developer Fundamentals (Version 2) — Concepts](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/)

書籍：

視頻：
- [Android开发教程（2019最新版,使用JetPack](https://www.bilibili.com/video/BV1w4411t7UQ/)：操作跟講解都很清楚
- [Android开发书籍推荐：从入门到精通系列学习路线书籍介绍](https://zhuanlan.zhihu.com/p/25843565)
- [Adroid Studio User Guide](https://developer.android.com/studio/intro)
課程：



-[回调函数（callback）是什么？](https://www.zhihu.com/question/19801131/answer/26586203): 舉例的深入簡出

[How to delete a module in Android Studio](https://mranderson.nl/2019/06/08/how-to-delete-a-module-in-android-studio/)
1. Right click on the Project and select “Open module settings”
2. Select the module you want to delete and press the minus button above.

[https://zhuanlan.zhihu.com/p/25843565](https://zhuanlan.zhihu.com/p/25843565)

## Issue
[TextView and Button get stuck in the top-left corner of the blueprint in android studio](https://stackoverflow.com/questions/51056109/textview-and-button-get-stuck-in-the-top-left-corner-of-the-blueprint-in-android/51058177)

在Component Tree點選view convert 成[constraint layout](https://developer.android.com/training/constraint-layout#convert)


# Markdown Quick Lookup

[slackedit](https://stackedit.io/)

https://jekyll-themes.com/docsy-jekyll/

[Just The Docs Jekyll theme](https://jekyllthemes.io/theme/documentation)

You can use the [editor on GitHub](https://github.com/kuangyu0801/kuangyu0801.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column



```markdown
Syntax highlighted code block

- [Heading](#heading)
  * [Sub-heading](#sub-heading)
    + [Sub-sub-heading](#sub-sub-heading)
- [Heading](#heading-1)
  * [Sub-heading](#sub-heading-1)
    + [Sub-sub-heading](#sub-sub-heading-1)
- [Heading](#heading-2)
  * [Sub-heading](#sub-heading-2)
    + [Sub-sub-heading](#sub-sub-heading-2)

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kuangyu0801/kuangyu0801.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzMDMzMjEyNCwxNzAzNDEyOTEyLDQ1MT
Y4ODc4NSwxNjkwNTA0MjUsMTI0MzkxNDQzNCwtNzQ4NTM1NTY1
LDk1MDA5NDkxOCwtMzQwOTUxODQ2LC0xMTE4MTk1ODEyLC00Nz
U2NjMyNzEsLTk2NTY4MDE4OSwtMTU0MTkyMTEyLC0xMzExOTc4
MzI0LC0xNTE0OTIyNTY2LDY3NTc1MjUxMiwtMTgzNTYyMzAsLT
EzOTgwNDUzNTYsLTEzMjYyMjg2NDksLTE1ODU4MzMxMzQsLTEw
OTU4ODA2MDVdfQ==
-->