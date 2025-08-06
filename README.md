<html>
    <head>
        <title>Id card</title>

        <style>
            boby {
                background-color: blue;
                font-family: arial,sans-serif;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
            }
            .card {
                background-color: whitesmoke;
                width: 300px;
                padding: 20px;
                text-align: center;
                border-radius: 18px;
                box-shadow: blue;
                transition: transform 0.5s;

            }
            .card:hover {
                transform: scale(1.05);
            }
            .card img {
                border-radius: 50%;
                border: 4px dedug-black;
                margin-bottom: 15px;
                width: 100px;
                height: 100px;
                object-fit: cover;
            }
            .card h2 {
                color:black;
               
                margin: 10px;
            }
            .card p {
                color: #777;
                font-size: 18px;
            }.card button {
                background: skyblue;
                padding: 10px 20px;
                border: none;
                color: rgb(167,11,167);
                font-size: 16px;
                border-radius: 25px;
                cursor: pointer;
                transition: background 0.5s;
            }
            .card button:hover {
                background: orangered;
            }

        </style>
    </head>
    <boby>
        <div class="card">
            <img src="sai link small.jpg"/>
        <h2>chsai</h2>
        <p>Student</p>
        <button>Click</button></div>
    </boby>
</html>
