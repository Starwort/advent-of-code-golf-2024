L=readlines(stdin).|>l->parse.(Int,split(l))
~,!,s=sum,length,issorted
C(l)=(s(l)||s(l,rev=true))&&all(0 .<extrema(abs,diff(l)).<4)
K(l)=C(l)||any(1:!l.|>i->C([l[j] for j=1:!l if j!=i]))
println.([C~L,K~L])