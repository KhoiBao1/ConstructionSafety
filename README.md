<h2 data-start="345" data-end="367">Project Overview</h2>
<p data-start="369" data-end="590">This project is an AI-powered Personal Protective Equipment (PPE) violation detection system designed to help enterprises improve workplace safety monitoring through real-time computer vision and automated alerts.</p>
<p data-start="592" data-end="734">The system uses deep learning (YOLO-based object detection) to identify whether workers comply with mandatory safety requirements such as:</p>
<ul data-start="736" data-end="781">
<li data-start="736" data-end="749">
<p data-start="738" data-end="749">Hard hats</p>
</li>
<li data-start="750" data-end="766">
<p data-start="752" data-end="766">Safety vests</p>
</li>
<li data-start="767" data-end="781">
<p data-start="769" data-end="781">Face masks</p>
</li>
</ul>
<p data-start="783" data-end="926">When a violation is detected, the system can automatically send alert emails with evidence images/videos to supervisors or safety managers.</p>
<p data-start="928" data-end="958">This solution is suitable for:</p>
<ul data-start="960" data-end="1074">
<li data-start="960" data-end="982">
<p data-start="962" data-end="982">Construction sites</p>
</li>
<li data-start="983" data-end="1007">
<p data-start="985" data-end="1007">Manufacturing plants</p>
</li>
<li data-start="1008" data-end="1022">
<p data-start="1010" data-end="1022">Warehouses</p>
</li>
<li data-start="1023" data-end="1043">
<p data-start="1025" data-end="1043">Industrial zones</p>
</li>
<li data-start="1044" data-end="1074">
<p data-start="1046" data-end="1074">Smart factory environments</p>
</li>
</ul>
<h2 data-start="1081" data-end="1105">Project Objectives</h2>
<p data-start="1107" data-end="1142">The main goals of this project are:</p>
<ul data-start="1144" data-end="1461">
<li data-start="1144" data-end="1199">
<p data-start="1146" data-end="1199">Reduce workplace accidents caused by PPE violations</p>
</li>
<li data-start="1200" data-end="1269">
<p data-start="1202" data-end="1269">Automate safety supervision using AI instead of manual monitoring</p>
</li>
<li data-start="1270" data-end="1350">
<p data-start="1272" data-end="1350">Provide real-time detection from images, videos, and live webcam streams</p>
</li>
<li data-start="1351" data-end="1406">
<p data-start="1353" data-end="1406">Store inspection history for auditing and reporting</p>
</li>
<li data-start="1407" data-end="1461">
<p data-start="1409" data-end="1461">Notify responsible personnel immediately via email</p>
</li>
</ul>
<h2 data-start="1468" data-end="1486">Key Features</h2>
<h3 data-start="1488" data-end="1516">AI-Based PPE Detection</h3>
<ul data-start="1517" data-end="1691">
<li data-start="1517" data-end="1610">
<p data-start="1519" data-end="1527">Detects:</p>
<ul data-start="1530" data-end="1610">
<li data-start="1530" data-end="1554">
<p data-start="1532" data-end="1554">Hardhat / No-Hardhat</p>
</li>
<li data-start="1557" data-end="1589">
<p data-start="1559" data-end="1589">Safety Vest / No-Safety Vest</p>
</li>
<li data-start="1592" data-end="1610">
<p data-start="1594" data-end="1610">Mask / No-Mask</p>
</li>
</ul>
</li>
<li data-start="1611" data-end="1657">
<p data-start="1613" data-end="1657">Built on YOLO deep learning architecture</p>
</li>
<li data-start="1658" data-end="1691">
<p data-start="1660" data-end="1691">Custom-trained model (<code data-start="1682" data-end="1690">ppe.pt</code>)</p>
</li>
</ul>
<h3 data-start="1698" data-end="1724">Multi-Input Support</h3>
<p data-start="1725" data-end="1759">Users can perform detection using:</p>
<ul data-start="1761" data-end="1828">
<li data-start="1761" data-end="1780">
<p data-start="1763" data-end="1780">Uploaded images</p>
</li>
<li data-start="1781" data-end="1800">
<p data-start="1783" data-end="1800">Uploaded videos</p>
</li>
<li data-start="1801" data-end="1828">
<p data-start="1803" data-end="1828">Real-time webcam stream</p>
</li>
</ul>
<h3 data-start="1835" data-end="1868">User Authentication System</h3>
<ul data-start="1869" data-end="1993">
<li data-start="1869" data-end="1902">
<p data-start="1871" data-end="1902">Secure login &amp; sign-up system</p>
</li>
<li data-start="1903" data-end="1923">
<p data-start="1905" data-end="1923">Password hashing</p>
</li>
<li data-start="1924" data-end="1956">
<p data-start="1926" data-end="1956">Session-based authentication</p>
</li>
<li data-start="1957" data-end="1993">
<p data-start="1959" data-end="1993">Individual user history tracking</p>
</li>
</ul>
<h3 data-start="2000" data-end="2035">Detection History Management</h3>
<ul data-start="2036" data-end="2189">
<li data-start="2036" data-end="2155">
<p data-start="2038" data-end="2045">Stores:</p>
<ul data-start="2048" data-end="2155">
<li data-start="2048" data-end="2066">
<p data-start="2050" data-end="2066">Uploaded files</p>
</li>
<li data-start="2069" data-end="2090">
<p data-start="2071" data-end="2090">Processed outputs</p>
</li>
<li data-start="2093" data-end="2117">
<p data-start="2095" data-end="2117">Detection statistics</p>
</li>
<li data-start="2120" data-end="2139">
<p data-start="2122" data-end="2139">Violation count</p>
</li>
<li data-start="2142" data-end="2155">
<p data-start="2144" data-end="2155">Timestamp</p>
</li>
</ul>
</li>
<li data-start="2156" data-end="2189">
<p data-start="2158" data-end="2189">Powered by MongoDB database</p>
</li>
</ul>
<h3 data-start="2196" data-end="2221">Email Alert System</h3>
<ul data-start="2222" data-end="2351">
<li data-start="2222" data-end="2275">
<p data-start="2224" data-end="2275">Automatic email notifications when violations occur</p>
</li>
<li data-start="2276" data-end="2351">
<p data-start="2278" data-end="2287">Includes:</p>
<ul data-start="2290" data-end="2351">
<li data-start="2290" data-end="2309">
<p data-start="2292" data-end="2309">Violation summary</p>
</li>
<li data-start="2312" data-end="2328">
<p data-start="2314" data-end="2328">Detection time</p>
</li>
<li data-start="2331" data-end="2351">
<p data-start="2333" data-end="2351">Evidence reference</p>
</li>
</ul>
</li>
</ul>
<h3 data-start="2358" data-end="2383">Web-Based Platform</h3>
<ul data-start="2384" data-end="2510">
<li data-start="2384" data-end="2401">
<p data-start="2386" data-end="2401">Flask backend</p>
</li>
<li data-start="2402" data-end="2423">
<p data-start="2404" data-end="2423">HTML/CSS frontend</p>
</li>
<li data-start="2424" data-end="2458">
<p data-start="2426" data-end="2458">Works entirely through browser</p>
</li>
<li data-start="2459" data-end="2510">
<p data-start="2461" data-end="2510">No software installation required for end users</p>
</li>
</ul>
<h2 data-start="2517" data-end="2542">System Architecture</h2>
<div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary">
<blockquote>
<h3 class="overflow-y-auto p-4" dir="ltr"><span style="color: #666699;">User</span><br /><span style="color: #666699;"> │</span><br /><span style="color: #666699;"> │ Upload Image / Video / Webcam</span><br /><span style="color: #666699;"> ▼</span><br /><span style="color: #666699;">Web Interface (Flask)</span><br /><span style="color: #666699;"> │</span><br /><span style="color: #666699;"> │ Authentication &amp; Validation</span><br /><span style="color: #666699;"> ▼</span><br /><span style="color: #666699;">AI Detection Engine (YOLOv8)</span><br /><span style="color: #666699;"> │</span><br /><span style="color: #666699;"> │ Bounding box + classification</span><br /><span style="color: #666699;"> ▼</span><br /><span style="color: #666699;">Result Processor</span><br /><span style="color: #666699;"> │</span><br /><span style="color: #666699;"> ├── Save result to MongoDB</span><br /><span style="color: #666699;"> ├── Store media in server</span><br /><span style="color: #666699;"> └── Trigger email alert</span></h3>
</blockquote>
</div>
<h2 data-start="2830" data-end="2852">Technology Stack</h2>
<h3 data-start="2854" data-end="2865">Backend</h3>
<ul data-start="2866" data-end="2940">
<li data-start="2866" data-end="2880">Scipy</li>
<li data-start="2866" data-end="2880">
<p data-start="2868" data-end="2880">Python 3.10+</p>
</li>
<li data-start="2881" data-end="2888">
<p data-start="2883" data-end="2888">Flask</p>
</li>
<li data-start="2889" data-end="2902">
<p data-start="2891" data-end="2902">PyTorch</p>
</li>
<li data-start="2903" data-end="2912">
<p data-start="2905" data-end="2912">Matplotlib</p>
</li>
<li data-start="2913" data-end="2921">
<p data-start="2915" data-end="2921">OpenCV</p>
</li>
<li data-start="2922" data-end="2940">
<p data-start="2924" data-end="2940">Ultralytics</p>
</li>
<li data-start="2922" data-end="2940">
<p data-start="2924" data-end="2940">YOLOv8</p>
</li>
<li data-start="2922" data-end="2940">Google Colab</li>
</ul>
<h3 data-start="2942" data-end="2954">Frontend</h3>
<ul data-start="2955" data-end="2981">
<li data-start="2955" data-end="2962">
<p data-start="2957" data-end="2962">HTML5</p>
</li>
<li data-start="2963" data-end="2969">
<p data-start="2965" data-end="2969">CSS3</p>
</li>
<li data-start="2970" data-end="2981">
<p data-start="2972" data-end="2981">Bootstrap</p>
</li>
<li data-start="2970" data-end="2981">Javascript</li>
</ul>
<h3 data-start="2983" data-end="2995">Database</h3>
<ul data-start="2996" data-end="3029">
<li data-start="2996" data-end="3029">
<p data-start="2998" data-end="3029">MongoDB (Local / MongoDB Atlas)</p>
</li>
</ul>
<h3 data-start="3031" data-end="3055">AI &amp; Computer Vision</h3>
<ul data-start="3056" data-end="3122">
<li data-start="3056" data-end="3079">
<p data-start="3058" data-end="3079">YOLO object detection</p>
</li>
<li data-start="3080" data-end="3100">
<p data-start="3082" data-end="3100">Custom PPE dataset</p>
</li>
<li data-start="3101" data-end="3122">
<p data-start="3103" data-end="3122">Trained <code data-start="3111" data-end="3116">.pt</code> model</p>
</li>
</ul>
<h2 data-start="3129" data-end="3159">Example Detection Output</h2>
<ul data-start="3161" data-end="3372">
<li data-start="3161" data-end="3201">
<p data-start="3163" data-end="3201">Bounding boxes with confidence score</p>
</li>
<li data-start="3202" data-end="3234">
<p data-start="3204" data-end="3234">Violation highlighted in red</p>
</li>
<li data-start="3235" data-end="3281">
<p data-start="3237" data-end="3281">PPE-compliant objects highlighted in green</p>
</li>
<li data-start="3282" data-end="3372">
<p data-start="3284" data-end="3303">Summary statistics:</p>
<ul data-start="3306" data-end="3372">
<li data-start="3306" data-end="3325">
<p data-start="3308" data-end="3325">Number of workers</p>
</li>
<li data-start="3328" data-end="3350">
<p data-start="3330" data-end="3350">PPE compliance count</p>
</li>
<li data-start="3353" data-end="3372">
<p data-start="3355" data-end="3372">Violation count</p>
</li>
</ul>
</li>
</ul>
<h2 data-start="3379" data-end="3430">&nbsp;</h2>
<h2 data-start="3819" data-end="3856">Potential Business Applications</h2>
<ul data-start="3858" data-end="4022">
<li data-start="3858" data-end="3891">
<p data-start="3860" data-end="3891">Smart construction monitoring</p>
</li>
<li data-start="3892" data-end="3921">
<p data-start="3894" data-end="3921">Factory safety automation</p>
</li>
<li data-start="3922" data-end="3949">
<p data-start="3924" data-end="3949">AI-powered CCTV systems</p>
</li>
<li data-start="3950" data-end="3980">
<p data-start="3952" data-end="3980">Industrial IoT integration</p>
</li>
<li data-start="3981" data-end="4022">
<p data-start="3983" data-end="4022">Safety compliance analytics dashboard</p>
</li>
</ul>
<h2 data-start="4029" data-end="4054">Future Enhancements</h2>
<ul data-start="4056" data-end="4287">
<li data-start="4056" data-end="4093">
<p data-start="4058" data-end="4093">OSHA rule-based violation scoring</p>
</li>
<li data-start="4094" data-end="4134">
<p data-start="4096" data-end="4134">SMS / Slack / Microsoft Teams alerts</p>
</li>
<li data-start="4135" data-end="4168">
<p data-start="4137" data-end="4168">Multi-camera CCTV integration</p>
</li>
<li data-start="4169" data-end="4202">
<p data-start="4171" data-end="4202">Real-time dashboard analytics</p>
</li>
<li data-start="4203" data-end="4243">
<p data-start="4205" data-end="4243">Cloud deployment (AWS / Azure / GCP)</p>
</li>
<li data-start="4244" data-end="4287">
<p data-start="4246" data-end="4287">Edge AI deployment (Jetson Nano / Orin)</p>
</li>
</ul>
<h2 data-start="4294" data-end="4312">👨&zwj;💻 Developer</h2>
<p data-start="4314" data-end="4383"><strong data-start="4314" data-end="4326">Kh&ocirc;i Bảo</strong><br data-start="4326" data-end="4329" /> Computer Science Student</p>
<p data-start="4385" data-end="4400"><strong data-start="4385" data-end="4400">Core Skills</strong></p>
<ul data-start="4401" data-end="4512">
<li data-start="4401" data-end="4420">
<p data-start="4403" data-end="4420">Computer Vision</p>
</li>
<li data-start="4421" data-end="4438">
<p data-start="4423" data-end="4438">Deep Learning</p>
</li>
<li data-start="4439" data-end="4457">
<p data-start="4441" data-end="4457">Python Backend</p>
</li>
<li data-start="4458" data-end="4478">
<p data-start="4460" data-end="4478">Flask &amp; REST API</p>
</li>
<li data-start="4479" data-end="4490">
<p data-start="4481" data-end="4490">MongoDB</p>
</li>
<li data-start="4491" data-end="4512">
<p data-start="4493" data-end="4512">Web AI Deployment</p>
</li>
</ul>
<h2 data-start="4519" data-end="4532">📬 Contact</h2>
<p data-start="4534" data-end="4589">For collaboration, research, or enterprise integration:</p>
<p data-start="4591" data-end="4656">📧 Email:&nbsp;<em data-start="4601" data-end="4620">khoibao655@gmail.com</em><br data-start="4620" data-end="4623" /> 🌐 GitHub: https://github.com/KhoiBao1</p>
<h2 data-start="4663" data-end="4675">Summary</h2>
<p data-start="4677" data-end="4718">This project demonstrates the ability to:</p>
<ul data-start="4720" data-end="4954">
<li data-start="4720" data-end="4761">
<p data-start="4722" data-end="4761">Build a real-world AI safety system</p>
</li>
<li data-start="4762" data-end="4823">
<p data-start="4764" data-end="4823">Integrate deep learning with full-stack web development</p>
</li>
<li data-start="4824" data-end="4885">
<p data-start="4826" data-end="4885">Deploy AI models into production-ready web applications</p>
</li>
<li data-start="4886" data-end="4954">
<p data-start="4888" data-end="4954">Design solutions aligned with U.S. industrial safety standards</p>
</li>
</ul>
<p>You can read my project report in PDF/Word format via :&nbsp;</p>
<p>
<a href="https://drive.google.com/drive/u/0/folders/1k_GvYWr_BAVZbhxnYtfhjvafqKj2zMfc">Report</a>
</p>
<p>You can also watch the demo videos of this project via :</p>
<p>
<a href="https://drive.google.com/drive/folders/1kLbCdwoNRBA2cWlWR9_glggM4ut2KZev?usp=drive_link">Video Demo</a>
</p>
<p>&nbsp;</p>
