
<body>
<main id="top">
  <article>
    <header>
      <h1>Improved Efficiency of Fog and Cloud Computing Paradigms</h1>
      <p class="muted">A two-tier Fog–Cloud architecture for real-time, scalable, and energy-efficient smart grid computing.</p>
      <div class="taglist" aria-label="keywords">
        <span class="tag">Fog Computing</span>
        <span class="tag">Cloud</span>
        <span class="tag">Smart Grids</span>
        <span class="tag">IoT</span>
        <span class="tag">iFogSim</span>
      </div>
    </header>

  <hr />

  <section id="overview">
      <h2>Overview</h2>
      <p>
        This repository contains the research work <strong>“Improved Efficiency of Fog and Cloud Computing Paradigms”</strong>,
        which investigates how a <strong>two-tier Fog–Cloud architecture</strong> improves performance in smart grid systems.
        Traditional Cloud-only models centralize computation in remote data centers, causing <em>high latency</em>,
        <em>excessive bandwidth usage</em>, and <em>scalability issues</em> for real-time IoT applications.
      </p>
      <p>
        To overcome these limitations, we design and evaluate a Fog layer that pushes compute closer to data sources.
        The Fog tier provides fast local decision-making, reduces backhaul congestion, and lowers overall energy consumption,
        while the Cloud retains long-horizon analytics, storage, and coordination.
      </p>
    </section>

  <section id="why-fog-cloud">
      <h2>Why Fog + Cloud?</h2>
      <ul>
        <li><strong>Lower Latency:</strong> Edge processing enables immediate responses near data sources.</li>
        <li><strong>Reduced Congestion:</strong> Preprocessing/ filtering at Fog nodes cuts backbone traffic.</li>
        <li><strong>Energy Efficiency:</strong> Less redundant data movement and balanced workload distribution.</li>
        <li><strong>Better Scalability:</strong> Hierarchical compute tiering scales with device counts.</li>
      </ul>
    </section>

  <section id="architecture">
      <h2>Proposed Architecture</h2>
      <h3>1) Fog Layer (Edge Tier)</h3>
      <ul>
        <li>Situated close to IoT devices for local context awareness.</li>
        <li>Performs data preprocessing, filtering, and time-critical decisions.</li>
        <li>Relieves Cloud from bursty, latency-sensitive workloads.</li>
      </ul>
      <h3>2) Cloud Layer (Central Tier)</h3>
      <ul>
        <li>Handles large-scale analytics, historical storage, orchestration.</li>
        <li>Consumes <em>only</em> necessary/aggregated data from the Fog tier.</li>
        <li>Supports global optimization and long-term planning.</li>
      </ul>
    </section>

  <section id="evaluation">
      <h2>Simulation &amp; Evaluation</h2>
      <p>
        We evaluate the design using <strong>iFogSim</strong>, a simulator for Fog/Cloud environments, modeling realistic
        IoT dataflows and resource constraints. The key outcomes:
      </p>
      <div class="kpis" role="list">
        <div class="kpi" role="listitem"><strong>Latency Reduction:</strong> <br />≈ <strong>98.7%</strong> vs Cloud-only</div>
        <div class="kpi" role="listitem"><strong>Network Load:</strong> <br />Significantly lower backhaul traffic</div>
        <div class="kpi" role="listitem"><strong>Energy:</strong> <br />Reduced Cloud-side energy consumption</div>
        <div class="kpi" role="listitem"><strong>Scalability:</strong> <br />Improved with increasing IoT device counts</div>
      </div>
    </section>

  <section id="publication">
      <h2>Publication Details</h2>
      <ul>
        <li><strong>Conference:</strong> 2024 2nd International Conference on Advancements and Key Challenges in Green Energy and Computing (AKGEC)</li>
        <li><strong>Publisher/Indexing:</strong> IEEE Xplore</li>
        <li><strong>DOI:</strong> <a href="https://doi.org/10.1109/AKGEC62572.2024.10869278" target="_blank" rel="noopener">10.1109/AKGEC62572.2024.10869278</a></li>
        <li><strong>Dates:</strong> 21–23 November 2024</li>
        <li><strong>Location:</strong> Ghaziabad, India</li>
      </ul>
    </section>

  <section id="abstract">
      <h2>Abstract (Extended)</h2>
      <p>
        We propose a <strong>two-tier Fog–Cloud architecture</strong> to mitigate latency, congestion, and energy
        inefficiency in smart grids. The Fog layer intermediates IoT devices and the Cloud, executing preprocessing,
        filtering, and partial analytics locally. By offloading initial computation to Fog nodes, the system reduces
        dependency on Cloud servers for real-time decisions. Simulations using <em>iFogSim</em> show a
        <strong>98.7% latency reduction</strong>, decreased network congestion, and improved energy efficiency relative
        to Cloud-only models. Our findings indicate that Fog computing enables <em>responsive, sustainable, and scalable</em>
        IoT operations in smart grids, paving the way for intelligent, real-time energy management.
      </p>
    </section>

  <section id="contributors">
      <h2>Contributors</h2>
      <ul>
        <li>Ronit Wakankar</li>
        <li>Sumanyu Simhachalam</li>
        <li>Raghavendran Ganesan</li>
        <li>T. Velmurugan</li>
      </ul>
    </section>

  <section id="results">
      <h2>Results &amp; Visuals</h2>
      <figure>
        <img
          src="https://github.com/user-attachments/assets/0af8fecd-5fe4-4fdc-b082-db44024413dc"
          alt="Simulation results comparing Fog–Cloud vs Cloud-only models"
          style="max-width:100%;height:auto;"
          width="1200"
        />
        <figcaption>Performance comparison: Fog–Cloud vs Cloud-only models.</figcaption>
      </figure>
    </section>

  <section id="conclusion">
      <h2>Conclusion</h2>
      <p>
        A hybrid <strong>Fog–Cloud</strong> stack offers a practical alternative to centralized Cloud-only designs in
        IoT-heavy domains like smart grids. By placing computation near data sources, our approach
        <em>reduces latency</em>, <em>mitigates congestion</em>, and <em>improves energy efficiency</em>, all while
        preserving the Cloud’s strengths in global analytics and storage. The architecture supports <strong>real-time
        decision-making</strong> and scales gracefully with device growth, enabling reliable and sustainable smart-energy operations.
      </p>
    </section>

  <hr />

  <footer>
      <p class="muted">
        Repository name suggestion:
        <code>improved-efficiency-fog-cloud-computing</code>
      </p>
      <p class="muted">© Your Name / Contributors</p>
    </footer>
  </article>
</main>

<a class="toplink" href="#top" aria-label="Back to top">↑ Top</a>
</body>
</html>
