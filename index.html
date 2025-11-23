<body>
<div class="container">
  <div class="header">
    <h1>📊 Master Investment Checklist</h1>
    <h1>📊 Quality Investment Checklist</h1>
    <p>Bill Ackman's Quality Framework + Mohnish Pabrai's Dhando Principles</p>
  </div>

  <!-- Stock Input Section -->
  <div class="stock-input-section">
    <label for="stockCode">Enter Stock Code:</label>
    <input type="text" id="stockCode" placeholder="e.g., AAPL">
    <button class="btn" onclick="showStockResult()">✅ Check Stock</button>
  </div>

  <!-- Checklist Section -->
  <div class="progress-section">
    <div class="progress-bar-container">
      <div class="progress-bar" id="progressBar">0%</div>
    </div>
    <div class="progress-text" id="progressText">0 of 18 criteria met</div>
  </div>
  <div class="scrollable-content" id="checklistContainer"></div>

  <div class="actions">
    <button class="btn btn-reset" onclick="resetChecklist()">🔄 Reset All</button>
    <button class="btn btn-print" onclick="window.print()">🖨️ Print Checklist</button>
  </div>

  <!-- Stock Result Display -->
  <div id="stockResult" style="margin-top:20px; font-weight:bold;"></div>

  <div class="footer">
    <p>📧 Feedback? Email: <a href="mailto:will@willfaulkner.com">will@willfaulkner.com</a></p>
  </div>
</div>

<script>
// Checklist code remains mostly the same
const checklistSections = [ /* your checklistSections here */ ];

let checkedItems = {};

function initChecklist() {
  loadProgress();
  renderChecklist();
  updateProgress();
}

function renderChecklist() {
  const container = document.getElementById('checklistContainer');
  container.innerHTML = '';

  let globalIndex = 0;

  checklistSections.forEach((section) => {
    const sectionHeader = document.createElement('div');
    sectionHeader.className = 'section-header';
    sectionHeader.innerHTML = `
      <div class="section-title">${section.title}</div>
      <div class="section-subtitle">${section.subtitle}</div>
    `;
    container.appendChild(sectionHeader);

    const checklist = document.createElement('div');
    checklist.className = 'checklist';

    section.items.forEach((item) => {
      const isChecked = checkedItems[globalIndex] || false;

      const itemDiv = document.createElement('div');
      itemDiv.className = `checklist-item ${isChecked ? 'checked' : ''}`;
      itemDiv.innerHTML = `
        <label style="display:flex; align-items:flex-start; gap:8px; cursor:pointer;">
          <input type="checkbox" ${isChecked ? 'checked' : ''} onchange="toggleItem(${globalIndex})">
          <div>
            <div class="item-title">${item.title}</div>
            <div class="item-description">${item.description}</div>
          </div>
        </label>
      `;
      checklist.appendChild(itemDiv);
      globalIndex++;
    });

    container.appendChild(checklist);
  });
}

function getTotalItems() {
  return checklistSections.reduce((total, section) => total + section.items.length, 0);
}

function toggleItem(index) {
  checkedItems[index] = !checkedItems[index];
  saveProgress();
  renderChecklist();
  updateProgress();
}

function updateProgress() {
  const total = getTotalItems();
  const checkedCount = Object.values(checkedItems).filter(Boolean).length;
  const percentage = Math.round((checkedCount / total) * 100);
  const progressBar = document.getElementById('progressBar');
  const progressText = document.getElementById('progressText');

  progressBar.style.width = percentage + '%';
  progressBar.textContent = percentage + '%';
  progressText.textContent = `${checkedCount} of ${total} criteria met`;
}

function saveProgress() {
  localStorage.setItem('masterInvestmentChecklist', JSON.stringify(checkedItems));
}

function loadProgress() {
  const saved = localStorage.getItem('masterInvestmentChecklist');
  if (saved) {
    checkedItems = JSON.parse(saved);
  }
}

function resetChecklist() {
  if (confirm('Are you sure you want to reset all checkboxes?')) {
    checkedItems = {};
    saveProgress();
    renderChecklist();
    updateProgress();
  }
}

// New function to show stock result
function showStockResult() {
  const stockCode = document.getElementById('stockCode').value.trim().toUpperCase();
  const resultDiv = document.ge
