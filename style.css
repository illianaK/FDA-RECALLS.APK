:root {
    --md-sys-color-background: #f8f9fa;
    --md-sys-color-surface: #ffffff;
    --md-sys-color-primary: #1a73e8;
    --md-sys-color-text: #202124;
    --md-sys-color-text-secondary: #5f6368;
    --risk-high: #b3261e;
    --risk-medium: #e65100;
    --risk-low: #79747e;
    --border-radius-m3: 16px;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}

body {
    background-color: var(--md-sys-color-background);
    color: var(--md-sys-color-text);
    padding-bottom: 24px;
}

.app-header {
    background-color: var(--md-sys-color-surface);
    padding: 16px;
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.header-title {
    display: flex;
    align-items: center;
    gap: 8px;
    color: var(--md-sys-color-primary);
    margin-bottom: 12px;
}

.header-title h1 {
    font-size: 1.3rem;
    font-weight: 600;
}

.search-filter-container {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.search-bar {
    display: flex;
    align-items: center;
    background-color: var(--md-sys-color-background);
    padding: 8px 12px;
    border-radius: 24px;
    border: 1px solid #dadce0;
}

.search-icon {
    color: var(--md-sys-color-text-secondary);
    margin-right: 8px;
}

.search-bar input {
    border: none;
    background: transparent;
    width: 100%;
    outline: none;
    font-size: 1rem;
}

.filter-select select {
    width: 100%;
    padding: 10px 12px;
    border-radius: 8px;
    border: 1px solid #dadce0;
    background-color: var(--md-sys-color-surface);
    font-size: 0.95rem;
    outline: none;
}

.dashboard-container {
    padding: 16px;
}

.results-meta {
    display: flex;
    justify-content: space-between;
    font-size: 0.85rem;
    color: var(--md-sys-color-text-secondary);
    margin-bottom: 12px;
}

.recalls-list {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

/* Card Styling */
.recall-card {
    background-color: var(--md-sys-color-surface);
    border-radius: var(--border-radius-m3);
    padding: 16px;
    position: relative;
    overflow: hidden;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    display: flex;
    flex-direction: column;
    gap: 6px;
    cursor: pointer;
    transition: transform 0.15s ease;
}

.recall-card:active {
    transform: scale(0.98);
}

.recall-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    width: 5px;
}

.recall-card.high::before { background-color: var(--risk-high); }
.recall-card.medium::before { background-color: var(--risk-medium); }
.recall-card.low::before { background-color: var(--risk-low); }

.card-header {
    display: flex;
    justify-content: space-between;
    font-size: 0.8rem;
    color: var(--md-sys-color-text-secondary);
}

.card-brand {
    font-weight: 700;
    font-size: 1.1rem;
    color: var(--md-sys-color-text);
}

.card-desc {
    font-size: 0.95rem;
    color: #3c4043;
}

.card-reason {
    font-size: 0.85rem;
    font-style: italic;
    color: var(--md-sys-color-text-secondary);
    margin-top: 4px;
}

/* Modal UI */
.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    z-index: 100;
    justify-content: center;
    align-items: flex-end; /* Bottom sheet style on mobile */
}

.modal-content {
    background-color: var(--md-sys-color-surface);
    width: 100%;
    max-width: 500px;
    border-top-left-radius: var(--border-radius-m3);
    border-top-right-radius: var(--border-radius-m3);
    padding: 24px 20px;
    position: relative;
    box-shadow: 0 -4px 16px rgba(0,0,0,0.1);
    animation: slideUp 0.25s ease-out;
}

@keyframes slideUp {
    from { transform: translateY(100%); }
    to { transform: translateY(0); }
}

.close-btn {
    position: absolute;
    top: 16px;
    right: 16px;
    cursor: pointer;
    color: var(--md-sys-color-text-secondary);
}

.modal-body h2 {
    margin-bottom: 12px;
    color: var(--md-sys-color-text);
}

.modal-body p {
    margin-bottom: 10px;
    font-size: 0.95rem;
    line-height: 1.4;
}

.modal-label {
    font-weight: bold;
    color: var(--md-sys-color-text-secondary);
}
