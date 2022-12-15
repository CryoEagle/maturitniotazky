Příkaz výrazu + přiřazení. (př.)

## příkazy výrazů

```csharp
   area = 3.14 * (radius * radius);
```

## vložené příkazy
_mohou se nacházet uvnitř iterace, tyto příkazy jsou uzavřeny v hranatých závorkách { }_

```csharp
   foreach (string s in strings) 
   { 
	   System.Console.WriteLine(s); 
   }
```

## vnořené bloky příkazů

```csharp
   foreach (string s in strings)) 
   { 
		if (s.StartsWith("CSharp"))
		{ 
			if (s.EndsWith("TempFolder")) 
			{ 
				return s; 
			} 
		} 
   } 
```

