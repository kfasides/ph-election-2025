# PH Election May 2025 Senatorial Candidate Data

This project contains data for the 2025 Philippine Senatorial Election candidates. This web app is purely done via Vibe Coding.

## Objective

The objective of this app is to provide voters with an interactive platform to explore, compare, and select their preferred senatorial candidates for the 2025 Philippine National Elections. It aims to promote informed decision-making by presenting candidate profiles, platforms, and other relevant details in an accessible format.

## Methodology

1. **Data Sources**:

   - Data was manually scraped from Facebook Pages, including:
     - PhilStar
     - The NUntium
     - Supreme Student Council - BatStateU Alangilan Campus

2. **Dynamic Loading**:

   - Candidate data is stored in `candidates.json` and dynamically fetched by the application.

3. **Image Processing**:

   - Images containing candidate information were processed using **Google Gemini Flash 2.5**, which extracted text from the images.

4. **Data Compilation**:

   - Extracted data was organized and structured into JSON format using **Microsoft Copilot** and **Vibe Coding** principles.

5. **AI Search**:
   - The application features an AI-powered search functionality using **Google Gemini**.
   - Users can ask questions about the candidates, and the AI will provide relevant information based on the available data.
   - An API key is required to enable the AI search feature.

## Disclaimer

The data in this project is for informational purposes only and is based on publicly available information. While efforts were made to ensure accuracy, there may be discrepancies due to the nature of manual scraping, AI processing, and the dynamic nature of election-related data. Users are encouraged to verify the information from official sources.

## Data References and Sources

The following sources were used to compile the data:

1. **PhilStar**:

   - Official Facebook Page: [PhilStar](https://www.facebook.com/philstarnews)
   - Posts and announcements related to the 2025 Senatorial Elections.

2. **The NUntium**:

   - Official Facebook Page: [The NUntium](https://www.facebook.com/NUDNUntium)
   - Election-related posts and candidate profiles.

3. **Supreme Student Council - BatStateU Alangilan Campus**:

   - Official Facebook Page: [Supreme Student Council - BatStateU Alangilan Campus](https://www.facebook.com/sscalangilan)
   - Posts and updates on election candidates.

4. **Google Gemini Flash 2.5**:

   - Used for text extraction from candidate-related images.

5. **Microsoft Copilot**:
   - Assisted in organizing and coding the data into JSON format.

## Acknowledgments

Special thanks to:

- **Google Gemini Flash 2.5** for its powerful text recognition capabilities.
- **Microsoft Copilot** for its assistance in organizing and coding the data.
- The Facebook Pages (PhilStar, The NUntium, Supreme Student Council - BatStateU Alangilan Campus) for providing the publicly available information.

This project is a testament to the potential of AI-driven data processing and collaboration.
