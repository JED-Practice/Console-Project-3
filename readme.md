# Bolt Food clone

## Proyektin adı: Bolt Food klonu

## Açıqlama:

Restoranların məhsullarınnı idarə etməsi üçün olan sistemdir. Proyekti yazarkən repository pattern və N-tier arxitektura istifadə edilməlidir. Databaza kimi də MsSql tərcih edilsə əla olar.

## Əsas özəllikləri:


### Pattern dizayn üçün:
  - BoltFood.App
    > bu hissədə yalnız program.cs file daxilində MenuService işlətməlisiniz hansı ki, bu da BoltFood.Serives-dən gəlməlidir.
  - BoltFood.Core
    > Bu hissədə sizin Models və Enums folderləriniz olacaq.
  - BoltFood.Data
    > Bu hissədə sizin da yalnız database hissəsi olan olan məsələləriniz həll olunmalıdır.
  - BoltFood.Services
    > Bu hissədə sizin Services folderiniz olacaq hansı ki, metodlarınızın yoxlamaları burda olmalıdır.


### Restoran üçün:


- **Yeni restoran əlavə etmək:**
  >Bu bölmədə `CreateRestaurant()` adlı metod yazılmalıdır hansı ki yeni yaradılacaq restoranın məlumatlarını alır və databazaya əlavə edir.
- **Restoranların siyahısına baxmaq:**
  > Bu bölmədə `GetAll()` adlı metod yazılmalıdır hansı ki databazada olan bütün restoranları ekrana çap edir.
- **Restorana id-ə əsasən baxmaq:**
  > Bu bölmədə `GetById()` adlı metod yazılmalıdır hansı ki databazada olan verilən id-də olan restoranı ekrana çap edir.
- **Restoranı update etmək:**
  > Bu bölmədə `Update()` adlı metod yazılmalıdır hansı ki databazada olan  restoranı update edir.    
- **Restoranı remove etmək:**
  > Bu bölmədə `Remove()` adlı metod yazılmalıdır hansı ki databazada olan seçilmiş restoranı silir.      


### Product üçün:


- **Yeni product əlavə etmək:**
  > Bu bölmədə `CreateProduct()` adlı metod yazılmalıdır hansı ki, databazada olan restoranı seçib ora həmən productı əlavə etmək lazımdır.
- **Productların siyahısına baxmaq:**
  > Bu bölmədə `GetAll()` adlı metod yazılmalıdır hansı ki databazada olan bütün productları və onalrın hansı restorana aid olmasını  ekrana çap edir.
- **Product-a id-ə əsasən baxmaq:**
  > Bu bölmədə `GetById()` adlı metod yazılmalıdır hansı ki databazada olan həmən id-də olan productı ekrana çap edir.
- **Productı update etmək:**
  > Bu bölmədə `Update()` adlı metod yazılmalıdır hansı ki databazada olan  productı update edir.    
- **Productı remove etmək:**
  > Bu bölmədə `Remove()` adlı metod yazılmalıdır hansı ki databazada olan seçilmiş productı silir.      
