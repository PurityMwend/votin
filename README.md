<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            text-align: center;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;

        h1 {
            font-size: 24px;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        select {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
        }

        button {
            background-color: #4607f4;
            color: #db8d8d;
            border: #8ee391;
            padding: 10px 20px;
            cursor: pointer;
        }

        #voting-result {
            display: none;
            background-color: #ed7e4b;
            color: #151ec5;
            margin-top: 10px;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1> Welcome! please cast your vote. </h1>
        <form id="voting-form">
            <label for="candidate">Select a candidate:</label>
            <select id="candidate" name="candidate">
                <option value="candidate1">Candidate 1</option>
                <option value="candidate2">Candidate 2</option>
                <option value="candidate3">Candidate 3</option>
            </select>
            <button type="button" id="vote-button">Vote</button>
        </form>
        <div id="voting-result">
            <p>Thank you for voting!</p>
        </div>
    </div>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const votingForm = document.getElementById("voting-form");
            const voteButton = document.getElementById("vote-button");
            const votingResult = document.getElementById("voting-result");

            voteButton.addEventListener("click", function() {
                const selectedCandidate = document.getElementById("candidate").value;
                // You would typically send the vote data to the server here.
                // For this example, we'll just display a "Thank you for voting" message.
                votingForm.style.display = "none";
                votingResult.style.display = "block";
            });
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            text-align: center;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        h1 {
            font-size: 24px;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        select {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
        }

        button {
            background-color: #7dabd7;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        #voting-result {
            display: none;
            background-color: #4CAF50;
            color: #fff;
            margin-top: 10px;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Campus Voting System</h1>
        <form id="voting-form">
            <label for="candidate">Select a candidate:</label>
            <select id="candidate" name="candidate">
                <option value="candidate1">Cynthia</option>
                <option value="candidate2">waithera</option>
                <option value="candidate3">Caleb</option>
            </select>
            <button type="button" id="vote-button">Vote</button>
        </form>
        <div id="voting-result">
            <p>Thank you for voting!</p>
        </div>
    </div>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const votingForm = document.getElementById("voting-form");
            const voteButton = document.getElementById("vote-button");
            const votingResult = document.getElementById("voting-result");

            voteButton.addEventListener("click", function() {
                const selectedCandidate = document.getElementById("candidate").value;
                // You would typically send the vote data to the server here.
                // For this example, we'll just display a "Thank you for voting" message.
                votingForm.style.display = "none";
                votingResult.style.display = "block";
            });
        });
    </script>
</body>
</html>
