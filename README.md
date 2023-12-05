<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookConnect</title>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "poppins", sans-serif;
        }
        body {
            min-height: 100vh;
            background: linear-gradient(to right, #3498db, #2c3e50);
            background-size: cover;
            background-position: center;
        }

        .header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 20px 100px;
            background: black;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 100;
        }

        .logo {
            font-size: 32px;
            color: rgb(0, 234, 255);
            text-decoration: none;
            font-weight: 700;
        }
        #navbar {
            position: sticky;
        }

        .navbar a {
            position: relative;
            font-size: 18px;
            color: #fff;
            font-weight: 500;
            text-decoration: none;
            margin-left: 40px;
        }

        .navbar a::before {
            content: '';
            position: absolute;
            top: 100%;
            left: 0;
            width: 0;
            height: 2px;
            background: #fff;
            transition: .3s;
        }

        .navbar a:hover::before {
            width: 100%;
        }

        #books {
            text-align: center;
            padding: 20px;
        }

        #books .images {
            width: 23%;
            min-width: 250px;
            padding: 10px 12px;
            border: 2px solid green;
            border-radius: 10px;
            cursor: pointer;
            box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.02);
            margin: 15px 0;
            position: relative;
            background-color: white;
        }

        #books .images:hover {
            box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.02);

        }

        #books .images img {
            width: 100%;
            border-radius: 20px;
        }

        #books .images .des {
            text-align: center;
            pad: 10px 0;
        }
        #books .probooks {
            display: flex;
            justify-content: space-between;
            padding-top: 20px;
            flex-wrap: wrap;
        }

    </style>
</head>
<body>
<section id="navbar">
    <header class="header">
        <a href="Home.html" class="logo">BookConnect</a>
        <nav class="navbar">
            <a href="Home.html">Home</a>
            <a href="Library.html" target="_self">Library</a>
            <a href="Groups.html" target="_self">Groups</a>
            <a href="More.html" target="_self">More</a>
            <a href="Login.html" target="_self">Login</a>
        </nav>
    </header>
</section><br><br><br><br><br><br>


<section id="books">
        <h2>Some Featured Books</h2>
        <div class="probooks">
            <div class="images">
                <a href="The-Psychology-of-Money-PDF.pdf"><img src="moneybook" alt=""></a>
                <div class="des">
                    <h5>The Pyschology Of moneybook</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="atomic" alt="">
                <div class="des">
                    <h5>Atomic Habits</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="monk" alt="">
                <div class="des">
                    <h5>THINK LIKE A MONK</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="win" alt="">
                <div class="des">
                    <h5>How To Win Friends And Influence People</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

        </div>
</section>

<section id="books">
    <div class="probooks">
        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

    </div>
</section>
</body>
</html>
