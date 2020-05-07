## Welcome to GitHub Pages


- [刷題](#刷題)
  * [紀錄](#紀錄)
  * [Problems](#problems)
  * [Frequent-Used Library](#frequent-used-library)
- [Java](#java)
  * [IntelliJ](#intelliJ)
    + [Sub-sub-heading](#sub-sub-heading)
- [Python](#python)
  * [numpy](#sub-heading-1)
    + [Sub-sub-heading](#sub-sub-heading-1)
- [Android Development](#android-development)
  * [Reference](#reference)
    + [Sub-sub-heading](#sub-sub-heading-2)
- [Markdown Quick Lookup](#markdown-quick-lookup)

# Java
## IntelliJ
- [Josh’s IntelliJ Editor Settings](https://drive.google.com/drive/folders/1Y5cHl-nNe731EgG4pAk2Dokgbu4ZpV5E?usp=sharing):CS61B Josh自己tune的的color scheme,兩個字：好看！黑背景、高對比、關鍵字一目瞭然，用過就回不去！[original page](https://sp18.datastructur.es/materials/lab/lab2setup/lab2setup)

### Version Control

- [Version control](https://www.jetbrains.com/help/idea/version-control-integration.html)
- [Check out a project from a remote host (clone)](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#clone-repo)
- [Push your Project to Github directly](https://youtu.be/Zx74laLnFvw)
- [Exclude files from version control (ignore)](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#ignore-files)

# GitHub


# Python
## Reference
- [Fluent Python](https://drive.google.com/file/d/1AV59fwciY2RwgEN11vs5V9_G_mJhyy6e/view?usp=sharing) 
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): 非常實用的入門書，把python data science最重要的numpy, matplotlib都介紹一遍, 基本function就不需要一直去查overstack查的很心累
- [w3schools](https://www.w3schools.com/python/default.asp): 網站把所有常用的python syntax都列入，每次忘記直接來查

##  numpy
### numpy.loadtxt
```
np_array = np.loadtxt(f, comments='#', skiprows=1)
```
### numpy.ndarray.tostring
一個點 <class 'numpy.float64'> 用formatter
ndarray 必須改用 ndarray.tostring
不能用tostring(ndarry[0])
```
# correct
str_single_point = 'mean_x= ' + '{:.2f}'.format(mean[0])
print(str_single_point)

# correct
str_array = np.ndarray.tostring(mean, precision=3)

# error
str_array = np.ndarray.tostring(mean[0], precision=3)
```
# 刷題 
## 連結 
- [高頻一百連結](https://leetcode.com/problemset/top-interview-questions/)
## 紀錄

Sun|Mon|Tue|Wed|Thu|Fri|Sat  
---|---|---|---|---|---|---
5.3|5.4|5.5|5.6|5.7|5.8|5.9
11  |11  |12(+1) |/145  |/145  |/145  |/145


Nr.|1st|2nd|3rd
---|---|---|---
124| v | - | - 
---|---|---|---

## Frequent-Used Library
**[HashMap](https://docs.oracle.com/javase/8/docs/api/java/util/HashMap.html)**
```markdown
replace(K key, V value)
```
## Problems

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

### 476.	Number Complement (Easy)   
記住Java還是support shift >>


# Android Development
## Reference

- [Android Developer Fundamentals (Version 2) — Concepts](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/)
- [Adroid Studio User Guide](https://developer.android.com/studio/intro)

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
