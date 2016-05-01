# pomfsecure
Encrypted uploads to any [pomf.se](http://pomf.se) clone!

If ran on a file, it will generate a strong but URL-friendly password, encrypt the file, upload it, and return the URL with the password appended.

If ran on one such password-containing URL, it will download that file and decrypt it, saving to the current directory.


```
$ ./pomfsecure diceware8k.txt

Encrypting diceware8k.txt...
Uploading encrypted file...
Upload attempt #0... Uploaded!
File has been encrypted and uploaded to: http://a.pomf.cat/gslbrg.txt#j6Vp6_BvPtE5xb7dz9ecBj2C-tzc9WyO


$ ./pomfsecure http://a.pomf.cat/gslbrg.txt#j6Vp6_BvPtE5xb7dz9ecBj2C-tzc9WyO

Downloading and decrypting gslbrg.txt...
File saved to: gslbrg.txt
```

## AUR package

maintained by [Johnathan "ShaggyTwoDope" Jehnkins](https://github.com/shaggytwodope)

[https://aur.archlinux.org/packages/1339secure-git/](https://aur.archlinux.org/packages/1339secure-git/)

