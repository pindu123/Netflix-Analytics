<!-- README.md (HTML version) -->
<div align="center">
  <h1>📊 Netflix Data Power BI Dashboard</h1>
  <p><em>Shows Overview · Content Popularity · User Engagement</em></p>
</div>

<!-- Content wrapper for nicer alignment on wide screens -->
<div style="max-width: 960px; margin: 0 auto; line-height: 1.6; font-size: 16px;">

  <!-- Quick nav -->
  <p align="center">
    <a href="#overview">Overview</a> •
    <a href="#dataset-description">Dataset</a> •
    <a href="#report-pages--key-insights">Report Pages</a> •
    <a href="#usage">Usage</a>
  </p>

  <h2 id="overview">📌 Overview</h2>
  <p>
    This Power BI dashboard provides a comprehensive view of Netflix content performance, audience engagement,
    and platform usage. The dataset combines metadata about shows with user behavior and engagement metrics,
    enabling deep insights into <strong>content strategy, viewer preferences, and platform stickiness</strong>.
  </p>

  <p>The report is organized into <strong>three pages</strong>:</p>
  <ul>
    <li><strong>Shows Overview</strong> – High-level summary of Netflix catalog and key distribution metrics</li>
    <li><strong>Content Popularity</strong> – Analysis of most-watched and most-liked shows</li>
    <li><strong>User Engagement</strong> – Insights into audience behavior, watch time, and stickiness</li>
  </ul>

  <h2 id="dataset-description">📂 Dataset Description</h2>
  <!-- Using a definition list keeps names & meanings aligned cleanly -->
  <dl>
    <dt><code>show_id</code></dt><dd>Unique identifier for each show</dd>
    <dt><code>type</code></dt><dd>Category (Movie / TV Show)</dd>
    <dt><code>title</code></dt><dd>Show title</dd>
    <dt><code>director</code></dt><dd>Director of the show/movie</dd>
    <dt><code>cast</code></dt><dd>Main cast members</dd>
    <dt><code>country</code></dt><dd>Country of production</dd>
    <dt><code>date_added</code></dt><dd>Date when the show was added to Netflix</dd>
    <dt><code>release_year</code></dt><dd>Year of release</dd>
    <dt><code>rating</code></dt><dd>Official maturity rating (e.g., PG, R, TV-MA)</dd>
    <dt><code>duration</code></dt><dd>Duration (minutes for movies, seasons for series)</dd>
    <dt><code>listed_in</code></dt><dd>Genres or categories the content belongs to</dd>
    <dt><code>description</code></dt><dd>Short description of the show</dd>
    <dt><code>total_views</code></dt><dd>Total views received</dd>
    <dt><code>unique_viewers</code></dt><dd>Number of unique viewers</dd>
    <dt><code>avg_watch_time_minutes</code></dt><dd>Average time spent watching</dd>
    <dt><code>completion_rate</code></dt><dd>% of viewers completing the show/movie</dd>
    <dt><code>likes</code></dt><dd>Number of likes received</dd>
    <dt><code>shares</code></dt><dd>Number of shares/recommendations</dd>
    <dt><code>avg_rating_by_users</code></dt><dd>Average user rating</dd>
    <dt><code>watch_sessions</code></dt><dd>Number of viewing sessions</dd>
    <dt><code>stickiness_score</code></dt><dd>Measure of repeat engagement</dd>
    <dt><code>subscription_uplift_rate</code></dt><dd>% contribution to new subscriptions</dd>
    <dt><code>favored_device</code></dt><dd>Most common device used for watching</dd>
    <dt><code>first_content_for_new_users_flag</code></dt><dd>Whether the show was the first watched by new users</dd>
    <dt><code>peak_viewing_hour</code></dt><dd>Time of day with peak engagement</dd>
    <dt><code>peak_viewing_region</code></dt><dd>Region where the content peaks in views</dd>
  </dl>

  <h2 id="report-pages--key-insights">🎯 Report Pages &amp; Key Insights</h2>

  <!-- Page 1 -->
  <h3>1️⃣ Shows Overview</h3>
  <ul>
    <li>Content distribution by <strong>type (Movies vs. TV Shows)</strong></li>
    <li>Trends by <strong>release year, genre, and region</strong></li>
    <li>Availability patterns based on <strong>date added</strong></li>
  </ul>
  <p align="center">
<img width="1140" height="624" alt="image" src="https://github.com/user-attachments/assets/377b3143-5461-4780-83a7-a4baa217f126" />
  </p>

  <!-- Page 2 -->
  <h3>2️⃣ Content Popularity</h3>
  <ul>
    <li>Top shows by <strong>total views, unique viewers, and likes</strong></li>
    <li>Most <strong>shared</strong> and <strong>highly rated</strong> titles</li>
    <li>Peak <strong>regional</strong> and <strong>time-based</strong> viewing trends</li>
  </ul>
  <p align="center">
<img width="1123" height="632" alt="image" src="https://github.com/user-attachments/assets/ae4d16a6-cc5b-49dd-9606-a64b969d8897" />
  </p>

  <!-- Page 3 -->
  <h3>3️⃣ User Engagement</h3>
  <ul>
    <li>Insights into <strong>watch sessions, avg watch time, and completion rate</strong></li>
    <li>Analysis of <strong>stickiness score</strong> and retention patterns</li>
    <li>Impact on <strong>subscription uplift</strong> &amp; <strong>new user behavior</strong></li>
    <li><strong>Favored device</strong> usage patterns</li>
  </ul>
  <p align="center">
    <img width="1134" height="634" alt="image" src="https://github.com/user-attachments/assets/fce8e769-fa4f-4082-9de2-724cbef2b67a" />
   </p>
  <br>
  <p align="center">
    <sub>Made with ❤️ in Power BI</sub>
  </p>
</div>

