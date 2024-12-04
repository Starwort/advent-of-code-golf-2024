L=join(eachline())
!m=parse(Int,m)
e,~=eachmatch,isnothing
S(i,s=0,M=1)=(e(r"(do\(\))|(don\'t\(\))|mul\((\d+),(\d+)\)",i).|>m->~m[1]&&~m[2] ? (s+=(!m[3]*!m[4])M) : (M=1-~m[1]);s)
print(sum(e(r"mul\((\d+),(\d+)\)",L).|>m->!m[1]*!m[2])," ",S(L))