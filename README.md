# Youtube-Data-Harvesting-and-Warehousing
This project is centered on the efficient handling and 
migration of YouTube channel data, leveraging the YouTube Data API to extract 
detailed and user-interacted statistical information from selected channels. The 
primary focus is on collecting key performance metrics that provide insight into 
channel activities, including views, likes, comments, and subscriber growth. The 
YouTube Data API is integral in obtaining this data, ensuring that the most 
relevant and up-to-date information is retrieved. The system prioritizes not only 
the retrieval of data but also its organization and storage in a format that supports 
dynamic and extensible usage.
Once the data is retrieved, it is stored in MongoDB, a widely recognized NoSQL 
database system known for its flexibility in handling unstructured data. 
MongoDB's schema-less design allows it to accommodate a variety of data types, 
making it an ideal choice for the varied and complex datasets generated by 
YouTube channels. This storage approach ensures that the data is both accessible 
and adaptable, supporting future modifications or expansions of the project. 
However, to enhance query performance and support more complex data 
analysis, the project includes a critical migration process, transferring the data 
from MongoDB to PostgreSQL. PostgreSQL, with its advanced querying 
capabilities and support for relational data, enables more efficient data 
manipulation and detailed analysis, allowing users to generate custom reports and 
perform in-depth analysis with greater speed and accuracy.
To make the data more accessible and user-friendly, the project integrates 
Streamlit, a powerful tool for creating interactive web applications. Streamlit's 
straightforward interface allows users to interact with the data effortlessly, 
offering functionalities for viewing, querying, and analyzing the stored 
information. Through Streamlit, users can generate clear and understandable 
insights into their YouTube channel’s performance, utilizing simple calculations 
and customizable statistics tailored to their specific needs. This approach not only 
democratizes access to complex data but also empowers users to make informed 
decisions based on real-time analytics, enhancing their ability to manage and 
grow their YouTube channels effectively.
