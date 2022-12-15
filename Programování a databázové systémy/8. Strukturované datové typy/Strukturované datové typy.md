zpět na [[Programování a databázové systémy]]

Například: 
- enumerátory => **_výčty_**
- strukturovaný typ => **_struct_**

Funkce enumerátoru se dají docela snadno přetížit a **rozšířit**, například konvertování (například vytažení stringů).

```Csharp
public enum MyEnum 
{ 
	[Description("value 1")] 
	Value1, 
	[Description("value 2")] 
	Value2, 
	[Description("value 3")] 
	Value3 
}
```

**_Nahoře je uveden příklad pomocí description tagu_**.
