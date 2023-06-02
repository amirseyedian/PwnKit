# PwnKit

Self-contained exploit for CVE-2021-4034 - Pkexec Local Privilege Escalation


### Build

```bash
gcc -shared PwnKit.c -o PwnKit -Wl,-e,entry -fPIC
```

