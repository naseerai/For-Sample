$ f(X) = sinX $
$$ f(x) cos+1 $$
$ (a-b)^2 = a^2+b^2-2ab $
$ (a+b)^2 = a^2+b^2+2ab $
$ {\pi} =\frac a b $
$ \cfrac {(a+b)^2}{a+ \cfrac{x}{y}}   $
$ \displaystyle\sum_{n=786}^{\pi}  $
$ \int^c_d\int^a_b $
$ \sqrt{\frac{y}{x}}$
$ \frac{d^2y}{dx^2}= $
$ \int_{a}^{b} x^2 \,dx $ 
 
 
 
```mermaid 
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
 ```wavedrom
{ signal: [
  { name: "pclk", wave: 'p..P....p' },
  { name: "Pclk", wave: 'P........' },
  { name: "nclk", wave: 'n........' },
  { name: "Nclk", wave: 'N.......' },
  {},
  { name: 'clk0', wave: 'phnlPHNL' },
  { name: 'clk1', wave: 'xhlhLHl.' },
  { name: 'clk2', wave: 'hpHplnLn' },
  { name: 'clk3', wave: 'nhNhplPl' },
  { name: 'clk4', wave: 'xlh.L.Hx' },
]}

```
```wavedrom
{ signal: [
  { name: 'A', wave: '01........0....',  node: '.a........j' },
  { name: 'B', wave: '0.1.......0.1..',  node: '..b.......i' },
  { name: 'C', wave: '0..1....0...1..',  node: '...c....h..' },
  { name: 'D', wave: '0...1..0.....1.',  node: '....d..g...' },
  { name: 'E', wave: '0....10.......1',  node: '.....ef....' }
  ],
  edge: [
    'a~b t1', 'c-~a t2', 'c-~>d time 3', 'd~-e',
    'e~>f', 'f->g', 'g-~>h', 'h~>i some text', 'h~->j'
  ]
}
```
```wavedrom
{ signal: [{ name: "Alfa", wave: "01.zx=ud.23.456789" }] }
```