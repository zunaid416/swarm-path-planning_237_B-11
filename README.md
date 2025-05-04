<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A* Algorithm in Robotics Path Planning</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; background-color: #f4f4f4; }
    header, footer { background: #333; color: #fff; padding: 20px 0; text-align: center; }
    .container { padding: 20px; max-width: 1000px; margin: auto; background: #fff; }
    h1, h2, h3 { color: #333; }
    .gallery img { width: 100%; max-width: 400px; margin: 10px; }
    .about, .methodology, .results, .future { margin-bottom: 40px; }
    footer small { display: block; margin-top: 10px; color: #ccc; }
  </style>
</head>
<body>

  <header>
    <h1>A* Algorithm in Robotics Path Planning</h1>
    <p>Group B11 | Islamic University Of Technology</p>
  </header>

  <div class="container">
    <section class="about">
      <h2>Background & Motivation</h2>
      <p>
        Inspired by biological systems such as ants and bees, our project explores the integration of swarm robotics with path planning algorithms. Our goal was to design a decentralized, efficient robotic system for real-world applications like search and rescue.
      </p>
      <p>
        With the help of simulations in ROS and Gazebo, our swarm leverages PSO for coordination and RRT*/TEB for path planning and obstacle avoidance. This marks a new chapter in collaborative robot navigation.
      </p>
    </section>

    <section class="objectives">
      <h2>Objectives</h2>
      <ul>
        <li>Develop a robust simulation combining swarm robotics and path planning</li>
        <li>Analyze performance in dynamic environments</li>
        <li>Explore decentralized control mechanisms</li>
        <li>Lay groundwork for future real-world deployment</li>
      </ul>
    </section>

    <section class="gallery">
      <h2>Gallery</h2>
      <img src="gazebo_world_example.jpg" alt="Gazebo Swarm World" />
      <img src="swarm_path_output.png" alt="Path Planning Output" />
      <p><small>Note: Replace placeholders with actual images/screenshots from your project.</small></p>
    </section>

    <section class="methodology">
      <h2>Methodology</h2>
      <p>
        Our robots initialize in a Gazebo-simulated world using ROS. Each uses the RRT* algorithm for global planning and TEB for local adjustments. PSO coordinates the swarm behavior, enabling robust obstacle avoidance and path optimization.
      </p>
      <pre><code>class Particle:
    def update_velocity(...):
        # PSO logic

def rrt_star(...):
    # Node expansion for path finding
      </code></pre>
    </section>

    <section class="results">
      <h2>Results & Analysis</h2>
      <p>
        Robots demonstrated smooth coordination and effective navigation around obstacles. Simulated results confirmed the efficiency of decentralized control and advanced planning strategies.
      </p>
    </section>

    <section class="future">
      <h2>Future Work</h2>
      <p>
        Future development includes hardware implementation, adaptation for highly dynamic environments, and real-time sensor integration.
      </p>
    </section>

    <section class="references">
      <h2>References</h2>
      <ul>
        <li>Obstacle Avoidance Motion in Mobile Robotics – Yunchao Tang et al.</li>
        <li>Swarm Robotics: Cooperative Control in Multi-Agent Systems – Venkata Ramana Devi et al.</li>
        <li>Route planning of mobile robot using improved RRT* and TEB – XiongYin et al.</li>
      </ul>
    </section>
  </div>

  <footer>
    <p>Group B11 – A* in Robotics Path Planning</p>
    <small>Instructor: Md Arefin Rabbi Emon | Submitted: 21 March 2025</small>
  </footer>

</body>
</html>
