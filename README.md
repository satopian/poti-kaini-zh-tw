# 繪圖板 PHP script POTI-board 改二的中文翻譯version
## 這是POTI-board 改二的繁體中文翻譯version.
This is the traditional Chinese translation version of POTI-board kai ni.  
這是日語顯示的原文.  
[satopian/poti-kaini: お絵かき掲示板PHPスクリプトPOTI-board改二, for PHP7 (PHP5.5～, 7.x, 8.0)](https://github.com/satopian/poti-kaini)  
存儲庫管理員依靠Google翻譯，因為它只懂日語.  
### Overview of required work.
There is a language resource for messages in `template_ini.php`, such as error messages and messages used when images are uploaded successfully.
The HTML of the template uses Japanese, so you need to translate it.
we also need to translate the external programs `search.php` and `search.html` for search.  
However, potiboard.php externalizes all language settings, so no changes are needed.  
Translation of `config.php` requires translation of the descriptive text for the end user to set.    

### [2021/04/29]  
- I translated `config.php` except for the detailed settings. I took care not to change the meaning, but I need to replace it with an appropriate translation.   
- Advanced settings are not translated.

### [2021/04/28]  
開始翻譯. 
Translated the const in template_ini.php.  
Some translations remain in English or Japanese.  
This is because the translation of that part did not go well.  
I would like help from those who understand Chinese.  
- template_ini.php 
- I translated template_ini.php.  
This is an incomplete translation.  
Please pull request and fix this.  

