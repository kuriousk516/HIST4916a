```python
$ mkdir wget-activehistory
```


      File "<ipython-input-1-d8a3f361290a>", line 1
        $ mkdir wget-activehistory
        ^
    SyntaxError: invalid syntax
    



```python
mkdir wget-activehistory
```


```python
cd wget-activehistory
```

    C:\Users\jenny\HIST4916a\wget-activehistory
    


```python
wget http://activehistory.ca/papers/
```


      File "<ipython-input-4-8173d4a2e53b>", line 1
        wget http://activehistory.ca/papers/
             ^
    SyntaxError: invalid syntax
    



```python
$ wget http://activehistory.ca/papers
```


      File "<ipython-input-5-847d16611588>", line 1
        $ wget http://activehistory.ca/papers
        ^
    SyntaxError: invalid syntax
    



```python
wget "http://activehistory.ca/papers"
```


      File "<ipython-input-6-f65ee55f0c6f>", line 1
        wget "http://activehistory.ca/papers"
             ^
    SyntaxError: invalid syntax
    



```python
wget https://activehistory.ca/papers
```


      File "<ipython-input-7-b2ebca4d8330>", line 1
        wget https://activehistory.ca/papers
             ^
    SyntaxError: invalid syntax
    



```python
wget -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers/
```


      File "<ipython-input-8-fdb460e3e4e9>", line 1
        wget -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers/
                       ^
    SyntaxError: invalid syntax
    



```python
$ wget http://activehistory.ca/papers/
```


      File "<ipython-input-9-e568fe7df582>", line 1
        $ wget http://activehistory.ca/papers/
        ^
    SyntaxError: invalid syntax
    



```python
$ wget -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers
```


      File "<ipython-input-10-f992a845b538>", line 1
        $ wget -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers
        ^
    SyntaxError: invalid syntax
    



```python
!wget http://activehistory.ca/papers
```

    --2021-04-08 10:31:53--  http://activehistory.ca/papers
    Resolving activehistory.ca (activehistory.ca)... 142.93.149.250
    Connecting to activehistory.ca (activehistory.ca)|142.93.149.250|:80... connected.
    HTTP request sent, awaiting response... 301 Moved Permanently
    Location: http://activehistory.ca/papers/ [following]
    --2021-04-08 10:31:54--  http://activehistory.ca/papers/
    Reusing existing connection to activehistory.ca:80.
    HTTP request sent, awaiting response... 200 OK
    Length: unspecified [text/html]
    Saving to: 'papers'
    
         0K .......... .......... .......... .......... ........    972K=0.05s
    
    2021-04-08 10:31:54 (972 KB/s) - 'papers' saved [50093]
    
    


```python
!wget -r -np -w 2 --limit-rate=20k http://activehistory.ca/papers
```


```python
# okay, so it worked. Huzzah! But now how do I do anything with the data?
```


```python
!wget -i urls.text -r --no-parent -nd -w 2 --limit-rate-100k
```


```python

```
