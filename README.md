# BlazorUtil

多少なりとも工数がかかったものを上げていきます

質問等あればQiitaか kobayashi.50po100po@gmail.com まで

## How To Use

### 依存関係注入

Program.cs または MauiProgram.cs に
```C#
builder.Services.AddScoped<JSInterop>();
```
を追加

これでJSが動かせます(ないと例外出ます)

### Bootstrap

BlazorはデフォルトでBootstrapが適用されているので不要？

```
<link rel="stylesheet" href="lib/bootstrap/css/bootstrap.min.css" />
<script src="lib/bootstrap/js/bootstrap.bundle.min.js"></script>
```

もしなかったら、JSも追加してください  
当然ですが、パスは自分の環境を確認してください