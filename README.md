<h1 align="center">ESP32-S3 Numpad (Bluetooth/USB)</h1>

<h2>Project Overview</h2>
<p>
This project is a custom 12-key numpad built around the ESP32-S3-WROOM-1 module. 
The system supports both Bluetooth Low Energy (BLE) HID and <b>USB HID</b> operation, allowing it to function as a standalone wireless or wired keyboard.
</p>

<h2>Hardware Features</h2>
<ul>
  <li><b>Key Input</b>:
    <ul>
      <li>12 individual mechanical switch footprints arranged in a numpad configuration</li>
      <li>Direct GPIO mapping for reduced latency</li>
      <li>Internal pull-up resistors utilized for simplified hardware design</li>
    </ul>
  </li>
  <li><b>Power Management</b>:
    <ul>
      <li>BQ24074 battery charger and power-path management IC</li>
      <li>Supports single-cell Li-ion battery charging</li>
      <li>Simultaneous operation while charging via USB</li>
    </ul>
  </li>
  <li><b>Connectivity</b>:
    <ul>
      <li>USB 2.0 connector for both data and power</li>
      <li>Integrated ESD protection on USB data lines via TVS diode</li>
    </ul>
  </li>
  <li><b>System Control</b>:
    <ul>
      <li>Dedicated reset button for programming and debugging</li>
    </ul>
  </li>
  <li><b>PCB Design</b>:
    <ul>
      <li>Developed in Altium</li>
    </ul>
  </li>
</ul>

<h2>Firmware Features</h2>
<ul>
  <li>Implemented using the Arduino framework for ESP32</li>
  <li>Provides both BLE HID keyboard and <b>USB HID keyboard</b> operation</li>
  <li>Automatic deep sleep feature after 3 minutes of inactivity</li>
</ul>

<h2>Repository Structure</h2>
<ul>
  <li><code>/hardware</code> – Altium schematic and PCB layout files</li>
  <li><code>/firmware</code> – Source code for ESP32-S3 (Arduino framework)</li>
  <li><code>/images</code> – Images</li>
</ul>

<h2>Potential Extensions</h2>
<ul>
  <li>RGB backlighting integration</li>
  <li>Expansion to larger key matrices or custom layouts</li>
</ul>
