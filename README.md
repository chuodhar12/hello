<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>


    <style>
        * {
            margin: 0;
            padding: 0;
        }



        body {
            background-color: gray;
            padding: 7px 5px;
            display: flex;

        }

        .card {
            background-color: white;
            height: 480px;
            width: 300px;
            border-radius: 10px;
            margin: 5px;


        }

        img {
            border-radius: 12px;
            height: 225px;
            width: 260px;
            padding: 6px;
        }

        .capsuls span {
            border: none;
            background-color: #ddd;
            padding: 5px 20px 0px 13px;

            padding-bottom: 4px;
            text-align: center;
            display: inline-block;
            margin: 2px 2px;
            border-radius: 16px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            color: rgb(143, 90, 158);

        }

        h2 {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: 1000;
            padding: 10px;
            font-family: ;
        }

        .button {
            border-radius: 20px;
            padding: 10px 10px;
            text-align: center;
            margin: 3px 2px;

        }

        .content {
            color: rgb(107, 107, 221);
            font-size: 15px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

        }

        .button button {
            padding: 5px 20px;
            padding-top: 4px;
            border-radius: 10px;
            border: none;
            background-color: aqua;
            color: blue;

        }

        button:hover {
            color: black;
        }

        .content p {
            text-align: center;

        }
    </style>
</head>

<body>
    <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRK6aaif6VBLI7FeglR42z8-Ij6J6S6fmxM16GmL99tJQ&s"
            alt="">
        <div class="capsuls">
            <span>Nature</span>
            <span>Sun</span>
        </div>
        <div class="bol">
            <h2>The Nature view</h2>
        </div>
        <div class="content">
            <p>Nature provides us air to breathe, water to drink, soil to make a home and the land to stay. It gives us
                fruits, vegetables and grains to eat. Nature is a precious gift given to us by God. Hence, we should
                enjoy .</p>
        </div>
        <div class="button"><button>read more</button></div>
    </div>
    <div class="card">
        <img
            src="data:image/jpeg;base64,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">
        <div class="capsuls">
            <span>Alone</span>
            <span>strong</span>
        </div>
        <div class="bol">
            <h2>The Alone boy</h2>
        </div>
        <div class="content">
            <p>“My alone time is for self-discovery and growth.” “I enjoy the silence and peace that solitude brings.”
                “I don't need someone to complete me, I am already whole.” “Being alone doesn't mean I'm lonely; it
                means I'm free.”</p>
        </div>
        <div class="button"><button>read more</button></div>
    </div>
    <div class="card">
        <img
            src="data:image/jpeg;base64,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"> 
            <div class="capsuls">
            <span>Lake</span>
            <span>water</span> </div>
        <div class="bol">
            <h2>The Lake View</h2>
        </div>
        <div class="content">
            <p>“"Once More to the Lake" is an essay that reflects upon White's memories of visiting the lake as a child and the memories he creates with his son many years later. White describes experiencing a sense.”</p>
        </div>
        <div class="button"><button>read more</button></div>
    </div>
   

</body>

</html>
