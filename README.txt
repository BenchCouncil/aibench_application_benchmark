AIBench E-commerce Search is the first end-to-end Internet service AI benchmark suite that models the
critical paths and primary modules of industry-scale Internet services.

Online server receives the query requests and performs personalized searching and recommendation, integrated with AI inference.

Offline analyzer chooses the appropriate AI algorithm implementations and performs a training stage to generate a learning model. Also, the offline analyzer is responsible to build data indexes to accelerate data access.

Query generator is to simulate concurrent users and send query requests to online server based on a specific configuration. The configuration designates parameters like concurrency, query arriving rate, distribution, and user thinking time, to simulate different query characteristics and satisfy multiple generation strategies. We implement our query generator based on JMeter.

Data storage module stores all kinds of data, including the user database that saves all the attributes of user information, the product database that holds all the attributes of product information, logs that record the complete query histories, text data that contains the product description text or the user comments, image and video data that depict the appearance and usage of product vividly, and audio data that stores the voice search data and voice chat data.
