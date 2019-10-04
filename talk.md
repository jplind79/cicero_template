class: center, middle

# Hur klimatmodeller hjälper oss förstå dagens och framtidens klimat

## Petter Lind

Rossby Centre, SMHI

---
name: inverse

## Rossby Centre

Nyligen 20 år fyllda

- Vad pysslar vi med?
- Varför då?

---

<img src="img/noaa_satellite_visible_5km_180308.png" style="width: 80%;"/>

.cite[NASA Worldview (https://worldview.earthdata.nasa.gov/)]

---
class: middle, center

# Hur känsligt är klimatet?

---
class: top, center

<img src="img/ECS_history.png" style="width: 100%;"/>

---

## Code blocks are no problem

Here we have some Python code:

```python
from itertools import cycle

fizz = cycle(['', '', 'Fizz'])
buzz = cycle(['', '', '', '', 'Buzz'])

for i in range(1, 101):
    print((next(fizz) + next(buzz)) or i)
```

[Source](https://github.com/olemb/nonsense/blob/master/fizzbuzz/itertools_cycle.py)

---

## Images

An image fetched from the web:

![Sample image](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/The_Young_Cicero_Reading.jpg/316px-The_Young_Cicero_Reading.jpg)

---

## Local image
<img src="img/surftemp_ARCTIC24.png" style="width: 60%;"/>

.cite[Lindstedt et. al., Tellus (2015)]

---

## Videos
<video width="400" controls>
  <source src="img/mov_bbb.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

---

## Math equations
`\(E = mc^2\)`
`$$ \Gamma(t) = \pi \, \Im\left\{ \mathbf{x}_+^H(t) \, \frac{\mathrm{d}}{\mathrm{d} t}\mathbf{x}_+(t) \right\} $$`

---

## Unravel text

- figure 1

---

count: false
## Unravel text

- figure 1
- figure 2

---

count: false
## Unravel text

- figure 1
- figure 2
- figure 3

---

## Unravel text (better way, not solved)
use countIncrementalSlides see

https://github.com/gnab/remark/wiki/Markdown#count

- figure 1

--
- figure 2

--
- figure 3

---

## Slide notes

- Press P, to get presentation mode and see if you have any notes..

???
This is my notes and only visible to me..
