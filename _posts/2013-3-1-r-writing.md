<!DOCTYPE html>
<!-- saved from url=(0014)about:internet -->
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

<title>科技论文写作</title>

<style type="text/css">
body, td {
   font-family: sans-serif;
   background-color: white;
   font-size: 12px;
   margin: 8px;
}

tt, code, pre {
   font-family: 'DejaVu Sans Mono', 'Droid Sans Mono', 'Lucida Console', Consolas, Monaco, monospace;
}

h1 { 
   font-size:2.2em; 
}

h2 { 
   font-size:1.8em; 
}

h3 { 
   font-size:1.4em; 
}

h4 { 
   font-size:1.0em; 
}

h5 { 
   font-size:0.9em; 
}

h6 { 
   font-size:0.8em; 
}

a:visited {
   color: rgb(50%, 0%, 50%);
}

pre {	
   margin-top: 0;
   max-width: 95%;
   border: 1px solid #ccc;
   white-space: pre-wrap;
}

pre code {
   display: block; padding: 0.5em;
}

code.r, code.cpp {
   background-color: #F8F8F8;
}

table, td, th {
  border: none;
}

blockquote {
   color:#666666;
   margin:0;
   padding-left: 1em;
   border-left: 0.5em #EEE solid;
}

hr {
   height: 0px;
   border-bottom: none;
   border-top-width: thin;
   border-top-style: dotted;
   border-top-color: #999999;
}

@media print {
   * { 
      background: transparent !important; 
      color: black !important; 
      filter:none !important; 
      -ms-filter: none !important; 
   }

   body { 
      font-size:12pt; 
      max-width:100%; 
   }
       
   a, a:visited { 
      text-decoration: underline; 
   }

   hr { 
      visibility: hidden;
      page-break-before: always;
   }

   pre, blockquote { 
      padding-right: 1em; 
      page-break-inside: avoid; 
   }

   tr, img { 
      page-break-inside: avoid; 
   }

   img { 
      max-width: 100% !important; 
   }

   @page :left { 
      margin: 15mm 20mm 15mm 10mm; 
   }
     
   @page :right { 
      margin: 15mm 10mm 15mm 20mm; 
   }

   p, h2, h3 { 
      orphans: 3; widows: 3; 
   }

   h2, h3 { 
      page-break-after: avoid; 
   }
}

</style>

<!-- Styles for R syntax highlighter -->
<style type="text/css">
   pre .operator,
   pre .paren {
     color: rgb(104, 118, 135)
   }

   pre .literal {
     color: rgb(88, 72, 246)
   }

   pre .number {
     color: rgb(0, 0, 205);
   }

   pre .comment {
     color: rgb(76, 136, 107);
   }

   pre .keyword {
     color: rgb(0, 0, 255);
   }

   pre .identifier {
     color: rgb(0, 0, 0);
   }

   pre .string {
     color: rgb(3, 106, 7);
   }
</style>

