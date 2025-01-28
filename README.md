<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>New Year's Celebration</title>
    <style>
        body {
            font-family: fantasy, sans-serif;
            margin:auto;
            padding: 15px;
            background-color: red;
            color:black;
            border: 30px dotted rgb(255, 183, 0);
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0,0.1);
        }

        h1 {
            text-align: center;
            color: red;
            background-color:yellow;
            padding:10px 0px 10px 2;
            border:10px dotted rgb(17, 128, 14);
             text-shadow:-3px 3px 2px #000;
            
         }
        
        
        p {
            text-align:center;
            
        }

        .event-details {
         margin-bottom: 20px;
            
        }

        .event-details p {
            margin: 10px 0;
            background-color:pink; 
        }

        .guest-list {
            margin-top: 20px;
            text-align: center;
             color: yellow;
            background-color:red;
            font-family: fantasy,san-serif;
            text-shadow:-3px 3px 2px #000;
       }

        .guest-list ul {
            list-style-type: none;
            padding: 0;
            
        }

        .guest-list li {
            padding: 10px;
            border-bottom: 1px solid ;
            border:frame;
             border-radius: 50px;
            

        }

        .rsvp-button {
            display: block;
            width: 100%;
            text-align: center;
            padding: 10px;
            font-size: 16px;
            color: white;
            background-color: red;
            border:frame;
            border-radius: 20px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .rsvp-button:hover {
            background-color:grey;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>New Year's Celebration</h1>

        <div class="event-details">
            <p><strong>Date:</strong> Wednesday, January 1, 2025</p>
            <p><strong>Time:</strong> 6:00 PM - Midnight</p>
            <p><strong>Location:</strong> Hampstead Heath, London</p>
            <em><p>Celebrate the start of the new year with us at Hampstead Heath! Enjoy live music, fireworks, and delicious treats as we welcome 2025 together.</p></em>
        </div>

        <div class="guest-list">
            <h2>Guest List</h2>
            <ul>
                <li>J C</li>
                <li>T S</li>
                <li>E J</li>
            </ul>
        </div>

        <button class="rsvp-button" onclick="rsvp()">RSVP Now</button>
    </div>

    <script>
        function rsvp() {
            alert('Thank you for your RSVP! We look forward to seeing you at the event.');
        }
    </script>
</body>
</html>
