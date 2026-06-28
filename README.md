* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-image: 
        linear-gradient(rgba(0, 0, 0, 0.07) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0, 0, 0, 0.07) 1px, transparent 1px),
        linear-gradient(180deg, #d32f2f 0%, #5f0101 100%);
    background-size: 40px 40px, 40px 40px, 100% 100%;
    background-attachment: fixed;
    color: #2d3748; 
    line-height: 1.6;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.full-width-banner {
    width: 100%;
    margin-bottom: 40px;
    transition: all 0.2s ease;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    border-bottom: 4px solid #fbc02d;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.03);
}

.banner-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 50px 20px;
}

.home-bg {
    background-image: linear-gradient(rgba(0, 0, 0, 0.65), rgba(0, 0, 0, 0.65)), url('home-banner.jpg');
}

.home-bg .banner-content h1 { 
    color: #ffffff; 
    text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3); 
}

.home-bg .banner-content p { 
    color: #e2e8f0; 
}

.banner-content h1 {
    font-weight: 800;
    margin-bottom: 12px;
    padding-left: 20px;
    font-size: 2.6rem;
}

.banner-content p {
    font-size: 1.15rem;
    max-width: 850px;
    line-height: 1.7;
    margin-bottom: 0;
    padding-left: 20px;
}

.card-banner {
    background-color: #ffffff;
    padding: 40px;
    border-radius: 12px;
    border: 1px solid #e2e8f0;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.02);
    margin-top: 20px;
    margin-bottom: 40px;
}

.card-banner h1 {
    color: #444444;
    font-size: 2.4rem;
    font-weight: 800;
    margin-bottom: 12px;
}

.card-banner p {
    color: #64748b;
    font-size: 1.15rem;
    max-width: 850px;
    line-height: 1.7;
    margin-bottom: 0;
}

a {
    color: #d32f2f; 
    text-decoration: none;
    font-weight: 600;
}

a:hover {
    text-decoration: underline;
}

nav {
    background-color: #ffffff; 
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08); 
    border-top: 4px solid #d32f2f; 
}

.brand-container {
    display: flex;
    align-items: center;
    gap: 10px;
}

.nav-logo-img {
    width: 65px !important;
    height: 65px !important;
    max-width: none !important;
    max-height: none !important;
    object-fit: contain;
}

.auth-logo-img {
    width: 130px !important;
    height: 130px !important;
    max-width: none !important;
    max-height: none !important;
    object-fit: contain;
    margin-bottom: 2px !important;
}

nav .logo {
    font-size: 1.4rem;
    font-weight: 800;
    color: #d32f2f; 
    letter-spacing: 1px;
}

nav ul {
    display: flex;
    list-style: none;
    align-items: center;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #4a5568; 
    font-weight: 600;
    padding: 8px 14px;
    border-radius: 6px;
    transition: all 0.2s ease;
}

nav ul li a:hover {
    background-color: #fffde7; 
    color: #d32f2f; 
    text-decoration: none;
}

nav ul li a.logout-btn {
    background-color: #d32f2f;
    color: #ffffff;
}

nav ul li a.logout-btn:hover {
    background-color: #b71c1c;
    color: #ffffff;
}

.auth-wrapper {
    display: flex;
    flex: 1;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.auth-container {
    width: 100%;
    max-width: 420px;
    background-color: #ffffff; 
    padding: 40px 30px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.05); 
    border-bottom: 4px solid #fbc02d; 
    text-align: center;
}

.auth-logo-img {
    width: 60px;
    height: 60px;
    object-fit: contain;
    margin-bottom: 15px;
}

.auth-container h2 {
    color: #d32f2f; 
    font-size: 1.8rem;
    font-weight: 800;
    margin-bottom: 5px;
}

.auth-container p {
    color: #718096;
    font-size: 0.95rem;
}

.form-group {
    margin-bottom: 20px;
    text-align: left;
}

.form-group label {
    display: block;
    margin-bottom: 6px;
    font-weight: 600;
    color: #4a5568;
    font-size: 0.9rem;
}

.form-group input {
    width: 100%;
    padding: 12px;
    border: 2px solid #e2e8f0; 
    background-color: #f8fafc;
    color: #2d3748;
    border-radius: 8px;
    font-size: 1rem;
    transition: border-color 0.2s;
}

.form-group input:focus {
    border-color: #fbc02d; 
    background-color: #ffffff;
    outline: none;
}

.btn-submit {
    display: inline-block;
    width: 100%;
    padding: 14px;
    background-color: #d32f2f; 
    color: #ffffff;
    border: none;
    border-radius: 8px;
    font-weight: 700;
    font-size: 1rem;
    cursor: pointer;
    text-align: center;
    box-shadow: 0 4px 12px rgba(211, 47, 47, 0.2);
    transition: background-color 0.2s;
}

.btn-submit:hover {
    background-color: #b71c1c; 
    color: #ffffff;
    text-decoration: none;
}

main {
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
}

h1 {
    color: #ffffff;
    font-size: 2.2rem;
    font-weight: 800;
    margin-bottom: 10px;
}

main > p {
    color: #64748b;
    font-size: 1.1rem;
    margin-bottom: 40px;
}

h2 {
    color: #fbc02d;
    font-size: 1.5rem;
    margin-bottom: 20px;
    padding-left: 0;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin-top: 20px;
}

.full-width-banner {
    width: 100%;
    background-image: 
        linear-gradient(rgba(0, 0, 0, 0.65), rgba(0, 0, 0, 0.65)), 
        url('banner.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
    border-bottom: 4px solid #fbc02d;
    margin-bottom: 40px;
}

.banner-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 60px 20px;
}

.banner-content h1 {
    color: #ffffff; 
    font-size: 2.8rem;
    font-weight: 800;
    margin-bottom: 12px;
    padding-left: 20px;
    text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); 
}

.banner-content p {
    color: #e2e8f0; 
    font-size: 1.2rem;
    max-width: 850px;
    line-height: 1.7;
    margin-bottom: 0;
    padding-left: 20px;
}

.card {
    background-color: #ffffff; 
    border: 1px solid #e2e8f0;
    border-radius: 10px;
    overflow: hidden;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.02);
    transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 20px rgba(0, 0, 0, 0.05);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 15px;
    background-color: #edf2f7; 
}

.card h3 {
    color: #2d3748;
    font-size: 1.25rem;
    margin-bottom: 10px;
}

.card p {
    color: #64748b;
    font-size: 0.95rem;
}

footer {
    text-align: center;
    padding: 30px;
    background-color: #ffffff;
    color: #718096;
    margin-top: 80px;
    font-size: 0.9rem;
    border-top: 1px solid #e2e8f0;
}
