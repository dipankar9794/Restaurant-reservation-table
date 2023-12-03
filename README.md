# demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Your Seat</title>
</head>
<style>
    *{
        box-sizing: ;
        border-box;
        padding: 0;
        margin: 0;
    }
    body{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        
    }
    .banner{
        min-height: 100vh;
        background: linear-gradient(rgb(0,0,0,0.5),rgba(0,0,0,0.5)),url();
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: #fff;
        padding-bottom: 20px;
    }
    .card-container{
        display: grid;
        grid-template-columns: 420px 420px;
    }
    .card-image{ 
        background:url(res.jpg);

    }
    .banner h2{
        padding-bottom: 40px;
        margin-bottom: 20px;
    }
    .card-content{
        background-color: #fff;
        height: 330px;
    }
    .card-content h3{
        text-align: center;
        color: #000;
        padding: 25px 0 10px 0;
        font-size: 26px;
        font-weight: 500px;
    }
    .form-row{
        display: flex;
        width: 90%;
        margin: 0 auto;
    }
    form select,form input{
        display: block;
        width: 100%;
        margin: 15px 12px;
        padding: 5px;
        font-size: 15px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        outline: none;
        border:none;
        border-bottom: 1px solid#eee;
        font-weight: 300;
    }
    form input[type=text],form input[type = number],form input::placeholder,
    select{
        color: #9a9a9a;
    } 
    form input[type=
    submit]{
        color:wheat;
        background: #f2745f;
        padding: 12px 0;
        border-radius: 4px;
        cursor: pointer;
    }
    video{
         height: 100%;
         width: 100%;
         object-fit: cover;position: fixed;
         z-index: -1;
        }

        
    
</style>
<body>
    <video autoplay loop muted src="https://dm0qx8t0i9gc9.cloudfront.net/watermarks/video/Vd3bj2jPe/videoblocks-6216b23c5b317a1c95da65cb_sqthgpjgq__ea2e2cf6366720cd60a1cef8a7f5ac61__P360.mp4"></video>
   <section class="banner">
    <h2>Book Your Table Now</h2>
    <div class="card-container"></div>
    <div class="card-content">
        <h3>Reservation</h3>
        <form>
            <div class="form-row">
                <select name="days">
                    <option value="day-select">select Day</option>
                    <option value = "sunday">Sunday</option>
                    <option value = "monday">Monday</option>
                    <option value="tuesday">Tuesday</option>
                    <option value="wednesday">Wednesday</option>
                    <optIon value="thursday">Thursday</optIon>
                    <option value="friday">Friday</option>
                    <option value="saturday">Saturday</option>
                </select>
                <select name="hours">
                    <option value="hour-select">Select Hour</option>
                    <option value="10">10:00</option>
                    <option value="10">11:00</option>
                    <option value="10">12:00</option>
                    <option value="10">13:00</option>
                    <option value="10">14:00</option>
                    <option value="10">15:00</option>
                    <option value="10">16:00</option>
                    <option value="10">17:00</option>
                    <option value="10">18:00</option>
                    <option value="10">19:00</option>
                    <option value="10">20:00</option>

                    
                </select>

            </div>
            <div class="form-row"><input type="text" placeholder="Full Name">
            <input type ="text" placeholder="Phone Number"></div>
            <div class = "form-row"><input type="number" placeholder="How Many Persons" min="1">
            <input type= "submit" value ="BOOK TABLE"></div>
        </form>
    </div>
   </section> 
</body>
</html>
