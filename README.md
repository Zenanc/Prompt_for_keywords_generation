# Prompt_for_keywords_generation
This is the prompt template I used to generate keywords with LLM from Wikipedia event description.


prompt = """Extract 2-4 keywords for Google Trends search from this historical event.
Focus only on the most essential terms people would search for.
Exclude dates, numbers, and descriptive details. Only add years when necessary.
Keep your response extremely brief - just the essential search terms.


Here are examples of good keyword extractions:
{examples_text}


Now extract keywords for this event:
Event: {event_text}


Keywords:"""
