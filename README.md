# Ejercicios-Linux
Ejercicios de Linux

## Ejercicio1
-Show all the jpg pictures in the current directory.


```console
ls *.jpg
```

## Ejercicio2
-Display all the files in the directory /usr/bin starting with letter “j”.


```console
ls /usr/bin/j*
```

## Ejericio3
-Show all the files in the directory /usr/bin starting with the letter “k”, with an “a”
in the 3 rd place.

```console
ls /usr/bin/k?a*
```

## Ejercicio4
-Show all the files in the directory /bin ending with “n”.


```console
ls /bin/*n
```

## Ejercicio5
-Display all the files in the directory /etc and all the files in every subdirectory
recursively.

```console
ls -R /etc/
```

## Ejercicio6
-In your home directory, create another directory named test. Copy the file gzip from
the directory /bin to test. Create a duplicate of gzip named gzip2 inside test.

```console
mkdir test
```
```console
cp /bin/gzip test
```


## Ejercicio7
-Change the name of the directory test to test2. Create test3 at the same level in
the directory tree as test2 and move all the files from test2 to test3. Delete test2.


```console
mv test/ test2/
```

```console
mkdir test3/
mv test2/* test3/
```

```console
rmdir test2/
```




