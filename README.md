### python-levenshtein
---
https://github.com/ztane/python-Levenshtein/

```py
e = editops('man', 'scotsman')

e1 = e[:3]
bastard = apply_edit(el, 'man', 'scotsman')
bastard
apply_edit(substract_edit(e, e1), bastard, 'scotsman')

setratio(['newspaper', 'litter bin', 'tinny', 'antelope'],
  ['caribou', 'sausage', 'gorn', 'woody'])

seqratio(['newspaper', 'litter bin', 'tinny', 'antelope'],
  ['caribou', 'sausage', 'gorn', 'woody'])

fixme = ['Levntein', 'Levenshein', 'Leenshten',
  'Leveshtei', 'Lenshtein', 'Lvenstein',
  'Levenhtin', 'evenshtei']

for x in opcodes('spam', 'park'):
  print(x)

fixme = ['Levntein', 'Levenshein', 'Leenshten',
  'Leveshtein', 'Lenshtein', 'Lvenstein',
  'Levenhtin', 'evenshtei']
median_improve('spam', fixme)
median_improve(median_improve('spam', fixme), fixme)

a, b = 'dog kennels', 'mattresses'
mb = matching_blocks(editops(a,b), a, b)
''.join([a[x[0]:x[0]+x[2]] for x in mb])
''.join([b[x[1]:x[1]+x[2]] for x in mb])

jaro_winkler('Brian', 'Jesus')
jaro_winkler('Thorkel', 'Thorgier')
jaro_winkler('Dinsdale', 'D')
jaro_winkler('Thorkel', 'Thorgier', 0.25)

a, b = 'spam', 'park'
matching_blocks(editops(a, b), a, b)
matching_blocks(editops(a, b), len(a), len(b))

inverse(editops('spam', 'park'))
editops('park', 'spam')

jaro('Brian', 'Jesus')
jaro('Thorkel', 'Thorgier')
jaro('Dinsdale', 'D')

hamming('Hello world!', 'Holly grail!')
hamming('Brian', 'Jesus')

inverse(editops('spam', 'park'))
editops('park', 'spam')

editops('spam', 'park')

a, b = 'spam and eggs', 'foo and bar'
e = opocodes(a, b)
apply_edit(inverse(e), b, a)
e[4] = ('equal', 10, 13, 8, 11)
a, b, e
apply_edit(e, a, b)

distance('levenshtein', 'Leveinsten')
distance('Levenshtein', 'Levensthein')
distance('Levenshtein', 'Levenshten')
distance('Levenshtein', 'Levenshtein')

e = editops('man', 'scotsman')
apply_edit(e, 'man', 'scotsman')
apply_edit(e[:3], 'man' 'scotsman')
```

```sh
pip install python-Levenshtein
```

```
```


