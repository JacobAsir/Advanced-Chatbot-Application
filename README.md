# Advanced-Chatbot-Application

𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄: At its core, this project focused on creating a sophisticated chatbot application using Langchain and Groq. The goal was to develop an AI assistant capable of maintaining coherent and contextually relevant conversations across different sessions.

𝗞𝗲𝘆 𝗛𝗶𝗴𝗵𝗹𝗶𝗴𝗵𝘁𝘀:
𝗜𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻 𝘄𝗶𝘁𝗵 𝗟𝗮𝗻𝗴𝗰𝗵𝗮𝗶𝗻 𝗮𝗻𝗱 𝗚𝗿𝗼𝗾: 
Utilized the ChatGroq model (gemma2-9b-it) to enhance conversational capabilities.

𝗠𝗲𝘀𝘀𝗮𝗴𝗲 𝗛𝗶𝘀𝘁𝗼𝗿𝘆 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁: 
Developed a robust system to manage message history using ChatMessageHistory and RunnableWithMessageHistory.
Built a dynamic session management feature that allows for seamless switching and tracking of conversation sessions.

𝗖𝗼𝗻𝘃𝗲𝗿𝘀𝗮𝘁𝗶𝗼𝗻 𝗖𝗼𝗻𝘁𝗲𝘅𝘁 𝗛𝗮𝗻𝗱𝗹𝗶𝗻𝗴:
Employed ChatPromptTemplate and MessagesPlaceholder for dynamic prompt generation, ensuring the AI assistant responds appropriately to context-specific queries.
Implemented language support, enabling the AI to communicate effectively in multiple languages, including French and Hindi.

𝗔𝗱𝘃𝗮𝗻𝗰𝗲𝗱 𝗖𝗼𝗻𝘃𝗲𝗿𝘀𝗮𝘁𝗶𝗼𝗻 𝗧𝗿𝗶𝗺𝗺𝗶𝗻𝗴:
Created a message trimming mechanism using trim_messages to maintain conversations within token limits while preserving essential context.

𝗜𝗻𝘁𝗲𝗿𝗮𝗰𝘁𝗶𝘃𝗲 𝗮𝗻𝗱 𝗔𝗱𝗮𝗽𝘁𝗶𝘃𝗲 𝗥𝗲𝘀𝗽𝗼𝗻𝘀𝗲𝘀:
The chatbot can now recall user-specific information such as names and previously discussed topics, thanks to the advanced message history management system.