<!-- R syntax highlighter -->
<script type="text/javascript">
var hljs=new function(){function m(p){return p.replace(/&/gm,"&amp;").replace(/</gm,"&lt;")}function f(r,q,p){return RegExp(q,"m"+(r.cI?"i":"")+(p?"g":""))}function b(r){for(var p=0;p<r.childNodes.length;p++){var q=r.childNodes[p];if(q.nodeName=="CODE"){return q}if(!(q.nodeType==3&&q.nodeValue.match(/\s+/))){break}}}function h(t,s){var p="";for(var r=0;r<t.childNodes.length;r++){if(t.childNodes[r].nodeType==3){var q=t.childNodes[r].nodeValue;if(s){q=q.replace(/\n/g,"")}p+=q}else{if(t.childNodes[r].nodeName=="BR"){p+="\n"}else{p+=h(t.childNodes[r])}}}if(/MSIE [678]/.test(navigator.userAgent)){p=p.replace(/\r/g,"\n")}return p}function a(s){var r=s.className.split(/\s+/);r=r.concat(s.parentNode.className.split(/\s+/));for(var q=0;q<r.length;q++){var p=r[q].replace(/^language-/,"");if(e[p]){return p}}}function c(q){var p=[];(function(s,t){for(var r=0;r<s.childNodes.length;r++){if(s.childNodes[r].nodeType==3){t+=s.childNodes[r].nodeValue.length}else{if(s.childNodes[r].nodeName=="BR"){t+=1}else{if(s.childNodes[r].nodeType==1){p.push({event:"start",offset:t,node:s.childNodes[r]});t=arguments.callee(s.childNodes[r],t);p.push({event:"stop",offset:t,node:s.childNodes[r]})}}}}return t})(q,0);return p}function k(y,w,x){var q=0;var z="";var s=[];function u(){if(y.length&&w.length){if(y[0].offset!=w[0].offset){return(y[0].offset<w[0].offset)?y:w}else{return w[0].event=="start"?y:w}}else{return y.length?y:w}}function t(D){var A="<"+D.nodeName.toLowerCase();for(var B=0;B<D.attributes.length;B++){var C=D.attributes[B];A+=" "+C.nodeName.toLowerCase();if(C.value!==undefined&&C.value!==false&&C.value!==null){A+='="'+m(C.value)+'"'}}return A+">"}while(y.length||w.length){var v=u().splice(0,1)[0];z+=m(x.substr(q,v.offset-q));q=v.offset;if(v.event=="start"){z+=t(v.node);s.push(v.node)}else{if(v.event=="stop"){var p,r=s.length;do{r--;p=s[r];z+=("</"+p.nodeName.toLowerCase()+">")}while(p!=v.node);s.splice(r,1);while(r<s.length){z+=t(s[r]);r++}}}}return z+m(x.substr(q))}function j(){function q(x,y,v){if(x.compiled){return}var u;var s=[];if(x.k){x.lR=f(y,x.l||hljs.IR,true);for(var w in x.k){if(!x.k.hasOwnProperty(w)){continue}if(x.k[w] instanceof Object){u=x.k[w]}else{u=x.k;w="keyword"}for(var r in u){if(!u.hasOwnProperty(r)){continue}x.k[r]=[w,u[r]];s.push(r)}}}if(!v){if(x.bWK){x.b="\\b("+s.join("|")+")\\s"}x.bR=f(y,x.b?x.b:"\\B|\\b");if(!x.e&&!x.eW){x.e="\\B|\\b"}if(x.e){x.eR=f(y,x.e)}}if(x.i){x.iR=f(y,x.i)}if(x.r===undefined){x.r=1}if(!x.c){x.c=[]}x.compiled=true;for(var t=0;t<x.c.length;t++){if(x.c[t]=="self"){x.c[t]=x}q(x.c[t],y,false)}if(x.starts){q(x.starts,y,false)}}for(var p in e){if(!e.hasOwnProperty(p)){continue}q(e[p].dM,e[p],true)}}function d(B,C){if(!j.called){j();j.called=true}function q(r,M){for(var L=0;L<M.c.length;L++){if((M.c[L].bR.exec(r)||[null])[0]==r){return M.c[L]}}}function v(L,r){if(D[L].e&&D[L].eR.test(r)){return 1}if(D[L].eW){var M=v(L-1,r);return M?M+1:0}return 0}function w(r,L){return L.i&&L.iR.test(r)}function K(N,O){var M=[];for(var L=0;L<N.c.length;L++){M.push(N.c[L].b)}var r=D.length-1;do{if(D[r].e){M.push(D[r].e)}r--}while(D[r+1].eW);if(N.i){M.push(N.i)}return f(O,M.join("|"),true)}function p(M,L){var N=D[D.length-1];if(!N.t){N.t=K(N,E)}N.t.lastIndex=L;var r=N.t.exec(M);return r?[M.substr(L,r.index-L),r[0],false]:[M.substr(L),"",true]}function z(N,r){var L=E.cI?r[0].toLowerCase():r[0];var M=N.k[L];if(M&&M instanceof Array){return M}return false}function F(L,P){L=m(L);if(!P.k){return L}var r="";var O=0;P.lR.lastIndex=0;var M=P.lR.exec(L);while(M){r+=L.substr(O,M.index-O);var N=z(P,M);if(N){x+=N[1];r+='<span class="'+N[0]+'">'+M[0]+"</span>"}else{r+=M[0]}O=P.lR.lastIndex;M=P.lR.exec(L)}return r+L.substr(O,L.length-O)}function J(L,M){if(M.sL&&e[M.sL]){var r=d(M.sL,L);x+=r.keyword_count;return r.value}else{return F(L,M)}}function I(M,r){var L=M.cN?'<span class="'+M.cN+'">':"";if(M.rB){y+=L;M.buffer=""}else{if(M.eB){y+=m(r)+L;M.buffer=""}else{y+=L;M.buffer=r}}D.push(M);A+=M.r}function G(N,M,Q){var R=D[D.length-1];if(Q){y+=J(R.buffer+N,R);return false}var P=q(M,R);if(P){y+=J(R.buffer+N,R);I(P,M);return P.rB}var L=v(D.length-1,M);if(L){var O=R.cN?"</span>":"";if(R.rE){y+=J(R.buffer+N,R)+O}else{if(R.eE){y+=J(R.buffer+N,R)+O+m(M)}else{y+=J(R.buffer+N+M,R)+O}}while(L>1){O=D[D.length-2].cN?"</span>":"";y+=O;L--;D.length--}var r=D[D.length-1];D.length--;D[D.length-1].buffer="";if(r.starts){I(r.starts,"")}return R.rE}if(w(M,R)){throw"Illegal"}}var E=e[B];var D=[E.dM];var A=0;var x=0;var y="";try{var s,u=0;E.dM.buffer="";do{s=p(C,u);var t=G(s[0],s[1],s[2]);u+=s[0].length;if(!t){u+=s[1].length}}while(!s[2]);if(D.length>1){throw"Illegal"}return{r:A,keyword_count:x,value:y}}catch(H){if(H=="Illegal"){return{r:0,keyword_count:0,value:m(C)}}else{throw H}}}function g(t){var p={keyword_count:0,r:0,value:m(t)};var r=p;for(var q in e){if(!e.hasOwnProperty(q)){continue}var s=d(q,t);s.language=q;if(s.keyword_count+s.r>r.keyword_count+r.r){r=s}if(s.keyword_count+s.r>p.keyword_count+p.r){r=p;p=s}}if(r.language){p.second_best=r}return p}function i(r,q,p){if(q){r=r.replace(/^((<[^>]+>|\t)+)/gm,function(t,w,v,u){return w.replace(/\t/g,q)})}if(p){r=r.replace(/\n/g,"<br>")}return r}function n(t,w,r){var x=h(t,r);var v=a(t);var y,s;if(v){y=d(v,x)}else{return}var q=c(t);if(q.length){s=document.createElement("pre");s.innerHTML=y.value;y.value=k(q,c(s),x)}y.value=i(y.value,w,r);var u=t.className;if(!u.match("(\\s|^)(language-)?"+v+"(\\s|$)")){u=u?(u+" "+v):v}if(/MSIE [678]/.test(navigator.userAgent)&&t.tagName=="CODE"&&t.parentNode.tagName=="PRE"){s=t.parentNode;var p=document.createElement("div");p.innerHTML="<pre><code>"+y.value+"</code></pre>";t=p.firstChild.firstChild;p.firstChild.cN=s.cN;s.parentNode.replaceChild(p.firstChild,s)}else{t.innerHTML=y.value}t.className=u;t.result={language:v,kw:y.keyword_count,re:y.r};if(y.second_best){t.second_best={language:y.second_best.language,kw:y.second_best.keyword_count,re:y.second_best.r}}}function o(){if(o.called){return}o.called=true;var r=document.getElementsByTagName("pre");for(var p=0;p<r.length;p++){var q=b(r[p]);if(q){n(q,hljs.tabReplace)}}}function l(){if(window.addEventListener){window.addEventListener("DOMContentLoaded",o,false);window.addEventListener("load",o,false)}else{if(window.attachEvent){window.attachEvent("onload",o)}else{window.onload=o}}}var e={};this.LANGUAGES=e;this.highlight=d;this.highlightAuto=g;this.fixMarkup=i;this.highlightBlock=n;this.initHighlighting=o;this.initHighlightingOnLoad=l;this.IR="[a-zA-Z][a-zA-Z0-9_]*";this.UIR="[a-zA-Z_][a-zA-Z0-9_]*";this.NR="\\b\\d+(\\.\\d+)?";this.CNR="\\b(0[xX][a-fA-F0-9]+|(\\d+(\\.\\d*)?|\\.\\d+)([eE][-+]?\\d+)?)";this.BNR="\\b(0b[01]+)";this.RSR="!|!=|!==|%|%=|&|&&|&=|\\*|\\*=|\\+|\\+=|,|\\.|-|-=|/|/=|:|;|<|<<|<<=|<=|=|==|===|>|>=|>>|>>=|>>>|>>>=|\\?|\\[|\\{|\\(|\\^|\\^=|\\||\\|=|\\|\\||~";this.ER="(?![\\s\\S])";this.BE={b:"\\\\.",r:0};this.ASM={cN:"string",b:"'",e:"'",i:"\\n",c:[this.BE],r:0};this.QSM={cN:"string",b:'"',e:'"',i:"\\n",c:[this.BE],r:0};this.CLCM={cN:"comment",b:"//",e:"$"};this.CBLCLM={cN:"comment",b:"/\\*",e:"\\*/"};this.HCM={cN:"comment",b:"#",e:"$"};this.NM={cN:"number",b:this.NR,r:0};this.CNM={cN:"number",b:this.CNR,r:0};this.BNM={cN:"number",b:this.BNR,r:0};this.inherit=function(r,s){var p={};for(var q in r){p[q]=r[q]}if(s){for(var q in s){p[q]=s[q]}}return p}}();hljs.LANGUAGES.cpp=function(){var a={keyword:{"false":1,"int":1,"float":1,"while":1,"private":1,"char":1,"catch":1,"export":1,virtual:1,operator:2,sizeof:2,dynamic_cast:2,typedef:2,const_cast:2,"const":1,struct:1,"for":1,static_cast:2,union:1,namespace:1,unsigned:1,"long":1,"throw":1,"volatile":2,"static":1,"protected":1,bool:1,template:1,mutable:1,"if":1,"public":1,friend:2,"do":1,"return":1,"goto":1,auto:1,"void":2,"enum":1,"else":1,"break":1,"new":1,extern:1,using:1,"true":1,"class":1,asm:1,"case":1,typeid:1,"short":1,reinterpret_cast:2,"default":1,"double":1,register:1,explicit:1,signed:1,typename:1,"try":1,"this":1,"switch":1,"continue":1,wchar_t:1,inline:1,"delete":1,alignof:1,char16_t:1,char32_t:1,constexpr:1,decltype:1,noexcept:1,nullptr:1,static_assert:1,thread_local:1,restrict:1,_Bool:1,complex:1},built_in:{std:1,string:1,cin:1,cout:1,cerr:1,clog:1,stringstream:1,istringstream:1,ostringstream:1,auto_ptr:1,deque:1,list:1,queue:1,stack:1,vector:1,map:1,set:1,bitset:1,multiset:1,multimap:1,unordered_set:1,unordered_map:1,unordered_multiset:1,unordered_multimap:1,array:1,shared_ptr:1}};return{dM:{k:a,i:"</",c:[hljs.CLCM,hljs.CBLCLM,hljs.QSM,{cN:"string",b:"'\\\\?.",e:"'",i:"."},{cN:"number",b:"\\b(\\d+(\\.\\d*)?|\\.\\d+)(u|U|l|L|ul|UL|f|F)"},hljs.CNM,{cN:"preprocessor",b:"#",e:"$"},{cN:"stl_container",b:"\\b(deque|list|queue|stack|vector|map|set|bitset|multiset|multimap|unordered_map|unordered_set|unordered_multiset|unordered_multimap|array)\\s*<",e:">",k:a,r:10,c:["self"]}]}}}();hljs.LANGUAGES.r={dM:{c:[hljs.HCM,{cN:"number",b:"\\b0[xX][0-9a-fA-F]+[Li]?\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\b\\d+(?:[eE][+\\-]?\\d*)?L\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\b\\d+\\.(?!\\d)(?:i\\b)?",e:hljs.IMMEDIATE_RE,r:1},{cN:"number",b:"\\b\\d+(?:\\.\\d*)?(?:[eE][+\\-]?\\d*)?i?\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"number",b:"\\.\\d+(?:[eE][+\\-]?\\d*)?i?\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"keyword",b:"(?:tryCatch|library|setGeneric|setGroupGeneric)\\b",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\.\\.\\.",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\.\\.\\d+(?![\\w.])",e:hljs.IMMEDIATE_RE,r:10},{cN:"keyword",b:"\\b(?:function)",e:hljs.IMMEDIATE_RE,r:2},{cN:"keyword",b:"(?:if|in|break|next|repeat|else|for|return|switch|while|try|stop|warning|require|attach|detach|source|setMethod|setClass)\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"literal",b:"(?:NA|NA_integer_|NA_real_|NA_character_|NA_complex_)\\b",e:hljs.IMMEDIATE_RE,r:10},{cN:"literal",b:"(?:NULL|TRUE|FALSE|T|F|Inf|NaN)\\b",e:hljs.IMMEDIATE_RE,r:1},{cN:"identifier",b:"[a-zA-Z.][a-zA-Z0-9._]*\\b",e:hljs.IMMEDIATE_RE,r:0},{cN:"operator",b:"<\\-(?!\\s*\\d)",e:hljs.IMMEDIATE_RE,r:2},{cN:"operator",b:"\\->|<\\-",e:hljs.IMMEDIATE_RE,r:1},{cN:"operator",b:"%%|~",e:hljs.IMMEDIATE_RE},{cN:"operator",b:">=|<=|==|!=|\\|\\||&&|=|\\+|\\-|\\*|/|\\^|>|<|!|&|\\||\\$|:",e:hljs.IMMEDIATE_RE,r:0},{cN:"operator",b:"%",e:"%",i:"\\n",r:1},{cN:"identifier",b:"`",e:"`",r:0},{cN:"string",b:'"',e:'"',c:[hljs.BE],r:0},{cN:"string",b:"'",e:"'",c:[hljs.BE],r:0},{cN:"paren",b:"[[({\\])}]",e:hljs.IMMEDIATE_RE,r:0}]}};
hljs.initHighlightingOnLoad();
</script>


<!-- MathJax scripts -->
<script type="text/javascript" src="https://c328740.ssl.cf1.rackcdn.com/mathjax/2.0-latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>



</head>

<body>
<hr/>

<p>layout: post
title: R和Markdown科技论文写作
categories:</p>

<ul>
<li>技术
tags:</li>
<li>R</li>
<li>Markdown</li>
<li>knitr</li>
<li>Pandoc</li>
</ul>

<hr/>

<h1>科技论文写作</h1>

<h2>1.Markdown测试</h2>

<p>Markdown的目标是实现** 易读易写 **。</p>

<p><strong>兼容Html</strong></p>

<p>对于Markdown不提供的标签可以直接用html的标签来写。在html区块标签内的Markdown语法是无效的，但在行内标签间是有效地。</p>

<h2>标题</h2>

<blockquote>
<h1>标题一</h1>

<h2>标题二</h2>

<h3>标题三</h3>
</blockquote>

<p><em>区块引用</em></p>

<blockquote>
<p>这是一个区块。
可以只在整个段落第一行加&gt; 号。</p>

<p>这是第二段。</p>
</blockquote>

<p>区块引用嵌套，使用不同数量的&gt;就行。</p>

<blockquote>
<p>第一层</p>

<blockquote>
<p>第二层</p>
</blockquote>

<p>返回第一层</p>
</blockquote>

<h2>列表</h2>

<p>无序列表，使用星号，加号或是减号。</p>

<blockquote>
<p>*green
+red
-blue</p>
</blockquote>

<p>有序列表使用数字加英文句号：</p>

<blockquote>
<ol>
<li>蛇</li>
<li>年</li>
<li>大</li>
<li>吉</li>
</ol>
</blockquote>

<p>列表项目的多个段落，段落需要缩进。</p>

<h2>代码区块</h2>

<pre><code>简单缩进4个空格或是一个TAB。
</code></pre>

<h2>分割线</h2>

<h2>三个以上的星号、减号、底线来建立一个分割线。</h2>

<h2>链接</h2>

<p><a href="http://www.baidu.com/">百度首页</a>。
参考式链接
<a href="https://www.google.com.hk/" title="google">google</a>。</p>

<h2>强调</h2>

<p><em>强调</em> 
<strong>加粗</strong></p>

<h2>代码</h2>

<p>行内代码，可以用反引号，例如：</p>

<blockquote>
<p>use the <code>printf()</code> function.</p>
</blockquote>

<h2>图片</h2>

<p><img src="http://www.baidu.com/img/shouye_b5486898c692066bd2cbaeda86d74448.gif" alt="baidu首页"/></p>

<h2>2.R语言测试</h2>

<h3>画出自带数据集cars</h3>

<pre><code class="r">plot(cars)
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAkAAAAFoCAMAAACIU7TCAAAAbFBMVEX9/v0AAAAAADkAAGUAOTkAOWUAOY8AZrU5AAA5ADk5AGU5OY85j9plAABlADllAGVlOQBlZjlltf2POQCPOTmPOWWPjzmPtY+P2/21ZgC1/rW1/v3ajzna24/a/v39tWX924/9/rX9/tr9/v0hhXJqAAAAJHRSTlP//////////////////////////////////////////////wBYLA0NAAAACXBIWXMAAAsSAAALEgHS3X78AAAJcklEQVR4nO3dDXfaNh+G8ZF1IWshbNBtsLDw9v2/4ywH2rQoRua2/tbL9TvPGc/OVrturskSxMovJ0Dwy9i/AeSNgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKC5HZA+6eJ8+uLwe8G2bkZ0HG1bF93j68//6MJaiAGdFi8/PD6PqBbvxYFUAPqGoHu/C0hJ2pAp8O8Hcg8cyACqoEc0N2HRhEICBI5oGYZ/7BmEl2cm+ury7/X/Y+DJtHH1YyACjM5BX4Bh1nGb6bvAgp8hwApMwvovIzffvrMCFQSs4CaZfzMvWyv1/EElDOrOdD9h0YRCAgSAoKEgCCRl/Hz85qdSXSd5BHIvYt416FRBP0Wdnhe33VoFIE5ECQEBAkBQUJAkBAQJAQECQFBQkCQEBAkBAQJAUFCQJAQECQEBAkBQUJAkBAQJENsrsD+QBVjhzJI2CMREkYgSNgjERJWYZAQECQs4yFhEg1JhGU8eyTWhBEIEpbxkLAKg4SAICEgSAgIEvZIhIQ9EiFhj0RImAPBi5+VAYXdT+u5+9BIWfCHmQQEH0YgSBiBIGEEgoZVGEwQECQEBAkBQUJAkBAQJAQECQEhnOfNIQJCMN/b0wSUpiQf7CWgbAR/FGWKgLKRZkBR5kBs7xJDogF5sLlCmpKcA/mwSyskjECQsL2LKpubTRyswkT5THfjiBBQXVvcEVCnoGX8dFvxLYyAOt2eRH9dn7bTpqMvtU6iaxlqPzDEMn47YxlfLUYgSIaYA81qngPVjmV8mrKZWRFQkvJZ2xFQkgjo9qHRgYBuHxpdmAMRUB0ICBICgoSAICEgSAgIXmxxBwWbbEJCQJAQUIks355mDlSeJD8gI6B8EBAkekAR7oEElBH16x9jCAsK6O2RC8+DF8qhYW6kgL79YObr/ROUQ8PcyCPQwIfGQHrc2JgD4crIa7OwgLaPr9vJZDnooTGMHAI6PK+b/+0/+25k7JE4siwCWrw0Y5A3IHYoG924338feAubPKx33lsYeyRWjj0SIWGPRFU2T3DFEfJG4uLfDyMRDl2IJD/hNMQeiSIC6hSyP9DyuPJ+zFHHHysBdfrhszDfLcxNojfLmncoq2Wo/UDYCLSZNX9xO9ldaZbvbpc7lvG1kr+doxl+dk1eu+u6CKgGQQEdV+0I5P92jk17e/OMTgQkGPcj9h7CbmFumuxrRDk0OvSYmufwWViUQ6MDAd0+NDoQ0O1Dl03+/ne7OZD26wkoiozeXhR/qwQUBQGdEdB9LAMSb2EElCS7N2fkVpkD1Y1VGCQEVLtxl+EqAhpbRgs2HwIaGwHdeWi8IaA7D40z5kD3HRrDYBUGCQHlY+zvn/een4CyMfZ094PzMwfKRaIBjYuAwo39BRz7/F4E1EOSc6CRERAkBASJHBB7JEaR4t3KSw2IHcqiSHK+7KUGxB6JUdQTECNQFPUExB6JPfgnNv4PKGqZA91/6Pr4h5V8BhuvCAHVtUdiDwT0Ie8m9hn/qcRBQB4dGyhm/KcSSY85UDYGmEQ36TACVWuAW9hh/vgfAdVqkDnQ/sm3A3AlARnegVK82bGMFxnOgZOcbhOQiIA6EdAtBNSpqIDkKcTYHzowBxqV/B9wkiPA2AjI8AAlIiDLA0R5J5rnwqzEmQP1+OWnGJ+FjTwu1hTQ2Aho0EPXh4AGPXSFmAMNeWgUgYAgIaCx317OXPUBeeegvGUYjIBOBKQgoBMBKWoKSH6uT/1XS1RRQHE+C4vz7mA+CEg8AAF1qjWg8A11CahTSQH1mJd88PVnDnStpoDC1TOAyOSAitzijoCCqQFZbjBV+bevp0kNyHCLO4aFFGU0AhFQiuQ5kN0Wd5YBjf3t0/nIaRVm90WJ855jkSIEVMAWdwQUbIhl/MO6tH2iCSjYEJPo42qWRUA9BkXmQKGGWcZvphkEVM+oYGmgZfz20/Umd6l9sfp8wIVQAyzjZ+5lm/4urbV/bh5HTst4/1nEiQ0BaXIPiPXSyKoPiDmQhoD8h6WqQLkHFOdLzX0tWPYBRUFAwQjIh4CCEZAXc6BQBAQJAUFiGRDfFF8gw4AMZ6ZMgs0QECQEBAlzIEhYhUFCQJAQECQEBAkBQUJAkOQUEGvzBGUUEO8OpoiAICEgSHL6KIM5UILK/DAVZggIEjmg8H2iCahEA23vErRLK3OYAqkBefaJLmCPRASzHIFQoAE2mCrwZ2UgWEZvJCJFBARJzIBQg3gBhXYW/xQjnKrQy+p9KgLK4Fwpn4qAMjhXyqcioAzOlfKpCCiDc6V8KgLK4Fwpn4qAMjhXyqcyCAglIyBICAgSAoKEgCAhIEgICBICgoSAICEgSGIHtJ14vx8/gr37ueSH+eT66ZFI57K4NPdU59Lmss6n6ntVsQPaLCOf4GLnLts9g7Sd2pzL4tIOz+vT/ve1xWWdT9X7qiIHdPy6jnuCi83DP82o4J5+bEcHg3NZXNrOVbNZWlzW+VS9rypyQO1DZTaDkPsT3n95bf9TsjiX1aU112N1Wc05el9V5IDcoGg0Crkvqnt81iogo0s7rmZWl+VO1fuqLFZhNvMg6xGoFf3SDvPZyeiy2lO1+lxVWQHZzIEMA9o/uROYXNbbqVoJBeQG3+NfZst4NwgbrMK+3S5jX9r5i2pxWedT9b4qg/eBHmwWYmO8DxT70rbto6FLi8u6nKrvVfFONCQEBAkBQUJAkBAQJAQECQFBQkCQEBAkBAQJAUFCQJAQECQEBAkBQUJAkBAQJAQECQFBQkCQEJDg8uNAa0ZAAgIioG67dquTw+Lv9lGXw7zdleP7y29/EBABdXBPhG6nTSqPr7ummc3b433fX3ZG+0akjIA6nJ9HP8yXbsMB93dNUpeXxQu3sBMBdds/uXtX29Fm2e588rA+v7QPp5ptn5UuArph9/jqAnIj0KJ9ZPzdCyMQAXVyOw24gObT9v9uZj+/MAcioE6bt1XY85+XVdi7l+OKVdiJgEJYbFmVLQK6jYA6EBAkBAQJAUFCQJAQECQEBAkBQUJAkBAQJAQECQFBQkCQEBAkBAQJAUFCQJD8Dx5CYOQr/4zTAAAAAElFTkSuQmCC" alt="plot of chunk block"/> </p>

<h2>3.knitr测试</h2>

<h3>The Normal Distribution</h3>

<p>The normal distribution is defined as follows:</p>

<p>\[ f(x;\mu,\sigma^2) = \frac{1}{\sigma\sqrt{2\pi}} e^{ -\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2 }
 \]</p>

<p>To generate random draws from a normal distribution we use the <strong>rnorm</strong> function:</p>

<pre><code class="r">output &lt;- rnorm(1000, 100, 15)
</code></pre>

<p>The normal distribution has the typical bell shape:</p>

<pre><code class="r">ggplot2::qplot(output)
</code></pre>

<pre><code>## stat_bin: binwidth defaulted to range/30. Use &#39;binwidth = x&#39; to adjust
## this.
</code></pre>

<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAkAAAAFoCAMAAACIU7TCAAAAq1BMVEUAAAAAADoAAGYAOpAAZrYzMzM6AGY6kJA6kNtmAABmADpmAGZmZjpmtv9/f39/f5V/f6t/lcF/q9aQOgCQOjqQkDqQ2/+Vf3+Vq9aVweurf6urlZWrlcGr1v+2ZgC2/7a2///BlX/BlZXBlavBq8HBwdbB6//Wq3/Wq5XW///bkDrb///l5eXrwZXr///y8vL/tmb/1qv/25D/68H//7b//9b//9v//+v///+ca0xVAAAACXBIWXMAAAsSAAALEgHS3X78AAANvElEQVR4nO2bDXvTOBZGO7DDDrC4UHZhAtOhwExDgJSGaYn//y9bO0rryFjK1Yclf5zz9AmtuH1e36uDatP2pAQI4CT3BcC4QSAIAoEgCASCIBAIgkAgCAKBIAgEgiAQCIJAIAgCgSAIBIIgEAiCcBfoaxfdq8f55vl55GWLQ6AJ5yGQuAvycsUh0ITzEEjcBXm54hBownkIJO6CvFxxCDThPAQSd0FerjgEmnAeAom7IC9XHAJNOG9YAt2+WZXlsji9vHtFoKHnDUqgTfF8VW5eXN2/IdDg84Yk0Pbv7cdVuV7UB5F6rRaLCvORNXF+1ch9NUPB8iVsJ9B5/Yd63S8HK3zImE4EXaD+8zwY0gm0F0g/gRAIgdwE4h6oyUMgVeskEE9hTR4CqVqxQAaCr+AQBDLneYBA4i4y5CGQqkUgzzwEUrUI5JmHQKoWgTzzEEjVIpBnHgKpWgTyzEMgVYtAnnkIpGoRyDMPgVQtAnnmIZCqRSDPPARStQjkmYdAqhaBPPMQSNUikGceAqlaBPLMQyBVi0CeeQikahHIMw+BVC0CeeYhkKpFIM88BFK1COSZh0CqFoE88xBI1SKQZx4CqVoE8sxDIFWLQJ55CKRqEcgzD4FULQJ55iGQqkUgzzwEUrUI5JmHQKoWgTzzEEjVIpBnHgKp2lCBvnXRvdofOfJ0gfrPS4hLHCeQbx4nkKpFIM88BFK1COSZh0CqFoE88xBI1SKQZx4CqVoE8sxDIFWLQJ55CKRqEcgzD4FULQJ55iGQqkUgzzwEUrUI5JmHQKoWgcT8aqGPvAYEEoJA3SCQEATqBoGE5BfIJgkCddUikAYCOcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COca5CbQuKhblsihOLxEIgb56nEDbv662Hy6bj4Ov4BAE6mZKAn26LG/fvi7O6vfr8+joJ4wLX4FyX/dQOCrQpjJn83xVrs/3C8EKH8IJ1M2ETqBP+69emwUCIdBXZ4Fu/7hS8nACIZCqdRPon9/r12X9KIZACPSV/wdqg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQikg0COcQik4yuQTC4EQiAEatUikAYCOcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhkA4COcYhUB/KIBACIZCwFoEQKCRuhgL1bwwCOfCti+7V/nDKSy5Q4v7SxnEC9U/i/tLGIRACBcUhEAIFxSEQAgXFIRACBcUhEAIFxSEQAgXFIRACBcUhEAIFxSEQAgXFIRACBcUhEAIFxSEQAgXFIRACBcUhEAIFxSEQAgXFIRACBcUhUD6deuqvAYHEXbgUI1DMOKtAN08v7l8RCIE6a80C3Tw+UTz8gkAIZKo9fgLZCb6CQxAoQn8N2QWSEHwFhyBQhP4a8gt0vfsS9oB7oP6I319DdoFuHj/jBOqZ+P015BeIe6Deid9fQ3aByj9/Q6Ceid9fQ3aB9g/y3AP1SPz+GrILJCH4Cg5BoAj9NSCQuAuX4tzK6MTvryG7QHwJ65/4/TVkF0jx2XonHXwFhyBQhP4aBiLQ4cP8sihOL6vX6gWBohC/v4aBCHTdfAnbfqjF2by4qt4QKArx+2vILtD+Hqj57+jbt6+Ls3K9KG/frKoPi4oO4wZObmV0ck8jMkeewjbPV+X6fH1ebj+u9kvBCh/CCRShv4bsJ1C3RIv7EwiBwonfX0N+gX681H+ebLMoqxOIe6CIxO+vIbtAP17WT/CfDwyqnsIWJU9hEYnfX0N2gfiZ6P6J319DdoF+PoEQKDbx+2vILtBP90AIFJ34/TXkF0hA8BUcgkAR+mtAIHEXLsW5ldGJ319DfoGuT56Vn395hUD9Eb+/huwC3Typ3fn+iKew/ojfX0N2gX68rL8Nds1TWI/E768hu0Dqu6nWnydDoEDi99eQXyABwVdwSLSObZuURxQTfv3JQCBxF+0F2yblEcWEX38yEEjcRXvBtkl5RDHh158MBBJ30V6wbVIeUUz49ScDgcRdtBdsm5RHFBN+/clAIHEX7QXbJuURxYRffzIQSNxFe8G2SXlEMeHXnwwEEnfRXrBtUh5RTPj1JwOBxF20F2yblEcUE379yUAgcRftBdsm5RHFhF9/MhBI3EV7wbZJeUQx4defDAQSd9FesG1SHlFM+PUnA4HEXbQXbJuURxQTfv3JQCBxF+0F2yblEcWEX38yEEjcRXvBtkl5RDHh158MBBJ30V6wbVIeUUz49ScDgcRdtBdsm5RHFBN+/clAIHEX7QXbJuURxYRffzIQSNxFe8G2SXlEMeHXnwwEEnfRXrBtUh5RTPj1JwOBxF20F2yblEcUE379yRiFQN+66F7tj5/y9E2y/V1u/PrrF5c4TqDM+PUnYxQnUPAVHIJAwv5kIJC4i/aCbZPyiGLCrz8ZCCTuor1g26Q8opjw608GAom7aC/YNimPKCb8+pOBQOIu2gu2Tcojigm//mQgkLiL9kJuLeT49ScDgcRdtBdyayHHrz8ZCCTuor2QWws5fv3JQCBxF+2F3FrI8etPBgKJu2gv5NZCjl9/MhBI3MWYlNGR9ucDAom7QKAuEEjcBQJ1gUDiLsYrkI65v8TjlNci0JAw95d4nPJaBBoS5v4Sj1Nei0BDwtxf4nHKaxFoSJj7SzxOeS0CDQlzf4nHKa9FoCFh7i/xOOW1CDQkzP0lHqe8FoGGS+g8EUjcBQJFHqe8FoGGS+g8EUjcBQJFHqe8FoGGS+g8EUjcBQJFHqe8FoGGS+g8EUjcBQJFHqe8FoGGS+g8EUjcBQJFHqe81kmg7fuieHFVLovi9BKBeid0nsMTaHNWlsvz7YfLZin4Cg5BII3QeQ5PoJr1+e3b18VZ/W5RcfwT0pB7s/sg90w9OC5QdQhtnq8qjfYfByt8CCeQRug8h3gCLc/2Hi0QKDFJxymvdRJo+/58Lw8nUHKSjlNe6yTQsr7rWdR/3B1ACJSMpOOU1zoJ1EHwFRyCQBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bUINBaSjlNei0BjIek45bVjEij3FuYl+jiNINAkiT5OIwg0SaKP0wgCTZLo4zSCQJMk+jiNINAkiT5OIwg0SaKP0wgCTZLo4zSCQJMk+jiNJBXoWxfdq8Hk3sK89DPTLly2jxNoNEQfpxG+hE0S2yy8xmkEgSaJbRZe4zSCQJPENguvcRpBoElim4XXOI0g0CSxzcJrnEYmJFCerRofwnEKQaDZIRynEASaHcJxCkGg2SEcpxAEmh3CcQpBoNkhHKcQBJodwnEKQaDZIRynEASaHcJxCkGg2SEcpxAEmh3CcQpBoNkhHKcQBJodwnEKQaDZIRynEASaHcJxCkGg2SEcpxAEmh3CcQoZmUC5hz8FbBN12Qv37UOgSWCbqMteuG8fAk0C20Rd9sJ9+xBo8rjshfv2IdDkcdkL9+1DoMnjshfu24dAk8c2bYMUDruHQJPHNm2DFA67l0Yg61WnGyW0cdmniAIti9NLBJoCeQTavLiq3hBoAuQRaL0ob9+sqneKCsknwGyQCXRebj+u9h+ITiApKb77N6O8oX4z9f4EQqBh5w1VIPd7ICkT31AE2uP8FCZl4huKQB0EX8EhE99QBEKgUeUhkLgL8nLFIdCE8xBI3AV5ueIQaMJ5CCTugrxccQg04TwEEndBXq64YIE6Sf09evKGEodA5CEQefniEIi8IQgEcwWBIAgEgiAQCIJAIAgiXKBlUf+86+EPvfbKuv7VosU+tX92v0ygmkvSYp23fV8UL66StLhvL2AHgwXafqhjtR+775vtX1cqtX82xfPVvrkkLaq8s2pTz1O0uIsL28FggW7fvi7O9F/86ZtPl/vU3tn+Xf8+nGouRYsqr2Z9nqBFFRe2g8ECbSqH1+farx72TP0PVKUmCNsJtGsuTYv7iKrHJC3WcWE7GOUmerNIeQJ9urxLTRCW9gS6E2i5P3p6b/HOGf8dDD+BFvV5m/Ae6PaPq7vUBGm7f6Lp7oF2edv3dWdJWty1F7SDUZ7CFokeUXb883uT2j+7f6IJn8LqvOX9g2bvLe7bC9hB/h8IgkAgCAKBIAgEgiAQCIJAICe+P7o4sjA3EMgJBGqDQMe4eXzy4GInyvdH76r33z3938kvrw4W5m0QAh3jz9/K64dflC8X1dvN44dfrh9cNAu5LzAvCHSEm6cX5c2TV4cCPSt//PcVAikQ6Ai1IZovlU3VsfQMgRQIdISfT6BKIE6gexDoGOoeqNbm8wP1Jexf+kLuC8wLAh1DPYWVn09O/v304sfLB++e/Kd+CmsW5m0QArmyuweCOxDIFQTSQCAIAoEgCASCIBAIgkAgCAKBIAgEgiAQCIL4P0Bgen0g2mFrAAAAAElFTkSuQmCC" alt="plot of chunk block3"/> </p>

</body>

</html>

