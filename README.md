<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Career Guidance for Students</title>
<style>
    /* General Styles */
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        margin: 0;
        padding: 0;
        background: linear-gradient(to right, #f5f7fa, #c3cfe2);
        color: #333;
    }

    header {
        background: #4CAF50;
        color: white;
        text-align: center;
        padding: 40px 20px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    header h1 {
        font-size: 2.5rem;
        margin-bottom: 10px;
        letter-spacing: 1px;
    }

    header p {
        font-size: 1.2rem;
        font-weight: 300;
    }

    /* Career Cards */
    .career-options {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 30px 15px;
        gap: 20px;
    }

    .career-card {
        width: 95%;
        max-width: 700px;
        background: white;
        border-radius: 12px;
        box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        padding: 25px 20px;
        text-align: center;
        transition: transform 0.3s, box-shadow 0.3s;
        cursor: pointer;
        overflow: hidden;
        position: relative;
    }

    .career-card:hover {
        transform: translateY(-8px);
        box-shadow: 0 12px 30px rgba(0,0,0,0.25);
    }

    .career-card h2 {
        font-size: 1.8rem;
        margin-bottom: 15px;
    }

    .career-card p {
        font-size: 1rem;
        margin: 5px 0;
    }

    .career-card button {
        background-color: #4CAF50;
        color: white;
        border: none;
        padding: 12px 20px;
        margin-top: 15px;
        border-radius: 25px;
        font-weight: bold;
        cursor: pointer;
        transition: background 0.3s;
    }

    .career-card button:hover {
        background-color: #45a049;
    }

    .more-info {
        display: none;
        margin-top: 15px;
        font-size: 0.95rem;
        line-height: 1.5;
        text-align: left;
        color: #555;
    }

    /* Color-coded cards */
    #engineering { background: #e3f2fd; border-left: 5px solid #2196F3; }
    #medical { background: #fce4ec; border-left: 5px solid #e91e63; }
    #arts { background: #fff3e0; border-left: 5px solid #ff9800; }
    #commerce { background: #e8f5e9; border-left: 5px solid #4caf50; }

    /* Footer */
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 25px 10px;
        font-size: 0.95rem;
    }

    footer a {
        color: #4CAF50;
        text-decoration: none; 
        font-weight: bold;
    }

    footer a:hover {
        text-decoration: underline;
    }
</style>
</head>
<body>

<header>
    <h1>Career Guidance for Students</h1>
    <p>Explore • Learn • Choose the Right Career Path</p>
</header>

<section class="career-options">
    <div class="career-card">
        <h2>🔧 Engineering</h2>
        <p><strong>After 10th:</strong> NEON (JEE Mains)</p>
        <p><strong>After 12th:</strong> CSE, ECE, Mechanical, Civil</p>
        <button onclick="showMore('eng-info')">Learn More</button>
        <p id="eng-info" class="more-info">Engineering is a dynamic field involving the design, development, and maintenance of machines, structures, and software. It offers careers in Computer Science, Electronics, Mechanical, Civil, and more.</p>
    </div>

    <div class="career-card">
        <h2>🩺 Medical</h2>
        <p><strong>After 10th:</strong> LEO (EAMCET)</p>
        <p><strong>After 12th:</strong> MBBS, BDS, Nursing, Pharmacy</p>
        <button onclick="showMore('med-info')">Learn More</button>
        <p id="med-info" class="more-info">Medical careers focus on healthcare, medicine, and wellness. Options include MBBS, Dentistry, Nursing, Pharmacy, and other allied health professions.</p>
    </div>

    <div class="career-card">
        <h2>🎨 Arts & Humanities</h2>
        <p><strong>After 10th:</strong> Choose Arts Stream</p>
        <p><strong>After 12th:</strong> BA, Journalism, Psychology</p>
        <button onclick="showMore('arts-info')">Learn More</button>
        <p id="arts-info" class="more-info">Arts & Humanities emphasize creativity, critical thinking, and human culture. Fields include Literature, Psychology, Journalism, History, and Sociology.</p>
    </div>

    <div class="career-card">
        <h2>💼 Commerce & Management</h2>
        <p><strong>After 10th:</strong> Commerce Stream</p>
        <p><strong>After 12th:</strong> BCom, CA, MBA</p>
        <button onclick="showMore('com-info')">Learn More</button>
        <p id="com-info" class="more-info">Commerce and Management careers revolve around business, finance, accounting, and leadership. Popular paths include Chartered Accountancy, Business Administration, and Management roles.</p>
    </div>
</section>

<footer>
    <h3>Contact Us</h3>
    <p>Email: <a href="mailto:careerhelp@gmail.com">careerhelp@gmail.com</a> | Mobile: 9908164728</p>
    <p>© 2025 Career Guidance Website | Student Project</p>
</footer>

<script>
function showMore(id) {
    const info = document.getElementById(id);
    info.style.display = info.style.display === "block" ? "none" : "block";
}
</script>

</body>
</html>
