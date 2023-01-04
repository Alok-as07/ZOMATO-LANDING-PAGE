

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zomato-page</title>
    <link rel="stylesheet" href="style.css">

    <link rel="icon" href="https://b.zmtcdn.com/images/logo/zomato_logo_2017.png" type="image/icon type">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
        
        <style>
        Skip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@Alok-as07 
Alok-as07
/
ZOMATO-LANDING-PAGE
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
ZOMATO-LANDING-PAGE/style.css
@Alok-as07
Alok-as07 first comit
Latest commit 260819e 2 weeks ago
 History
 1 contributor
505 lines (478 sloc)  10.1 KB

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

body{
    margin: 0;
    padding: 0;
    font-family: 'poppins',sans-serif;
    /* background-color: blue; */
    
}
header{
    width: 100%;
    height: 40vw;
    overflow: hidden;
    position: relative;
    object-fit: cover;
    margin-bottom: 2rem;
}
.header-image{
    position: absolute;
    width: 100%;
    top: -20vh;
    z-index: -1;
}
.header-image img{
    width: 100%;
}
.nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    font-size: 1.1rem;
    margin: 0 48px;
    padding-left: 150px;
    padding-right: 150px;
}
.nav-bar{
    list-style: none;
    font-weight:300;
    display: flex;
    gap: 2rem;
}
.head{
    display: flex;
    flex-direction: column;
    top: 70vh;
    left: 50%;
    align-items: center;
    align-content: center;
}
.logo img{
   padding-top: 7vh;
    width: 300px;
    padding-left: 34%;
}
.logo h3{
    color: white;
    font-size: 35px;
    font-weight: lighter;
}
.search{  
      display:flex;
      width: 55vw;
      height: 42px;
      align-items: center;
      border-radius: 10px;
      background: white;
      padding: 5px 4px;
}
.search .search-item{
    display: flex;
    align-items: center;
    margin-left: 10px;
}
.search .search-item p{
    color: grey;
    font-size: 100;
    font-weight: lighter;
    font-family: 'poppins' sans-serif;
    border-right: 1.5px solid rgba(128, 128, 128, 0.7);
    padding-right: 100px;
    padding-left: 10px;
    font-size: 100;
}
.search .search-item input{
    outline: none;
    border: none;
    padding-left: 10px;
    font-size: 15px;
    width: 300px;
    font-weight: lighter;
    font-family: 'poppins' sans-serif;
}
.search .search-item:first-child{
    width: 30%;
    color: rgb(255, 126, 139);
}
.search .search-item:last-child{
    color: grey;
    font-size: larger;
    font-weight: 100;

}
.nav:hover{
    cursor:pointer ;
}
.section-1{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 4rem;
}
.section-1 .section-1-item {
    position: relative;
    width: 22rem;
    height: 200px;
    margin: 3px 10px;
    overflow: hidden;
    border-radius: 10px;
    background-color: white;
    border: 1px solid rgba(128, 128, 128, 0.2);
    transition: all 0.4s;

}
.section-1  .section-1-item img{
    width: 100%;
    height: 300px;
}
.section-1  .section-1-item .items-details{
    position: absolute;
    bottom: 0px;
    align-items: center;
    background-color: white;
    height: 30%;
    width: 100%;
    z-index: 1;

}
.section-1  .section-1-item .items-details p{
    /* text-align: center; */
    margin: 2px 0;
    margin-left: 1rem;
    /* box-shadow: 0px 1px 2px rgba(207, 207, 207, 0.8); */
}
.p-head{
    
    font-weight: 400;
    font-size: 1.2rem;

}
.p-subhead{
    color: rgb(128, 128, 128);
}
.section-1  .section-1-item:hover{
    box-shadow: 0px 5px 7px rgba(207, 207, 207, 1);
    transform:scale(1.05,1.05);   
    
}
.section-2{
    width: 75%;
    margin: 0 auto;
    margin-bottom: 4rem;


}
.section-2-heading{
    font-size: 2rem;
    line-height: 1.2;
    font-weight: 400;
}
.section-2 .section-2-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    
}
.section-2-items{
    justify-content: space-between;
    border: 2px solid rgba(128, 128, 128, 0.2);
    padding: 3px;
    padding-top: 0px;
    width: 30%;
    height: rem;
    margin-bottom: 20px;
    border-radius: 5px;
}
.section-2 .section-2-container .section-2-items .section-2-item{
    width: 80%;
    max-width: 26%;
    margin-bottom: 20px;
}
.item-head
{
   padding-left: 5px;
   margin-bottom: 2px;
   padding-top: 1px;
   font-size: 19px;
   font-weight: lighter;
}
.item-subhead {
    margin: 5px 5px;
    color: rgba(128, 128, 128, 0.9);
}
.section-4{
    height: 620px;
    background-color: rgb(255, 251, 247);
}
.section-4-container{
    width: 1000px;
    height: 100%;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
}
.section-4-img{
    width: 27%;
}
.section-4-img img{
    height: 290px;
}
.section-4-containt
{
    height: 400px;
    margin-top: -70px;
    width: 470px;

}
.section-4-containt .dowmload-head{
    font-size: 2.7rem;
    font-weight: 420;
    margin-top: 0;
    margin-bottom: 0;

}
.section-4-containt .dowmload-subhead{

    color: gray;
    
}

