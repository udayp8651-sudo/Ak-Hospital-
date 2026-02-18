<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AK Hospital | Premium</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background: radial-gradient(circle at 20% 30%, rgba(0,212,255,0.15), transparent 40%),
            radial-gradient(circle at 80% 70%, rgba(255,0,150,0.15), transparent 40%),
            linear-gradient(135deg,#0f2027,#203a43,#2c5364);
color:white;
padding:40px;
}

header{
text-align:center;
margin-bottom:40px;
}

header h1{
font-size:38px;
font-weight:700;
letter-spacing:1px;
}

header p{
opacity:0.8;
margin-top:10px;
}

.card{
background:rgba(255,255,255,0.08);
backdrop-filter:blur(20px);
border:1px solid rgba(255,255,255,0.1);
padding:25px;
border-radius:20px;
margin-bottom:35px;
box-shadow:0 15px 40px rgba(0,0,0,0.4);
transition:0.4s ease;
}

.card:hover{
transform:translateY(-6px);
box-shadow:0 25px 60px rgba(0,0,0,0.6);
}

h2{
margin-bottom:20px;
font-weight:600;
letter-spacing:1px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;
}

.doctor-card{
background:rgba(0,0,0,0.35);
padding:18px;
border-radius:18px;
transition:0.4s;
border:1px solid rgba(255,255,255,0.08);
}

.doctor-card:hover{
transform:scale(1.03);
box-shadow:0 10px 30px rgba(0,0,0,0.5);
}

.doctor-card img{
width:100%;
height:230px;
object-fit:cover;
border-radius:14px;
margin-bottom:15px;
}

.doctor-card h3{
margin-bottom:6px;
font-weight:600;
}

.doctor-card p{
opacity:0.85;
font-size:14px;
}

ul{
list-style:none;
}

ul li{
padding:10px;
margin:8px 0;
background:rgba(0,0,0,0.35);
border-radius:10px;
border-left:4px solid #00c6ff;
}

.contact-box p{
margin:8px 0;
font-size:15px;
}
</style>
</head>
<body>

<header>
<h1>🏥 AK Hospital</h1>
<p>Premium Multi-Speciality Healthcare Center</p>
</header>

<!-- MD SECTION -->
<div class="card">
<h2>👨‍⚕️ Managing Director (MD)</h2>
<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1537368910025-700350fe46c7">
<h3>Dr. Rajesh Kapoor (MD)</h3>
<p><strong>Qualification:</strong> MBBS, MD (Cardiology)</p>
<p><strong>Experience:</strong> 20+ Years</p>
<p><strong>Specialization:</strong> Advanced Heart & Cardiac Surgery</p>
<p><strong>Email:</strong> md@akhospital.com</p>
</div>
</div>

<!-- DOCTOR LIST -->
<div class="card">
<h2>👨‍⚕️ Our Specialist Doctors</h2>

<div class="grid">

<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1559839734-2b71ea197ec2">
<h3>Dr. Neha Verma</h3>
<p>Neurologist</p>
<p>Experience: 12 Years</p>
<p>Expert in Brain & Spine Disorders</p>
</div>

<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1582750433449-648ed127bb54">
<h3>Dr. Aman Singh</h3>
<p>Orthopedic Surgeon</p>
<p>Experience: 10 Years</p>
<p>Joint Replacement Specialist</p>
</div>

<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1594824475317-6e1e7c5c7a74">
<h3>Dr. Priya Mehta</h3>
<p>Pediatrician</p>
<p>Experience: 8 Years</p>
<p>Child & Neonatal Care Expert</p>
</div>

<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e">
<h3>Dr. Kunal Joshi</h3>
<p>General Physician</p>
<p>Experience: 15 Years</p>
<p>Internal Medicine Specialist</p>
</div>

<div class="doctor-card">
<img src="https://images.unsplash.com/photo-1622253692010-333f2da6031d">
<h3>Dr. Anjali Rao</h3>
<p>Dermatologist</p>
<p>Experience: 9 Years</p>
<p>Skin & Cosmetic Treatment Expert</p>
</div>

</div>
</div>

<!-- DEPARTMENTS -->
<div class="card">
<h2>🏥 Hospital Departments</h2>
<ul>
<li>Cardiology & Heart Surgery</li>
<li>Neurology & Brain Care</li>
<li>Orthopedics & Joint Replacement</li>
<li>Pediatrics & Neonatal Care</li>
<li>Dermatology & Cosmetic Treatments</li>
<li>Emergency & Trauma Care (24/7)</li>
<li>Radiology & Advanced Diagnostics</li>
</ul>
</div>

<!-- CONTACT -->
<div class="card contact-box">
<h2>📞 Emergency & Contact</h2>
<p><strong>Emergency Helpline:</strong> +91 98765 43210</p>
<p><strong>Email:</strong> info@akhospital.com</p>
<p><strong>Address:</strong> Main City Center, India</p>
<p><strong>Working Hours:</strong> 24/7 Emergency Services Available</p>
</div>

</body>