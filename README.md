# Research Projects

Hello! Welcome to my portfolio repository. These are the workings of some projects during my stint as a Senior Research Asst. at SUTD (and my graduation thesis from TU Delft). My work here delved into urban challenges of modern cities and the different approaches used to tackle them: community engagement through participatory design, GIS and data science. Each link leads to an elaboration of each phase and the documentation in code. 

<br>

<div class="project-cards">

  <a href="https://urbanjeans.github.io/dfn-dashboard" target="_blank" class="card-link">
    <div class="card">
      <img src="assets/img/Habitats and Tree Canopy.png" alt="Map of natural spaces in Singapore" />
      <div class="card-text">
        Good Public Spaces: Mapping natural habitats in Singapore with remote sensing and government datasets
      </div>
    </div>
  </a>

  <a href="https://urbanjeans.github.io/dfn-dashboard" target="_blank" class="card-link">
    <div class="card">
      <img src="assets/img/Accessibility.png" alt="Accessibility map of natural spaces in Singapore" />
      <div class="card-text">
        Good Public Spaces: Mapping accessibility of nature spaces across Singapore
      </div>
    </div>
  </a>

  <a href="https://urbanjeans.github.io/dfn-dashboard" target="_blank" class="card-link">
    <div class="card">
      <img src="assets/img/1990s.png" alt="Map of provision shops in singapore in 1990 (part of a timelapse series of maps)" />
      <div class="card-text">
        The Modern Mamak: mapping mamak shops since the 1980s
      </div>
    </div>
  </a>

  <a href="https://urbanjeans.github.io/dfn-dashboard" target="_blank" class="card-link">
    <div class="card">
      <img src="assets/img/spearmanns.png" alt="Spearman's correlation between provision shops and supermarkets and HDBs" />
      <div class="card-text">
        The Modern Mamak: Exploritory Data Analsyis (EDA) of mamak shops in Singapore
      </div>
    </div>
  </a>

  <a href="https://urbanjeans.github.io/dfn-dashboard" target="_blank" class="card-link">
  <div class="card">
    <img src="assets/img/mindmap.png" alt="Concept map of common themes of shop owner participants and local communities" />
    <div class="card-text">
      The Modern Mamak: Preliminary analysis of interviews and shop owners' participation
    </div>
  </div>
</a>


<hr>


<style>
header img {
  width: 140px !important;
  height: auto !important;
}   

a {
  color: #b20738;
  font-weight: 400;        
  text-decoration: none;
}

a:hover {
  color: #b20738;
  text-decoration: none;
  font-weight: 400;       
}
  

  
.project-cards {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 1rem;
  justify-content: space-between;
  box-sizing: border-box;
}

.card {
  border: 0.7px solid #ddd;
  padding: 1rem;
  border-radius: 3px;
  background-color: #ffffff;
  transition: transform 0.2s;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  height: 100%;
  box-sizing: border-box;
}

.card:hover {
  transform: scale(1.02);
}

.card img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 3px;
  display: block;
  margin: 0 auto;
}

.card-link {
  display: block;
  text-decoration: none;
  color: inherit;
  width: calc(50% - 10px); 
  box-sizing: border-box;
}

.card-text {
  margin-top: 0.5rem;
  font-weight: 500;
  font-size: 0.75rem;
}

@media (max-width: 768px) {
  .card-link {
    flex: 1 1 100%;
    max-width: 100%;
  }
}
</style>
