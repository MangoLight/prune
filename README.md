# Prune

Prune is a lightweight CSS framework inspired from Tailwind (based on the utility classes pattern).

- 📦 Highly reusable
- 🍃 Lightweight (~14kb gzipped)
- ⚡️ Much faster developments (much less custom styles)
- 📐 Based on flexbox and em sizes
- ⛔️  No preprocessor, just plug-n-play

## Non exhaustive documentation
(Look at the code, it's easy to understand and use)

#### Width
`.w:[0,5,10,15,...,100]`: width 0,5%,...,100%

`.w:[17,33,66,83]`: width 17%,...,83%

`.w:[1,1.5,2,3,4,5,6,7,8,9,10,11,13,15,17,19,21,23,25,30,35,40,45,50,55,60,75,100]e`: width 1em,...,100em

`.w-m:[1,2,3,4,5,6,7,8,9,10,11,13,15,17,19,21,23,25,30,35,40,45,50,55,60,75,100]e`: min-width 1em,....,100em

#### Height
`.h:[0,10,20,...,100]`: height 0,10%,...,100%

`.h:[5,17,25,33,66,75,95]`: height 5%,...,95%

`.h:[25,50,75,100]v`: height 25vh,...,100vh

`.h-m:[25,50,75,100]v`: min-height 25vh,...,100vh

`.h-r:[3/5,2/3,3/4,4/3,5/3,16/9,21/9,32/9]`: responsive-height ratio w/h

#### Grid
section > .con > .row > .col

Example: `<section><div class="row"><div class="col w:50 s=w:100">col 1</div><div class="col w:50 s=w:100">col 2</div></div></section>`

#### Padding
`.p[,x,y,t,b,l,r]:[0,1,...,10]`: Padding[,horizontal,vertical,top,bottom,left,right]

#### Margin
`.m[,x,y,t,b,l,r]:[0,1,...,10]`: Margin[,horizontal,vertical,top,bottom,left,right]

#### Font size
`.s:[1-14]`: font-size relative (1-2 for decreased size, 3 for 1em size, 4+ for bigger size)

#### Display
`.d:[n,b,f,i,g,d,ib]`: none,block,flex,inline,grid,initial,inline-block

#### Position
`.po:[s,f,a,full]`: static,fixed,absolute,full(100%-100%)

`.[to,le,ri,bo]:[0,10,...,100]`: [top,left,right,bottom] [0,10%,...,100%]

#### Align
`.a:[l,c,r,a,na,t,m,b,s,va,cm]`: left,center,right,horizontal auto,flex-wrap,top,middle,bottom,stretch,vertical auto,center+middle

#### Buttons
`.pr:button`

#### Shadows
`.sh:[0-6]`: 0-none,1..6 level of shadow

#### Z-index
`.z:[0-5]`: 0,10,...50

#### Overflow
`.ov:[a,x,y,v,h,t]`: auto,horizontal-scroll,vertical-scroll,visible,hidden,ellipsis

#### Reponsive
`.s=[...]`: max-width:575px

`.m=[...]`: 576px to 980px

Example: `.s=w:100` means width:100% under 576px.

#### Others
Borders, Radius, Effects, ...
