### Java中實現日期向後加一天

****

在new Date()后增加一天，即往后延一天

```
import java.util.Date;

Date current = new Date();
Calendar calendar = new GregorianCalendar();
calendar.setTime(current);
calendar.add(calendar.DATE, 1);
current = calendar.getTime();
```

****

.
