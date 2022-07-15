     1.Soru

```
Console.WriteLine("Kaç adet sayı gireceksiniz : "); 
int n = Convert.ToInt32(Console.ReadLine());  
List<int> ciftSayiListesi=new List<int>();   

for(int i=0; i < n; i++)
{ 
    int sayi = Convert.ToInt32(Console.ReadLine()); 
    if (sayi % 2 == 0)
    {
        ciftSayiListesi.Add(sayi);
    }
}

foreach(var sayi in ciftSayiListesi)
{
    Console.Write(sayi+" ");
} 
```
***
                   
                   
      2.Soru
```
Console.WriteLine("Pozitif 2 adet sayı giriniz : ");
int n = Convert.ToInt32(Console.ReadLine());
int m = Convert.ToInt32(Console.ReadLine());
List<int> tamBolenLisesi=new List<int>();  

for(int i=0; i < n+1; i++)
{
    
    if (i!=0)
    {
        int yeniBirSayi = Convert.ToInt32(Console.ReadLine());
        if (m % yeniBirSayi == 0)
        {
            tamBolenLisesi.Add(yeniBirSayi);
        }

    }
   
}
Console.Write("Girdiğiniz Sayının katları : ");
foreach (var sayi in tamBolenLisesi)
{
    Console.Write(sayi + " ");
}

```
***





      3.Soru
```
Console.WriteLine("Pozitif bir sayı giriniz : ");
int n = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Girdiğiniz sayı kadar kelime giriniz : ");
string metin = Console.ReadLine();
string[] yeniMetin = metin.Split(' ');



for(int i=n-1; i >= 0; i--)
{
    Console.Write(yeniMetin[i]+" "); 
}
```
***

        4.Soru
```
Console.Write("Bir Cümle Yazınız : ");
string metin = Console.ReadLine();
string[] kelimeler = metin.Split(' ');
int harfSayar = 0;
int kelimeSayar = 0;

for (int i = kelimeler.Length - 1; i >= 0; i--)
{
    kelimeSayar++;

}

for(int i = 0; i < metin.Length; i++)
{
    if (metin[i]==' ') { continue; }
    else
    {
        harfSayar++;
    }
}

Console.WriteLine("Girdiğiniz metinde " + kelimeSayar + " adet kelime ve " + harfSayar + " adet harf bulunmaktadır");

```
***


