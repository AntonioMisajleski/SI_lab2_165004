# Втора лабораториска вежба по Софтверско инженерство

# Aнтонио Мисајлески, бр. на индекс 165004
Ја добив групата на код 3

# Control Flow Graph

![](/Images/cfg.png)

## Цикломатска комплексност
Цикломатската комплексност на овој код е 10, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=9, па цикломатската комплексност изнесува 10.

## Тест случаи според критериумот Every branch

1.user==null

2.user=1,userna=mearija,pw=null

3.user=2,username=Mar1, pw=marijatrajk

4.user=3,username=marm, pw=marijaraj1@

5.user=4,username=maria, pw=marija

6.user=6,username=Mar123, pw=Mar

Со every branch критериумот ги пишуваме(односно изминуваме) сеите гранки од CFG(графот) и низ овие 6 тест случаеви се препокрива цела функција се случи да ни се поклопат двата критериуми со истите тест примери немаше потреба од дополнителни.


## Тест случаи според критериумот Every statement

1.user==null
2.user=1,userna=mearija,pw=null
3.user=2,username=Mar1, pw=marijatrajk
4.user=3,username=marm, pw=marijaraj1@
5.user=4,username=maria, pw=marija
6.user=6,username=Mar123, pw=Mar

Со every statement критериумот ги пишуваме(односно изминуваме секоја линија код) од програата и низ овие 6 тест случаеви се препокрива цела функција се случи да ни се поклопат двата критериуми со истите тест примери немаше потреба од дополнителни.
