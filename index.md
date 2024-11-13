<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

## Portfolio
---


### About Me

- I worked as a Software Engineer at Ellucian and as an SvC Info Developer at HPE, where I gained extensive experience in software development and system management.
- My journey spans frontend development with React.js and backend integration with Node.js, alongside experience in cloud services and automation tools like Docker and AWS.
- I am passionate about creating user-friendly applications, solving complex problems, and continuously exploring new technologies to deliver impactful solutions.

---
<style>
    .hoverEffect img {
        transition: transform 0.3s; 
    }
    .hoverEffect img:hover {
        transform: scale(1.1); 
        cursor: pointer;
    }
    /* Styles for the Modal */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0,0,0,0.4);
}

.modal-content {
  background-color: #fefefe;
  margin: auto;
  padding: 20px;
  border: 1px solid #888;
  width: 80%;
}

.close {
  color: #aaaaaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
}
</style>
<!-- Your Work Experience Section -->
<div align="Center" style="margin: 10px" class="hoverEffect"> 
  <img src="images/ellucian.png?raw=true" alt="Ezofis" width="464" onclick="openModal('ellucianModal')">
  <img src="images/hpe.png?raw=true" alt="Ultimate Coders" width="324" onclick="openModal('hpeModal')">
</div>

<!-- Ellucian Modal -->
<div id="ellucianModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('ellucianModal')">&times;</span>
    <h3>Ellucian</h3>
    <p>Work experience at Ellucian...</p>
    <p><ul><li>Designed and implemented RESTful APIs to streamline service communication, reducing data retrieval times by 20% through optimized database queries and proactive performance tuning, ensuring efficient, high-speed service integration.</li><li>Led the migration of existing on-premise solutions to a SaaS platform, transforming legacy applications into flexible, cloud-based services that optimized accessibility, lowered maintenance requirements, and supported ongoing scaling needs.</li><li>Built and maintained interactive, responsive UIs using React.js, delivering a streamlined and visually engaging user experience across devices, which increased user satisfaction ratings by 15%.</li><li>Collaborated with the quality assurance team by assisting with software testing, investigating and documenting bugs, and developing test cases to support test-driven development, ensuring high software quality and performance standards.</li><li>Demonstrated expertise in the entire software development lifecycle, encompassing requirement analysis, data pipeline design, coding, various testing phases, and deployment, which led to fewer post-deployment defects and smoother project transitions.</li></ul></p>
  </div>
</div>

<!-- HPE Modal -->
<div id="hpeModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('hpeModal')">&times;</span>
    <h3>Hewlett Packard Enterprise</h3>
    <p>Work experience at Hewlett Packard Enterprise...</p>
   <p><ul><li>Acted as a Subject Matter Expert (SME) and led Incident Management calls while managing change management for three applications. Maintained data accuracy and prevented future discrepancies by updating and validating incident tickets using ServiceNow.</li><li>Reproduced issues and analyzed application logs and system logs by integrating system components into Splunk, AppDynamics to identify root causes of issues and provide solutions to customers.</li><li>Identified and documented potential software/hardware defects, authorized and reviewed technical documentation, and corrected non-conformances with processes and documentation.</li> <li>Collaborated with development teams to identify, troubleshoot, and resolve software bugs and issues. Created new/updated Knowledge Base documentation as required, fostered open team communication, and shared knowledge openly.</li><li>Conducted user acceptance testing, resulting in on-time and successful enterprise implementations for up to 1 million users.</li><li>Developed and maintained scripts using Ansible to automate repetitive tasks, improving efficiency and reducing downtime.</li></ul></p>
  </div>
</div>

---
### Awards and Recognition

##### Star Recognition Award
<img src="images/star_recognition.png?raw=true"/>

##### Appreciation
<img src="images/appreciation.png?raw=true"/>

---
##### Recent Works

<div id="demo" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
  
  </ul>
  <!-- Slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active hoverEffect">
      <a href="https://github.com/snehamiriyala/tic-tac-toe-game">
        <img src="https://github.com/user-attachments/assets/f562c217-4fde-4803-b109-1495deaa59e7" alt="image1"  width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
       <div class="carousel-item active hoverEffect">
      <a href="https://github.com/snehamiriyala/react-investment-calculator">
        <img src="https://github.com/user-attachments/assets/15e25561-f69a-4d6e-9a93-aca3cbb8e4e9" alt="image2"  width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
  </div>
  <!-- Left and right controls -->
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>

<script> 
    function openModal(modalId) {
  document.getElementById(modalId).style.display = "block";
}
function closeModal(modalId) {
  document.getElementById(modalId).style.display = "none";
}
</script>
<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Bootstrap JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

---

### [My Resume](/pdf/SnehaMiriyala_Resume.pdf)




