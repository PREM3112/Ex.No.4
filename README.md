# Experiment 4: Scenario-Based Report Development Utilizing Diverse Prompting Techniques
## Objective:
The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.

**Project:** AI-Powered Customer Support Chatbot for a Retail Environment

## Aim

To design and develop an AI-powered chatbot capable of handling customer inquiries, providing product information, assisting with order tracking, addressing complaints, and improving customer support in a retail environment using different prompting techniques: Zero-Shot, One-Shot, Few-Shot, Role-Based, Chain-of-Thought, and Scenario-Based Prompting.

## Algorithm

1. **Start:** Identify the objective of developing an AI-powered retail customer support chatbot.
2. **Define the scenario:** Consider an online retail store where customers need help with product availability, order status, returns, refunds, and payments.
3. **Identify prompting techniques:** Select Zero-Shot, One-Shot, Few-Shot, Role-Based, Chain-of-Thought, and Scenario-Based Prompting.
4. **Design prompts:** Construct prompts for realistic retail customer support situations.
5. **Execute prompts:** Enter the prompts into a generative AI tool and collect responses.
6. **Evaluate responses:** Assess accuracy, relevance, clarity, empathy, and potential customer satisfaction.
7. **Compare results:** Compare how the different techniques handle inquiries.
8. **Generate report:** Document prompts, sample outputs, observations, and findings.
9. **Stop.**

## Prompts and Sample Outputs

> **Note:** The outputs below are illustrative examples, not results from a recorded live chatbot test. Product availability, delivery dates, replacement eligibility, and refund status require access to actual store data and policies.

### 1. Zero-Shot Prompting

**Prompt**

```text
A customer asks, "Is the Samsung Galaxy S24 available in your store?"
Respond as a retail customer support chatbot.
```

**Sample Output**

> Hello! Thank you for your interest in the Samsung Galaxy S24. I can help you check its availability. Could you please share your preferred storage variant and store location?

**Observation:** Generates a relevant reply without example responses.

### 2. One-Shot Prompting

**Prompt**

```text
Example:
Customer: "Where is my order?"
Chatbot: "Please share your order ID so I can help you check its delivery status."

Now respond to:
Customer: "When will my laptop be delivered?"
```

**Sample Output**

> Sure! Please provide your order ID so I can help you check the estimated delivery date of your laptop.

**Observation:** Follows the response pattern in the provided example.

### 3. Few-Shot Prompting

**Prompt**

```text
Example 1:
Customer: "Can I return my shoes?"
Chatbot: "Please share your order details so I can help you check the return eligibility."

Example 2:
Customer: "I received a damaged product."
Chatbot: "I'm sorry about that. Please provide your order ID and details of the damage so I can guide you through the replacement process."

Example 3:
Customer: "My refund is delayed."
Chatbot: "I understand your concern. Please share your return reference number so I can help you check the refund status."

Now respond to:
Customer: "I received the wrong product."
```

**Sample Output**

> I'm sorry you received the wrong product. Please share your order ID and a description of the item received so I can help you with the return or replacement process.

**Observation:** Multiple examples encourage a consistent structure and tone.

### 4. Role-Based Prompting

**Prompt**

```text
Act as a professional customer support executive for an online retail store.
Respond politely, clearly, and empathetically.

Customer: "I ordered headphones five days ago, but I haven't received them. This is very disappointing."
```

**Sample Output**

> I'm sorry to hear about the delay in receiving your headphones. I understand how frustrating this must be. Please share your order ID so I can help you check the delivery status and guide you on the next steps.

**Observation:** Promotes professional and empathetic communication.

### 5. Chain-of-Thought Prompting (Structured Problem-Solving)

**Prompt**

```text
Act as a retail customer support chatbot. Evaluate the customer's issue by identifying the problem, determining the required information, and selecting an appropriate solution. Provide only a concise customer-facing response.

Customer: "I purchased a smartwatch yesterday, but it is not turning on. What should I do?"
```

**Sample Output**

> I'm sorry your smartwatch isn't turning on. Please try charging it with the recommended charger and checking the manufacturer's startup instructions. If it still doesn't work, share your order details so I can guide you through troubleshooting or the applicable replacement process.

**Observation:** Structured instructions encourage actionable, logical responses.

### 6. Scenario-Based Prompting

**Prompt**

```text
Scenario: A customer purchased a refrigerator online. The product arrived with visible damage, and the customer wants a replacement urgently.

Act as a retail customer support chatbot. Respond empathetically, request the necessary details, and explain the appropriate next steps without promising an unverified replacement timeline.
```

**Sample Output**

> I'm very sorry that your refrigerator arrived damaged. I understand the inconvenience. Please share your order ID and photos of the damage. I can then help you understand the replacement procedure and available options according to the store's policy.

**Observation:** Provides a context-aware response to a specific situation.

## Output

### Comparison of Prompting Techniques

| Prompting Technique | Customer Scenario | Observed Response Quality |
|---|---|---|
| Zero-Shot | Product availability | Direct and relevant |
| One-Shot | Delivery inquiry | Consistent with example |
| Few-Shot | Wrong product received | Structured and helpful |
| Role-Based | Delayed delivery | Professional and empathetic |
| Chain-of-Thought | Defective smartwatch | Logical and solution-oriented |
| Scenario-Based | Damaged refrigerator | Context-aware and empathetic |

### Sample Chatbot Conversation

**Customer:** I received a damaged laptop. Can I get a replacement?

**Chatbot:** I'm sorry your laptop arrived damaged. I can help you with the replacement process. Could you please provide your order ID and photos of the damage?

**Customer:** My order ID is ORD12345.

**Chatbot:** Thank you for sharing your order ID. Please upload photos of the damage. Once the details are reviewed, the support team can confirm your replacement eligibility and explain the next steps.

## Result

The experiment demonstrates how diverse prompting techniques can guide the responses of an AI-powered retail customer support chatbot. The illustrative outputs show that:

- **Zero-Shot Prompting** can provide direct answers to common inquiries.
- **One-Shot and Few-Shot Prompting** can improve consistency of response style.
- **Role-Based Prompting** can guide professional and empathetic communication.
- **Structured Problem-Solving Prompting** can encourage practical troubleshooting steps.
- **Scenario-Based Prompting** can tailor responses to customer situations.

**Conclusion:** Diverse prompting techniques are useful in designing customer support interactions. Their actual effectiveness and impact on customer satisfaction should be validated using systematic testing and access to real store policies and order information.
