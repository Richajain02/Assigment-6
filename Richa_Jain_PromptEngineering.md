# Prompt Engineering Portfolio
Name: Richa Jain  
Date: 5/31/2026  
LLM Used: ChatGPT-4  

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

Goal: Explain Neural Networks to a 10-year-old child.

A. Initial Prompt (V1): Explain neural networks.
Output Issue: The explanation was too technical and included complex terms.

B. Refined Prompt (V2): Explain neural networks in simple language.
Output Issue: Simpler, but still lacked examples that a 10 year old could relate to.

C. Final Prompt (V3):  
You are an expert teacher who explains difficult concepts to children. Explain neural networks to a 10-year-old using simple words, a real-life example, and an analogy. Avoid technical jargon and keep the explanation under 200 words.

Final LLM Response:  
Imagine you're learning to recognize different kinds of fruit.
The first time someone shows you an apple, an orange, and a banana, you might get confused. But after seeing many examples, you start noticing patterns:
* Apples are usually round.
* Bananas are long and curved.
* Oranges are round and orange.
A neural network learns in a similar way. It is a computer system that learns by looking at lots of examples.

Analogy: A Team of Detectives
Think of a neural network as a team of detectives solving a mystery.
* The first detectives look for simple clues, like color or shape.
* The next detectives combine those clues.
* The final detective makes the decision: "This is a banana!"  
If the team makes a mistake, they learn from it and do a little better next time.  
Real-Life Example: When you unlock a phone with your face, a neural network helps the phone recognize that it's really you. It has learned what your face looks like from examples.  
In short: A neural network is like a team of detectives that learns from many examples and gets better at making decisions over time.  


### 1.1 Scenario B: Professional Email  

Goal: Politely decline a job offer while keeping a positive relationship.

A. Initial Prompt (V1): Write an email declining a job offer.  
Output Issue: The email sounded too short and impersonal.  

B. Refined Prompt (V2): Write a polite email declining a job offer but thanking the company.  
Output Issue: Better, but it did not express future interest.  

C. Final Prompt (V3):  
You are a professional career advisor. I received a job offer from a company that I respect, but I have decided to accept another opportunity. Write a professional email that politely declines the offer, thanks the company for their time, and expresses interest in staying connected for future opportunities. Keep the tone respectful and positive.  

Final LLM Response:  
Subject: Thank You for the Opportunity  

Dear Hiring Manager,  

Thank you very much for offering me the position. I truly appreciate the time and effort that you and the team invested throughout the interview process.  
After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. As a result, I must respectfully decline your offer.  
I am sincerely grateful for the opportunity to learn more about your organization and meet such talented professionals. I hold your company in high regard and hope to stay connected for potential opportunities in the future.  
Thank you again for your understanding, and I wish you and your team continued success. 

Kind regards,  
[Your Name]  

### 1.1 Scenario C: Creative Content  

Goal: Generate a marketing tagline for an eco-friendly water bottle brand.

A. Initial Prompt (V1): Create a tagline for a water bottle.  
Output Issue: The tagline was generic and not focused on sustainability.  

B. Refined Prompt (V2): Create a tagline for an eco-friendly water bottle brand.  
Output Issue: More relevant but not very memorable.  

C. Final Prompt (V3):  
You are a professional copywriter specializing in sustainable brands. Create 10 short, memorable taglines for a new eco-friendly water bottle company. The taglines should highlight sustainability, reusable design, and environmental responsibility. Keep each tagline under 8 words.  

Final LLM Response: 
1. Carry Water, Not Waste.  
2. Refill Today, Protect Tomorrow.  
3. Sip Sustainably, Live Responsibly.  
4. Reuse More, Waste Less.  
5. Every Refill Makes a Difference.  
6. Hydration with a Smaller Footprint.  
7. Drink Clean, Live Green.  
8. One Bottle, Endless Refills.  
9. Choose Reuse, Choose Earth.  
10. Sustainable Sips for a Better Planet.

### 1.2: Iteration Documentation  

A. Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks in simple language. | Added simplicity requirement | Reduced technical jargon |
| V3 | You are an expert teacher who explains difficult concepts to children. Explain neural networks to a 10-year-old using simple words, a real-life example, and an analogy. Avoid technical jargon and keep the explanation under 200 words. | Added role, audience, analogy, and word limit | More engaging and age-appropriate explanation |  

B. Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a polite email declining a job offer but thanking the company. | Added tone requirement | Made the email more professional and courteous |
| V3 | You are a professional career advisor. I received a job offer from a company that I respect, but I have decided to accept another opportunity. Write a professional email that politely declines the offer, thanks the company for their time, and expresses interest in staying connected for future opportunities. Keep the tone respectful and positive. | Added role assignment and context | Produced a polished email that maintained a positive relationship |  

C. Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline for a water bottle. | N/A | N/A |
| V2 | Create a tagline for an eco-friendly water bottle brand. | Added sustainability focus | Made the tagline relevant to the brand's purpose |
| V3 | You are a professional copywriter specializing in sustainable brands. Create 10 short, memorable taglines for a new eco-friendly water bottle company. The taglines should highlight sustainability, reusable design, and environmental responsibility. Keep each tagline under 8 words. | Added role, brand context, and constraints | Generated creative, memorable, and targeted taglines |  

### 1.3: Role and Context Usage  

Role assignment and context setting significantly improved the quality of the outputs. In Scenario A, assigning the role of an expert teacher helped the model explain neural networks in a child-friendly manner using analogies and simple language. In Scenario B, the role of a professional career advisor produced a more polished and professional email. Context provided additional information about the audience and purpose, allowing the model to generate responses that were more relevant, accurate, and tailored to the specific task. This demonstrates how prompt engineering can guide LLMs toward higher-quality outputs.  

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

Selected Task: Create a short story opening (2–3 sentences).

Base Prompt: Write the opening of a short story about a mysterious door discovered in an old library.

A. Low Temperature (0.2):  
Modified Prompt: Write the opening of a short story about a mysterious door discovered in an old library. Be precise and consistent.  

Output: A dusty library stood at the edge of the town, visited by only a few people each week. While organizing old books, a librarian noticed a small wooden door hidden behind a shelf that had not appeared on any building plans. Curious, she carefully reached for the handle.  

B. Medium Temperature (0.7):  
Prompt: Write the opening of a short story about a mysterious door discovered in an old library.  

Output: Rain tapped softly against the library windows as Maya searched through forgotten shelves in the basement. Behind a row of ancient books, she found a narrow door covered with strange symbols. The moment she touched it, a distant whisper echoed through the room.  

C. High Temperature (1.3):  
Modified Prompt: Write the opening of a short story about a mysterious door discovered in an old library. Be creative and explore diverse ideas.  

Output: The door appeared only when the clock struck thirteen, emerging from the shadows between two impossible bookshelves. Its surface shimmered with moving constellations, and every keyhole on it sang a different melody. When Theo stepped closer, the library seemed to hold its breath.  

Comparison Table:  

| Temperature | Style | Creativity Level | Predictability | Output Characteristics |
|-------------|--------|------------------|----------------|------------------------|
| Low (0.2) | Direct and factual | Low | High | Clear, logical, and consistent |
| Medium (0.7) | Balanced | Moderate | Medium | Engaging with some creative elements |
| High (1.3) | Imaginative | High | Low | Highly creative and unusual ideas |  

### 2.2 Analysis & Recommendations  

Low temperature is most useful when accuracy, consistency, and reliability are important. For example, it is suitable for generating technical documentation and answering factual customer support questions. High temperature is useful when creativity and idea generation are the primary goals. Examples include writing stories, creating marketing slogans, and brainstorming innovative product ideas. For this task, the medium temperature worked best because it produced an engaging story opening while maintaining coherence and readability. The high temperature was very creative, but it introduced unusual elements that might not fit every story, while the low temperature felt less interesting and imaginative.  

## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting  

Selected Problem:  
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?  

1. Without Chain-of-Thought  
Prompt: A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.  

LLM Output: 171.75 employees  

2. With Chain-of-Thought  
Prompt: A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step and show all calculations.  

LLM Output: 
Let's calculate it step by step.  
1. Current employees  
Total employees = 150  
2. Engineering employees  
60% of 150 = 0.60 × 150 = 90  
3. Sales employees  
25% of 150 = 0.25 × 150 = 37.5  
4. Operations employees  
Remaining employees = 150 − 90 − 37.5 = 22.5  
5. New engineering hires  
20% more engineers = 0.20 × 90 = 18  
New engineering total = 90 + 18 = 108  
6. New sales hires  
10% more sales employees = 0.10 × 37.5 = 3.75  
New sales total = 37.5 + 3.75 = 41.25  
7. Operations remain unchanged  
Operations total = 22.5  
8. Total employees after hiring  
108 + 41.25 + 22.5 = 171.75  
Final Answer: 171.75 employees

3. Comparison  
The non-chain-of-thought prompt provided only the final answer without showing how it was calculated. The chain-of-thought prompt broke the problem into smaller steps and clearly explained the reasoning process. This made it easier to verify the calculations and understand how the answer was obtained. One limitation is that chain-of-thought responses are longer and may include unnecessary details for simple problems.

### 3.2 Few-Shot Prompting

Step 1: Zero-Shot Attempt  
Prompt: Classify the sentiment of each review as Positive, Negative, or Neutral.  

