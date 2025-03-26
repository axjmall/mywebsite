<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio</title>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/echarts/5.5.0/echarts.min.js"></script>
<script>
tailwind.config = {
theme: {
extend: {
colors: {
primary: '#0EA5E9',
secondary: '#64748B'
},
borderRadius: {
'none': '0px',
'sm': '4px',
DEFAULT: '8px',
'md': '12px',
'lg': '16px',
'xl': '20px',
'2xl': '24px',
'3xl': '32px',
'full': '9999px',
'button': '8px'
}
}
}
}
</script>
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body { font-family: 'Inter', sans-serif; }
.contribution-graph {
display: grid;
grid-template-columns: repeat(52, 1fr);
gap: 3px;
}
.contribution-cell {
width: 10px;
height: 10px;
border-radius: 2px;
}
</style>
</head>
<body class="bg-white min-h-screen">
<nav class="fixed top-0 left-0 right-0 bg-white/80 backdrop-blur-sm z-50 border-b border-gray-100">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex justify-between items-center h-16">
<a href="#" class="text-2xl font-semibold text-gray-900">Ajmal Faisal</a>
<div class="hidden md:flex space-x-8">
<a href="#about" class="text-gray-600 hover:text-primary">About</a>
<a href="#projects" class="text-gray-600 hover:text-primary">Projects</a>
<a href="#github" class="text-gray-600 hover:text-primary">GitHub</a>
<a href="#contact" class="text-gray-600 hover:text-primary">Contact</a>
</div>
</div>
</div>
</nav>
<main class="pt-16">
<section id="hero" class="py-20 bg-gradient-to-br from-blue-50 to-white">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex flex-col items-center text-center">
<img src="https://static.readdy.ai/image/0baa0e90b8b1bb8386971b7fe2a554b5/97cc81759b7600fc787d1d5e3006f222.png"
alt="Profile"
class="w-32 h-32 rounded-full object-cover mb-8 shadow-lg">
<h1 class="text-4xl font-bold text-gray-900 mb-4">Ajmal Faisal</h1>
<p class="text-xl text-gray-600 mb-8">Cybersecurity Analyst</p>
<div class="flex space-x-4">
<a href="https://github.com/axjmall" target="_blank" class="flex items-center justify-center w-10 h-10 rounded-full bg-gray-900 text-white hover:bg-gray-700 transition cursor-pointer">
<i class="ri-github-fill ri-lg"></i>
</a>
<a href="https://ae.linkedin.com/in/ajmal-faisal-93318827a?trk=people-guest_people_search-card" target="_blank" class="flex items-center justify-center w-10 h-10 rounded-full bg-[#0077B5] text-white hover:bg-[#006399] transition cursor-pointer">
<i class="ri-linkedin-fill ri-lg"></i>
</a>
<a href="https://twitter.com/axjmall" target="_blank" class="flex items-center justify-center w-10 h-10 rounded-full bg-[#1DA1F2] text-white hover:bg-[#1a91da] transition cursor-pointer">
<i class="ri-twitter-fill ri-lg"></i>
</a>
<a href="https://tryhackme.com/p/ZAP" target="_blank" class="flex items-center justify-center w-10 h-10 rounded-full bg-[#1C2538] text-white hover:bg-[#161d2b] transition cursor-pointer">
<i class="ri-shield-keyhole-fill ri-lg"></i>
</a>
</div>
</div>
</div>
</section>
<section id="about" class="py-20">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-gray-900 mb-8">About Me</h2>
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div>
<p class="text-gray-600 leading-relaxed mb-6">
I'm a passionate and driven Cybersecurity student with a strong interest in network security, cyber operations, and enterprise networking. I hold a Bachelor of Science (BSc) in Cybersecurity, and I am currently enhancing my skill set through various industry-recognized certifications to further my career in the field.
I have a deep interest in understanding the intricacies of network infrastructure, security protocols, and the tools that protect organizations from cyber threats. With hands-on experience and a rigorous academic background, I am building a solid foundation in cybersecurity and network management.
</p>
<div class="mt-8">
<h3 class="text-xl font-semibold text-gray-900 mb-4">Certifications</h3>
<div class="space-y-4">
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">Certified Ethical Hacker (CEH) by Cisco <span class="text-primary text-sm">(Ongoing)</span></h4>
<p class="text-gray-600">Developing expertise in identifying and addressing vulnerabilities through ethical hacking techniques.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">GL04-Network Security <span class="text-primary text-sm">(Ongoing)</span></h4>
<p class="text-gray-600">Gaining hands-on knowledge in securing networks and mitigating cyber threats.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">GL05-CyberOps Associate <span class="text-primary text-sm">(Ongoing)</span></h4>
<p class="text-gray-600">Diving deeper into cybersecurity operations, focusing on incident response, monitoring, and security operations.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">Certified in Cybersecurity (CC) by (ISC)² <span class="text-primary text-sm">(Ongoing)</span></h4>
<p class="text-gray-600">Enhancing my overall understanding of cybersecurity principles, risk management, and securing enterprise environments.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">GL02-CCNA: Switching, Routing, and Wireless</h4>
<p class="text-gray-600">Mastering the core principles of routing and switching to ensure seamless network operations.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">GL03-CCNA: Enterprise Networking, Security</h4>
<p class="text-gray-600">Focusing on enterprise-level networking solutions and building secure, efficient networks.</p>
</div>
</div>
<div class="flex items-start">
<i class="ri-award-line text-primary w-6 h-6 mt-1 flex-shrink-0"></i>
<div class="ml-4">
<h4 class="font-medium text-gray-900">GL01-CCNA: Introduction to Networks</h4>
<p class="text-gray-600">Foundation course covering network fundamentals and basic configurations.</p>
</div>
</div>
</div>
</div>
<div class="flex flex-wrap gap-2">
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Network Security</span>
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Threat Analysis</span>
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Incident Response</span>
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Penetration Testing</span>
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">SIEM</span>
<span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Security Architecture</span>
</div>
</div>
<div>
<div id="skillChart" class="w-full h-64"></div>
</div>
</div>
</div>
</section>
<section id="projects" class="py-20 bg-gray-50">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-gray-900 mb-8">Featured Projects</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<div class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition cursor-pointer">
<img src="https://public.readdy.ai/ai/img_res/2f4323864b33b8bb6f1700e485a8880c.jpg"
alt="ZapShare"
class="w-full h-48 object-cover">
<div class="p-6">
<h3 class="text-xl font-semibold text-gray-900 mb-2">ZapShare</h3>
<p class="text-gray-600 mb-4">A secure file transfer application with end-to-end encryption, real-time progress tracking, and multi-platform support.</p>
<div class="flex flex-wrap gap-2 mb-4">
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Python</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Cryptography</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Socket</span>
</div>
</div>
</div>
<div class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition cursor-pointer">
<img src="https://public.readdy.ai/ai/img_res/263fe9bf8f87ff795227389330a78409.jpg"
alt="VPN Firewall Bypass"
class="w-full h-48 object-cover">
<div class="p-6">
<h3 class="text-xl font-semibold text-gray-900 mb-2">VPN Firewall Bypass</h3>
<p class="text-gray-600 mb-4">Implementation of VPN tunneling techniques to bypass firewall restrictions using SEED Labs, demonstrating network security concepts.</p>
<div class="flex flex-wrap gap-2 mb-4">
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">OpenVPN</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Linux</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Networking</span>
</div>
</div>
</div>
<div class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition cursor-pointer">
<img src="https://public.readdy.ai/ai/img_res/6c449c0ce8c23c405373ecd282e2e79f.jpg"
alt="RSA Encryption App"
class="w-full h-48 object-cover">
<div class="p-6">
<h3 class="text-xl font-semibold text-gray-900 mb-2">RSA Encryption App</h3>
<p class="text-gray-600 mb-4">A comprehensive RSA encryption application featuring key generation, message encryption/decryption, and digital signatures.</p>
<div class="flex flex-wrap gap-2 mb-4">
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Java</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">RSA</span>
<span class="px-2 py-1 bg-gray-100 text-gray-600 rounded-full text-xs">Security</span>
</div>
</div>
</div>
</div>
</div>
</section>
<section id="github" class="py-20">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-gray-900 mb-8">GitHub Activity</h2>
<div class="bg-white rounded-lg shadow-sm p-6 mb-8">
<div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
<div class="p-4 bg-gray-50 rounded-lg">
<div class="flex items-center justify-between">
<span class="text-gray-600">Contributions</span>
<span class="text-2xl font-semibold text-gray-900">1,247</span>
</div>
</div>
<div class="p-4 bg-gray-50 rounded-lg">
<div class="flex items-center justify-between">
<span class="text-gray-600">Repositories</span>
<span class="text-2xl font-semibold text-gray-900">34</span>
</div>
</div>
<div class="p-4 bg-gray-50 rounded-lg">
<div class="flex items-center justify-between">
<span class="text-gray-600">Stars</span>
<span class="text-2xl font-semibold text-gray-900">156</span>
</div>
</div>
</div>
<div id="contributionGraph" class="w-full h-32 mb-8"></div>
<a href="https://github.com" target="_blank" class="inline-flex items-center px-4 py-2 bg-gray-900 text-white rounded-button hover:bg-gray-800 transition cursor-pointer">
<i class="ri-github-fill mr-2"></i> View GitHub Profile
</a>
</div>
</div>
</section>
<section id="contact" class="py-20 bg-gray-50">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-gray-900 mb-8">Get in Touch</h2>
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div>
<p class="text-gray-600 mb-6">
I'm always interested in hearing about new projects and opportunities.
Feel free to reach out if you'd like to collaborate or just say hello!
</p>
<div class="space-y-4">
<a href="https://ae.linkedin.com/in/ajmal-faisal-93318827a?trk=people-guest_people_search-card" target="_blank" class="flex items-center text-gray-600 hover:text-primary">
<i class="ri-linkedin-line w-6 h-6 flex items-center justify-center"></i>
<span class="ml-2">linkedin.com/in/ajmal-faisal-93318827a</span>
</a>
<a href="https://twitter.com/axjmall" target="_blank" class="flex items-center text-gray-600 hover:text-primary">
<i class="ri-twitter-line w-6 h-6 flex items-center justify-center"></i>
<span class="ml-2">@axjmall</span>
</a>
<a href="https://github.com/axjmall" target="_blank" class="flex items-center text-gray-600 hover:text-primary">
<i class="ri-github-line w-6 h-6 flex items-center justify-center"></i>
<span class="ml-2">github.com/axjmall</span>
</a>
<a href="https://tryhackme.com/p/ZAP" target="_blank" class="flex items-center text-gray-600 hover:text-primary">
<i class="ri-shield-keyhole-line w-6 h-6 flex items-center justify-center"></i>
<span class="ml-2">tryhackme.com/p/ZAP</span>
</a>
</div>
</div>
<form id="contactForm" class="space-y-6">
<div>
<label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
<input type="text" id="name" name="name" class="w-full px-4 py-2 border border-gray-300 rounded-button focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent">
</div>
<div>
<label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
<input type="email" id="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-button focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent">
</div>
<div>
<label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
<textarea id="message" name="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-button focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent"></textarea>
</div>
<button type="submit" class="w-full px-6 py-3 bg-primary text-white rounded-button hover:bg-blue-600 transition cursor-pointer">Send Message</button>
</form>
</div>
</div>
</section>
</main>
<footer class="bg-gray-900 text-white py-12">
<div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex flex-col md:flex-row justify-between items-center">
<div class="text-center md:text-left mb-6 md:mb-0">
<h3 class="text-xl font-semibold mb-2">Ajmal Faisal</h3>
<p class="text-gray-400">Cybersecurity Analyst</p>
</div>
<div class="flex space-x-6">
<a href="https://github.com/axjmall" target="_blank" class="hover:text-primary transition cursor-pointer">
<i class="ri-github-fill ri-lg"></i>
</a>
<a href="https://ae.linkedin.com/in/ajmal-faisal-93318827a?trk=people-guest_people_search-card" target="_blank" class="hover:text-primary transition cursor-pointer">
<i class="ri-linkedin-fill ri-lg"></i>
</a>
<a href="https://twitter.com/axjmall" target="_blank" class="hover:text-primary transition cursor-pointer">
<i class="ri-twitter-fill ri-lg"></i>
</a>
<a href="https://tryhackme.com/p/ZAP" target="_blank" class="hover:text-primary transition cursor-pointer">
<i class="ri-shield-keyhole-fill ri-lg"></i>
</a>
</div>
</div>
<div class="mt-8 pt-8 border-t border-gray-800 text-center text-gray-400">
<p>&copy; 2025 Ajmal Faisal. All rights reserved.</p>
</div>
</div>
</footer>
<button id="backToTop" class="fixed bottom-8 right-8 bg-primary text-white w-10 h-10 rounded-full shadow-lg flex items-center justify-center opacity-0 transition-opacity duration-300 cursor-pointer">
<i class="ri-arrow-up-line ri-lg"></i>
</button>
<script>
document.addEventListener('DOMContentLoaded', function() {
const skillChart = echarts.init(document.getElementById('skillChart'));
const contributionChart = echarts.init(document.getElementById('contributionGraph'));
const skillOption = {
animation: false,
radar: {
indicator: [
{ name: 'Network Security', max: 100 },
{ name: 'Web Security', max: 100 },
{ name: 'Cryptography', max: 100 },
{ name: 'Malware Analysis', max: 100 },
{ name: 'Incident Response', max: 100 },
{ name: 'Forensics', max: 100 }
],
splitArea: {
areaStyle: {
color: ['rgba(87, 181, 231, 0.02)', 'rgba(87, 181, 231, 0.05)']
}
}
},
series: [{
type: 'radar',
data: [{
value: [65, 58, 52, 60, 55, 57],
name: 'Current Skills',
areaStyle: {
color: 'rgba(87, 181, 231, 0.1)'
},
lineStyle: {
color: 'rgba(87, 181, 231, 1)',
width: 2
},
itemStyle: {
color: 'rgba(87, 181, 231, 1)'
},
symbolSize: 6
}]
}]
};
const contributionOption = {
animation: false,
tooltip: {
trigger: 'axis',
backgroundColor: 'rgba(255, 255, 255, 0.9)',
textStyle: {
color: '#1f2937'
}
},
xAxis: {
type: 'category',
data: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'],
axisLine: { show: false },
axisTick: { show: false },
axisLabel: {
color: '#64748B'
}
},
yAxis: {
type: 'value',
name: 'Rooms Completed',
nameTextStyle: {
color: '#64748B'
},
splitLine: {
lineStyle: {
color: 'rgba(100, 116, 139, 0.1)'
}
},
axisLabel: {
color: '#64748B'
}
},
series: [{
name: 'Learning Progress',
data: [5, 8, 6, 10, 8, 12, 9, 15, 11, 18, 14, 20],
type: 'line',
smooth: true,
symbol: 'circle',
symbolSize: 8,
areaStyle: {
color: new echarts.graphic.LinearGradient(0, 0, 0, 1, [
{
offset: 0,
color: 'rgba(87, 181, 231, 0.3)'
},
{
offset: 1,
color: 'rgba(87, 181, 231, 0.1)'
}
])
},
lineStyle: {
color: 'rgba(87, 181, 231, 1)',
width: 3
},
itemStyle: {
color: 'rgba(87, 181, 231, 1)',
borderWidth: 2,
borderColor: '#fff'
}
}]
};
skillChart.setOption(skillOption);
contributionChart.setOption(contributionOption);
window.addEventListener('resize', function() {
skillChart.resize();
contributionChart.resize();
});
const backToTop = document.getElementById('backToTop');
window.addEventListener('scroll', () => {
if (window.pageYOffset > 300) {
backToTop.style.opacity = '1';
} else {
backToTop.style.opacity = '0';
}
});
backToTop.addEventListener('click', () => {
window.scrollTo({
top: 0,
behavior: 'smooth'
});
});
const contactForm = document.getElementById('contactForm');
contactForm.addEventListener('submit', function(e) {
e.preventDefault();
const formData = new FormData(contactForm);
const data = Object.fromEntries(formData);
const notification = document.createElement('div');
notification.className = 'fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded-lg shadow-lg transform transition-transform duration-300 translate-x-full';
notification.textContent = 'Message sent successfully!';
document.body.appendChild(notification);
setTimeout(() => {
notification.style.transform = 'translateX(0)';
}, 100);
setTimeout(() => {
notification.style.transform = 'translateX(100%)';
setTimeout(() => {
notification.remove();
}, 300);
}, 3000);
contactForm.reset();
});
});
</script>
</body>
</html>