class KeithLWeirJr:
    def __init__(self):
        self.name = "Keith L. Weir Jr."
        self.location = "Tallahassee, FL 32304"
        self.email = "Keith1.Weir@famu.edu"
        self.phone = "561-997-4463"

    def education(self):
        return """
        EDUCATION
        Florida Agricultural & Mechanical University, College of Social Sciences, Arts and Humanities\tTallahassee, FL
        Anticipated Degree: Bachelor of Science in Political Science\tExpected Graduation: Spring 2024
        """

    def experience(self):
        return """
        EXPERIENCE
        Xfinity Store by Comcast\tTallahassee, FL
        Retail Sales Consultant\tMarch 2023– Present
        Deliver compelling product demonstrations showcasing technological prowess of Xfinity services.
        Spearhead immersive onboarding experiences that go beyond basic functionalities, ensuring a deep customer understanding.
        Staying Abreast to Xfinity products and promotions while exceeding competitor offers and company sales goals.
        
        T-Mobile Telecommunications \tTallahassee, FL
        Mobile Expert\tJanuary 2021– December 2022
        Mobile Technology Proficiency including IOS and Android platforms.
        Cross-Functional Collaborations seamlessly with software developers, UX/UI designers, and project managers.
        Serve as the point of contact and administrative support for all campaign digital organizing and online community tools.
        
        Students For Justice\tTallahassee, FL
        Technical Political Data Analyst\tJuly 2022– February 2023
        Leveraged Python and various coding programs to streamline data entry processes.
        Implemented sophisticated algorithms for sorting and cleaning extensive datasets.
        Hosted numerous speakers’ series showcasing profound understanding of data analysis goals, emphasizing how technical expertise contributes to surpassing competitors.
        
        Teleperformance\tRemote
        Technical Customer Support Specialist\tJuly 2022– March 2023
        Expertly resolved intricate consumer issues within the telecommunications domain, providing guidance to first-level representatives on complex matters related to agronomics, products, and procedures.
        Led negotiations, conducted timely follow-ups, and ensured quality assurance for all escalated concerns, demonstrating personal attention to achieve optimal consumer satisfaction and effective conflict resolution.
        Managed key customer accounts, applying advanced technical skills in JavaScript, Python, SQL, CSVs, and HTML/CSS. Facilitated seamless communication between technical complexities and consumer interactions, ensuring a cohesive and efficient experience.
        """

    def leadership(self):
        return """
        LEADERSHIP & PROFESSIONAL DEVELOPMENT
        Alpha Eta Chapter of Phi Beta Sigma Fraternity, Inc.\tTallahassee, FL
        Social Action Chairman, Sigma Beta Club Chairman, and Bigger and Better Business Chairman\tApril 2022 – May 2024
        Allocate budget to various on-campus events, from weekly meetings to fundraisers
        Oversee and present budgets, accounts, and financial statements to the Executive Board
        Implement Financial Request forms to assist in planning and budgeting
        
        Phi Alpha Delta International Law Fraternity, Inc.\tTallahassee, FL
        Florida A&M Chapter\tApril 2023 – May 2024
        Coordinated and participated in various legal events, seminars, and networking opportunities.
        Oversee community engagement and outreach projects.
        Implement leadership and demonstrate a commitment to using legal expertise.
        """

    def skills_interests(self):
        return """
        SKILLS & INTERESTS
        Technical: Technical Writing, Data Entry, Public Policy, Account Management, Financial Auditing, Managerial Accounting, Telecommunications, Case Analysis, Criminal Justice and Document Analyzation.
        Software Expertise: Data Analysis with Python,Tableau, SQL, CSVs, Numpy, Pandas, Maltplotlib, Seaborn, Microsoft Excel, and Word Document.
        Teaching:Cross-Cultural Communication, Emotional Intelligence,Visual Aid, Personalized Learning, Adaptability, Patience, Growth Mindset, and Collaborative Learning.
        Other Affiliations:Phi Alpha Delta International Law Fraternity, Phi Beta Sigma Fraternity, Inc., National Honor Society.
        Languages: Fluent in English, French and Haitian Creole
        """

# Create an instance of KeithLWeirJr
keith_resume = KeithLWeirJr()

# Print resume sections
print(keith_resume.education())
print(keith_resume.experience())
print(keith_resume.leadership())
print(keith_resume.skills_interests())
