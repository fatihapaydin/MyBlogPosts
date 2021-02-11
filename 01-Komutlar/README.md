## .Net Core

#### Projeyi solutiona ekle
``` 
dotnet sln add App/App.csproj
``` 

#### Projeyi solutiondan sil
``` 
dotnet sln remove App/App.csproj
``` 

#### Domain adında bir .net core kütüphane projesi oluştur
``` 
dotnet new classlib -o Domain -f netcoreapp3.1
``` 

#### Migration ekle
``` 
dotnet ef migrations add Student_Table_Added
``` 

#### Migrationı veri tabanına uygula
``` 
dotnet ef database update
``` 

#### Veri tabanını sil
``` 
dotnet ef database drop
``` 
## Git

#### Git için kullanıcı adı ve e-posta ayarlamasını yap
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

#### Projenin git originini ayarla
```
git remote add origin https://github.com/yourusername/yourapp.git 
```
#### Kodu git kaynağına gönder
```
git push -u origin --all
```

#### Daha önceden git kaynağına gönderilmiş dosyayı kaynaktan sil
```
git rm -rf --cached .   
git add . 
``` 