# How to Use Laravel Query Builder
介紹 Laravel Query Builder 常用功能

### 單獨查一行

- 單獨查一列
```php
$user = DB::table('users')->where('name', 'John')->first();

return $user->email;
```

- 單獨查一個欄位
```php
$email = DB::table('users')->where('name', 'John')->value('email');
```