.section-4-input input[type="radio"]{
    appearance: none;
    -webkit-appearance: none;
    background-color: white;
    height: 15px;
    width: 15px;
    border: 2px solid #ef4f5f;
    border-radius: 50%;
    
}
.section-4-input input[type="radio"]:checked{
    appearance: none;
    -webkit-appearance: none;
    background-color: #ef4f5f;
    border: 2px solid #ef4f5f;
    outline: 1px solid #ef4f5f;
    outline-offset: 3px;
    transition: 120ms ease-in-out;
    height: 15px;
    width: 15px;
    border-radius: 50%;
    justify-content: space-between;
}
.section-4-containt .section-4-input .input-mail-or-phone #email{

    padding: 1.3rem 1.2rem;
    margin-top: 20px;
    height: 3.0rem;
    background: rgb(255, 255, 255);
    border: 0.1rem solid rgba(207, 207, 207,0.7);
    font-size: 17px;
    width: 60%;
    outline: none;
    box-sizing: border-box;
    border-radius: 0.5rem;
    color: rgb(28, 28, 28);
}
.section-4-containt .section-4-input .input-mail-or-phone #email::placeholder{
    color: rgba(128, 128, 128, 0.6);
    font-size: 18px;

}
.section-4-containt .section-4-input #box2{
    margin-left: 3.2rem;
}
.section-4-containt .section-4-input .input-radio label{
    font-weight: 400;
    color: rgba(12, 12, 12,0.7);
    padding-left: 5px;
} 
.section-4-containt .section-4-input .input-mail-or-phone .button{
    height: 2.99rem;
    width: 10rem;
    border-radius: 5px;
    background-color: #ef4f5f;
    border: none;
    color: white;
    font-size: 17px;
    font-weight: lighter;
    cursor: pointer;
}
.section-4-containt .section-4-download p{

    color: rgba(128, 128, 128, 0.9);
    font-size: 15px;
    padding-left: 11px;
}
.section-4-containt .section-4-download
{
    width: 500px;
}
.section-4-containt .section-4-download img{
    width: 9rem;
    padding: 10px;
}
@media screen and (max-width:1350px) and (min-width:950px) {
    header {
        width: 120%;
        height: 25rem;
        overflow: hidden;
        position: relative;
        object-fit: cover;
        margin-bottom: 2rem;
    }
    .logo img{
        padding-top: 7vh;
         width: 300px;
         padding-left: 25%;
     }
     .logo h3{
         color: white;
         font-size: 1.5rem;
         font-weight: lighter;
     }
     .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        font-size: 0.7rem;
        margin: 0 48px;
        padding-left: 150px;
        padding-right: 150px;
    }
    .section-1 {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 4rem;
        margin-left: 9rem;
    }
    .section-2 {
        width: 75%;
       
        margin-left: 13rem;
    }
    
}
@media screen and (max-width:950px) and (min-width:900px){

    header {
        width: 120%;
        height: 25rem;
        overflow: hidden;
        position: relative;
        object-fit: cover;
        margin-bottom: 2rem;
    }
    .logo img{
        padding-top: 7vh;
         width: 300px;
         padding-left: 25%;
     }
     .logo h3{
         color: white;
         font-size: 1.5rem;
         font-weight: lighter;
     }
     .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        font-size: 0.7rem;
        margin: 0 48px;
        padding-left: 150px;
        padding-right: 150px;
    }
    .section-1 {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 4rem;
        margin-left: 9rem;
    }
    .section-2 {
        width: 75%;
       
        margin-left: 13rem;
    }
}
@media screen and (max-width:899px) and (min-width:225px)
{
    body{
        width: 900px;
    }
    header {
        width: 110%;
        height: 25rem;
        overflow: hidden;
        position: relative;
        object-fit: cover;
        margin-bottom: 2rem;
    }
    .logo img{
        padding-top: 7vh;
         width: 300px;
         padding-left: 25%;
     }
     .logo h3{
         color: white;
         font-size: 1.5rem;
         font-weight: lighter;
     }
     .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        font-size: 0.7rem;
        margin: 0 48px;
        padding-left: 150px;
        padding-right: 150px;
    }
    .search .search-item input{
        outline: none;
        border: none;
        padding-left: 10px;
        font-size: 15px;
        width: 70px;
        font-weight: lighter;
        font-family: 'poppins' sans-serif;
    
    }
    .section-1 {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 4rem;
        margin-left: 7rem;
    }

}
@media screen and (max-width:224px) and (min-width:100px)
{
    body{
        width: 900px;
    }
    header {
        width: 110%;
        height: 25rem;
        overflow: hidden;
        position: relative;
        object-fit: cover;
        margin-bottom: 2rem;
    }
    .logo img{
        padding-top: 7vh;
         width: 300px;
         padding-left: 25%;
     }
     .logo h3{
         color: white;
         font-size: 1.5rem;
         font-weight: lighter;
     }
     .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        font-size: 0.7rem;
        margin: 0 48px;
        padding-left: 150px;
        padding-right: 150px;
    }
    .search .search-item input{
        outline: none;
        border: none;
        padding-left: 10px;
        font-size: 15px;
        width: 70px;
        font-weight: lighter;
        font-family: 'poppins' sans-serif;
    
    }
    .section-1 {
        display: grid;
        justify-content: center;
        align-items: center;
        margin-bottom: 4rem;
        margin-left: 7rem;
    }
}

        </style>

