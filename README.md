[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/gaQlcHTs)
# aw3-template

simapi projesindeki Category ve Product modelleri 1-M relation olacak sekilde yeniden modelleyiniz.
Iki model icin iligli controllerlari yeniden duzenleyiniz. 
Iki modeli iceren bir migration dosyasi hazirlayip ekleyiniz. 
odev icersinde sadece 2 modeli gonderiniz. 


# SİMPRA_HOMEWORK3

## Projeyi çalıştırmak için:
1. SimpraHomewroks.Apı -> appsettings.json -> MsSQL tanımlamasındaki ‘Server’ bilgisini kendiMsSQL server adı ile değiştiriniz. 
2. Package Manager Console -> Default Project -> SimpraHomework.Repository seçilir. 
3. Add-migration v1.1 veya EntityFramework6\Add-Migration initial komutu girilerek migration oluşturulur. 
4. Update-database komutu ile MsSQL’de ‘SimraHomework3Db’ ve tablolar oluşturulur.

![alt text](https://i.ibb.co/GFZ3N13/Connection.png)

## Proje detay ve içerikleri: 
1. Projenin Database’i  MsSQL kullanılılarak geliştirildi.
2. Projenin backend’i ‘Web API’ projesi olup, NLayer Architecture yapısına uygun olarak dizayn edildi.



3. RESTAPI PRINCIPLES VE CRUD Operations kullanıldı. 
   Category Controller:
   
![alt text](https://i.ibb.co/CwT6WgV/Catgory-Controller.jpg)
   
   Product Controller:
   
![alt text](https://i.ibb.co/Yd3dHbN/Product-Controller.jpg)
   
4. Generic Repository Design Pattern ve Unit of Work Design Pattern uygulandı.
5. Fluent  Validation ve AutoMapper kullanıldı.
6. CustomResponse ve Middleware kullanıldı.
7. SOLID Prensipleri.
8. Include ile Category'si aynı olan Productlar listelendi 
9. Include ile Productlar categoryleri ile listelendi ve 2 tane Where sorgusu kullanıldı.
    

    
        
## Kullanılan Teknolojiler: 
1. IDE : Visual Studio 2022 
2. DB: MsSQL Languages: C#, 
3. Frameworks: .NET 6, ASP.NetCore, EntityFramework6, EFCore/SqlServer/, DependencyInjection Abstractions 
  
