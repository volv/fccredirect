<html lang="en">
    <head>
        <title>Timestamp microservice</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    </head>
    <body>
        <div class="container">
            <h1 class="header">
                API Basejump: Timestamp microservice
            </h1>
            <blockquote>
                User stories:
                <ul>1) I can pass a string as a parameter, and it will check to see whether that string 
                contains either a unix timestamp or a natural language date (example: January 1, 2016)</ul>
                <ul>2) If it does, it returns both the Unix timestamp and the natural language form of that date.</ul>
                <ul>3) If it does not contain a date or Unix timestamp, it returns null for those properties.</ul>
            </blockquote>
            <h3>Example usage:</h3>
            <code>https://timestamp-ms.herokuapp.com/December%2015,%202015</code><br>
            <code>https://timestamp-ms.herokuapp.com/1450137600</code>
            <h3>Example output:</h3>
            <code>
                {
                  "unix": 1450137600,
                  "natural": "December 15, 2015"
                }
            </code>
        </div>
    </body>
</html>