## Welcome to GitHub Pages
[slackedit](https://stackedit.io/)

[Just The Docs Jekyll theme](https://jekyllthemes.io/theme/documentation)

You can use the [editor on GitHub](https://github.com/kuangyu0801/kuangyu0801.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

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

# 刷題
## 連結 
- [高頻一百連結](https://leetcode.com/problemset/top-interview-questions/)
## 紀錄
|Sun  |Mon  |Tue  |Wed  |Thu  |Fri  |Sat  |
|---|---|---|---|---|---|---|
|5.3  |5.4  |5.5  |5.6  |5.7  |5.8  |5.9  |
|11/145  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
## Java Library
**[HashMap](https://docs.oracle.com/javase/8/docs/api/java/util/HashMap.html)**
```markdown
replace(K key, V value)
```
## Problem
### 383. Ransom Note (Easy)
要快的話就用array lookup
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
