# PubMed-Research-Paper-Scraper
PubMed Research Paper Scraper

This Python project fetches research papers from PubMed based on a user-defined search query and saves the details in a CSV file. It retrieves paper titles, publication dates, and includes placeholders for non-academic authors, company affiliations, and corresponding author emails.

Features

Fetches PubMed papers using NCBI Entrez API.

Retrieves paper title and publication date.

Adds placeholders for non-academic authors, company affiliations, and emails.

Saves results in a CSV file.

Automatically downloads the CSV file in Google Colab.

Installation

Clone the repository:

git clone https://github.com/yourusername/pubmed-scraper.git
cd pubmed-scraper

Install required dependencies:

pip install requests

Usage

Run the script in Google Colab or a local Python environment:

python pubmed_scraper.py

Steps:

Enter a search query when prompted.

Provide a filename for the output CSV.

Results will be saved and downloaded automatically (Google Colab only).

Example Output (CSV)

PubmedID

Title

Publication Date

Non-academic Author(s)

Company Affiliation(s)

Corresponding Author Email

12345678

Sample Paper Title

2024-03-15

John Doe

BioTech Solutions

johndoe@example.com

API Used

PubMed Entrez API: NCBI API

Contributing

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m "Added feature").

Push to the branch (git push origin feature-branch).

Open a Pull Request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Author

Your NameGitHub: @sireeshakuruba