</head>

<body>
    <header>
        <div class="nav">
            <div>
                <p><i class="fa-solid fa-mobile-alt"></i> Get the App</p>
            </div>
            <ul class="nav-bar">
                <li>Investor Relations</li>
                <li>Add Restaurant</li>
                <li>Log in</li>
                <li>sign up</li>
            </ul>
        </div>
        <div class="head">
            <div class="logo">
                <img src="https://b.zmtcdn.com/web_assets/8313a97515fcb0447d2d77c276532a511583262271.png" alt="">
                <h3>Discover the best food and drink in your  <strong style="font-weight: 500;">Bhubaneswar</strong></h3>
            </div>
            <div class="search">
                <div class="search-item">
                    <i class="fa fa-map-marker-alt"></i>
                    <p>Bhubaneswar</p>
                </div>
                <div class="search-item">
                    <i class="fas fa-search"></i>
                    <input type="text" placeholder="Search for a Restaurant,cuisine or a dish">
                </div>
            </div>
        </div>
        <div class="header-image">
            <img src="https://b.zmtcdn.com/web_assets/81f3ff974d82520780078ba1cfbd453a1583259680.png" alt="">
        </div>
    </header>

    <section class="section-1">
        <div class="section-1-item">
            <div class="items-details">
                <p class="p-head">Order Online </p>
                <p class="p-subhead">Stay home and order to your doorstep</p>
            </div>
            <img src="https://b.zmtcdn.com/webFrontend/e5b8785c257af2a7f354f1addaf37e4e1647364814.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*"
                alt="">

        </div>
        <div class="section-1-item">
            <div class="items-details">
                <p class="p-head">Dining</p>
                <p class="p-subhead">View the city's favourite dining venues</p>
            </div>
            <img src="https://b.zmtcdn.com/webFrontend/d026b357feb0d63c997549f6398da8cc1647364915.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*"
                alt="">
        </div>
        <div class="section-1-item">
            <div class="items-details">
                <p class="p-head">Nightlife & Club</p>
                <p class="p-subhead"> Explor the city's top nightlife outlets</p>
            </div>
            <img src="https://b.zmtcdn.com/webFrontend/d9d80ef91cb552e3fdfadb3d4f4379761647365057.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*"alt="">
        </div>

    </section>
    <section class="section-2">
        <div class="section-2-heading">
            <p>Popular Location in around the  <strong style="font-weight: 500;">Bhubaneswar</strong>  </p>
        </div>
        <div class="section-2-container">
            <div class="section-2-items">
                <p class="item-head">Patia</p>
                <p class="item-subhead">519 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Chandrashekharpur</p>
                <p class="item-subhead">260 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Sahid Nagar</p>
                <p class="item-subhead">185 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Jaydev vihar</p>
                <p class="item-subhead">94 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Nayapali</p>
                <p class="item-subhead">136 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Kharabela Nagar</p>
                <p class="item-subhead">143 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Unit 4</p>
                <p class="item-subhead">71 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Lakshmi Sagar</p>
                <p class="item-subhead">127 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Gajapati Nagar</p>
                <p class="item-subhead">21 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Bapuji Nagar</p>
                <p class="item-subhead">53 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head">Baramunda</p>
                <p class="item-subhead">86 places</p>
            </div>
            <div class="section-2-items">
                <p class="item-head" style="cursor:pointer"> see more <i class="fa-sharp fa-solid fa-angle-down" style="padding-left: 5px; color: grey;"></i></p>
                
                <!-- <p class="item-subhead">388 places</p> -->
            </div>
        </div>

    </section>

    <section class="section-4">
        <div class="section-4-container">
            <div class="section-4-img">
                <img src="https://b.zmtcdn.com/data/o2_assets/a500ffc2ab483bc6a550aa635f4e55531648107832.png" alt="">
            </div>
            <div class="section-4-containt">
                <p class="dowmload-head">Get the Zomato app</p>
                <p class="dowmload-subhead">We will send you a link, open it on your phone to download the app</p>
                <div class="section-4-input">
                    <div class="input-radio">
                        <input type="radio" id="box1" class="radio-box" name="emailorphone" value="Email" ><label for="Email">Email</label>
                        <input type="radio" id="box2" class="radio-box" name="emailorphone" value="Phonenumber" ><label for="Email">Phone</label>
                    </div>
                    <div class="input-mail-or-phone">
                        <input type="email" name="" id="email" placeholder="Email">
                        <button class="button">share app link</button>
                    </div>
                    
                </div>
                
                <div class="section-4-download">
                    <p>Download app from</p>
                    <img src="https://b.zmtcdn.com/data/webuikit/23e930757c3df49840c482a8638bf5c31556001144.png" alt="">
                    <img src="https://b.zmtcdn.com/data/webuikit/9f0c85a5e33adb783fa0aef667075f9e1556003622.png" alt="">
                </div>
            </div>
        </div>
    </section>

</body>

</html>
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
ZOMATO-LANDING-PAGE/projectzomato.html at master · Alok-as07/ZOMATO-LANDING-PAGE
