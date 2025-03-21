
<section class="dashboard-preview">
  <div class="dashboard-container">
    <div class="dashboard-frame">
      <img src = "/images/Dashboardpreview.png" alt = "Dashboard Preview">
      <img class="aspire-logo" src="/images/aspirelogo.png" alt="Aspire Logo">
      <img class="bottom-overlay" src="/images/bottom_dashboard.png" alt="Dashboard Bottom">
    </div>
  </div>

    <div class="integrations">
        <img src="/images/Click_up.png" /> 
        <img src="/images/Dropbox.png" /> 
        <img src="/images/Segment.png" /> 
        <img src="/images/freshbooks.png" /> 
        <img src="/images/GitHub.png" /> 
    </div>
</section>

<style>
  .dashboard-preview {
    padding: 2rem 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
  }

  .dashboard-container {
    max-width: 900px;
    width: 100%;
    position: relative;
    background-image: url('/images/Product screenshot bg.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    border-radius: 16px;
    padding: 0.75rem;

  }

  .dashboard-frame {
    position: relative;
    border-radius: 16px;
    background: #fefefe;
    background: transparent;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

  }

  .dashboard-frame img:first-of-type {
  width: 100%;
  height: auto;
  border-radius: 16px;
  position: relative;
  z-index: 2; 
  }

  .integrations {
    display: flex;
    align-items: center;
    gap: 5rem;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 5rem;
  }

  .integrations img {
    height: 24px;
    width: auto;
    opacity: 0.8;
    transition: opacity 0.2s;
  }

  .integrations img:hover {
    opacity: 1;
  }

  .bottom-overlay {
  position: absolute;
  width: 87%;
  max-width: 700px; 
  left: 50%; 
  transform: translateX(-50%); 
  bottom: -55px; 
  z-index: 3; 


  }

  .aspire-logo {
    position: absolute;
    top: 5%;
    left: 2%;
    width: 120px;
    z-index: 4;
    
}


</style>