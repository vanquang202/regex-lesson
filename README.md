## Lesson 1 
( va ) => so sanh mot khoang chuoi
(abc)
=> So khop mot ky tu trong mot chuoi ky tu 

## Lesson 1 
\d
=> So khop cac ky tu so 0-9

## Lesson 2 
\.
=> So khop cac ky tu la dau .

## Lesson 3 
[cmf]
=> So khop mot trong cac ky tu co trong chuoi ky tu co mot trong cac chu c , m ,f

## Lesson 4 
[^bog]
=> So khop cac chuoi ky tu khon co b , o , g 

## Lesson 5 
[0-6] => So khop cac so tu 0 - 6 
[^n-p] => So khop cac chu khong nam trong khoang n-p
[A-Za-z0-9_] => So khop cac ky tu in hoa , in thuong va so 

## Lesson 6 
\w\w\w => So khop 3 chu so 
\w{3} => tuong tu
waz{3} => So khop ky tu co 3 chu z
waz{3,} => So khop ky tu co 3 chu z so tro len
waz{3,5} => So khop ky tu co 3 chu z so den 5 so

## Lesson 7 
[*] => Null hoac nhieu ky tu 
[+] => Mot hoac nhieu ky tu
[?] => Mot hoac khong ky tu nao
a\w+ => Ky tu a va nhieu ky tu a-zA-Z0-9

## Lesson 8 
ab?c => so khop ky tu co c hoac khong co c 
\? => Cung nhu dau \. So khop chuoi co dau ?

## Lesson 9 
( ) space
(\t) tab
(\n) new line
(\r) xuong dong 
\s Khoang trang 

## Lesson 10
^ => dau chuoi 
$ => cuoi chuoi
(\ssuccessful$) => so sanh chuoi cuoi la tu " successfull"

## Lesson 11 
( va ) => so sanh mot khoang chuoi
^(file_\w*) => so sanh chuoi co ky tu file_cac ky tu sau 

## Lesson 12 
( va ( va )) => so khop 2 nhom voi nhau
(\w+\s(\d+)) => so khop nhom cos ky tu chu dau khoang trang va mot nhom so 

## Lesson 13 
((\d{1,4})x(\d{1,})?) => so khop chuoi dang 0121x1212  

## Lesson 14 
| dau hoac dieu kien so khop
(\scat|dogs) so khop ky tu " cat" hoac "dogs"

## Lesson 15 
(\w+\s)+(\S+)+((\s\w+)+)? => Ma loc theo vi du lesson 5 

## Lesson x 

^-?\d+(,\d+)*(\.\d+(e\d+)?)?$ => Xu ly chuoi thap phan 


(\d{3}) => Xu ly 3 so dau tien cua moi so dien thoai
1?[\s-]?\(?(\d{3})\)?[\s-]?(\d+-?\s?)+ => So khop mau so dien thoai va group 3 so dau cua so dien thoai 

^([\w\.]*) => Xu ly lay name email co dau . truoc ky tu bat ki 

^<(\w+) => Xu ly ky tu sau < la mot the html 

([\w]*)\.(png|jpg|gif)$ => Xu ly ky tu image 

^\s*([\w\s\.]*)$ => Xu ly chuoi ky tu khoi dau space 

(\w+)\(([\w\.]*)\:(\d+) > Xy ly chuoi ky tu theo dang log error
E/( 1553):   at widget.List.makeView(ListView.java:1727) => **makeView**|**ListView.java**|**1727**

(\w+)\W+([\w+\.?\-?]*)(\:?(\d+))? => Xy ly chuoi dang domain => http
"https://regexone.com/lesson/introduction#section" => **https**|**regexone.com**
file://localhost:4040/zip_file => **file**|**localhost**|**4040**
Loi giai (\w+)://([\w\-\.]+)(:(\d+))? 


i => Khong phan biet chu hoa chu thuong 
g => Tim toan bo ket qua 
m ==> Xu ly nhieu dong 
[] => Mo ta mot tap hop ca ky tu 
[^ ] => Phu dinh cua []
\w => [a-zA-Z0-9_]
\W => [^a-zA-Z0-9_]
\d => [0-9]
\D => [^0-9]
\s => [\t\f\n\r\p{Z}] 
\S => [^\t\f\n\r\p{Z}]
\b => Phan tach cac tu 
\B => Khong phan tach cac tu
[*] => Null hoac nhieu lan 
[+] => Mot hoac nhieu lan 
[?] => Co hay khong deu duoc
?! => Lookahead
{min,max} => Do dai
(abc) => SO khop chuoi gorup ky tu 
| phep hoac 
\ Lay ky tu dac biet 
^ Dau chuoi 
$ Cuoi chuoi 
\z Diem ket thuc chuoi input 
