# get-datetime

get_datetime is a Python 3 Package, that returns you a time int or str.

# Install

Via pypi:
```
$ pip install get-datetime
```

Manuel:  
[Github Repo](https://github.com/JohannLULW/get_time)

# Documentation
## Info:
Time at the Documentation: 5 June 2021 20:27:14 (8 PM)
<hr>

## get year int:

Code:
```
from get_datetime import *

print(get_date_year())
``` 

Output:
```
$ python main.py
2021
```
<hr>

## get month int:

Code:
```
from get_datetime import *

print(get_date_month())
```

Output:
```
$ python main.py
6
```
<hr>

## get day int:

Code:
```
from get_datetime import *

print(get_date_day())
```

Output:
```
$ python main.py
5
```
<hr>

## get Day and month str:

Code:
```
from get_datetime import *

print(get_date_DM("."))
```

Output:
```
$ python main.py
5.6
```
<hr>

## get Day, Month and Year str:

Code:
```
from get_datetime import *

print(get_date_DMY("."))
```
You can write any string between the brackets.

Output:
```
$ python main.py
5.6.2021
```
<hr>

## get Month, Day and Year str:

Code:
```
from get_datetime import *

print(get_date_DMY("/"))
```
You can write any string between the brackets.

Output:
```
$ python main.py
6/5/2021
```
<hr>

## get hour int:

Code:
```
from get_datetime import *

print(get_time_hour())
```

Output:
```
$ python main.py
20
```
<hr>

## get minute int:

Code:
```
from get_datetime import *

print(get_time_minute())
```

Output:
```
$ python main.py
27
```
<hr>

## get second int:

Code:
```
from get_datetime import *

print(get_time_second())
```

Output:
```
$ python main.py
14
```
<hr>

## get hour and minute str:

Code:
```
from get_datetime import *

print(get_time_HM(":"))
```
You can write any string between the brackets.

Output:
```
$ python main.py
20:27
```
<hr>

## get hour, minute and second str:

Code:
```
from get_datetime import *

print(get_time_HMS(":"))
```
You can write any string between the brackets.

Output:
```
$ python main.py
20:27:14
```
