 <h2><p align ="center"> Phishing-Email-Analysis-Report</p></h2>
 <h2><p align ="center"> By:</p</h2>
<h2><p align ="center"> Ogunsanwo Adeniyi Nelly, Cybersecurity Analyst</p</h2
                                                                           <h2><p align ="center"> Date 24th of April 2025</p></h2>



<br>
<h3> <li>Phishing Email Analysis Summary</li></h3>
Performed a detailed investigation of a suspicious email received through the corporate email gateway. The message was securely isolated in a sandboxed Virtual environment and analyzed using advanced techniques, including header inspection, URL reputation checks, and threat intelligence correlation. Findings confirmed the email was a phishing attempt aimed at directing users to a malicious link for potential credential compromise or malware delivery.
 








<h3><li> Email Metadata Analysis</li></h3>


<b>1. Sender Information</b>

 <ul>
  <li> <strong>Return Path:</strong> apache@sk.globalexceltrade.xyz </li>
  
   <li> <strong> SeSender IP Address:</strong> 151.80.93.107 </li>
   <li> <strong>IP Reputation Check (AbuseIPDB):</strong>  No existing reports were freports does not indicate safety, especially given the suspicious context.ound for this IP address in the AbuseIPDB database. However, the lack of </li> 
</ul>






<img src = "Folder/sample 3501.jpg">

<li> <b>⦁	nding Server:</b> SJ1P223MB0531.NAMP223.PROD.OUTLOOK.COM (::1)
</li>


<br>

<li> <h3>2 Email Authentication Results</h3> </li>

<li> <b>	SPF (Sender Policy Framework):</b> PASS </li>
<br>
<li>  	The SPF record validated successfully, suggesting that the sending server is authorized to send mail on behalf of the domain. However, SPF alone is not a reliable indicator of legitimacy.  </li>

<br>
<li> <b>	DKIM (DomainKeys Identified Mail):</b> NONE   </li>
</br>

<li> 	No DKIM signature was present, indicating the email was not cryptographically signed. This reduces the credibility and makes the email susceptible to spoofing.  </li>
<br>
<li> <b>DMARC (Domain-based Message Authentication, Reporting, and Conformance):</b> NONE  </li>
<br>
<li> 	The domain lacks a DMARC policy, increasing the likelihood of unauthorized use and spoofing. </li>

<br>


<li>  <h3>3 Embedded URL Analysis</h3> </li>

<li>  <b>1 Suspicious Link</b>  </li>

<li> 	<strong>URL Found in Email:</strong> <a href="https://innovatech.website"></a> 
