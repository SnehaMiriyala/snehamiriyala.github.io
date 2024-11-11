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
  <img src="images/ezofis.jpg?raw=true" alt="Ezofis" width="124" onclick="openModal('ezofisModal')">
  <img src="images/UC.png?raw=true" alt="Ultimate Coders" width="124" onclick="openModal('ucModal')">
</div>

<!-- Ezofis Modal -->
<div id="ezofisModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('ezofisModal')">&times;</span>
    <h3>Ezofis</h3>
    <p>Work experience at Ezofis...</p>
    <p><ul><li>Boosted Ticketing system performance by 30% through query and table structure optimizations, including subquery elimination and pre-join filtering.</li>Streamlined a unified view across 15 databases, implementing advanced indexing and partitioning strategies to enhance multi-database search efficiency.<li>Led end-to-end development of a Random Forest classifier for client demo, encompassing data preprocessing, feature engineering, model building, and deployment using Streamlit and FastAPI.</li>Engineered secure import/export functionality with dynamic table definition generation, encryption, and decryption processes, streamlining data transfer across systems.<li>Conducted POC for SingleStore implementation, integrating Azure pipelines and evaluating ML model performance across platforms.</li><li>Developed queries to identify modified columns in history tables, retrieving changes as JSON objects, and conducted table-level optimizations.</li></ul></p>
  </div>
</div>

<!-- Ultimate Coders Modal -->
<div id="ucModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('ucModal')">&times;</span>
    <h3>Ultimate Coders</h3>
    <p>Work experience at Ultimate Coders...</p>
    <p>Instructed students on various programming languages and domains, including - Python, Java, Web Design and Development (HTML5, CSS, JavaScript). Took on management responsibilities to ensure effective course delivery and curriculum alignment.</p>
  </div>
</div>

<!-- TCS Modal -->
<div id="tcsModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('tcsModal')">&times;</span>
    <h3>TCS</h3>
    <p>Work experience at TCS...</p>
    <p><ul><li>Gained proficiency in Data Analytics by employing complex SQL queries and procedures. Performed query tuning for optimal application response.</li><li>Developed Bash shell scripts for extracting metadata, conducting business validations, and triggering PL/SQL stored procedures to populate database tables.</li><li>Did the bidirectional data transfer between Teradata, Snowflake, and Oracle, leveraging AWS as the intermediary. Established and maintained disaster recovery pipelines from one Teradata system to another using Kafka, ensuring data synchronization and replication.</li><li>Successfully migrated from on-premises infrastructure to AWS+Snowflake Cloud Data Platform. Utilized Apache Airflow for seamless connection to Snowflake and implemented Snowflake's data processing layer with Python.</li><li>Demonstrated expertise in the entire software development lifecycle, encompassing requirement analysis, data pipeline design, coding, various testing phases, and deployment.</li></ul></p>
  </div>
</div>

<!-- MAQ Modal -->
<div id="maqModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('maqModal')">&times;</span>
    <h3>MAQ Software</h3>
    <p>Work experience at MAQ...</p>
    <p>Worked on projects
based on Business Intelligence, which involved technologies like T-SQL, SSIS, Multidimensional
Tabular Model(SSAS) and Power BI for reporting.</p>
  </div>
</div>
---
### Awards and Recognition

##### Performance Excellence Award
<img src="images/Special_Achievement_Award.jpg?raw=true"/>

##### Appreciation
<img src="images/Puneet_Appreciation.jpg?raw=true"/>

---
##### Recent Works

<div id="demo" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
    <li data-target="#demo" data-slide-to="3"></li>
    <li data-target="#demo" data-slide-to="4"></li>
    <li data-target="#demo" data-slide-to="5"></li>
    <li data-target="#demo" data-slide-to="6"></li>
    <li data-target="#demo" data-slide-to="7"></li>
  </ul>
  <!-- Slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active hoverEffect">
      <a href="https://github.com/snehalathatuniki/Music-Genre-Classification">
        <img src="https://github.com/snehalathatuniki/snehalathatuniki.github.io/assets/43737913/8bf3fe55-f21f-4830-9508-1e6add815292" alt="image"  width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Stock-Market-Analysis">
        <img src="https://github.com/snehalathatuniki/Stock-Market-Analysis/assets/43737913/6e30f41f-3fd7-41af-9e2e-9fec0ad8a41c" alt="Image 1" width="1000" height="300">
      </a>
      <div class="carousel-caption">
    </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Twitter_Sentimental_Analysis">
        <img src="/images/Sentiment-analysis-of-Twitter-Social.png?raw=true" alt="Image 1" width="1000" height="300">
      </a>
      <div class="carousel-caption">
    </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Toonifyme">
        <img src="https://github.com/snehalathatuniki/snehalathatuniki.github.io/assets/43737913/3b116097-3b88-4e3e-8ac0-0da47c589e7f" alt="Image 3" width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Linkedin_Analysis">
        <img src="https://github.com/snehalathatuniki/snehalathatuniki.github.io/assets/43737913/0f6114b4-cf2d-4582-911f-e47e23b2037e" alt="Image 1" width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Comparing_Cosmetics_by_Ingredients">
        <img src="https://github.com/snehalathatuniki/snehalathatuniki.github.io/assets/43737913/7ba54007-ff4a-417b-b0a6-b006c9e68531" alt="Image 1" width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
    <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/Image-Compression">
        <img src="https://github.com/snehalathatuniki/snehalathatuniki.github.io/assets/43737913/b4e8a146-0e30-4d1c-a396-26df4740a4f5" alt="Image 3" width="1000" height="300">
      </a>
      <div class="carousel-caption">
      </div>   
    </div>
     <div class="carousel-item hoverEffect">
      <a href="https://github.com/snehalathatuniki/AgroSelect/">
        <img src="https://github.com/snehalathatuniki/AgroSelect/assets/43737913/2087f190-b7e5-4b43-977b-db2bb7e93c78" alt="Image 1" width="1000" height="300">
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

### [My Resume](/pdf/SnehalathaTuniki_Resume.pdf)