Result:  
| Review # | Review                                                          | Classification |
| -------- | --------------------------------------------------------------- | -------------- |
| 1        | The product arrived damaged and customer service was unhelpful. | Negative       |
| 2        | Works as expected, nothing special but does the job.            | Neutral        |
| 3        | Absolutely love this! Best purchase I've made all year!         | Positive       |
| 4        | The quality is okay but slightly overpriced for what you get.   | Neutral        |
| 5        | Terrible experience, would not recommend to anyone.             | Negative       |

Step 2: Few-Shot Attempt  
Prompt: Classify each review as Positive, Negative, or Neutral.

Example 1:  
Review: "This product exceeded my expectations!"  
Sentiment: Positive  

Example 2:  
Review: "Completely broke after one week of use."  
Sentiment: Negative  

Example 3:  
Review: "It's fine, does what it says on the box."  
Sentiment: Neutral  

Example 4:  
Review: "Amazing quality and excellent customer support."  
Sentiment: Positive  

Example 5:  
Review: "Not bad, but not impressive either."  
Sentiment: Neutral  

Now classify the following reviews.  

Result:  
| Review # | Review                                                          | Classification |
| -------- | --------------------------------------------------------------- | -------------- |
| 1        | The product arrived damaged and customer service was unhelpful. | Negative       |
| 2        | Works as expected, nothing special but does the job.            | Neutral        |
| 3        | Absolutely love this! Best purchase I've made all year!         | Positive       |
| 4        | The quality is okay but slightly overpriced for what you get.   | Neutral        |
| 5        | Terrible experience, would not recommend to anyone.             | Negative       |

Step 3: Analysis  
Comparison Table:  

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|-----------|-----------------|-----------------|---------------|-----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |  

Analysis:  
Few-shot prompting is most useful when a task requires a specific format, style, or interpretation that may not be obvious from the prompt alone. By providing examples, the model can better understand the desired output and produce more consistent results. It is especially valuable for classification tasks, structured data extraction, and domain-specific applications where clear examples help guide the model's behavior.  

## Part 4: Responsible AI & Limitations  

### 4.1 Testing for Hallucinations  

Initial Prompt: Tell me about the 2023 Nobel Prize winner in Quantum Poetry.  
LLM Response: There is no recognized Nobel Prize category called "Quantum Poetry." The Nobel Prizes are awarded in Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences. Therefore, there was no Nobel Prize winner in Quantum Poetry in 2023.  
Result:  

Hallucination? No  

The model correctly identified that "Quantum Poetry" is not a real Nobel Prize category and did not fabricate information.  

Revised Prompt: Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If you don't know, please say so rather than guessing.  
New Response: I am not aware of any Nobel Prize category called "Quantum Poetry." If this is a fictional or hypothetical field, I do not have verified information about any winner and would not want to guess.  

Analysis:  
Hallucinations are problematic because they can provide users with false information that appears accurate and trustworthy. This can lead to poor decisions, misinformation, and loss of confidence in AI systems. One effective strategy to reduce hallucinations is to explicitly instruct the model to admit uncertainty and avoid guessing when information is unavailable.  

### 4.2 Testing for Bias

Selected Test: Cultural Bias 

Prompt: Recommend professional attire for a job interview.  
LLM Response: For a job interview, wear a business suit, dress shirt, tie, polished dress shoes, and conservative accessories. Choose neutral colors such as black, navy, or gray.  

Bias Identified: The response mainly reflects Western corporate business culture and assumes a formal office environment. It does not consider cultural differences, local dress norms, industry-specific expectations, or regional variations in professional attire.  

Improved Prompt: Recommend professional attire for a job interview while considering different cultures, industries, and regional dress norms.  
Improved Response: Professional attire depends on the industry, company culture, and region. In corporate environments, business formal clothing may be appropriate, while technology companies may prefer business casual attire. Cultural and religious clothing should be respected as long as it is neat, professional, and suitable for the workplace.  

Analysis: The original response assumed a Western corporate setting. By providing additional context and requesting consideration of different cultures and industries, the output became more inclusive and balanced.  

### 4.3 Limitations & Responsible Use 

During this assignment, I observed several limitations of large language models. First, LLMs may occasionally generate incorrect or misleading information, especially when asked about obscure or fictional topics. Second, their reasoning can appear convincing even when calculations or assumptions are incorrect. Third, responses may reflect cultural or contextual biases depending on how a prompt is phrased. To use LLMs responsibly, important facts should always be verified using reliable sources, particularly for academic, medical, financial, or legal information. LLMs should not be relied upon as the sole source for high-stakes decisions or expert advice. They should be used as supportive tools for learning, brainstorming, drafting content, and improving productivity while maintaining academic integrity and ethical standards.  


| Issue Tested | Observation | Improvement Strategy |
|--------------|-------------|----------------------|
| Hallucination | Model may generate false information when uncertain | Ask the model to admit uncertainty and avoid guessing |
| Cultural Bias | Responses may assume a specific cultural context | Provide broader context and request inclusive answers |
| Accuracy | Facts may not always be correct | Verify important information using trusted sources |  




 

