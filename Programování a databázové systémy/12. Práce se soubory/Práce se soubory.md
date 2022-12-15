zpět na [[Programování a databázové systémy]]

## příklad uložení textu

použijeme **_System.IO_**.

Takto soubor vytvoříme:
```csharp
using (StreamWriter sw = new StreamWriter(@"soubor.txt"))  
{

}
```

psaní do souboru:
```csharp
using (StreamWriter sw = new StreamWriter(@"soubor.txt"))  
{
	sw.WriteLine("První řádek");  
	sw.WriteLine("Tento text je na druhém řádku");  
	sw.Flush();
}
```

pokud druhý parametr bude **_true_**, zapneme appende textu do souboru
```csharp
using (StreamWriter sw = new StreamWriter(@"soubor.txt", true))  
{
	sw.WriteLine("První řádek");  
	sw.WriteLine("Tento text je na druhém řádku");  
	sw.Flush();
}
```

kód pro výpis textu ze souboru:
```csharp
using (StreamReader sr = new StreamReader(@"soubor.txt", true))  
{
	string s;
	while((s = sr.ReadLine()) != null)
	{
		Console.WriteLine(s);
	}
}
```

další možnost čtení ze souboru:
```csharp
string[] radky = File.ReadAllLines("@soubor.txt");
foreach (string radka in radky) 
{
	Console.WriteLine(radka);
}
```