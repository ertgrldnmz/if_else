 ## Karar Yapıları
```csharp
//DateTime ile saati öğrenip time değişkenine atadık
int time =DateTime.Now.Hour;
 //ilk if kullanımı karmaşık yapılarda
 if(time>=6 && time<11)
 {
Console.WriteLine("Günaydın");
}
 else if(time<=18)
{
      Console.WriteLine("iyi Günler");
 }
    else
{
     Console.WriteLine("iyi geceler");
 }
//ikinci if kullanımı tek satırlık koşulu ifadelerde
string sonuc = time<=18 ? "iyi günler": "iyi geceler";
sonuc=time>=6 && time<=11 ? "günaydın": time<=18 ?"iyi günler": "iyi geceler"; 
 Console.WriteLine(sonuc);
 ```
