<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Challenge SNS</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        #login-screen, #app {
            max-width: 400px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        input, textarea, button {
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #007BFF;
            color: white;
            cursor: pointer;
            border: none;
        }
        button:hover {
            background-color: #0056b3;
        }
        #sns-section {
            margin-top: 20px;
            padding: 15px;
            background: #dff0d8;
            border-radius: 5px;
            display: none;
        }
        #sns-section a {
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div id="login-screen">
        <h2>ログイン</h2>
        <input type="text" id="username" placeholder="ユーザー名">
        <button onclick="login()">ログイン</button>
    </div>
    
    <div id="app" style="display: none;">
        <h2>今日のお題</h2>
        <p id="challenge-text">読み込み中...</p>
        <input type="file" id="upload-image">
        <textarea id="upload-text" placeholder="コメントを書く"></textarea>
        <button onclick="submitChallenge()">投稿</button>
        
        <div id="sns-section">
            <h2>SNSエリア</h2>
            <p>お題達成おめでとう！SNSが解放されました。</p>
            <a href="#">SNSを見る</a>
        </div>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", () => {
            const challenges = [
                "今日の空の写真を撮って投稿しよう！",
                "お気に入りの本を紹介しよう！",
                "今日のランチの写真を投稿しよう！"
            ];
            const challengeText = challenges[new Date().getDate() % challenges.length];
            document.getElementById("challenge-text").textContent = challengeText;
        });

        function login() {
            const username = document.getElementById("username").value;
            if (username) {
                localStorage.setItem("username", username);
                document.getElementById("login-screen").style.display = "none";
                document.getElementById("app").style.display = "block";
            } else {
                alert("ユーザー名を入力してください。");
            }
        }

        function submitChallenge() {
            const image = document.getElementById("upload-image").files[0];
            const text = document.getElementById("upload-text").value;
            if (image && text) {
                localStorage.setItem("challengeCompleted", true);
                document.getElementById("sns-section").style.display = "block";
                alert("お題を達成しました！SNSが解放されました。");
            } else {
                alert("画像とコメントの両方を投稿してください。");
            }
        }
    </script>
</body>
</html>
