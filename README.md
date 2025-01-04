<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Luiz Hamilton's GitHub Profile</title>
  <!-- Include Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-p6AaLfv1A61FcV1cV1f6sZqs2AOWoVppKxOQEmoIzYdja25I+N0YcSxqsXrHjk8l2+9ycic6I+NIMiKvo5a1Cg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <!-- Responsive Meta Tag -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
      padding: 20px;
    }

    /* Container */
    .container {
      max-width: 1200px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    /* Centered Text */
    .center {
      text-align: center;
    }

    /* Headings */
    h1, h2, h3 {
      margin-bottom: 10px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 2em;
      margin: 30px 0 10px;
      color: #0077B5; /* LinkedIn Blue */
    }

    h3 {
      font-size: 1.5em;
      margin-bottom: 20px;
      color: #555;
    }

    /* Paragraphs */
    p {
      margin-bottom: 20px;
      font-size: 1.1em;
    }

    /* Connect with Me Badges */
    .social-badges a {
      margin: 5px;
      display: inline-block;
      transition: transform 0.2s;
    }

    .social-badges a:hover {
      transform: scale(1.1);
    }

    /* Table Styling */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 30px;
    }

    th, td {
      padding: 15px;
      text-align: left;
      border: 1px solid #ddd;
      vertical-align: top;
    }

    th {
      background-color: #f4f4f4;
    }

    /* Repository Links */
    .repo-link {
      display: flex;
      align-items: center;
      gap: 10px;
      transition: transform 0.2s;
    }

    .repo-link:hover {
      transform: scale(1.02);
    }

    /* GitHub Statistics */
    .github-stats img {
      margin: 10px;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }

    /* Highlights and Contributions */
    ul {
      list-style-type: disc;
      margin-left: 20px;
    }

    /* Footer */
    footer {
      text-align: center;
      margin-top: 30px;
      font-size: 1em;
      color: #777;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      h1 {
        font-size: 2em;
      }

      h2 {
        font-size: 1.5em;
      }

      h3 {
        font-size: 1.2em;
      }

      table, thead, tbody, th, td, tr {
        display: block;
      }

      th {
        background-color: transparent;
        color: #555;
        font-size: 1.2em;
      }

      td {
        border: none;
        border-bottom: 1px solid #ddd;
        position: relative;
        padding-left: 50%;
      }

      td:before {
        position: absolute;
        top: 15px;
        left: 15px;
        width: 45%;
        padding-right: 10px;
        white-space: nowrap;
        font-weight: bold;
      }

      tr:nth-child(even) {
        background-color: #f9f9f9;
      }

      tr:hover {
        background-color: #f1f1f1;
      }

      /* Labeling table data for responsiveness */
      td:nth-of-type(1):before { content: "Repository"; }
      td:nth-of-type(2):before { content: "Description"; }
      td:nth-of-type(3):before { content: "Key Features"; }
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- Introduction Section -->
    <div class="center">
      <h1>👋 Hi There, I'm Luiz Hamilton (@brazilianscriptguy)</h1>
      <p>
        Welcome to my GitHub profile! I'm a passionate <strong>Cybersecurity Analyst</strong>, <strong>Senior IT Analyst</strong>, and 
        <strong>Systems Administrator</strong> with deep expertise in <strong>Windows Server</strong> and <strong>Workstation Administration</strong>. 
        I specialize in <strong>PowerShell</strong> and <strong>VBScript</strong> tools for advanced IT management, enabling seamless automation, compliance, 
        and security. My mission is to create efficient, secure, and automated IT environments for professionals and organizations worldwide.
      </p>
    </div>

    <hr>

    <!-- Connect with Me Section -->
    <h2>🌐 Connect with Me</h2>
    <p class="social-badges center">
      <a href="https://github.com/brazilianscriptguy" target="_blank" aria-label="GitHub">
        <img src="https://img.shields.io/badge/GitHub-@brazilianscriptguy-181717?style=for-the-badge&logo=github" alt="GitHub Badge">
      </a>
      <a href="https://www.patreon.com/c/brazilianscriptguy" target="_blank" aria-label="Patreon">
        <img src="https://img.shields.io/badge/Patreon-Support%20Me-red?style=for-the-badge&logo=patreon" alt="Patreon Badge">
      </a>
      <a href="https://x.com/brazscriptguy" target="_blank" aria-label="Twitter">
        <img src="https://img.shields.io/badge/X-@brazscriptguy-000000?style=for-the-badge&logo=x" alt="Twitter Badge">
      </a>
      <a href="https://www.linkedin.com/in/brazilianscriptguy/" target="_blank" aria-label="LinkedIn">
        <img src="https://img.shields.io/badge/LinkedIn-in/brazilianscriptguy-0077B5?style=for-the-badge&logo=linkedin" alt="LinkedIn Badge">
      </a>
      <a href="https://www.youtube.com/@brazilianscriptguy" target="_blank" aria-label="YouTube">
        <img src="https://img.shields.io/badge/YouTube-@brazilianscriptguy-FF0000?style=for-the-badge&logo=youtube" alt="YouTube Badge">
      </a>
      <a href="https://www.instagram.com/4tetraforensics" target="_blank" aria-label="Instagram">
        <img src="https://img.shields.io/badge/Instagram-@4tetraforensics-E4405F?style=for-the-badge&logo=instagram" alt="Instagram Badge">
      </a>
      <a href="https://wa.me/0029VaEgqC50G0XZV1k4Mb1c" target="_blank" aria-label="WhatsApp">
        <img src="https://img.shields.io/badge/WhatsApp-PowerShellBR-25D366?style=for-the-badge&logo=whatsapp" alt="WhatsApp Badge">
      </a>
      <a href="https://orcid.org/0000-0003-3705-7468" target="_blank" aria-label="ORCID">
        <img src="https://img.shields.io/badge/ORCID-0000--0003--3705--7468-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID Badge">
      </a>
      <a href="http://lattes.cnpq.br/0191525072495482" target="_blank" aria-label="Lattes CV">
        <img src="https://img.shields.io/badge/Lattes%20CV-0191525072495482-00A693?style=for-the-badge&logo=academia" alt="Lattes CV Badge">
      </a>
      <a href="mailto:luizhamilton.lhr@gmail.com" target="_blank" aria-label="Email">
        <img src="https://img.shields.io/badge/Email-luizhamilton.lhr@gmail.com-D14836?style=for-the-badge&logo=gmail" alt="Email Badge">
      </a>
    </p>

    <hr>

    <!-- My Repository Packages Section -->
    <h2>💻 My Repository Packages</h2>
    <h3>Ready-to-Download Solutions for Your IT Needs</h3>

    <table>
      <thead>
        <tr>
          <th>Repository</th>
          <th>Description</th>
          <th>Key Features</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/SysAdmin-Tools" target="_blank" class="repo-link" aria-label="SysAdminToolSet Repository">
              <i class="fas fa-tools" aria-hidden="true"></i>
              <img src="https://img.shields.io/badge/SysAdminToolSet-Tools-blue?style=flat&logo=windows" alt="SysAdminToolSet Badge">
            </a>
          </td>
          <td>
            Comprehensive tools for Windows Server and workstation administration.
          </td>
          <td>
            <ul>
              <li>Active Directory Management</li>
              <li>GPO Management</li>
              <li>Network Infrastructure Tools (DNS, DHCP, Certificates)</li>
              <li>Security and Optimization</li>
              <li>Complete ITSM Templates</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td>
            <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/BlueTeam-Tools" target="_blank" class="repo-link" aria-label="BlueTeam-Tools Repository">
              <i class="fas fa-shield-alt" aria-hidden="true"></i>
              <img src="https://img.shields.io/badge/BlueTeam-Forensics-orange?style=flat&logo=security" alt="BlueTeam-Tools Badge">
            </a>
          </td>
          <td>
            Toolkit for forensic analysis, threat detection, and incident response.
          </td>
          <td>
            <ul>
              <li>Incident Response Scripts</li>
              <li>Advanced Log Parsing</li>
              <li>Security Hardening Tools</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td>
            <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/ITSM-Templates-WKS" target="_blank" class="repo-link" aria-label="ITSM-Templates-WKS Repository">
              <i class="fas fa-laptop" aria-hidden="true"></i>
              <img src="https://img.shields.io/badge/ITSM-Templates-WKS-green?style=flat&logo=windows" alt="ITSM-Templates-WKS Badge">
            </a>
          </td>
          <td>
            Manage and enforce ITSM compliance on Windows 10/11 workstations.
          </td>
          <td>
            <ul>
              <li>PostIngress Scripts</li>
              <li>Configuration Audit Tools</li>
              <li>Customizable Modules</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td>
            <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/ITSM-Templates-SVR" target="_blank" class="repo-link" aria-label="ITSM-Templates-SVR Repository">
              <i class="fas fa-server" aria-hidden="true"></i>
              <img src="https://img.shields.io/badge/ITSM-Templates-SVR-purple?style=flat&logo=server" alt="ITSM-Templates-SVR Badge">
            </a>
          </td>
          <td>
            Templates and scripts for server hardening and ITSM compliance.
          </td>
          <td>
            <ul>
              <li>Server Hardening Scripts</li>
              <li>Policy Enforcement Templates</li>
              <li>Role-Specific Modules (DNS, File Server, IIS)</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td>
            <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/Core-ScriptLibrary" target="_blank" class="repo-link" aria-label="Core-ScriptLibrary Repository">
              <i class="fas fa-code" aria-hidden="true"></i>
              <img src="https://img.shields.io/badge/Core-ScriptLibrary-slategray?style=flat&logo=powershell" alt="Core-ScriptLibrary Badge">
            </a>
          </td>
          <td>
            A foundational library of PowerShell scripts for modular IT solutions.
          </td>
          <td>
            <ul>
              <li>Dynamic Automation</li>
              <li>Interactive GUIs</li>
              <li>Script Templates</li>
            </ul>
          </td>
        </tr>
      </tbody>
    </table>

    <!-- Latest Releases -->
    <p class="center">
      💡 <strong>Stay updated with the latest tools and improvements:</strong> 
      <a href="https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/releases" target="_blank">
        <img src="https://img.shields.io/github/v/release/brazilianscriptguy/Windows-SysAdmin-ProSuite?style=for-the-badge&label=Latest%20Releases&logo=github" alt="Latest Releases Badge">
      </a>
    </p>

    <hr>

    <!-- GitHub Statistics Section -->
    <h2>📊 My GitHub Statistics</h2>
    <p class="center github-stats">
      <img src="https://github-readme-stats.vercel.app/api?username=brazilianscriptguy&show_icons=true&theme=radical&v=2" alt="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=brazilianscriptguy&layout=compact&theme=radical&v=2" alt="Top Languages">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=brazilianscriptguy&theme=radical&v=2" alt="GitHub Streak">
    </p>

    <hr>

    <!-- Highlights of My Repositories -->
    <h2>🌟 Highlights of My Repositories</h2>
    <ul>
      <li><strong>GUI Integration:</strong> User-friendly graphical interfaces for every tool.</li>
      <li><strong>Advanced Logging:</strong> Detailed <code>.log</code> and <code>.csv</code> files for tracking and reporting.</li>
      <li><strong>Enhanced Security:</strong> Tools for compliance auditing, forensic data collection, and system hardening.</li>
      <li><strong>Customizable:</strong> Highly adaptable scripts tailored for diverse IT environments.</li>
    </ul>

    <hr>

    <!-- Support and Contributions Section -->
    <h2>🤝 Support and Contributions</h2>
    <p>
      If my work has been helpful, consider supporting me on 
      <a href="https://www.patreon.com/c/brazilianscriptguy" target="_blank">Patreon</a> for exclusive updates and content. 
      You can also contribute by reporting issues, sharing ideas, or submitting pull requests.
    </p>

    <hr>

    <!-- Closing Message -->
    <p class="center">
      Thank you for visiting my profile! Let's make IT management smarter, faster, and more secure—together! 💻🚀
    </p>

    <!-- Footer -->
    <footer>
      &copy; 2025 Luiz Hamilton. All rights reserved.
    </footer>

  </div>

</body>
</html>
