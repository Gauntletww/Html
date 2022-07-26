const leng = htm.querySelectorAll(".chapter-manhwa-title");
   const time = htm.querySelectorAll(".chapter-release-date"); 
   const href = htm.querySelectorAll(".chapter-link a");
   var arr=[];
   var arrr=[];
 document.querySelector(".btn-doctu-dau").setAttribute("data", href[leng.length - 1].href);
document.querySelector(".btn-docmoinhat").setAttribute("data", href[0].href);
   var html = document.getElementById("datahere");
        for(var i=0;i<leng.length;i++){
            arr.push(leng[i].textContent)
            arrr.push(href[i].href)
         var li =document.createElement("li");
        li.innerHTML = html.innerHTML.replace(/{chap}/g, leng[i].textContent).replace(/{time}/g, time[i].textContent).replace(/{url}/g, href[i].href);
        document.getElementById("append").appendChild(li);
        }
        var inf = document.querySelectorAll(".inf");
        for(var j=0;j<inf.length;j++){
       inf[j].addEventListener("click", function() {
           localStorage.setItem("selected", this.getAttribute("data"));
        window.open("https://mangareadhere.xyz/manga/QWNhZGVteQ" ).focus();
       })
       localStorage.setItem('title', JSON.stringify(arr));
       localStorage.setItem('url', JSON.stringify(arrr));
  
    }
        