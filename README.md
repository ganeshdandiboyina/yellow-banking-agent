## yellow-banking-agent
Yellow Bank AI Agent - A comprehensive Super Agent built on yellow.ai platform for secure loan details retrieval with multi-step authentication, OTP verification, and customer satisfaction surveys. Implements token optimization, edge case handling, and supports English-only communication.<br>





##🎯 Features<br>
✅ English Language Restriction: Agent only communicates in English<br>
✅ Multi-Step Authentication: Phone number + DOB + OTP verification<br>
✅ Token Optimization: Efficient API response filtering<br>
✅ Dynamic Rich Media Cards: Interactive loan account selection<br>
✅ Edge Case Handling: Automatic recovery for data corrections<br>
✅ CSAT Integration: Customer satisfaction survey<br>
✅ Mock API Support: Beeceptor integration for testing<br>
PUBLISHED LINK :https://cloud.yellow.ai/bot/x1770603771132/overview<br>



##📊 System Architecture<br>
Conversation Flow<br>
User initiates request for loan details<br>
Agent collects phone number and date of birth<br>
OTP is triggered via triggerOTP workflow<br>
User enters received OTP<br>
System retrieves loan accounts via getLoanAccounts workflow<br>
User selects desired account<br>
Full loan details displayed via loanDetails workflow<br>
User can rate service via CSAT agent<br>


API Endpoints (Beeceptor)<br>
POST /triggerOTP - Generate random OTP (1234, 5678, 7889, 1209)<br>
GET /getLoanAccounts - Retrieve list of loan accounts<br>
GET /loanDetails/:accountId - Get specific loan details<br>


##🔧 Technology Stack<br>
Platform: yellow.ai<br>
Mock APIs: Beeceptor<br>
Language: Python (for scripting)<br>
Authentication: Multi-factor (Phone + DOB + OTP)<br>



##📝 Configuration Details<br>
System Prompt<br>
The agent is configured with a comprehensive system prompt that includes:<br>
Language enforcement<br>
Conversation flow guidance<br>
Token optimization rules<br>
Error handling protocols<br>
Edge case management<br>
Conversation Rules (3 Active)<br>
Language restriction to English<br>
Mandatory authentication data collection<br>
Edge case handling for data corrections<br>



##🚀 Deployment<br>
Bot Name: Ganesh Dandiboyina<br>
Yellow Bank Agent Status: Published (Awaiting Approval)<br>
Access Level: Developer<br>
Visibility: Public<br>


Shared Access:<br>

Manasvi Sharma (manasvi.sharma@yellow.ai) - Developer<br>
Kushagra Shrivastava (kushagra.shrivastava@yellow.ai) - Developer<br>


📚 Documentation<br>
For detailed implementation guide and API specifications, please refer to the assignment requirements and yellow.ai documentation.<br>



##👨‍💻 Author<br>
Name: Ganesh Dandiboyina<br>
GitHub: ganeshdandiboyina<br>
Repository: yellow-banking-agent<br>



##📄 License<br>
This project is open source and available for review and testing purposes.<br>

Last Updated: February 9, 2026<br>
Status: Complete and Ready for Review<br>
