# Bu en büyük başlık
## bu ise ortanca

#### burada 4. seviye başlık var 


ardına da neler neler yazık


## şimdi de resim ekliyoruz:

![Atatürk'ün resmi](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Ataturk1930s.jpg/440px-Ataturk1930s.jpg)


## kod örnekleri girelim

```python

nickname = "rumuz" 

```


```java

import java.text.*;
import java.util.*;
import java.util.Date;
 
public class DateExample {
 
   public static void main(String args[]) {
 
     // Get the Date
     Date now = new Date();
 
     // Get date formatters for default, German, and French locales
     DateFormat theDate = DateFormat.getDateInstance(DateFormat.LONG);
     DateFormat germanDate = DateFormat.getDateInstance(DateFormat.LONG, Locale.GERMANY);
     DateFormat frenchDate = DateFormat.getDateInstance(DateFormat.LONG, Locale.FRANCE);
 
     // Format and print the dates
     System.out.println("Date in the default locale: " + theDate.format(now));
     System.out.println("Date in the German locale : " + germanDate.format(now));
     System.out.println("Date in the French locale : " + frenchDate.format(now));  
   } 
}

```


şimdi de liste hazırlıyoruz:

- [x] çalışmada 4. seviyeye geldim
- [ ] diğer seviyeler duruyor
