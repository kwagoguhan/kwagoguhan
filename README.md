<html>

<head>

    <title>Slider Show</title>
    <style>
        body {
            background-color: rgba(27, 31, 34, 0.85);
        }

        h1 {
            font-size: 2.1rem;
            line-height: 1.4;
            letter-spacing: 0.5rem;
            text-align: center;
            color: red;
            margin-top: 50px;
        }
        h3{
            
            color: pink;
        }

        p {
            color: white;
        }

        .maindiv {
            width: 30%;
            height: 500px;
            position: absolute;
            left: 50%;
            top: 80%;
            transform: translate(-50%, -80%);
            background-image: url('https://images.pexels.com/photos/2820876/pexels-photo-2820876.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
            background-size: 100% 100%;
            box-shadow: 1px 2px 10px 5px white;
            animation: slider 9s infinite linear;

        }

        @keyframes slider {
            1% {
                background-image: url('https://images.pexels.com/photos/2379179/pexels-photo-2379179.jpeg?auto=compress&cs=tinysrgb&w=400')
            }

            40% {
                background-image: url('https://images.pexels.com/photos/792777/pexels-photo-792777.jpeg?auto=compress&cs=tinysrgb&w=400');
            }


        }
    </style>

</head>

<body>

    <h1><span>About Your Love</span></h1>
    <p>
       <h3> Hey World's most beaatiful, cutest, sweetest and My <strong> Dear Junelle.</strong> <strong>I Love You</strong>
        from the core buttom of my heart and will always love you like that. I swear,I will hold your hand till the last
        breath of my life. I will never fade smile from your face.... Our relationship is a uniqe one, altho we fight like Tom & Jerry
        But our love is like Nobita and sizuka's.
        Only yours <strong>Junelle</strong></h3>
    </p>

    <div class="maindiv">



        <h1>LOVER'S IMAGE</h1>
    </div>
</body>

</html>
