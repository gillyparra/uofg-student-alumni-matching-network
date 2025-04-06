# uofg-student-alumni-matching-network
AI-powered tool that connects UofG students with alumni using semantic matching. It analyzes career goals and interests to generate personalized networking matches and outreach messages.


# UofG Alumni Matching Network 🔗

This project uses semantic matching and AI to connect University of Guelph students with alumni in related fields. Matches are scored and visualized, and personalized outreach emails are generated automatically.

##  What It Does

- Parses student and alumni survey data
- Generates profiles from free-text responses
- Uses transformer-based models to compare career goals and interests
- Computes similarity scores with penalties/boosts based on keyword overlap
- Produces match rankings, matrices, and personalized outreach messages
- Visualizes the student–alumni network graphically

##  Tech Used

- Python + Pandas
- `sentence-transformers` (BGE + MPNet models)
- NetworkX + Matplotlib for graph visualization
- Google Gmail API for automated emailing (optional)

##  Files

| File | Description |
|------|-------------|
| `student_network_match.ipynb` | Main notebook — performs matching, scoring, and visualization |
| `data/` | Folder where input survey responses (CSV/XLSX) are stored |
| `outputs/` | Contains match scores, emails, and exported text files |
| `client_secret.json` | Google API secret key   |

##  Email Automation 

- Connects to your Gmail to send out outreach messages
- Requires Gmail API + OAuth setup (see `gmail_send_script.py` for setup)

##  Example Output

- Top 5 matches per student
- Match heatmap
- Semantic network graph of all participants

##  Acknowledgments

Thanks to all UofG students and alumni who participated via the @uog_memes Instagram Page!

---

## Disclaimer

This is not a job-matching system — it’s a conversation starter. Matches are based on career paths and interests, not hiring potential.

