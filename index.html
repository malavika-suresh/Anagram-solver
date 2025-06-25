<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Professional Anagram Solver tool that finds meaningful words from scrambled letters using common English vocabulary">
  <title>Advanced Anagram Solver | Find Meaningful Word Combinations</title>
  <style>
    :root {
      --primary-color: #4f46e5;
      --primary-hover: #4338ca;
      --secondary-color: #e0e7ff;
      --text-dark: #1e293b;
      --text-light: #64748b;
      --bg-color: #f8fafc;
      --card-bg: #ffffff;
      --border-radius: 12px;
      --box-shadow: 0 4px 30px rgba(0, 0, 0, 0.08);
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--bg-color);
      color: var(--text-dark);
      line-height: 1.6;
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem 1rem;
    }

    .container {
      background: var(--card-bg);
      border-radius: var(--border-radius);
      box-shadow: var(--box-shadow);
      padding: 2.5rem;
      margin-bottom: 2rem;
    }

    .header {
      text-align: center;
      margin-bottom: 2rem;
    }

    .header h1 {
      color: var(--primary-color);
      font-size: 2.5rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
      background: linear-gradient(to right, #4f46e5, #7c3aed);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .header p.subtitle {
      color: var(--text-light);
      font-size: 1.1rem;
      max-width: 700px;
      margin: 0 auto;
    }

    .input-section {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-bottom: 2rem;
    }

    .input-group {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 1rem;
    }

    label {
      font-weight: 600;
      color: var(--text-dark);
    }

    input[type="text"] {
      flex: 1;
      min-width: 250px;
      padding: 0.75rem 1rem;
      border: 1px solid #e2e8f0;
      border-radius: var(--border-radius);
      font-size: 1rem;
      transition: all 0.2s;
    }

    input[type="text"]:focus {
      outline: none;
      border-color: var(--primary-color);
      box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.2);
    }

    button {
      background: var(--primary-color);
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: var(--border-radius);
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
    }

    button:hover {
      background: var(--primary-hover);
      transform: translateY(-1px);
    }

    button:active {
      transform: translateY(0);
    }

    #loading {
      color: var(--text-light);
      font-size: 0.9rem;
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
    }

    .spinner {
      border: 2px solid rgba(79, 70, 229, 0.2);
      border-top: 2px solid var(--primary-color);
      border-radius: 50%;
      width: 16px;
      height: 16px;
      animation: spin 1s linear infinite;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    .howto {
      background: var(--secondary-color);
      padding: 1.25rem;
      border-radius: var(--border-radius);
      margin-bottom: 2rem;
    }

    .howto h3 {
      margin-top: 0;
      color: var(--primary-color);
    }

    .howto ul {
      padding-left: 1.25rem;
      margin-bottom: 0;
    }

    .howto li {
      margin-bottom: 0.5rem;
    }

    #result {
      margin-top: 2rem;
    }

    .columns {
      display: grid;
      gap: 2rem;
      margin-top: 1.5rem;
    }

    @media (min-width: 768px) {
      .columns {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      }
    }

    .column {
      background: var(--card-bg);
      border-radius: var(--border-radius);
      padding: 1.25rem;
      box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
    }

    .col-header {
      font-size: 1.1rem;
      font-weight: 700;
      margin-bottom: 1rem;
      color: var(--primary-color);
      padding-bottom: 0.5rem;
      border-bottom: 2px solid var(--secondary-color);
    }

    .word-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .word {
      background: var(--secondary-color);
      padding: 0.5rem 1rem;
      border-radius: 999px;
      font-size: 0.95rem;
      color: var(--text-dark);
      transition: all 0.2s;
      border: 1px solid rgba(79, 70, 229, 0.1);
    }

    .word:hover {
      background: #d4dcfa;
      transform: translateY(-2px);
    }

    .empty {
      color: var(--text-light);
      font-style: italic;
      font-size: 0.95rem;
    }

    .error {
      color: #dc2626;
      background: #fee2e2;
      padding: 1rem;
      border-radius: var(--border-radius);
      margin-top: 1rem;
    }

    footer {
      text-align: center;
      color: var(--text-light);
      font-size: 0.9rem;
      margin-top: 3rem;
    }

    .github-corner {
      position: absolute;
      top: 0;
      right: 0;
      border: 0;
      z-index: 1;
    }
  </style>
