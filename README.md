<h1>🛰️ Discovery Scan Across Cyber Range Subnets (Tenable)</h1>

<p>
This project demonstrates how I used <strong>Tenable discovery scanning</strong> to identify live assets across an enterprise-style cyber range. The objective was to map the attack surface, validate network visibility, and build an initial asset inventory to support vulnerability management and tagging strategies.
</p>

<hr />

<h2>🎯 Objective</h2>
<p>
Perform a discovery scan across multiple subnets to identify reachable hosts and establish visibility into unmanaged or unknown assets prior to vulnerability scanning.
</p>

<img width="1299" height="751" alt="image" src="https://github.com/user-attachments/assets/b5a13a01-a064-4923-8526-fd419551cc27" />


<hr />

<h2>🧰 Tools & Concepts</h2>
<ul>
  <li>Tenable Vulnerability Management</li>
  <li>Discovery Scans</li>
  <li>CIDR Subnet Targeting</li>
  <li>Asset Inventory & Tagging</li>
  <li>Attack Surface Identification</li>
</ul>

<hr />

<h2>⚙️ Scan Configuration</h2>
<p>
I created a new <strong>Discovery</strong> scan in Tenable and targeted the following cyber range subnets:
</p>

<ul>
  <li><code>10.0.0.0/21</code></li>
  <li><code>10.1.0.0/21</code></li>
</ul>

<p>
These ranges simulate a segmented enterprise network with multiple asset groups.
</p>

<img width="511" height="193" alt="image" src="https://github.com/user-attachments/assets/2942bd1f-5e88-471d-a01d-a22f8123f205" />

<hr />

<h2>🚀 Scan Execution</h2>
<p>
After configuring the targets, I launched the discovery scan and monitored execution.
</p>

<ul>
  <li>Validated scan launch and progress</li>
  <li>Waited for asset enumeration to complete</li>
</ul>

<img width="2079" height="205" alt="image" src="https://github.com/user-attachments/assets/f6e01c58-b45f-4b2b-9c4f-a3977b16ebe3" />

<hr />

<h2>📊 Results & Observations</h2>
<p>
Once complete, I reviewed the discovered assets and evaluated their characteristics.
</p>

<ul>
  <li>Identified live hosts responding within each subnet</li>
  <li>Observed asset patterns based on IP ranges</li>
  <li>Distinguished likely servers, endpoints, and infrastructure devices</li>
</ul>

<p><strong>📸 Screenshot:</strong> Discovered Assets List</p>
<p><em>[INSERT SCREENSHOT HERE]</em></p>

<hr />

<h2>🏷️ Asset Tagging Strategy</h2>
<p>
Based on the discovery results, I evaluated how assets could be logically tagged for ongoing security operations.
</p>

<ul>
  <li><strong>Environment:</strong> Cyber Range / Lab</li>
  <li><strong>Network Zone:</strong> 10.0.0.0/21 vs 10.1.0.0/21</li>
  <li><strong>Asset Type:</strong> Server / Workstation / Network Device</li>
  <li><strong>Criticality:</strong> High / Medium / Low</li>
  <li><strong>Ownership:</strong> Team, Student, or Project</li>
</ul>

<p><strong>📸 Screenshot:</strong> Asset Tagging View</p>
<p><em>[INSERT SCREENSHOT HERE]</em></p>

<hr />

<h2>🧠 SOC & Vulnerability Management Alignment</h2>
<p>
Discovery scanning is a foundational step in Vulnerability Management because assets must be identified before they can be assessed, prioritized, and remediated. This workflow supports asset inventory accuracy, scan scoping, and risk-based decision-making in SOC environments.
</p>

<hr />

<h2>🎯 Skills Demonstrated</h2>
<ul>
  <li>Attack surface discovery</li>
  <li>Network and subnet enumeration</li>
  <li>Asset inventory analysis</li>
  <li>Tenable discovery scanning</li>
  <li>SOC & Vulnerability Management fundamentals</li>
</ul>
