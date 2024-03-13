<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #container{
            width: 100vw;
            height: 100vh;
            background-color: #A9C9FF;
            background-image: linear-gradient(180deg, #A9C9FF 0%, #FFBBEC 100%);
            display: flex;
            justify-content: center;
            align-items: center;

        }
        .card{
            width: 350px;
            height: 600px;
            border-radius: 20px;
            background-color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
           
        }
        .card img{
            height: 30%;
            width: 100%;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            
        }
        #textbox{
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        #leftbox{
            height: 100%;
            display: flex;

            align-items: center;
            gap: 15px;
        }
        #leftimage img{
            width: 2rem;
            height: 2rem;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
        }
        #amountbox{
            border-radius: 10px;
            width: 75%;
            height: 10%;
            background-color: rgb(77, 185, 215);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
           
        }
       
        #paymentbutton{
            width: 80%;
            height: 9%;
            background-color: rgb(19, 19, 91);
            border-radius: 10px;
            font-weight: bold;
        }
        #paymentcancel a{
            text-decoration: none;
            font-weight: bold;
            color: rgba(0, 0, 0, 0.945);
            font-size: large;
        }
    </style>
</head>
<body>
    <div id="container">
        <div class="card">
                <img src="aiimage.avif" alt="loading"> 
            


 
            <div id="textbox">
                <h2>ORDER SUMMARY</h2>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Earum non commodi maxime porro doloremque neque dicta et odit. Explicabo, optio?</p>
            </div>
            <div id="amountbox">
                <div id="leftbox">
                    <div id="leftimage">
                        <img src="aiiiicon.jpg" alt="loading">
                    </div>

                   
                        <p>Amount</p>
                        <p>$99</p>
                   
                </div>

                <div>
                    <a href="#">change</a>
                </div>
            </div>


            <button id="paymentbutton">Proceed to Submit</button>
            
            <div id="paymentcancel">
                <a href="#">Cancel</a>
            </div>
            
        </div>
    </div>
</body>
</html>
