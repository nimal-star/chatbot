1. The chatbot receives a user query (e.g., about an order, product, or policy).
2. The Agent analyzes the query and selects the appropriate tool.
3. The selected tool (OrderDBTool, ProductInfoTool, or PolicyTool) executes using dummy data.
4. The result is passed to mock_llm_call() to generate a human-readable response.
5. The chatbot prints the response and waits for the next input in a loop
