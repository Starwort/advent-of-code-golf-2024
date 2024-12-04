new Response(Deno.stdin.readable).text().then((t)=>{
var $$$
var l=t.split("\n"),m1,m2,r=-1,cc=-1,$$=0,x={}
for (let e1 of l) {
r++
    let e2=l[r+1]||"",e3=l[r+2]||""
    //console.log(JSON. stringify(e1))
    cc=-1
    for (let c of e1) {
        cc++
//console.log([e1.slice(cc,cc+3),e2.slice(cc,cc+3),e3.slice(cc,cc+3)].join("\n"))
var f1,f2,f3,f4
$$+=((f1=(
e1[cc]=="M"&&e1[cc+2]=="M"&&
e2[cc+1]=="A"&&
e3[cc]=="S"&&e3[cc+2]=="S"
)) || (f2=(
e1[cc]=="S"&&e1[cc+2]=="S"&&
e2[cc+1]=="A"&&
e3[cc]=="M"&&e3[cc+2]=="M"
))|| (f3=(
e1[cc]=="M"&&e1[cc+2]=="S"&&
e2[cc+1]=="A"&&
e3[cc]=="M"&&e3[cc+2]=="S"
))|| (f4=(
e1[cc]=="S"&&e1[cc+2]=="M"&&
e2[cc+1]=="A"&&
e3[cc]=="S"&&e3[cc+2]=="M"
))
)
//console.log(f1,f2,f3,f4)
    }
}


var c=0,p,$=[]
// left right 
c+=t.match(p=/X(?=MAS)|S(?=AMX)/g).length
//console.log(1,c, typeof c)

// up down
var f = [],j=1
for (var e of l) {
j=0
for (let c of e) {
f[j] = f[j]||[]
f[j].push(c)
j++
}
}
var o
var d=(o=f.join("\n").replace(/,/g,"")).match(p)?.length
c+=d
//console.log(2,typeof d)
var O=o

// diagonal, left to right
var f = [],j=1
for (var e of l.map((e,j)=>" ".repeat(j)+e+" ".repeat(l.length-j))) {
j=0
for (let c of e) {
f[j] = f[j]||[]
f[j].push(c)
j++
}
}
var o
var d=(o=f.join("\n").replace(/,/g,"")).match(p)?.length
c+=d
//console.log(3,)//c,o,l.map((e,j)=>" ".repeat(j)+e+" ".repeat(l.length-j)))

// diagonal, 
var f = [],j=1
for (var e of l.map((e,j)=>" ".repeat(l.length-j)+""+e+" ".repeat(j))) {
//console.log (JSON.stringify(e))
j=0
for (let c of e) {
f[j] = f[j]||[]
f[j].push(c)
j++
}
}
var o
var d=(o=f.join("\n").replace(/,/g,"")).match(p)?.length
c+=d
console.log(c,$$)
})