<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Bio</title>
    <style>
        /* Base styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .github-bio {
            max-width: 400px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }

        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin: 0 auto 10px;
            border: 3px solid #333;
        }

        .name {
            font-size: 1.5rem;
            font-weight: bold;
            color: #333;
            margin: 10px 0;
        }

        .bio {
            font-size: 1rem;
            color: #666;
            margin-bottom: 15px;
        }

        .github-stats {
            display: flex;
            justify-content: space-around;
            margin: 15px 0;
        }

        .stat {
            text-align: center;
        }

        .stat-value {
            font-size: 1.2rem;
            font-weight: bold;
            color: #333;
        }

        .stat-label {
            font-size: 0.9rem;
            color: #888;
        }

        .github-link {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background-color: #333;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        .github-link:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <div class="github-bio">
        <img class="profile-pic" src="https://github.com/username.png" alt="Profile Picture">
        <div class="name">John Doe</div>
        <div class="bio">Full Stack Developer | Open Source Enthusiast | Coffee Lover</div>
        
        <div class="github-stats">
            <div class="stat">
                <div class="stat-value">50</div>
                <div class="stat-label">Repos</div>
            </div>
            <div class="stat">
                <div class="stat-value">150</div>
                <div class="stat-label">Followers</div>
            </div>
            <div class="stat">
                <div class="stat-value">200</div>
                <div class="stat-label">Following</div>
            </div>
        </div>
        
        <a href="https://github.com/username" class="github-link" target="_blank">View GitHub Profile</a>
    </div>

</body>
</html>
