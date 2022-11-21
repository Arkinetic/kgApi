# kgApi ![1](https://img.shields.io/npms-io/quality-score/o) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/DanPlayz23/kgApi?display_name=release&label=Latest%20Release&logo=github&logoColor=black)
Key Generator API 
-----------------
How to get started
-----------------
Start by importing the api(dll) into your project.
> References/Dependencies > Add reference > Browse > Navigate to the dll > OK
### Make sure to add
```cs
using kgApi;
```
### Next create an instance of keygen:
```cs
keygen kgapi = new keygen();
```
### Write the key: (Works better with Console Application)
```css
Console.WriteLine(kgapi.Generatekey(25,false));
```
###### kgapi.Generatekey(int length, bool useUppercaseLetters);
### You can also use
```css
textBox1.Text = kgapi.Generatekey(25,false);
```
