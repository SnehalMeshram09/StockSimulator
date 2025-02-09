
# Stock Simulator

## Project Description Summary:




The Stock Simulator is an interactive Java-based application designed to replicate a virtual stock market environment. It enables users to create, view, filter, and manage a variety of stocks, helping them understand the dynamics of market behavior in a simulated setting.


## Need and Purpose

The Stock Simulator is a comprehensive Java-based application designed to provide a realistic and interactive platform for understanding stock market dynamics. It empowers users to experiment with various investment strategies, analyze market trends, and make informed investment decisions without risking real-world capital.

## Key Features and Implementations

### Data Structures
- **Stack:** Used to store buy and sell transactions for tracking historical data and analyzing investment performance.
- **Priority Queue:** Employs a priority queue to organize stocks based on market capitalization, allowing for efficient retrieval of top-performing stocks.
- **Linked List:** Implements a linked list to manage a user's wishlist, enabling flexible addition and removal of stocks under consideration.
- **Hashmaps:** Utilizes hashmaps to maintain a user's stock portfolio, storing stock symbols as keys and corresponding quantities as values.
- **Binary Trees:** Leverages binary trees to efficiently store and search market stocks, enabling filtering by market capitalization (large, small, mid) and sector (IT, FMCG, Textiles, Oil, etc.).
- **Max Heap:** Employs a max heap to store and retrieve the top-performing stocks, catering to users who prefer a concise view of the market.

### Real-Time Data Integration
- Leverages Java's Connection URL package to fetch real-time stock prices from external sources, ensuring up-to-date market information.

### File Handling
- Implements file handling to store and retrieve stock data from a `stocks.dat` file, facilitating persistent storage and data backup.

## Benefits

**Overall, the Stock Simulator offers a valuable tool for both novice and experienced investors to:**
- Gain practical experience in stock market investing
- Experiment with different strategies and risk tolerance levels
- Analyze market trends and make informed decisions
- Develop a deeper understanding of financial concepts
- Practice portfolio management and diversification techniques
