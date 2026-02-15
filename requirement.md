1. 📌 Project Overview
- The Patent & Research Novelty Checker is an AI-powered system designed to evaluate the originality of user ideas by comparing them against existing patents and research publications.
- The system automates literature review and novelty assessment using AI, vector similarity search, and multi-source academic data retrieval.
- It helps students, researchers, developers, and innovators determine whether their ideas are suitable for patent filing or better suited for research publication.

2. 🎯 Objectives
- The primary objectives of the system are:
- Reduce time required for manual novelty checking
- Provide AI-based evaluation of idea originality
- Assist users in making informed decisions about patents or research papers
- Improve productivity in innovation and research workflows
- Simplify complex patent search processes for beginners

3. 👥 Target Users
- The system is intended for:
- Students working on academic projects
- Researchers conducting literature reviews
- Startup founders validating product ideas
- Developers exploring innovation opportunities
- Individuals preparing patent applications

4. ⚙️ Functional Requirements
4.1 User Input
- The system shall allow users to:
- Enter an idea title and description
- Provide optional keywords or domain category
- Submit the idea for novelty analysis

4.2 Data Collection
The system shall:
- Fetch research papers from multiple sources
- Retrieve patent documents related to the idea
- Aggregate results into a searchable dataset

4.3 Novelty Analysis
The system shall:
- Convert idea and documents into vector embeddings
- Calculate similarity scores using vector search
- Generate an overall novelty percentage

4.4 AI Evaluation
The system shall:
- Provide AI-generated explanation of novelty results
- Identify overlapping concepts
- Suggest potential improvements or innovation areas

4.5 Results Display
The system shall display:
- Novelty score
- Confidence score
- Similar patents and research papers
- AI-generated insights

4.6 Interactive Chat
The system shall:
- Allow users to ask questions about analysis results
- Provide AI responses based on retrieved data

4.7 Export Features
The system shall allow users to:
- Download novelty reports in PDF format
- Export data in CSV format

4.8 History Management
The system shall:
- Store previous analyses
- Allow users to view past results

4.9 Decision Guidance
The system shall:
- Suggest whether an idea is suitable for patent filing
- Recommend writing a research paper if novelty is low

5. 🚀 Future Functional Requirements
Planned enhancements include:
- Negative Novelty Detector to identify risky claims
- AI suggestions for improving low-novelty ideas
- Voice input and output support
- Automated literature review generation
- Domain-specific innovation recommendations

6. ⚡ Non-Functional Requirements
6.1 Performance
- Analysis should complete within 30–60 seconds
- System should support multiple concurrent users

6.2 Usability
- User interface should be simple and intuitive
- Results should be easy to understand

6.3 Reliability
- System must handle API failures gracefully
- Results should still display partial data if some sources fail

6.4 Scalability
- System should support increasing document volume
- Vector database should handle large datasets

6.5 Security
- API keys must be securely stored
- User data should not be publicly exposed

7. 🔒 Constraints
- Depends on third-party API availability
- Limited by API rate limits
- Requires internet connectivity
- AI analysis accuracy depends on data quality

8. 📊 Assumptions
- Users provide clear and meaningful idea descriptions
- External data sources remain accessible
- AI models provide reasonably accurate insights

9. ✅ Success Criteria
- The system will be considered successful if it:
- Accurately identifies similar patents and papers
- Generates reliable novelty scores

Reduces manual research effort significantly

Provides meaningful AI insights to users
