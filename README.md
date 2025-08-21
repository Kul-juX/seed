# Phishing Demo Assignment

This is an educational project to simulate a phishing attack for cybersecurity studies. It demonstrates how attackers might capture credentials using a fake login page and store them remotely (in this case, appended to `credentials.txt` via GitHub API).

## Files
- `app.py`: Flask server that serves the fake page and handles credential capture.
- `templates/index.html`: Fake Instagram login page.
- `credentials.txt`: Where test credentials are appended (use fake data only).

## Setup and Testing
1. Generate a GitHub Personal Access Token (PAT) with `repo` scope.
2. Update `app.py` with your PAT and repo name.
3. Use GitHub Codespaces to run the app (see instructions below).
4. Test locally in Codespaces with fake credentials.

## Ethics
- This is for educational purposes only.
- Tested with fake data in a private environment.
- No real phishing or data collection.

## Running in GitHub Codespaces
- Open the repo in Codespaces.
- Install dependencies: `pip install flask PyGitHub`.
- Run `python app.py`.
- Access the app via the forwarded port.
