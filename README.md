# clock
A simple, customizable, embedable html clock.  
You can customize it via url paramaters.  
*the clock's time is taken from your system time*  

You can add this to your [Notion](https://www.notion.so/) / [obsidian](https://obsidian.md/) by putting this url as an embed / iframe:  
if you stream, you can add it as an OBS browser source.  
```
https://crazykitty357.github.io/clock/
```
## Documentation
```t=12h``` - Sets the clock to a 12 hour format, anything else will make it the default which is a 24 hour format. | [example](https://crazykitty357.github.io/clock/?t=12h) 

```seconds=false``` - hides the seconds, anything else will show the seconds | [example](https://crazykitty357.github.io/clock/?seconds=false)

```font=``` - can be set to a custom font based on [google fonts](https://fonts.google.com) | [example](https://crazykitty357.github.io/clock/?font=Tiny5)

```color=``` - can be set to any hexcode you want, **DON'T ADD THE # IN FRONT OF THE HEXCODE** | [example](https://crazykitty357.github.io/clock/?color=ad540f)

```size=NUMBERpx``` - can change the size of the clock | [example](https://crazykitty357.github.io/clock/?size=50px)

```sysfont=``` - is similar to font except instead of it using google fonts it uses whatever font is installed on your system | [windows example](https://crazykitty357.github.io/clock?sysfont=Comic%20Sans%20MS) [linux example](https://crazykitty357.github.io/clock?sysfont=Noto%20Sans)  
**NOTE**: if combined with ```font=``` sysfont will have priority. 

also all of these can stack | [example](https://crazykitty357.github.io/clock/?t=12h&seconds=false&font=Tiny5&color=ad540f&size=50px)
