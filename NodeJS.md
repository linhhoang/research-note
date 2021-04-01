## Error sh: 1: ng: Permission denied

![image](https://user-images.githubusercontent.com/1127728/113274046-71e7c180-9307-11eb-94d1-66dbd9633730.png)
Solution:
``` Terminal
 chmod 775 app/node_modules/.bin/ng
 chmod 775 app/node_modules/.bin/ng.cmd
```