</head>
<body>
  <!-- GitHub corner ribbon -->
  <a href="https://github.com/yourusername/anagram-solver" class="github-corner" aria-label="View source on GitHub">
    <svg width="80" height="80" viewBox="0 0 250 250" style="fill:#4f46e5; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true">
      <path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path>
      <path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path>
      <path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path>
    </svg>
  </a>

  <div class="container">
    <div class="header">
      <h1>Advanced Anagram Solver</h1>
      <p class="subtitle">Discover meaningful word combinations from scrambled letters using our curated database of common English words</p>
    </div>

    <div class="howto">
      <h3>How to use this tool:</h3>
      <ul>
        <li><strong>Full-length anagrams</strong> appear in the first column</li>
        <li>Subsequent columns show words using progressively fewer letters</li>
        <li>Results are filtered to show only common English words for practical use</li>
        <li>Works with up to 18 letters (desktop) or 12 letters (mobile)</li>
      </ul>
    </div>

    <div class="input-section">
      <div class="input-group">
        <label for="letters">Enter your letters:</label>
        <input type="text" id="letters" maxlength="18" placeholder="e.g. 'education', 'creative', 'solution'">
        <button id="solveBtn">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="11" cy="11" r="8"></circle>
            <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
          </svg>
          Solve Anagram
        </button>
      </div>
      <div id="loading"></div>
    </div>

    <div id="result"></div>
  </div>

  <footer>
    <p>Anagram Solver &middot; Uses the 20,000 most common English words &middot;</p>
  </footer>

  <script>
    // Common words, 20k, public domain:
    const COMMON_DICT_URL = "https://raw.githubusercontent.com/first20hours/google-10000-english/master/20k.txt";
    let COMMON_WORDS = [];

    // Load the common English word list
    async function loadCommonDictionary() {
      if (COMMON_WORDS.length) return;
      
      const loadingElement = document.getElementById('loading');
      loadingElement.innerHTML = '<span class="spinner"></span> Loading dictionary...';
      
      try {
        let response = await fetch(COMMON_DICT_URL);
        if (!response.ok) throw new Error('Network response was not ok');
        
        let text = await response.text();
        COMMON_WORDS = text
          .split(/\r?\n/)
          .map(w => w.trim().toLowerCase())
          .filter(w => w.length > 2 && w.length < 17 && /^[a-z]+$/.test(w));
          
        loadingElement.textContent = '';
      } catch(error) {
        console.error('Error loading dictionary:', error);
        loadingElement.innerHTML = '<span style="color:#dc2626;">Could not load word list. Please check your connection.</span>';
      }
    }

    // Check if a word can be formed from the given letters
    function canForm(word, letters) {
      const letterCount = {};
      for (const char of letters) {
        letterCount[char] = (letterCount[char] || 0) + 1;
      }
      
      for (const char of word) {
        if (!letterCount[char]) return false;
        letterCount[char]--;
      }
      return true;
    }

    // Main function to solve the anagram
    async function solveAnagram() {
      await loadCommonDictionary();
      const input = document.getElementById('letters').value.trim().toLowerCase();
      const resultDiv = document.getElementById('result');
      const loadingElement = document.getElementById('loading');
      
      resultDiv.innerHTML = '';
      
      // Input validation
      if (!input) {
        resultDiv.innerHTML = '<div class="error">Please enter some letters to solve.</div>';
        return;
      }
      
      if (!input.match(/^[a-z]+$/)) {
        resultDiv.innerHTML = '<div class="error">Please enter letters only (a-z).</div>';
        return;
      }
      
      if (input.length > 18) {
        resultDiv.innerHTML = '<div class="error">Maximum 18 letters allowed for performance reasons.</div>';
        return;
      }
      
      loadingElement.innerHTML = '<span class="spinner"></span> Finding word combinations...';

      // Calculate word length parameters
      const maxWordLength = input.length;
      const minWordLength = 3;
      const maxUnusedLetters = maxWordLength - minWordLength;

      // Group results by how many letters are unused
      const groupedResults = Array.from({length: maxUnusedLetters + 1}, () => []);
      
      for (const word of COMMON_WORDS) {
        if (word.length <= maxWordLength && 
            word.length >= minWordLength && 
            canForm(word, input)) {
          const unusedLetters = maxWordLength - word.length;
          groupedResults[unusedLetters].push(word);
        }
      }
      
      // Sort each group by length (descending) then alphabetically
      groupedResults.forEach(group => {
        group.sort((a, b) => b.length - a.length || a.localeCompare(b));
      });

      // Filter out empty groups and generate HTML
      const nonEmptyGroups = groupedResults.filter(group => group.length > 0);
      
      if (nonEmptyGroups.length === 0) {
        loadingElement.textContent = '';
        resultDiv.innerHTML = '<div class="error">No valid words found with these letters. Try different letters.</div>';
        return;
      }
      
      let resultsHTML = `<div class="columns">`;
      
      nonEmptyGroups.forEach((words, index) => {
        const unusedLetters = groupedResults.indexOf(words);
        let columnTitle;
        
        if (unusedLetters === 0) {
          columnTitle = `Perfect Anagrams <span style="color:var(--text-light); font-weight:normal;">(${maxWordLength} letters)</span>`;
        } else {
          columnTitle = `${maxWordLength - unusedLetters}-Letter Words <span style="color:var(--text-light); font-weight:normal;">(missing ${unusedLetters})</span>`;
        }
        
        resultsHTML += `
          <div class="column">
            <div class="col-header">${columnTitle}</div>
            <div class="word-list">
              ${words.map(word => `<span class="word" title="${word.length} letters">${word}</span>`).join('')}
            </div>
          </div>
        `;
      });
      
      resultsHTML += `</div>`;
      
      loadingElement.textContent = '';
      resultDiv.innerHTML = resultsHTML;
      
      // Add word count summary
      const totalWords = nonEmptyGroups.reduce((sum, group) => sum + group.length, 0);
      const summary = document.createElement('p');
      summary.style.color = 'var(--text-light)';
      summary.style.marginTop = '1rem';
      summary.textContent = `Found ${totalWords} valid word${totalWords !== 1 ? 's' : ''} from "${input}"`;
      resultDiv.prepend(summary);
    }

    // Event listeners
    document.getElementById('solveBtn').addEventListener('click', solveAnagram);
    
    document.getElementById('letters').addEventListener('keydown', function(e) {
      if (e.key === 'Enter') solveAnagram();
    });

    // Preload dictionary when page loads
    document.addEventListener('DOMContentLoaded', () => {
      loadCommonDictionary().catch(error => {
        console.error('Dictionary preload failed:', error);
      });
    });
  </script>
</body>
</html>
