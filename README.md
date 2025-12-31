<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anirudh Singh - GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .profile-header {
            text-align: center;
            padding: 40px 20px;
            background: rgba(30, 41, 59, 0.8);
            border-radius: 20px;
            margin-bottom: 40px;
            border: 1px solid #334155;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .greeting {
            font-size: 2.8rem;
            font-weight: 700;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #60a5fa, #34d399);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            display: inline-block;
        }
        
        .title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #cbd5e1;
        }
        
        .description {
            max-width: 800px;
            margin: 0 auto 30px;
            font-size: 1.2rem;
            color: #94a3b8;
        }
        
        .section {
            background: rgba(30, 41, 59, 0.8);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            border: 1px solid #334155;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .section-title {
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: #60a5fa;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section-title i {
            font-size: 1.5rem;
        }
        
        .tech-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        
        .tech-table th {
            background-color: #1e40af;
            color: white;
            text-align: left;
            padding: 15px;
            font-size: 1.1rem;
            border-radius: 8px 8px 0 0;
        }
        
        .tech-table td {
            padding: 15px;
            border-bottom: 1px solid #334155;
        }
        
        .tech-table tr:last-child td {
            border-bottom: none;
        }
        
        .tech-table tr:hover {
            background-color: rgba(59, 130, 246, 0.1);
        }
        
        .category {
            font-weight: 600;
            color: #34d399;
            width: 30%;
        }
        
        .focus-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 10px;
        }
        
        .focus-card {
            background: rgba(15, 23, 42, 0.7);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #60a5fa;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .focus-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .focus-icon {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #60a5fa;
        }
        
        .focus-title {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: #e2e8f0;
        }
        
        .focus-desc {
            color: #94a3b8;
            font-size: 0.95rem;
        }
        
        .exploring-list {
            list-style-type: none;
            padding-left: 0;
        }
        
        .exploring-list li {
            padding: 12px 0;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 15px;
            border-bottom: 1px solid #334155;
        }
        
        .exploring-list li:last-child {
            border-bottom: none;
        }
        
        .exploring-icon {
            font-size: 1.3rem;
            color: #34d399;
            width: 30px;
            text-align: center;
        }
        
        .contact-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        
        .contact-table td {
            padding: 15px;
            border-bottom: 1px solid #334155;
        }
        
        .contact-table tr:last-child td {
            border-bottom: none;
        }
        
        .contact-icon {
            font-size: 1.3rem;
            color: #60a5fa;
            width: 50px;
            text-align: center;
        }
        
        .contact-link {
            color: #60a5fa;
            text-decoration: none;
            transition: color 0.2s;
        }
        
        .contact-link:hover {
            color: #34d399;
            text-decoration: underline;
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            margin-top: 40px;
            padding: 20px;
            color: #94a3b8;
            border-top: 1px solid #334155;
            font-size: 1.1rem;
        }
        
        .quote-author {
            margin-top: 10px;
            color: #60a5fa;
            font-weight: 600;
        }
        
        @media (max-width: 768px) {
            .greeting {
                font-size: 2.2rem;
            }
            
            .title {
                font-size: 1.5rem;
            }
            
            .section {
                padding: 20px;
            }
            
            .tech-table th, .tech-table td {
                padding: 10px;
                font-size: 0.9rem;
            }
            
            .focus-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="profile-header">
            <h1 class="greeting">👋 Hi, I'm Anirudh Singh</h1>
            <h2 class="title">Cybersecurity Enthusiast & AWS Cloud Specialist</h2>
            <p class="description">
                I'm passionate about building secure, scalable systems and defending digital infrastructures. 
                I focus on ethical hacking, cloud security architecture, and developing applications with security-first principles.
            </p>
        </header>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-tools"></i> Tech Stack</h2>
            <table class="tech-table">
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Technologies & Tools</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="category">Languages</td>
                        <td>Java, Python, SQL, JavaScript, HTML/CSS</td>
                    </tr>
                    <tr>
                        <td class="category">Security Tools</td>
                        <td>Nmap, Wireshark, Metasploit, Splunk, Snort</td>
                    </tr>
                    <tr>
                        <td class="category">Cloud & DevOps</td>
                        <td>AWS (EC2, S3, IAM, VPC, CloudFormation), Git, Linux</td>
                    </tr>
                    <tr>
                        <td class="category">Web Development</td>
                        <td>React, Node.js, MongoDB</td>
                    </tr>
                </tbody>
            </table>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-bullseye"></i> Focus Areas</h2>
            <div class="focus-grid">
                <div class="focus-card">
                    <div class="focus-icon">🔐</div>
                    <h3 class="focus-title">Penetration Testing & Vulnerability Assessment</h3>
                    <p class="focus-desc">Identifying and exploiting security vulnerabilities to strengthen defenses.</p>
                </div>
                <div class="focus-card">
                    <div class="focus-icon">☁️</div>
                    <h3 class="focus-title">AWS Cloud Security & Solution Architecture</h3>
                    <p class="focus-desc">Designing secure, scalable cloud infrastructures on AWS.</p>
                </div>
                <div class="focus-card">
                    <div class="focus-icon">🛡️</div>
                    <h3 class="focus-title">Application Security & OWASP Compliance</h3>
                    <p class="focus-desc">Building applications with security-first principles and OWASP standards.</p>
                </div>
                <div class="focus-card">
                    <div class="focus-icon">📡</div>
                    <h3 class="focus-title">OSINT & Cyber Threat Intelligence</h3>
                    <p class="focus-desc">Gathering and analyzing information for security insights and threat detection.</p>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-rocket"></i> Currently Exploring</h2>
            <ul class="exploring-list">
                <li>
                    <span class="exploring-icon">📚</span>
                    <span>Advancing my AWS Security & Solutions Architect certifications</span>
                </li>
                <li>
                    <span class="exploring-icon">🤖</span>
                    <span>Implementing ML for threat detection and automated security</span>
                </li>
                <li>
                    <span class="exploring-icon">🛠️</span>
                    <span>Contributing to open-source security projects and tools</span>
                </li>
            </ul>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-envelope"></i> Connect With Me</h2>
            <table class="contact-table">
                <tbody>
                    <tr>
                        <td class="contact-icon">📧</td>
                        <td>
                            <strong>Email:</strong> 
                            <a href="mailto:anirudhsingh2708@gmail.com" class="contact-link">anirudhsingh2708@gmail.com</a>
                        </td>
                    </tr>
                    <tr>
                        <td class="contact-icon">💼</td>
                        <td>
                            <strong>LinkedIn:</strong> 
                            <a href="https://linkedin.com/in/anirudh" target="_blank" class="contact-link">linkedin.com/in/anirudh</a>
                        </td>
                    </tr>
                    <tr>
                        <td class="contact-icon">🐙</td>
                        <td>
                            <strong>GitHub:</strong> 
                            <a href="https://github.com/anirudh" target="_blank" class="contact-link">github.com/anirudh</a>
                        </td>
                    </tr>
                </tbody>
            </table>
        </section>
        
        <div class="quote">
            <p>"Security is not a product, but a process."</p>
            <p class="quote-author">– Bruce Schneier</p>
        </div>
    </div>
</body>
</html>
