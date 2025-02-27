CDP Assist

This chatbot helps users answer "how-to" questions related to four Customer Data Platforms (CDPs): **Segment, mParticle, Lytics, and Zeotap**. It retrieves information from official documentation to guide users on performing various tasks within these platforms.

Features
- ✅ Answer "How-to" Questions: Provides step-by-step guidance on using Segment, mParticle, Lytics, and Zeotap.
- ✅ Documentation Extraction: Retrieves relevant information from official documentation.
- ✅ Handles Question Variations: Supports different question phrasing and terminology.

Data Sources
The chatbot uses official documentation from:
- [Segment Documentation](https://segment.com/docs/)
- [mParticle Documentation](https://docs.mparticle.com/)
- [Lytics Documentation](https://docs.lytics.com/)
- [Zeotap Documentation](https://docs.zeotap.com/home/en-us/)

Technologies Used
- Python – Backend programming language
- Flask – Web framework
- NLTK – NLP for query understanding
- BeautifulSoup4 – Web scraping for documentation extraction
- FAISS – Vector-based search for efficient retrieval
- HTML/CSS/JavaScript – Frontend UI for chatbot
