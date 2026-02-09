## yellow-banking-agent
Yellow Bank AI Agent - A comprehensive Super Agent built on yellow.ai platform for secure loan details retrieval with multi-step authentication, OTP verification, and customer satisfaction surveys. Implements token optimization, edge case handling, and supports English-only communication.





##🎯 Features
✅ English Language Restriction: Agent only communicates in English
✅ Multi-Step Authentication: Phone number + DOB + OTP verification
✅ Token Optimization: Efficient API response filtering
✅ Dynamic Rich Media Cards: Interactive loan account selection
✅ Edge Case Handling: Automatic recovery for data corrections
✅ CSAT Integration: Customer satisfaction survey
✅ Mock API Support: Beeceptor integration for testing
PUBLISHED LINK :https://cloud.yellow.ai/bot/x1770603771132/overview



##📊 System Architecture
Conversation Flow
User initiates request for loan details
Agent collects phone number and date of birth
OTP is triggered via triggerOTP workflow
User enters received OTP
System retrieves loan accounts via getLoanAccounts workflow
User selects desired account
Full loan details displayed via loanDetails workflow
User can rate service via CSAT agent
API Endpoints (Beeceptor)
POST /triggerOTP - Generate random OTP (1234, 5678, 7889, 1209)
GET /getLoanAccounts - Retrieve list of loan accounts
GET /loanDetails/:accountId - Get specific loan details


##🔧 Technology Stack
Platform: yellow.ai
Mock APIs: Beeceptor
Language: Python (for scripting)
Authentication: Multi-factor (Phone + DOB + OTP)



##📝 Configuration Details
System Prompt
The agent is configured with a comprehensive system prompt that includes:

Language enforcement
Conversation flow guidance
Token optimization rules
Error handling protocols
Edge case management
Conversation Rules (3 Active)
Language restriction to English
Mandatory authentication data collection
Edge case handling for data corrections



##🚀 Deployment
Bot Name: Ganesh Dandiboyina Yellow Bank Agent Status: Published (Awaiting Approval) Access Level: Developer Visibility: Public

Shared Access
Manasvi Sharma (manasvi.sharma@yellow.ai) - Developer
Kushagra Shrivastava (kushagra.shrivastava@yellow.ai) - Developer
📚 Documentation
For detailed implementation guide and API specifications, please refer to the assignment requirements and yellow.ai documentation.

##👨‍💻 Author
Name: Ganesh Dandiboyina
GitHub: ganeshdandiboyina
Repository: yellow-banking-agent

##📄 License
This project is open source and available for review and testing purposes.

Last Updated: February 9, 2026
Status: Complete and Ready for Review
