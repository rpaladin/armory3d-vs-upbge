<div align="center">
  <h1>Armory3D 🆚 UPBGE</h1>
  <p>A detailed comparison of pros and cons for <a href="https://www.armory3d.org">Armory3D</a> &amp; <a href="https://www.upbge.org">UPBGE</a></p>
</div>
<table align="center">
  <tr>
    <th>‎</th>
    <th>
      <br />
      <img src="https://avatars.githubusercontent.com/u/20436620?s=200&v=4" width=64 alt="Armory3D Logo" />
      <p>Armory3D</p>
    </th>
    <th>
      <br />
      <img src="https://avatars.githubusercontent.com/u/16006310?s=200&v=4" width=64 alt="UPBGE Logo" />
      <p>UPBGE</p>
    </th>
  </tr>
  <!-- Blender Foundation Support -->
  <tr align="center">
    <td>Blender Foundation Support</td>
    <td><a href="https://www.youtube.com/watch?v=EaMT6Nyu79w">Officially</a></td>
    <td><a href="https://www.youtube.com/watch?v=hS7iV3NfddI&start=512">Unofficially</a></td>
  </tr>
   <!-- Development Status -->
  <tr align="center">
    <td>Development Status</td>
    <td>Original creator, <a href="https://www.github.com/luboslenco">Lubos Lenco</a>, has moved on to <a href="https://www.armorpaint.org">ArmorPaint</a> after being awarded a <a href="https://www.youtube.com/watch?v=M1X2Qdz8QDc">EpicMegaGrant</a> by Epic Games<br />(company of Unreal Engine)<br />Current development is maintained by community contributors</td>
    <td>A spin-off of Blender's old Game Engine<br />Original creator, <a href="https://www.github.com/panzergame">Tristan Porteries</a>, stopped development after internal disagreements with the organization team, external & internal pressure, and additionally some in-real-life distractions<br />The project is maintained by community contributors</td>
  </tr>
  <!-- Development Roadmap -->
  <tr align="center">
    <td>Development Roadmap</td>
    <td>No exact roadmap is specified except for monthly core & bug-fix contributions by the community</td>
    <td>Only bug fixes - awaiting Blender developers for Vulkan Port, EEVEE Rewrite & Real-Time Compositing Nodes</td>
  </tr>
  <!-- Development Team -->
  <tr align="center">
    <td>Development Team</td>
    <td><a href="https://www.github.com/MoritzBrueckner">MoritzBrueckner</a>, <a href="https://www.github.com/tong">tong</a>, <a href="https://www.github.com/QuantumCoderQC">QuantumCoderQC</a><br /><a href="https://www.github.com/rpaladin">RPaladin</a>, <a href="https://www.github.com/Naxela">Naxela</a></td>
      <td><a href="https://www.github.com/youle31">youle31</a>, <a href="https://www.github.com/lordloki">lordloki</a>, <a href="https://www.github.com/izazed">izazed</a>, <a href="https://www.github.com/mysticfall">mysticfall</a></td>
  </tr>
  <!-- Community -->
  <tr align="center">
    <td>Community</td>
    <td>Large <a href="https://discord.gg/axq6qWV">community</a>,<br />but minimal activity beyond contributors</td>
    <td>Small, but very active <a href="https://discord.gg/DsTJ8Ga">community</a></td>
  </tr>
  <!-- Learning -->
  <tr align="center">
    <td>Learning</td>
    <td>Some tutorials, many are outdated.<br />Mnual is up to date however and is actively maintained.</td>
    <td>Very many tutorials, but most are outdated or simply incompatible due to UPBGE 0.2.x/0.3.x version variations.<br />Official Blender tutorials work well with UPBGE 0.3+ versions however. And new tutorials are being made by several contributors arbitrarily time to time.</td>
  </tr>
  <!-- Showcase -->
  <tr align="center">
    <td>Showcase</td>
    <td>Not exactly many "made with Armory3D" AAA game examples to direct people to except for the official <a href="https://www.github.com/armory3d/armory/wiki/Games-made-with-Armory">wiki games list</a><br />This may be caused by the game-engine being relatively new and/or rumors that development is dead; which it's not, at least not fully so<br />There is however an impressive collection of real-time, browser <a href="https://armory3d.github.io/armory_examples_browser/">demo examples</a> available to the public</td>
    <td>Being a fork of Blender's former Game Engine, UPBGE has a good and semi-long history of making AAA quality games<br />However, performance has always been one of the major negatives surrounding, thus preventing it for professional usage in the long term<br />This doesn't mean it's not bad for short-term, personal projects however!!</td>
  </tr>
  <!-- Blender Compatibility -->
  <tr align="center">
    <td>Blender Compatibility</td>
    <td>Blender 2.93.8 LTS<br />&<br />Blender 2.79 <a href="https://github.com/armory3d/armsdk/releases?q=0&expanded=true">(legacy/outdated)</a></td>
    <td>Blender 3.2 (Alpha)<br />&<br />Blender 2.79.7 (outdated/legacy)</td>
  </tr>
  <!-- Integration Method -->
  <tr align="center">
    <td>Integration Method</td>
    <td>Add-On</td>
    <td>Cloned (and modified) Source</td>
  </tr>
  <!-- Runtime Compatibility -->
  <tr align="center">
    <td>Runtime Compatibility</td>
    <td>Compatibility differences between Blender & Armory Player are moderately high<br />Additional unsupported elements can be seen <a href="https://www.github.com/armory3d/armory/wiki/supported_nodes">here</a> & <a href="https://www.github.com/armory3d/armory/wiki/supported_particles">here</a></td>
    <td>Impressive ~95% Blender graphics compatibility<br />at runtime including BPY code!</td>
  </tr>
  <!-- Software Reliability -->
  <tr align="center">
    <td>Software Reliability</td>
    <td>Tends to crash a lot</a></td>
    <td>Moderately bug free</td>
  </tr>
  <!-- Supported Platforms -->
  <tr align="center">
    <td>Supported Platforms</td>
    <td>Desktop, Mobile, Browser, Console, <a href="https://github.com/armory3d/armory/wiki">more</a></td>
    <td>Desktop</td>
  </tr>
  <!-- Logic Methods -->
  <tr align="center">
    <td>Logic Methods</td>
    <td>Haxe, C, Rust, WASM, JavaScript, Logic-Nodes</td>
    <td>Python, Python Components, Logic-Nodes, Logic-Bricks</td>
  </tr>
</table>
