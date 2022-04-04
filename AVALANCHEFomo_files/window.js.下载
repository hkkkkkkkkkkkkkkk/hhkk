window.addEventListener('load', onload);

 function onload() {

    let now = new Date().getTime()

    console.log("load")

    let hour = 60*60

    if(Math.abs(localStorage.getItem("NewsTime") - now )> hour*1000 ) {

        document.getElementById('id01').style.display='block'

        localStorage.setItem("NewsTime",now)

    }

    

   

    

}



// $("#close-news").on("click", function() {

//     $('#news-window').modal('hide')

// }) 



