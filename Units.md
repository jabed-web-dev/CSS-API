## Absolute length units:
 **Absolute units:** `px mm cm q in pc pt`

 * px = 1in/96
 * mm = 3.7795275590551185px
 * cm = 37.795275591px
 * in = 96px
 * pc = 16px
 * pt = 1.33333333333333px
 * q = 0.944881889775px

 **Absolute font size:**
  `xx-small x-small small smaller medium large larger x-large xx-large xxx-large`

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
  `mix(width, min-width)`\
  `max(min(width, max-width), min-width) = min(max()) = clamp()`\
  `clamp(min-width, width, max-width)`\
  `calc(length-x [+,-,*,/] length-y)`
