## Absolute length units:
 **Absolute units:** `px mm cm q in pc pt`

| Unit | Equivalent in Pixels  | Full Name          |
| ---- | --------------------- | ------------------ |
| `px` | 1in / 96              | pixel              |
| `mm` | 3.7795275590551185 px | millimeter         |
| `cm` | 37.795275591 px       | centimeter         |
| `in` | 96 px                 | inch               |
| `pc` | 16 px                 | pica               |
| `pt` | 1.33333333333333 px   | point              |
| `q`  | 0.944881889775 px     | quarter-millimeter |

---

 **Absolute font size:**
| Keyword    | Approx. px size  |
|------------|------------------|
| `xx-small` | ~9px             |
| `x-small`  | ~10px            |
| `small`    | ~13px            |
| `smaller`  | Smaller than parent font size |
| `medium`   | ~16px            |
| `large`    | ~18px            |
| `larger`   | Larger than parent font size |
| `x-large`  | ~24px            |
| `xx-large` | ~32px            |
| `xxx-large`| ~48px            |

---

## Relative length units:
 **Relative units:** `em rem vw vh vmin vmax cqw cqh cqmin cqmax %`

  * Based on parent element's font: `em ex ch ic lh cap`
  * Based on root element's font: `rem rex rch ric rlh rcap`
  * Based on viewport %: `vw vh vi vb vmax vmin`
  * Container query length units %: `cqw cqh cqi cqb cqmin cqmax`
  * Percentage: `%`
  * Inline and Block: `vi vb cqi cqb`

**Content length properties:**\
  `auto max-content min-content fit-content`
  
**Container length methods:**\
  `min(width, max-width)`\
  `max(width, min-width)`\
  `minmax(min-width, max-width)`\
  `clamp(min-width, width, max-width)`\
  `calc(length-x [+,-,*,/] length-y)`

---

*Note:*  
- `min()`, `max()`, `clamp()` are general CSS functions to compute lengths.  
- `minmax()` is used primarily within CSS Grid for track sizing.  
- `calc()` supports arithmetic operations on length values.
