
<html lang="en">
 
<style>
  body {
    font-family: 'Inter', sans-serif;
    margin: 0;
    padding: 0;
    background: #f4f7f9;
    color: #222;
    line-height: 1.6;
  }

  header {
    background: linear-gradient(135deg, #003d66, #006699);
    color: white;
    padding: 2rem;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.15);
  }

  header h1 {
    margin: 0;
    font-size: 2.2rem;
  }

  header p {
    margin: 0.5rem 0 0;
    font-size: 1.1rem;
    font-weight: 300;
  }

  nav {
    margin-top: 1.5rem;
  }

  nav a {
    color: white;
    margin: 0 12px;
    text-decoration: none;
    font-weight: 600;
    border-bottom: 2px solid transparent;
    transition: border-bottom 0.3s ease;
  }

  nav a:hover {
    border-bottom: 2px solid #ffcc00;
  }

  main {
    max-width: 960px;
    margin: 2.5rem auto;
    padding: 0 1.5rem;
  }

  section {
    margin-bottom: 4rem;
  }

  h2 {
    color: #003d66;
    margin-bottom: 1rem;
    border-bottom: 2px solid #ccc;
    padding-bottom: 0.5rem;
  }

  .project {
    background: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 1.5rem;
    margin-bottom: 2rem;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease;
  }

  .project:hover {
    transform: translateY(-5px);
  }

  .project h3 {
    margin-top: 0;
    font-size: 1.3rem;
    color: #004466;
  }

  .project p {
    margin: 0.5rem 0;
  }

  .project a {
    color: #007acc;
    text-decoration: none;
    font-weight: 600;
  }

  .project a:hover {
    text-decoration: underline;
  }

  footer {
    text-align: center;
    padding: 2rem;
    background: #e6e6e6;
    font-size: 0.95rem;
    color: #444;
  }

  footer a {
    color: #004466;
    text-decoration: none;
    font-weight: 600;
  }

  footer a:hover {
    text-decoration: underline;
  }
</style>
  <header>
    <h1>Patrice Davis</h1>
    <p>Data Analyst | SQL • Python • Tableau • Excel</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="https://www.linkedin.com/in/patrice-davis-948817165/" target="_blank">LinkedIn</a>
      <a href="https://github.com/pdavis99/pdavis99.github.io" target="_blank">GitHub</a>
      <a href="Your_Resume_Link.pdf" target="_blank">Resume</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I'm an early-career data analyst with experience in SQL, Python, and Tableau. I enjoy turning messy data into clear, actionable insights and building clean, informative dashboards. Currently open to data analyst roles — particularly those focused on business insights and process improvement.
      </p>
    </section>

   <section id="projects">
      <h2>Featured Projects</h2>

   <div class="project">
        <h3>📊 Airbnb Listings Analysis (SQL)</h3>
        <p><strong>Problem:</strong> Analyzed NYC Airbnb data to identify pricing trends and popular locations.</p>
        <p><strong>Tools:</strong> PostgreSQL, Excel</p>
        <p><strong>Process:</strong> Wrote complex SQL queries using joins, window functions, and aggregations. Created summary tables for data visualization.</p>
        <p><strong>Result:</strong> Identified key drivers of price variation and proposed 3 data-backed recommendations.</p>
        <p><a href="https://github.com/yourusername/airbnb-sql-analysis" target="_blank">View Project on GitHub</a></p>
      </div>

   <div class="project">
        <h3>🐍 Web Scraping + EDA on Zillow Rentals</h3>
        <p><strong>Problem:</strong> Gathered rental price data from Zillow to explore trends in rental markets.</p>
        <p><strong>Tools:</strong> Python, BeautifulSoup, Pandas, Seaborn</p>
        <p><strong>Process:</strong> Scraped live data, cleaned and analyzed it, and visualized insights with matplotlib/seaborn.</p>
        <p><strong>Result:</strong> Highlighted trends in price per sq ft and visualized them by neighborhood.</p>
        <p><a href="https://github.com/yourusername/zillow-rentals-eda" target="_blank">View Project on GitHub</a></p>
      </div>

   <div class="project">
        <h3>📈 Business KPI Dashboard</h3>
        <p><strong>Problem:</strong> Built a Tableau dashboard to track sales KPIs over time.</p>
        <p><strong>Tools:</strong> Tableau, Excel</p>
        <p><strong>Process:</strong> Cleaned and joined data in Excel, then built an interactive dashboard in Tableau Public.</p>
        <p><strong>Result:</strong> Delivered a sleek dashboard that helps managers monitor sales, conversion rates, and regional performance.</p>
        <p><a href="https://public.tableau.com/app/profile/yourprofile/viz/KPI-Dashboard" target="_blank">View Dashboard</a></p>
      </div>

   </section>
  </main>

  <footer>
    © 2025 Patrice Davis • Built with 💻 & ☕ • <a href="mailto:pdavisiaa@gmail.com">Contact Me</a>
  </footer>
</html>
