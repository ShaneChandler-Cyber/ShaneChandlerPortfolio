---
layout: default
---

#  [About me](./aboutme.html) | [Home](./index.html) | [Contact](./contactinfo.html) | [Resources](./resources.html) | [Projects](./projects.html)

# Resources

Welcome to the Resources page! Below, you'll find a curated list of tools, tutorials, and guides that I’ve used and recommend for anyone looking to dive deeper into IT and Cybersecurity.

### Cybersecurity Tools
- **Kali Linux**  
  Kali Linux is an essential tool for penetration testing and ethical hacking. It comes pre-installed with a wide range of tools for security testing, making it a go-to for anyone in the field. [Official Site](https://www.kali.org/)

- **Metasploit Framework**  
  An essential tool for penetration testers, Metasploit enables users to find, exploit, and validate vulnerabilities. [Get Started](https://www.metasploit.com/)

- **Security Onion**  
  A Linux distribution that helps with intrusion detection, network security monitoring, and log management. It’s particularly useful for setting up a home lab to practice real-time threat detection. [Learn More](https://securityonion.net/)

- **Nessus**  
  Nessus is a popular vulnerability scanning tool that identifies weaknesses in systems, applications, and networks. [Official Page](https://www.tenable.com/products/nessus)

### Python Learning Resources
- **Automate the Boring Stuff with Python**  
  A great resource for beginners looking to automate repetitive tasks and learn Python. Practical projects include automating emails, PDF manipulation, and web scraping. [Visit the Book](https://automatetheboringstuff.com/)

- **Real Python**  
  A platform full of tutorials, news, and resources for learning Python. It has articles on cybersecurity, automation, data science, and more. [Explore Real Python](https://realpython.com/)

### IT & Cybersecurity Certifications
- **CompTIA Security+**  
  A great entry-level certification that covers network security, cryptography, risk management, and more. [CompTIA Security+](https://www.comptia.org/certifications/security)

- **Certified Ethical Hacker (CEH)**  
  Learn to think like a hacker and find weaknesses in your network before malicious actors do. [CEH Certification](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)

- **Certified Information Systems Security Professional (CISSP)**  
  One of the most respected certifications in cybersecurity, CISSP is ideal for professionals looking to advance in the field. [More About CISSP](https://www.isc2.org/Certifications/CISSP)

### Blogs and News Sites
- **Krebs on Security**  
  Brian Krebs offers in-depth reporting on cybersecurity issues, breaches, and hacker tactics. [Read Krebs on Security](https://krebsonsecurity.com/)

- **The Hacker News**  
  Stay up to date with the latest news, vulnerabilities, and cybersecurity trends. [Visit The Hacker News](https://thehackernews.com/)

- **Dark Reading**  
  A resource focused on cyber defense, breach detection, and data protection. [Dark Reading](https://www.darkreading.com/)

### Learning Platforms
- **Cybrary**  
  A popular platform offering free courses in IT and cybersecurity, from beginner to advanced levels. [Explore Cybrary](https://www.cybrary.it/)

- **Udemy**  
  Online courses that span a wide array of tech topics, including ethical hacking, network security, and Python for cybersecurity. [Find Courses on Udemy](https://www.udemy.com/)

### PGP Implementation

<div class="accordion">
    <div class="accordion-header">How to Use PGP</div>
    <div class="accordion-content">
        <h4>1. Install GnuPG</h4>
        <ul>
            <li>Download and install GnuPG (GPG), an open-source implementation of the OpenPGP standard, on your system.</li>
        </ul>
        <h4>2. Generate Your Key Pair</h4>
        <ul>
            <li>Use a key management tool like <strong>Kleopatra</strong> to create a new PGP key pair (public and private keys).</li>
            <li>Set a strong passphrase to protect your private key.</li>
        </ul>
    </div>
</div>

<script>
    const headers = document.querySelectorAll('.accordion-header');

    headers.forEach(header => {
        header.addEventListener('click', () => {
            const content = header.nextElementSibling;
            const isActive = content.style.display === 'block';

            // Close all accordion contents
            document.querySelectorAll('.accordion-content').forEach(c => c.style.display = 'none');

            // Remove 'active' class from all headers
            headers.forEach(h => h.classList.remove('active'));

            // Toggle the clicked content
            if (!isActive) {
                content.style.display = 'block';
                header.classList.add('active');
            }
        });
    });
</script>
<script>
  setInterval(() => {
    const cursor = document.getElementById('cursor');
    cursor.style.visibility = cursor.style.visibility === 'hidden' ? 'visible' : 'hidden';
  }, 500); // Blink every 500ms
</script>

---
