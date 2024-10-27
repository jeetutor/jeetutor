* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

.profile-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.profile-card {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.profile-card img {
    width: 100%;
    border-radius: 50%;
    margin-bottom: 15px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}
