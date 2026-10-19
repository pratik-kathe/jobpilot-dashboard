# JobPilot dashboard

Password-protected page. No job data or resume is stored here — only `vault.json`, which holds the GitHub token encrypted with your password (PBKDF2-SHA256, 600,000 iterations + AES-256-GCM). Data loads from the private `jobpilot` repo after you unlock.
