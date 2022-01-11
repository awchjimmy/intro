# PHP Letter
一封信寫給自己關於 PHP 的信

### 為什麼？
PHP 已經有超過 25 年歷史，照理說應該是資源最豐富、整理最完整的語言體系，然而事實並非如此；常常這樣也可以、那樣也可以，造成許多混亂，於是寫這封信，紀錄還在作 PHP 工程師時的點點滴滴。

### 推薦閱讀
* [PHP The Right Way](https://phptherightway.com/)
> There’s a lot of outdated information on the Web that leads new PHP users astray, propagating bad practices and insecure code. PHP: The Right Way is an easy-to-read, quick reference for PHP popular coding standards, links to authoritative tutorials around the Web and what the contributors consider to be best practices at the present time.

### 在這裡暫停一下
等等，你點進去推薦閱讀了嗎？先至少知道有這個東西再往下閱讀。

### 語言
`PHP 7.4` 已經進入維護階段，只有資安漏洞才會進行修復；如果情況允許，請用 `PHP 8.x` 開始新專案。

### 套件管理器
在古早時期寫程式，網路上找可以用的 Library ，能用不能用不知道，下載下來放哪也沒有統一規範，有時候不能使用或是沒有再用到了，也不會記得把他刪除。

關於套件管理的好處，請花時間上網作功課，舉例說明如下：
  1. 統一紀錄所有套件版本。
  2. 套件跟套件之間可能會有相依性或排斥性，有一個統一的紀錄，可以鎖定使用的版本，以減少問題發生。

Composer 是 PHP 最多人使用的套件管理器，花時間學會使用他。

### 第三方套件
* 寄信 - [PHPMailer](https://github.com/PHPMailer/PHPMailer)
* 匯出 Excel - [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet)

### 關聯式資料庫



---

### 外行想了解的 FAQ
- 軟體寫不好的人才去寫網頁？
- PHP 是低薪工作？

  關於薪資高低的因素，跟是不是 PHP 工程師還比較沒有關係，跟以下因素較相關：
  1. 產業，例如金融產業的工程師 vs 傳產的工程師
  2. 職位，有沒有待管理職、有沒有需要責任制、有沒有需要輪班等
- PHP 不正經，C# / Java 才適合寫大型網站？
