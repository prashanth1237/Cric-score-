<!DOCTYPE html>
<html>
<head>
    <title>Cricket Scorecard</title>
    <style>
        .scorecard {
            width: 80%;
            margin: auto;
            border: 1px solid #ccc;
            padding: 20px;
        }
        .team {
            font-weight: bold;
            margin-bottom: 10px;
        }
        .player-row {
            display: flex;
            justify-content: space-between;
            padding: 5px;
        }
    </style>
</head>
<body>
    <div class="scorecard">
        <div class="team">India vs Australia</div>
        <div class="player-row">
            <span>Rohit Sharma</span>
            <span>56 (42)</span>
        </div>
        <!-- Add more players dynamically via JS -->
    </div>

    <script>
        // Fetch live scores from backend/API
        fetch('/api/live-scores')
            .then(response => response.json())
            .then(data => {
                // Update DOM dynamically
            });
    </script>
</body>
</html>
