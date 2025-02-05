## 👋 Welcome to My GitHub Profile

<div align="center">
  <div style="
      width: 500px; 
      border-radius: 10px; 
      border: 1px solid #ccc; 
      background: #1e1e1e;
      padding: 15px;
      font-family: monospace;
      color: #ddd;
      position: relative;
  ">
    <!-- File Tabs -->
    <div style="
        display: flex;
        background: #252526;
        padding: 5px 10px;
        border-radius: 6px 6px 0 0;
        font-size: 14px;
        color: #bbb;
    ">
      <span>📂 khatana.py</span>
    </div>

    <!-- Code Editor -->
    <pre style="
        margin: 10px 0;
        color: #f8f8f8;
    ">
<span style="color: #569cd6;">print</span>(<span style="color: #ce9178;">"Hello World"</span>)
    </pre>

    <!-- Run Button -->
    <button onclick="runCode()" style="
        background: #007acc;
        color: white;
        border: none;
        padding: 5px 10px;
        font-size: 14px;
        cursor: pointer;
        border-radius: 5px;
        position: absolute;
        right: 15px;
        bottom: 15px;
    ">▶ Run</button>

    <!-- Output Terminal -->
    <div id="output" style="
        margin-top: 10px;
        padding: 10px;
        background: #252526;
        color: #0f0;
        font-family: monospace;
        display: none;
        border-radius: 5px;
    "></div>
  </div>
</div>

<!-- JavaScript -->
<script>
  function runCode() {
    document.getElementById('output').style.display = 'block';
    document.getElementById('output').innerText = 'Hello World';
  }
</script>
