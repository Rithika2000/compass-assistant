# Comprehensive Master’s Program Assistant for Student Success

## Team Members 
  * Shashank Guda
  * Rithika Gurram
  * Roja Bugade
  * Rajat Rohilla

## Project Goal

The goal of this project is to create an intelligent chatbot that assists international students,
particularly those pursuing a master’s degree in the United States, in selecting the right university
and timing their studies. The system will provide tailored recommendations based on factors
such as cost of living, weather, job market outlook, and university strengths for specific courses,
helping students make informed decisions. A further aim of the project is to help students
identify potential scholarship opportunities from both university and external sources, enhancing
financial support options and facilitating affordability for international students.

## Project Functionality and Use:

The chatbot will operate as a conversational assistant, helping students navigate their choices
through a user-friendly web interface. Key functionalities will include:

* User-Friendly Web Interface: The chatbot will feature an intuitive web UI with
dropdowns and prompts for users to enter preferences seamlessly. Users can interactively
explore recommendations with minimal complexity.

* Session-Based Memory: The chatbot will remember user preferences, providing
continuity in recommendations across multiple sessions. This memory feature will enable
students to refine their inputs and receive consistent, tailored guidance as they progress in
their search.

* Personalized Recommendations: The chatbot will suggest universities based on input
criteria, job opportunities in different states, specific university strengths in chosen
courses, and anticipated trends in the job market.

## Target Users

* 1. Prospective Graduate Students:
    
     * Students planning master’s studies in the U.S., looking for guidance on
       selecting programs that align with career goals, budget, and lifestyle
       preferences.
    
     * This audience includes recent graduates and professionals seeking career
       advancement or a field switch, with a strong focus on industry demand
       and job market trends.
       
* 2. Educational Consultants and Advisors:
    
       * University admissions advisors who guide students on studying abroad,
         needing up-to-date insights on top programs, job markets, and relevant
         economic data.
         
     * Study abroad consultants assisting students in choosing programs by
       providing specific advice on program quality, geographic factors, and
       application timing.
       
* 3. Parents and Guardians:
     
     * Parents or guardians financially supporting students, interested in
       educational choices that align with family resources and potential job
       prospects.
       
     * Seeking a reliable resource for understanding program value, costs, and
       career outcomes relevant to the student’s aspirations.

* 4. Government and Nonprofit Organizations:
     
     * Scholarship and sponsorship providers who wish to fund students in highdemand programs aligned with organizational goals and market 
       needs.
       
     * These organizations require data-driven insights to support students in programs with high career potential and alignment with    
       global economic trends. The chatbot could allow input of program criteria to filter and
       recommend universities that align with specific funding priorities.

## Data Requirements

To deliver personalized and informed recommendations, the app will rely on multiple datasets:

 * University Data: Location, tuition fees, living expenses, admission criteria, placement
rates, and top-rated courses by university.

 * Geographical Data: State-wise information on average weather conditions, cost of
living, and available industries.

 * Job Market Data: Trends in hiring by field, company requirements for graduates, and
projections for growth or decline in various sectors.

 * Economic and Political Data: Cyclical job market trends to assess potential influences
on job prospects for graduates.

 * Scholarship Data: Information on university-based and external scholarship
opportunities, with eligibility criteria and application timelines for international students.

## Data Handling & RAG Architecture

The chatbot will use a vector database to store user session data, allowing for memory
persistence across interactions. The data sourcing will involve real-time access for job market
trends, with periodic updates for university and economic data. A high-level flow will involve:

 * Data retrieval modules for user inputs, job market trends, and university
recommendations.
 * Vector database integration to handle retrieval-augmented generation (RAG) for
seamless, contextually aware responses.
 * Session management to ensure user preferences are retained, allowing for personalized,
session-consistent recommendations.

## Ethical Considerations

Data privacy is a key concern, especially given the personalized nature of recommendations. Our
approach includes anonymizing user data and ensuring secure handling of preferences to avoid
any personally identifiable information misuse. We will also implement bias checks to ensure
fair and inclusive recommendations across all institutions, regardless of their location or profile,
avoiding favoritism or unbalanced suggestions.
