---
description: Ilhomjon Bekmirzayev
---

# Foreach sikl operatori

Assalomu aleykum bo‘lajak dasturchilar hozir sizlar bilan **foreach** sikli bilan tanishib chiqamiz. **foreach** siklining **for**, **while**, **do while** sikllaridan asosiy farqi **foreach** sikliga shart berilmaydi. Foreach sikli asosan massivlar va kolleksiya qiymatlari bilan ishlashni osonlashtirish uchun mo‘ljallangan bo‘lib, bunda massivning har bir elementiga undagi elementlar sonini bilmagan holda barcha elementlariga murojaat qilish imkonini beradi.

**foreach** blok sxemasi quydagicha:

![](../../../.gitbook/assets/photo_2021-05-24_10-30-05.jpg)

```csharp
// Sintaksisi quyidagicha
foreach (var item in collection)
{
    // body
}

// O'zimizning tilda :)
foreach(<o`zgaruvchi turi> <o`zgaruvchi nomi> in <massiv nomi>)
{
    //Sikl tanasi
}
```



Ko'p gapirgandan ko'ra soddaroq misolda ko'rsak :\)\)\)



```csharp
class Program
{
    static void Main(string[] args)
    {
        string[] mevalar = { "olma", "nok", "uzum", "shaftoli", "o`rik"};
        
        foreach (string meva in mevalar)
        {
            Console.WriteLine(meva);
        }
    }
}
```



Keyn esa foreach sikli string turidagi meva o’zgaruvchisiga mevalar massividagi elementlarini bitta-bitta olib uzatadi va har bir meva o’zgaruvchisini qiymatini ekranga chiqaramiz.
