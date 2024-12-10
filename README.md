<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Abdul Wasay</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Me</h1>
    </header>
    <section class="profile-card">
        <img src="placeholder.jpg" alt="Placeholder for Abdul Wasay" class="profile-image">
        <div class="profile-info">
            <h2>Abdul Wasay</h2>
            <p><strong>Year of Study:</strong> 2026</p>
            <p><strong>Degree:</strong> BSc Computer Science</p>
        </div>
    </section>
</body>
</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    padding: 20px;
}

/* Header Styling */
header {
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2rem;
    color: #2c3e50;
}

/* Profile Card Styling */
.profile-card {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 350px;
    text-align: center;
    padding: 20px;
}

.profile-image {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 15px;
    border: 3px solid #2c3e50;
}

.profile-info h2 {
    font-size: 1.5rem;
    color: #34495e;
    margin-bottom: 10px;
}

.profile-info p {
    font-size: 1rem;
    margin-bottom: 5px;
    line-height: 1.5;
}
