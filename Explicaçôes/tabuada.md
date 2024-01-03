```python

n = int(input('Digite o número inicial para o conjunto de tabuadas : '));
nDois = int(input('Digite o número final para o conjunto de tabuadas : ')); 
print('');
print('    Tabuada completa :');
print('     Do ',n,' até o ',nDois);
print('');
if (n < nDois) :
   for k in range(n,nDois+1):
    for i in range(0,11):
     calc = n * i;
     print(' ',n,' x ',i,' = ',calc);
    print('');
    n = n + 1;
   print('');
else :
  print('      ❌ Erro Fatal  ');
  print('pois ',n,' e maior do que ',nDois);
  print(' Algoritmo em ordem crescente ');
  print('  E não decrescente ');```python

```

