using System;

namespace AboutMeNamespace
{
    public class AboutMe
    {
        public string Name { get; } = "Mücahid Taha";
        public string Surname { get; } = "ÇİLLİ";
        public string Location { get; } = "Düzce / Kaynaşlı, Türkiye";
        public string Profession { get; } = "Yazılım Geliştiricisi";
        public string[] Skills { get; } = { 
            "Web Uygulamaları", 
            "Unity 2D ve 3D Oyun Geliştirme", 
            "Electron.js ile Multiplatform Masaüstü Uygulamaları", 
            "C# Masaüstü Uygulama Geliştirme" 
        };
        public string[] Projects { get; } = { 
            "Teknofest 2023 Eğitim Teknolojileri Türkiye 8.si", 
            "Teknofest 2023 Engelsiz Yaşam Teknolojileri Türkiye 11.si", 
            "MagaraJam2023 Top 50 Oyunu (Cybo)", 
            "Win Detective - Windows Gelişmiş Arama Çubuğu Uygulaması" 
        };
        public string[] Hobbies { get; } = { 
            "PC oyunları oynamak", 
            "sohbet etmek", 
            "program yazmak" 
        };
        public string Email { get; } = "mtahacilli8118@gmail.com";

        public void PrintInfo()
        {
            Console.WriteLine($"Merhaba! Ben {Name} {Surname}. {Location}'dan bir {Profession}yim.");
            Console.WriteLine("Yeteneklerim: " + string.Join(", ", Skills) + ".");
            Console.WriteLine("Projelerim: " + string.Join(", ", Projects) + ".");
            Console.WriteLine("Hobilerim: " + string.Join(", ", Hobbies) + ".");
            Console.WriteLine("E-posta ile bana ulaşabilirsiniz: " + Email + ".");
        }
    }
}
