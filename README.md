# CorsairCommanderProControl for Mac
Temporary readme with notes for myself.  
  
Do:  
compile for mac   
create patch script  

```
mount -uw /
cd /usr/libexec
mv ioupsd ioupsd.ORIG

#!/bin/sh
controller
while sleep 999999999; do :; done
```

