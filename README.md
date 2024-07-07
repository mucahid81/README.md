# README.md
```csharp
string name = "Mücahid Taha";
string surname = "ÇİLLİ";
string location = "Düzce / Kaynaşlı, Türkiye";
string profession = "Yazılım Geliştiricisi";
string[] skills = { "Web Uygulamaları", "Unity 2D ve 3D Oyun Geliştirme", "Electron.js ile Multiplatform Masaüstü Uygulamaları", "C# Masaüstü Uygulama Geliştirme" };
string[] projects = { 
    "Teknofest 2023 Eğitim Teknolojileri Türkiye 8.si", 
    "Teknofest 2023 Engelsiz Yaşam Teknolojileri Türkiye 11.si", 
    "MagaraJam2023 Top 50 Oyunu (Cybo)", 
    "Win Detective - Windows Gelişmiş Arama Çubuğu Uygulaması"
};
string[] hobbies = { "PC oyunları oynamak", "sohbet etmek", "program yazmak" };
string email = "mtahacilli8118@gmail.com";

Console.WriteLine("Merhaba! Ben " + name + " " + surname + ". " + location + "'dan bir " + profession + "yim.");
Console.WriteLine("Yeteneklerim: " + string.Join(", ", skills) + ".");
Console.WriteLine("Projelerim: " + string.Join(", ", projects) + ".");
Console.WriteLine("Hobilerim: " + string.Join(", ", hobbies) + ".");
Console.WriteLine("E-posta ile bana ulaşabilirsiniz: " + email + ".");
